# Resilient systems design
   ### Contents
1.  အပိုင်း (၁)

2.  [အပိုင်း (၂)](https://github.com/KoMoeArkarOhm/software_engineering/blob/master/PART%202%20-%20System%20Dependability%20and%20Security/Chapter_14_Resilience_engineering/Resilient_systems_design_part_2.md)

3.  [အပိုင်း (၃)]()
## အပိုင်း (၁)

resilient systems တွေသည် ဆိုက်ဘာတိုက်ခိုက်မူ, software failures လိုမျိုး ပျက်စီးကြောင်း incidents တွေမှ ခံခုတန်လှန် နိင်,  ပြန်လည် ကောင်းမွန်နိင်ပါတယ်။
resilient systems တွေသည် critical services တွေကို အနှောက်အယှက် အကင်းဆုံး နဲ့ လူတွေသုံး လို့ရအောင် incident တစ်ခုဖြစ်ပြီးတာနဲ့ ပုံမုန် အလုပ်လုပ်သော အခြေအနေကို မြန်မြန် ပြန်လုပ်နိင်ပါတယ်။

resilient system  ၁ ခု ဒီဇိုင်းဆွဲရာမှာ တိုက်ခိုက်သူက penetration လုပ်မယ်, system failures ဖြစ်ကိုဖြစ်မယ်လို့ ယူဆထားရပြီး  ပျက်စီးကြောင်း events တွေ ကို ဖြေရှင်းနိင်သော ကွဲပြားသော features များ နဲ့ redundant များပါဝင်ရပါတယ်။

resilience ဖြစ်သော systems design စွဲခြင်းမှာ ပူးကပ်စွာဆက်နွယ်နေသော အလုပ် နစ်ခု ပါဝင်ပါတယ်။

- ၁. critical services နဲ့ ‌assets များကို သိရှိ ကွဲပြား ချားနားခြား အောင်လုပ်ခြင်း

     Critical services နဲ့ assetsတွေဟာ system တစ်ခုကို သူ၏ရည်ရွယ်ချက်ကို ပြည်ဝစေတဲ့ သူ၏ elementsလေးတွေပါ။
ဉပမာ -
System တစ်ခု ၏ အဓိကရည်ရွယ်ချက် သည် တက်နိင်သမျှ အမြန်ဆုံး လိုအပ်သော ပြည်သူများအား ကူညီဖို အရေးပေါ calls တွေ အတိုင်း လူနာတင်ကားလွတ်ပေးရတာမျိုး ဆိုကြပါဆို့။

     - Critical services - calls လက်ခံ, လူနာတင်ကားပို့။
     - other services - call log, လူနာတင်ကား tracking .

- ၂. reinstatement, recovery, resistance, ပြဿနာကို (သိရှိ ကွဲပြားစေဖို့)(recognition) စသည်ဖြင့် ဒီလိုအလုပ်တွေကို ကူညီပေးသော system components များ ဒီဇိုင်းဆွဲခြင်း

     ဉပမာ လူနာတင်ယဉ်ခေါ sytem  တစ်ခုမှာ ကျွန်တော်တို့က လူနာတင်ယဉ် လာဆိုပြိး button နိပ်ခေါလိုက်တယ်။
response တစ်ခုခုပြန်ရမယ်။
"ဒီမှာလူနာတင်ယဉ် မအားသေးလို့ တခြား ဠာနကိုဆက်သွယ်ပါ ဘာညာပေါ"
အဲလိုမျိုး တစ်ခုခုပေါ့။
ပြန်ကိုပြန်ရမှာ response။
response မပြန်တော့တာကို သိဖို့ [watchdog timer(အခန်း ၁၂ )]()
တစ်ခုပါပါတယ်။


   ခွင့်မပြုသော accesss ဖြစ်နိင်ချေတွေ ခုခံနိုင်ဖို့ hardware token တစ်ခုနဲ့ operatorsက authenticate လုပ်ဖိုလိုပါတယ်။
   System fail ခဲ့ရင် မရှိမဖြစ် services တွေ maintian ဖြစ်စေဖို့ နောက်ထပ် center တစ်ခုကို calls တွေကို လွဲပေးပါလိမ့်မယ်။
   system functionတွေ failure ဖြစ်တာဖြစ်ဖြစ်, interruptionဖြစ်သွားတဲ့အခါ reinstatement ရစေဖိုအတွက် system database နဲ့ အခုကလို hardware token ၏ softwareကိုပဲ maintain လုပ်ရပါလိမ်မယ်။
 
 
  ## [အပိုင်း (၂) သို့](https://github.com/KoMoeArkarOhm/software_engineering/blob/master/PART%202%20-%20System%20Dependability%20and%20Security/Chapter_14_Resilience_engineering/Resilient_systems_design_part_2.md)
