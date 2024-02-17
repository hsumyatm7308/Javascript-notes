# => Variables ဆိုတာ ဘာလဲ။

   variable ဆိုတာ value တွေ data type တွေကို သိမ်းတဲ့ အရာတစ်ခုဖြစ်တယ်။ ဉပမာ ဘဏ် ထဲကို ပိုက်ဆံ သွင်းမယ် ဆိုပါစို့။ သွင်းမည့် ပိုက်ဆံသည် value ဖြစ်ပြီး  ထိန်းသိမ်းမည့် ဘဏ် က variable ဖြစ်တယ်။  သည်လိုဆို ဘဏ်ရဲ့ တန်ဖိုးသည် သွင်းလိုက်တဲ့ ပိုက်ဆံပမာဏ အတိုင်း တန်ဖိုးရှိသွားပြီဖြစ်တယ်။  
   
   
   ![Screenshot from 2024-02-05 18-41-58](https://github.com/hsumyatm7308/Javascript-notes/assets/107622230/a046e1e5-c57b-486f-ba3a-c8a5feaaffbd)

   
   
   
   
  ၁၀၀၀ ရဲ့ တန်ဖိုးက bank ဆိုတဲ့ variable name ကို တန်ဖိုးသတ်မှတ်ပြီးသားဖြစ်သွားပါတယ်။ ဒါကို variable ကြေငြာတယ်လို့ ခေါ်ပါတယ်။ variable name တွေကို ကိုယ်ပေးချင်တဲ့ နာမည်ပေးလို့ရပါတယ်။ သို့သော် ပေးလို့ရတဲ့ပုံစံနဲ့ ၊ မရတဲ့ ပုံစံတွေတော့ ရှိပါတယ်။ 

      
 ### -  အသုံးပြုနိုင်သော ပုံစံများ 
  
    (i)    စာသားများ ( letters )  
    
           (a)  var firstname  // စာလုံးအသေးများ တစ်ဆက်တည်းရေးခြင်း
           (b)  var Firstname   // အစ စကားလုံး အကြီးဖြင့်ရေးခြင်း
           (c)  var FIRSTNAME // စားလုံးအကြီးများ တစ်ဆက်တည်းခြင်း
    
    
    
    (ii)   နံပါတ်များ နှင့် တွဲရေးခြင်း ( numbers )  
         
           (a) var post1
           
           (b) var post2 
    
    
    
    (iii)  underscores အသုံးပြုခြင်း 
           
           (a) var last_name 
           
    
    (iv)   dollar sign အသုံးပြုခြင်း 
    
           (a) var $lastname
           
           ဒီနောက်ဆုံးနည်းကို သိပ်တော့ recommend မပေးပါဘူး။ ဘာလို့ဆို PHP မှာလည်း $ သုံးတာကြောင့် ရောသွားနိုင်လို့ပါ။ 
    
    
          
 ### -  အသုံးမပြုနိုင်သော ပုံစံများ 
   
    (i)    စကားစု နှစ်စု ခွဲရေးခြင်း  
    
           (a)  var first name    
    
    
    
    (ii)   စကားစု နှစ်စုကို ( - ) ဖြင့် ဆက်ခြင်း
         
           (a) var first-name
    
    
    (iii) special escape characters များ အသုံးပြုခြင်း  ( @ , # , % , ! , * , & )
           
           (a) var @firstname   
           
           (b) var \lastname 
    
    (iv)   နံပါတ်များ ကို ရှေ့မှာ ထားသုံးခြင်း 
    
           (a) var 2lastname 
           
           (b) var 23title 
           
           
    (v) variable name တွေကို single / double quote ထဲ ထည့်ရေးခြင်း
       
       (a) var "firstname"
       
        Tip:: ဘာကြောင့်လဲဆိုတော့ Data Type တွေကြောင့်ဖြစ်ပါတယ်။ data type တွေအကြောင်းကိုတော့ နောက်ပိုင်းမှာ ဆက်ရှင်းပါမယ်။ 
      
      
      
      
   
   var ဆိုတာက variable တွေကို declaration လုပ်ပေးတဲ့ကောင် ဖြစ်တယ်။ var နဲ့အလားတူတာ နှစ်ခု ရှိပါသေးတယ်။ အဲ့တာကတော့  const  နဲ့  let  ပါ။ 
   
   
## => var, let နဲ့ const တို့ရဲ့ ကွာခြားချက်များ 

 
     var a = 100;  
     console.log(a); // output - 100 
    
     let b = 100;
     console.log(b); // output - 100
     
     const c = 100; 
     console.log(c); // output - 100
     
     
  ဒီအပေါ်က အတိုင်းဆိုရင်တော့ output တွေက ဘာမှ ကွာခြားမှု မရှိသေးပါဘူး။


### => Overwriting
  
  ဒီတစ်ခေါက်မှာတော့ declare လုပ်ပြီးသား variable name တွေကို value အသစ်ထပ်ထည့် ပြပါမယ်။  ဒါကို overwrite တယ်လို့ခေါ်ပါတယ်။ ကုတ်တွေက အပေါ်ကနေ အောက်ကို ဆင်းတဲ့ အတိုင်း အလုပ်လုပ်တဲ့အတွက် (အပေါ်က code များအလုပ်လုပ်မှသာ အောက်က code များ ဆက်၍ အလုပ်လုပ်ခြင်း) အောက်ဆုံးက overwrite ထားတဲ့ value ကိုပဲ output ထွက်ပါတယ်။ 

    var x = 100; 
        x = 200;

    console.log(x); // 200 
        
   var နဲ့ declare လုပ်ထားတဲ့ကောင်ကို value အသစ်ပြန်ခေါ်တာ ရပါတယ်။  ဆိုလိုတာက overwrite လို့ရတယ်ပေါ့။ 

   
    let i = 100;  
        i = 200;

    console.log(i); // output - 200
     
   let နဲ့ declare လုပ်ထားတာကိုလည်း  overwrite လို့ရတယ်။  

   
     const y = 100;  
           y = 200;

     console.log(y); // output - Uncaught SyntaxError: Identifier 'c' has already been declared`
       
   const မှာဆိုရင်တော့ error တက်တာ တွေ့ရပါလိမ့်မယ်။ အပေါ်မှာ const နဲ့ declare လုပ်ထားတဲ့ variable ကို overwrite လုပ်လို့မရပါဘူး။ ဘာလို့ဆို သူက ပုံသေသတ်မှတ်ထားပြီးသား constant variable ဖြစ်နေလို့ပါ။ 
    

### => Variable အား declare ကြိုလုပ်ခြင်း 

    var car; // output - undefined 
        car = "Toyota";  // output - Toyota

   var နဲ့ ကြိုပြီး declare လုပ်ထားပြီး နောက်မှ value assign ချရင်ရပါတယ်။ 

    let brand; //output - undefined 
        brand = "Gucci"; // output - Gucci 

   let နဲ့လည်း ကြိုပြီး declare လုပ်လို့ရပါတယ်။ 

     const version; // output - undefined 
           version = "10.2.01";  // output - Uncaught SyntaxError: Missing initializer in const declaration 

   const နဲ့တော့ ကြိုပြီး declare လုပ်ထားလို့ မရပါဘူး။
    
 အခုချိန်မှာတော့ var နဲ့ let နဲ့က အတူတူပဲလို့ မှတ်ထားလို့ရပါတယ်။  const တစ်ခုပဲ overwrite မရတာပါ။  နောက်ပိုင်းမှာတော့ var နဲ့ let ကွာခြားမှုအကြောင်း သိပါလိမ့်မယ်။
      

### => Group variable decelerations 
   
      // First Method

       var num1,num2,num3;
      
       num1 = 100;
       console.log(num1); // output - 100

       num2 = 200;
       console.log(num2); // output - 200

       num3 = 300; 
       console.log(num3); // output - 300



      // Second Method

       var num1 = 100,num2 = 200,num3 = 300; 
       console.log(num1,num2,num3); //100 200 300
     

  var နဲ့ group အလိုက် ကြိုပြီး ကြေငြာထားလို့ရပါတယ်။

       // First Method

       let num4,num5,num6;
       
       num4 = 400; 
       console.log(num4);// output - 400

       num5 = 500;
       console.log(num5); // output - 500

       num6 = 600; 
       console.log(num6); // output - 600

       
       // Second Method

       let num4 = 400,num5 = 500,num6 = 600;
       console.log(num4,num5,num6); // 400 500 600

  
  let နဲ့လည်း group အလိုက် ကြေငြာလို့ရပါတယ်။


       // First Method

       const num7,num8,num9;
 
       num7 = 700; 
       console.log(num7); // error

       num8 = 800;
       console.log(num8); // error
  
       num9 = 900;
       console.log(num9); // error

       Note:: overwrite ပြသနာကြောင့် ပထမနည်းမှာတော့ ပေးလို့မရပါဘူး။


       // Second Method

       const num7 = 700,num8 = 800,num9 = 900;
       console.log(num7,num8,num9); // 700 800 900


  const မှာတော့ overwrite ပြသနာကြောင့် ဒုတိယနည်းပဲ သုံးလို့ရပါတယ်။
    

### Declare လုပ်ပြီးသား variable အား ထပ်၍ ကြေငြာခြင်း

     var x = 100;
     var x = 200; // output - 200

   var နဲ့ declare လုပ်ထားပြီးသားကို ထပ်ပြီး var နဲ့ ကြေငြာလည်း ရပါတယ်။

     let i = 100;
     let i = 200; // output - error

   let မှာတော့ ပြဿနာစတက်ပြီပဲ ဖြစ်ပါတယ်။ let မှာတော့ ကြေငြာထားပြီးသား variable ကို ထပ်ကြေငြာလို့မရပါဘူး။ 

     const y = 100; 
     const y = 200; // output - error 

   overwite လို့တောင် မရတဲ့ const မှာတော့ error တက်မှာ အသေချာပဲ ဖြစ်ပါတယ်။ 
    
     
    
    
