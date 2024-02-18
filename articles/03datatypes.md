# => Data Types

Data Types တွေမှာ အမျိုးအစားအနေဖြင့် (  ) မျိုးရှိပါတယ်။ အဲ့ဒါတွေကတော့
‌
      (1) String
      (2) Number
      (3) Boolean
      (4) Array   
      (5) Object
      (6) Undefined
      (7) Null

တို့ပဲဖြစ်ပါတယ်။

data type တွေကို စစ်ချင်တဲ့အခါ JavaScript မှာ  typeof နဲ့ စစ်ပါတယ်။

## - String 

string ဆိုတာကတော့ စာသားတွေပဲဖြစ်ပါတယ်။ မှတ်သားစရာအနေနဲ့ string data type တွေကို double quote (" ") သို့မဟုတ် single quote (' ') ထဲမှာ ထည့်ရေးရပါမယ်။ quote တွေထဲမှာ ရှိသော အရာတိုင်းသည် string ဖြစ်သည်။ ဉပမာအားဖြင့် 

        const name = "kyaw kyaw";
        console.log(name); //  kyaw kyaw
        console.log(typeof name) // string

နောက်ထပ် ဉပမာတစ်ခုထပ်ပြပါမယ်။

        let job = "He's a doctor.";
        console.log(job); // He's a doctor

        let content = 'He's a doctor';
        console.log(content); // Uncaught SyntaxError: Unexpected identifier 's' 

အပေါ်က double quote မှာတော့ error တက်တာ မတွေ့ရပဲ အောက်က single quote ထဲမှာရေးထားတာက error တက်နေတာ တွေ့ရပါလိမ့်မယ်။ အပေါ်မှာ ပြောထားခဲ့တုန်းက နှစ်ခုထဲက တစ်ခုမဟုတ် တစ်ခုသုံးနိုင်တယ်ဆိုရင် ဘာကြောင့် error တက်တာလဲ။

အဖြေကတော့ ရှင်းရှင်းလေးပါ။ quote တွေ ထဲမှာ တူညီတဲ့ quote  တစ်ခုပါလာတဲ့အခါ computer က အပိတ်အနေနဲ့ မှတ်ယူသွားပါတယ်။ 'He' သည် apostrophe ကို အပိတ်အဖြစ် မှတ်ယူသည့်အတွက် အဖွင့်အပိတ် ပြည့်စုံပြီး  s a doctor' မှာတော့ အပိတ်သာရှိပြီး အဖွင့်မရှိတဲ့အတွက် အလုပ်မလုပ်တာဖြစ်ပါတယ်။ double quote ထဲတွင်လည်း ဒီလိုပဲဖြစ်ပါတယ်။

        var sentence = "It"s a dog";   // Uncaught SyntaxError: Unexpected identifier 's' 



ဒီလို character တွေကို computer နားလည်စေဖို့ အတွက် backward slash (\) ထည့်သုံးပေးဖို့ လိုအပ်ပါတယ်။

        var dog = "It\"s a dog"; // It"s a dog
        console.log(dog);

        var cat = 'It\'s a cat';
        console.log(cat);   // It's a cat
        

ဒါဆို computer က ကိုယ်စာကြောင်းထဲမှာ ထည့်ရေးချင်တဲ့ character မှန်းသိသွားပြီ ဖြစ်တယ်။


## - Number 

number တွေဆိုတာကတော့ ကိန်းဂဏန်းတွေပဲဖြစ်ပါတယ်။ ဒီကိန်းတွေကိုတော့ ဘယ်ထဲမှ ထည့်ရေးစရာ မလိုအပ်ပါဘူး။ 

        var a = 200;
        console.log(a); //200
        console.log(typeof a); // number



        var a = "200";
        console.log(a); // 200
        console.log(typeof a); // string

အပေါ်က ဉပမာနှစ်ခုကို ကြည့်ခြင်းအားဖြင့် ကွဲပြားခြားနားချက်ကို မြင်တွေ့ပြီးဖြစ်ပါလိမ့်မယ်။

 ဒုတိယ ဉပမာမှာ data type သည် string အဖြစ် output ထွက်နေတာ တွေ့ရပါလိမ့်မယ်။ 

ဒါသည်  quotes တွေထဲမှာ ရေးတာကြောင့် string ထွက်နေတာဖြစ်ပြီး a ရဲ့တန်ဖိုးက 200 ( နှစ်ရာ) မဟုတ်တော့ပဲ 2, 0, 0 ( နှစ် သုံည သုံည) သာဖြစ်ပါတယ်။


## - Boolean

  Boolean ဆိုတာကတော့ true နဲ့ false ကို ခေါ်တာဖြစ်ပါတယ်။ 
  
  
        var x = true;
        console.log(x); // true
        console.log(typeof x); // boolean
  
  
        var y = false;
        console.log(y); // false
        console.log(typeof y); // boolean
        
        
  
     
  boolean တွေကိုလည်း  double quote ("") သို့မဟုတ် single quote ('') ထဲ ထည့်ရေးရင် string ဖြစ်ပါတယ်။
  
        var x = "true";
        console.log(x); // true
        console.log(typeof x); // string
  
        var y = "false";
        console.log(y); // false
        console.log(typeof y); // string

