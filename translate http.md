# သိသင့်သောHTTP အခြေခံသဘောတရားများ
အခုပြောမဲ့အကြောင်းအရာထဲမှာ world wide web (www.)ရဲ့အခြေခံသဘောတရားတွေကိုပြောပြပေးသွားမှာပါ. HTTP အရှည်ကောက်ကတော့ Hypertext Transfer Protocol လို့ခေါ်ပါတယ်. HTTPက Web Pageတစ်ကိုရှာတဲ့အခါမှာ ဆက်သွယ်ပေးတဲ့Protocol တစ်ခုဖြစ်ပါတယ်. ပထမဆုံး Website တစ်ခုကိုဖွင့်တဲ့အခါ သင့်ရဲ့ Browser က Sever ကို Request လှမ်းတောင်းပါတယ် အဲ့အခါမှာ Server ကနေ Resource တစ်ခုပြန်ပို့တယ် အဲ့ Resource ထဲမှာ Websiteတစ်ခုပြဖို့ လိုအပ်တဲ့ image,video ဒါမှမဟုတ် HTML file ပါပါတယ် HTTPထဲမှာ Resquestနဲ့Response ဆိုပြီး(၂)မျိုးဆိုပြီးရှိတယ် Requeset Messageတွေကတစ်ခုနဲ့တစ်ခုတူကြမှာမဟုတ်ပါဘူး ServerကိုRequestလုပ်ဖို့အတွက်တော့informationအပြည့်အစုံပါရမှာပါ 

## URls
URls အကြောင်းပြောရမယ်ဆိုရင် သူ့ Long Term ကိုအရင်ပြောရလိမ့်မယ် Long Termက Uniform Resource Locator ပဲဖြစ်တယ် Web တစ်ခုရဲ့ အဓိက Concept တစ်ခုဖြစ်တယ် Web Page ရဲ့ Resourceကို Request လုပ်တဲ့အခါ Website address အဖြစ်ဆောင်ရွက်ပေးတယ် Text/Html files,document,imagesအစရှိတာတွေ shareဖို့ Platformတစ်ခုအဖြစ်အသုံးပြုရာကနေ Resourcesတွေတစ်ခုတည်းShareဖို့ပြောင်းလဲလာခဲ့တာဖြစ်ပါတယ် 
[Example of an Url](https://www.freecodecamp.org/news/content/images/2019/08/0-DTR8JpFZo31ht-Kd.jpg)
                  Example of URL
**Protocol**-HTTPS က HTTPကို ပိုsecureဖြစ်စေတဲ့ Protocolတစ်ခုပါ အခြား Protocol တွေလည်းရှိပါသေးတယ် 
* File transfer Protocol(FTP)က Client နဲ့ Server ကြား File & Data တွေ Share ဖို့သုံးတာပါ
* Simple Mail Transfer Protocol(SMTP)ကတော့ E-Mail 
တွေ share ဖို့Standard Protocol တစ်ခုဖြစ်တယ်
**Domain**-Domainက IP addressကို ပိုပြီး တိကျစေဖို့သုံးရခြင်းဖြစ်တယ်
**Path**-Serverပေါ်မှာရှိတဲ့Resource Locationကို specific ဖြစ်ဖို့ပါ (ဥပမာ-/search/cars/VWBeetle.pdf or C:/my cars/VWBeetle.pdf)
**Parameters**-သူကလည်းServerပေါ်ကResourceကိုပိုသေချာအောင် ပြောတဲ့ Data ပါပဲ
**Note**:URLကို တစ်ခါတစ်ခါ URI(Uniform Resource Identifier)လို့လည်း ခေါ်ကျပါတယ်

## HTTP Requests
HTTP Requestတိုင်းမှာ URL addressရှိရမယ် Requestတိုင်းမှာMethodတစ်ခုပါတယ်  Method 4ခုရှိတယ်(GET,PUT,POST,DELETE) ဒီMethod 4ခုကိုနောက်လာမယ့် အပိုင်းကျ ဖော်ပြပေးထားမယ် HTTP Messagesတိုင်းမှာ Message Bodyအလိုက် Header တစ်ခုထက်ပိုပြီးရှိတယ် အဲ့Bodyထဲမှာ Requestနဲ့အတူပို့မယ့် data ဒါမှမဟုတ် Responseနဲ့အတူရမယ့်data တွေရှိပါတယ် HTTPရဲ့ ္first part မှာ GET/adds/search-result?item=vw+beetle HTTP/1.1 ဆိုပြီး item 3ခုပါတယ် ဖော်ပြထားတဲ့ Requestကဥပမာပြထားတာပါ
1. First partက ခုနကပြောတဲ့Methodတွေထဲကတစ်ခုခုပါ အများဆုံးသုံးတာကတော့GET Methodပါ 
1. Second partက Request URLပါ
1. နောက်ဆုံးThird Partက HTTP Versionဖြစ်ပါတယ် Browserအများစုက Version1.1 ပါ Version 2.0လည်းရှိပါသေးတယ်
HTTP Request ထဲမှာ Referer Headr,Agent Header(User),Host Header နဲ့ Cookie Header တွေလည်းကျန်ပါသေးတယ်

## HTTP Responses 
HTTP Request လိုပဲ Response မှာလည်း item3 ခုပါပါတယ် (ဥပမာ-HTTP/1.1 200 OK)
1. First Partက HTTP Version
1. Second Partက Resquestရဲ့ numberic code of the result
1. Third Partက second partရဲ့ textual description 
ပြီးတော့HTTP Responserမှာ Serverl Headder,Cookie Header(Set),Message Body နဲ့ Length Header(Content)တွေလည်းပါပါသေးတယ်

## HTTP Method 
အဓိက Method ကတော့ GETနဲ့POST ပါ 
**GET**-
**POST**-
**PUT**-
**HEAD**-
**TRACE**-
**OPTIONS**-
**OPTIONS**-
**PATCH**-
**DELETE**-

