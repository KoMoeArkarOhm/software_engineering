# အခန်း (၁၄) Resilience engineering(ဖြစ်လာရင်အကောင်းဆုံး ကြံကြံခိုင်ရင်ဆိုင်နိင်အောင် အစီအမံလုပ်ခြင်း) အနုပညာ
## ပေးချင်သော အကြောင်းအရာများ
ဒီအခန်း ရဲ့ ရည်ရွယ်ချက်ဟာဖြင့် cyber တိုက်ခိုက်ခံရမူတွေ, operator errors လိုမျိုး ပြင်ပ ဆိုးဝါးလှတဲ့ သာမန်မဟုတ်တဲ့ မှတ်သားဖွယ် ထူးခြားဖြစ်စဉ် တွေကို ခံနိင်သော system  ပုံစံတည်ဆောက်နိင်သော resilience engineering ဆိုတဲ့ အယူအဆတစ်ခုကို မိတ်ဆက်ပေးသွားဖို့ ဖြစ်ပါတယ်။
ဒီအခန်းကို ဖတ်ပြီးသွားတဲ့အခါမှာ [root@ကျွန်_တော်_တို_ဟာ:~#]


- resilience, reliability နဲ့ security တွေကြား ခြားနားချက်တွေ, 
ဘာကြောင့် network ပါသော system တွေမှာ resilience သည် အရေးကြီးလည်းဆိုတာ
- sytem down , သုံးမရတော့တာ ကို သုံးလိုရအောင် ပြန်လည်ကြိုစားခြင်း (System reinstatement), (recovery of critical services ) (ဆေးရုံမှာ အောက်စီဂျင် ကို လျှပ်စစ်အားနဲ့ပေးနေရတဲ့လူနာမျိုးတွေ အတွက် critical sevices က လျှပ်စစ်အားရှိခြင်းနဲ့ အခုနကစက်ကောင်းမွန်စွာလုပ်ဆောင်ခြင်းပါ။ စက်တစ်ခုခုဖြစ်တာနဲံဖြစ်ဖြစ် မိးပျက်သွားချင်ဖြစ်ဖြစ် ပြန်လည်ချက်ချင်း ဆက်လက် လျှပ်စစ်အားရှိနေအောင် စက်ပြန်ကောင်းအောင် လုပ်ခြင်းလိုမျိုးပေါ့ ဒီမှာတော့ software system တွေ ‌down ရင် recoveryကို ဆိုလိုတာပါ။), တိုက်ခိုက်မူ နဲ့ failures တွေကို ဖြစ်လာရင်အကောင်းဆုံး
ရင်ဆိုင်နိင်သော အစီအမံလုပ်ခြင်း, ပြဿနာကို အရင်ကတော့ ဘယ်လိုဖြစ်ဖူးတယ် အခုလည်းဒါမျိုးပဲလို သိခြင်း , ပြဿနာတွေ ရှိနေတာကို ဆိုတာ လက်ခံခြင်း
- resillience ရရှိစေဖို့အတွက် လုပ်ဆောင်တဲ့နေရာမှာ
managers, system operators တွေရဲ့အခန်းကဏ္ဏ နဲ့
 resilience သည် ဘာကြောင့် technical issue ထက် လူမူရေး နင့် နည်းပညာ ပြဿနာ ဖြစ်တာလည်းဆိုတာ နားလည်ခြင်း,
- resilience ကို ပံ့ပိုကူညီပေးသော system design နည်း တစ်ခု ,
အစရှိသဖြင့် နားလည်သွားမှာပါ။

## Contents
1.  [Cybersecurity](https://github.com/KoMoeArkarOhm/software_engineering/blob/master/PART%202%20-%20System%20Dependability%20and%20Security/Chapter_14_Resilience_engineering/Cybersecurity_part_1.md)
2.  [Sociotechnical resilience](https://github.com/KoMoeArkarOhm/software_engineering/blob/master/PART%202%20-%20System%20Dependability%20and%20Security/Chapter_14_Resilience_engineering/Sociotechnical_resilience_part_1.md)
3.  [Resilient systems design](https://github.com/KoMoeArkarOhm/software_engineering/blob/master/PART%202%20-%20System%20Dependability%20and%20Security/Chapter_14_Resilience_engineering/Resilient_systems_design_part_1.md)
