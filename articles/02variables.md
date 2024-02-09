# => Variables ဆိုတာ ဘာလဲ။

   variable ဆိုတာ value တွေ data type တွေကို သိမ်းတဲ့ အရာတစ်ခုဖြစ်တယ်။ ဉပမာ ဘဏ် ထဲကို ပိုက်ဆံ သွင်းမယ် ဆိုပါစို့။ သွင်းမည့် ပိုက်ဆံသည် value ဖြစ်ပြီး  ထိန်းသိမ်းမည့် ဘဏ် က variable ဖြစ်တယ်။  သည်လိုဆို ဘဏ်ရဲ့ တန်ဖိုးသည် သွင်းလိုက်တဲ့ ပိုက်ဆံပမာဏ အတိုင်း တန်ဖိုးရှိသွားပြီဖြစ်တယ်။  
   
   
   ![Screenshot from 2024-02-05 18-41-58](https://github.com/hsumyatm7308/Javascript-notes/assets/107622230/a046e1e5-c57b-486f-ba3a-c8a5feaaffbd)

   
   
   
   
  ၁၀၀၀ ရဲ့ တန်ဖိုးက bank ဆိုတဲ့ variable name ကို တန်ဖိုးသတ်မှတ်ပြီးသားဖြစ်သွားပါတယ်။ ဒါကို variable ကြေငြာတယ်လို့ ခေါ်ပါတယ်။ variable name တွေကို ကိုယ်ပေးချင်တဲ့ နာမည်ပေးလို့ရပါတယ်။ သို့သော် ပေးလို့ရတဲ့ပုံစံနဲ့ ၊ မရတဲ့ ပုံစံတွေတော့ ရှိပါတယ်။ 

      
 ### -  အသုံးပြုနိုင်သော ပုံစံများ 
  
    (i)    စာသားများ ( letters )  
    
         ` (a)  var firstname = "U Ba";   // စာလုံးအသေးများ တစ်ဆက်တည်းရေးခြင်း
           (b)  var Firstname = "U Ba";  // အစ စကားလုံး အကြီးဖြင့်ရေးခြင်း
           (c)  var FIRSTNAME = "U Ba";  // စားလုံးအကြီးများ တစ်ဆက်တည်းခြင်း`
    
    
    
    (ii)   နံပါတ်များ နှင့် တွဲရေးခြင်း ( numbers )  
         
          `(a) var post1 = "This is post one"; 
           
           (b) var post2 = "This is post two";`
    
    
    
    (iii)  underscores အသုံးပြုခြင်း 
           
           `(a) var last_name = "Aung";`
           
    
    (iv)   dollar sign အသုံးပြုခြင်း 
    
           `(a) var $lastname = "Aung";`
           
           ဒီနောက်ဆုံးနည်းကို သိပ်တော့ recommend မပေးပါဘူး။ ဘာလို့ဆို PHP မှာလည်း $ သုံးတာကြောင့် ရောသွားနိုင်လို့ပါ။ 
    
    
          
 ### -  အသုံးမပြုနိုင်သော ပုံစံများ 
   
    (i)    စကားစု နှစ်စု ခွဲရေးခြင်း  
    
           `(a)  var first name = "U Ba";   `
    
    
    
    (ii)   စကားစု နှစ်စုကို ( - ) ဖြင့် ဆက်ခြင်း
         
          ` (a) var first-name = "U Ba";`
    
    
    (iii) special escape characters များ အသုံးပြုခြင်း  ( @ , # , % , ! , * , & )
           
           `(a) var @firstname = "Aung";  
           
           (b) var \lastname = "Kyaw";` 
    
    (iv)   နံပါတ်များ ကို ရှေ့မှာ ထားသုံးခြင်း 
    
           `(a) var 2lastname = "Kyaw";
           
           (b) var 23title  = "This is title 23"; `
           
           
    (v) variable name တွေကို single / double quote ထဲ ထည့်ရေးခြင်း
       
           `(a) var "firstname" = "Aye Aye";`
       
            Tip:: ဘာကြောင့်လဲဆိုတော့ Data Type တွေကြောင့်ဖြစ်ပါတယ်။ data type တွေအကြောင်းကိုတော့ နောက်ပိုင်းမှာ ဆက်ရှင်းပါမယ်။ 
      
      
      
      
   
   var ဆိုတာက variable တွေကို declaration လုပ်ပေးတဲ့ကောင် ဖြစ်တယ်။ var နဲ့အလားတူတာ နှစ်ခု ရှိပါသေးတယ်။ အဲ့တာကတော့  const  နဲ့  let  ပါ။ 
   
   
### => var, let နဲ့ const တို့ရဲ့ ကွာခြားချက်များ 

 
    ` var a = 100;  // output - 100 
     
     let b = 100;  // output - 100
     
     const c = 100;  // output - 100`
     
     
  ဒီအပေါ်က အတိုင်းဆိုရင်တော့ output တွေက ဘာမှ ကွာခြားမှု မရှိသေးပါဘူး။ ဒီတစ်ခေါက်မှာတော့ အပေါ်က declare လုပ်ပြီးသား variable name တွေကို value အသစ်ထပ်ထည့် ပြပါမယ်။  ဒါကို overwrite တယ်လို့ခေါ်ပါတယ်။ ကုတ်တွေက အပေါ်ကနေ အောက်ကို ဆင်းတဲ့ အတိုင်း အလုပ်လုပ်တဲ့အတွက် အောက်ဆုံးက overwrite ထားတဲ့ value ကိုပဲ output ထွက်ပါတယ်။ 
     
    ` var a = 200;  // output - 200 `
     
    var နဲ့ declare လုပ်ထားတဲ့ကောင်ကို value အသစ်ပြန်ခေါ်တာ ရပါတယ်။  ဆိုလိုတာက overwrite လို့ရတယ်ပေါ့။ 
     
     `let b = 200; // output - 200` 
     
    let နဲ့ declare လုပ်ထားတာကိုလည်း  overwrite လို့ရတယ်။  
     
    ` const c = 200; // output - Uncaught SyntaxError: Identifier 'c' has already been declared`
     
     
    const မှာဆိုရင်တော့ error တက်တာ တွေ့ရပါလိမ့်မယ်။ အပေါ်မှာ const နဲ့ declare လုပ်ထားတဲ့ variable ကို overwrite လုပ်လို့မရပါဘူး။ ဘာလို့ဆို သူက ပုံသေသတ်မှတ်ထားပြီးသား constant variable ဖြစ်နေလို့ပါ။ 
     
  အခုချိန်မှာတော့ var နဲ့ let နဲ့က အတူတူပဲလို့ မှတ်ထားလို့ရပါတယ်။  const တစ်ခုပဲ overwrite မရတာပါ။  နောက်ပိုင်းမှာတော့ var နဲ့ let ကွာခြားမှုအကြောင်း သိပါလိမ့်မယ်။
    
     
    
    
