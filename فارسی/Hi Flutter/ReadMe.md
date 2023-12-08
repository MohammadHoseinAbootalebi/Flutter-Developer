# <span style="color:orange"><b>Hi Flutter</b></span>

این اپلیکیشن ساده ترین و اولین اپلیکیشنی هست که هر توسعه دهنده در هنگام ورود به یک دنیای جدید برنامه نویسی، آن را می نویسد. پس منم با ورود به دنیای فلاتر، بهش سلام کردم   ؛)

# <h2 id="Table_Of_Contents">**فهرست مطالب**</h2>

1. <a href="#application_properties">مشخصات اپلیکیشن</a>
2. <a href="#designing_part">قسمت طراحی</a>
    1. <a href="#wireframing_section">وایرفریمینگ</a> 
    2. <a href="#designing_section">طراحی کردن</a>
    3. <a href="#prototyping_section">پروتو تایپینگ</a>
    4. <a href="#mockups_section">ماکاپ ها</a>
3. <a href="#programming_part">قسمت برنامه نویسی</a>
    1. <a href="#front_end">فرانت - اند</a>
    2. <a href="#back_end">بک - اند</a>
    3. <a href="#review_functionality">مرور عملکرد</a>

<br><br><br>

## **<p id="application_properties"><b>1. مشخصات اپلیکیشن</b></p>**
مشخصات اپلیکیشن به شرح زیر است: <br>

- نام: **Hi Flutter**
- زمان کامل شدن: **3 ساعت**
- زمان اتمام اپلیکیشن: **2 آذر 1402**
- سطح: **مبتدی**

<a href="#Table_Of_Contents">[↑ برگشت ↑]</a><br><br>

## **<p id="designing_part"><b>2. قسمت طراحی</b></p>**
در این قسمت، من روند طراحی ای که برای به دنیا اومدن "های فلاتر" صورت گرفته را ارائه می کنم.
<br>
<a href="#Table_Of_Contents">[↑ برگشت ↑]</a><br><br><br>

### **<p id="wireframing_section"><b>2.1 وایر فریمینگ</b></p>**
در این قسمت من وایر فریم یا طراحی سطح پایین طراحیِ "های فلاتر" را ارائه می کنم.<br>

در تصویر زیر، پایه ی وایر فریم اپلیکیشن ارائه می شود:<br><br>

<img src="../../Assets/Hi Flutter/Presentations/Wireframing.png" width="100%" height="100%"><br>

همون طور که مشاهده میشه، اپلیکیشن در کل دو صفحه ی اصلی داره:
- صفحه ی سمت چپ، صفحه ی اول اپ هست که یک تصویر از لوگوی فلاتر در پس زمنیه باید داشته باشه و یک تصویر از پرنده "دَش" در جلوی اون. همچنین یک متن زیر این عکس اخیر و یک دکمه در زیر متن برای فشردن باید قرار داده بشه که پس از فشردن اون توسط کاربر، به صفحه ی دوم که صفحه ی سمت راست هست برود.</br></br>
- صفحه ی سمت راست، صفحه ی بعدی است که پس از اینکه کاربر بر روی دکمه ی "به دَش زنگ بزن" تپ می کنه وارد میشه. یک پیام به کاربر نشون داده میشه که می تونه با فشردن کلمه ی باشه، اون رو ببنده. و در خود جعبه پیام هم یک سری متن به عنوان جا نگهدار وجود داره.

<a href="#Table_Of_Contents">[↑ برگشت ↑]</a><br><br><br>

### **<p id="designing_section"><b>2.2 طراحی کردن</b></p>**
در این قسمت، طرح نهایی اپلیکیشن "های فلاتر" ارائه می گردد:<br>

طرح نهایی در یک نگاه به شرح تصویر زیر است. این طراحی در نرم افزار ادوبی اکس دی انجام شده است.<br><br>

<img src="../../Assets/Hi Flutter/Presentations/Design - One Sight.png" width="100%" height="100%"><br>

هر قسمت طراحی در ادامه می آید:

- صفحه ی اول اپلیکیشن [**صفحه ی خوش آمد گویی**] ↓ :<br><br><img src="../../Assets/Hi Flutter/Presentations/First Screen.png" width="100%" height="100%">

- صفحه ی دوم اپلیکیشن [**صفحه ی پیغام**] ↓ :<br><br><img src="../../Assets/Hi Flutter/Presentations/Second Screen.png" width="100%" height="100%">

- صفحه ی اول اپلیکیشن در حالت افقی [**صفحه ی خوش آمد گویی**] ↓ :<br><br><img src="../../Assets/Hi Flutter/Presentations/First Screen - Landscape.png" width="100%" height="100%">

- صفحه ی دوم اپلیکیشن در حالت افقی [**صفحه ی پیغام**] ↓ :<br><br><img src="../../Assets/Hi Flutter/Presentations/Second Screen - Landscape.png" width="100%" height="100%">

<a href="#Table_Of_Contents">[↑ برگشت ↑]</a><br><br><br>

### **<p id="prototyping_section"><b>2.3 پروتو تایپینگ</b></p>**
در این قسمت، من پروتو تایپ یا طراحی سطح پایین طرح "های فلاتر" را ارائه می کنم.

همون طور که کاراییِ اپلیکیشن خیلی ساده هست، برای پروتو تایپ اون، در اولین صفحه اپلیکیشن که همون صفحه ی خوش آمد گویی هست - چه در حالت افقی و چه در حالت عمودی - پس از فشردن دکمه ی پایین برنامه یک پیغام به کاربر نمایش داده  می شود. این روند در تصاویر زیر نمایش داده شده است:

- پروتو تایپ صفحه ی اول [**صفحه ی خوش آمد گویی در حالت عمودی**] ↓ : <br><br><img src="../../Assets/Hi Flutter/Presentations/Call Dash CTA Button.png" width="100%" height="100%">

- پروتو تایپ صفحه ی اول [**صفحه ی خوش آمد گویی در حالت افقی**] ↓ : <br><br><img src="../../Assets/Hi Flutter/Presentations/Call Dash CTA Button Landscape.png" width="100%" height="100%">

- پروتو تایپ صفحه ی دوم [**صفحه ی نمایش پیغام در حالت عمودی**] ↓ : <br><br><img src="../../Assets/Hi Flutter/Presentations/OK Button in the dialog box portrait.png" width="100%" height="100%">

- پروتو تایپ صفحه ی دوم [**صفحه ی نمایش پیغام در حالت افقی**] ↓ : <br><br><img src="../../Assets/Hi Flutter/Presentations/OK Button in the dialog box landscape.png" width="100%" height="100%">

<br><a href="#Table_Of_Contents">[↑ برگشت ↑]</a><br><br><br>

### **<p id="mockups_section"><b>2.4 ماکاپ ها</b></p>**
در این قسمت، من طرح های نهایی رو در قالب ماکاپ ارائه می کنم.<br><br>

<img src="../../Assets/Hi Flutter/Presentations/Mockups/Single Mockup - First Screen.png" width="100%" height="100%">

<br>

<img src="../../Assets/Hi Flutter/Presentations/Mockups/Single Mockup - Second Screen.png" width="100%" height="100%">

<br>

<video width="100%" height="100%" controls>
  <source src="../../Assets/Hi Flutter/Presentations/Mockups/Portrait Hi Flutter.mp4" type="video/mp4">
</video>

https://github.com/MohammadHoseinAbootalebi/Flutter-Developer/assets/111989636/e95f545a-39a5-4f3b-8422-c938c9ea8c9c

<br><a href="#Table_Of_Contents">[↑ برگشت ↑]</a><br><br><br>

## **<p id="programming_part"><b>3. قسمت برنامه نویسی</b></p>**
من در این قسمت، فرایند برنامه نویسی اتفاق افتاده برای اینکه "های فلاتر" به دنیا بیاد رو ارائه می کنم.<br>
<a href="#Table_Of_Contents">[↑ برگشت ↑]</a><br><br><br>

### **<p id="front_end"><b>3.1 فرانت - اند</b></p>**
در این قسمت، من چیز هایی که در جلو برای در تعامل بودن با کاربر هست رو ارائه می کنم.<br>

- صفحه ی اول [**صفحه ی خوش آمد گویی**] ↓ :<br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/Front_end_First_Screen.png" width="100%" height="100%"><br><br>

- صفحه ی دوم [**صفحه ی پیغام**] ↓ :<br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/Front_end_second_Screen.png" width="100%" height="100%">

<br>همان طور که نشان داده شده، اپلیکیشن به شکلی که طراحی شده بود و طرح های آن گذشت، برنامه نویسی شده است.

<br><a href="#Table_Of_Contents">[↑ برگشت ↑]</a><br><br><br>

### **<p id="back_end"><b>3.2 بک - اند</b></p>**
در این قسمت، من چیز هایی که در پس زمینه وجود داره برای اینکه عملکرد برنامه رو بر عهده بگیره ارائه می کنم.<br>

من ویجت هایی که استفاده شده رو به طور کلی نشون میدم. ارائه ی تمامی جزئیات ممکنه خوندن این سند رو خسته کننده کنه، به خاطر همین از ارائه ی تمامی جزئیات اجتناب میشه.<br><br>

- **تصویر لوگوی فلاتر** <br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/Flutter Picture.png" width="100%" height="100%"><br><br><p>همان طور که دیده می شود، کل ویجت های استفاده شده در یک "**پشته**" قرار دارند که این به دلیل پیچیده بودن طرح کاربری این اپلیکیشن ساده است. و همچنین همه ی آنها در یک ویجت "سینگل چایلد سکرول ویو" قرار دارد که در صورت نیاز کاربر بتواند با اسکرول کردن از نرم افزار استفاده کند. به هر حال، تصویر لوگوی فلاتر به عنوان یه ویجت تصویر که قبلاً در ادوبی ایلستریتور طراحی شده در اینجا به عنوان تصویر قرار گرفته است.</p>

<br><br>

- **تصویر دَش** <br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/Dash Picture.png" width="100%" height="100%"><br><br><p>این تصویر هم یک ویجت تصویر هست که مشابه تصویر قبلی در ویجت پشته جا دهی شده است.</p>

<br><br>

- **متن زیر تصویر دَش** <br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/Start Big Journey Text.png" width="100%" height="100%"><br><br><p>این جعبه متن تنها یک ویجت متن هست که حاوی متن "سفر بزرگ خودتو شروع کن" هست.</p>

<br><br>

- **CTA** <br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/Call Dash Button.png" width="100%" height="100%"><br><br><p>این مورد، یک دکمه ی "تکست باتتن" هست که پس از فشرده شدن، متد "شو دیالاگ" که به طور معمول در فلاتر استفاده می شود، فراخوانی می شود.</p>

<br><br>

- **سربرگ پیغام** <br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/I recieved your Call.png" width="100%" height="100%"><br><br><p>در بالای پیغام - که پس از فشرده شدن دکمه ی صفحه ی قبلی توسط کاربر نمایش داده می شود - یک متن به عنوان سربرگ تحت ویجت تکست وجود دارد.</p>

<br><br>

- **بدنه ی پیغام** <br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/dialog text content.png" width="100%" height="100%"><br><br><p>این هم یک ویجت تکست هست که به عنوان جا نگهدار یک متن جذاب و فان را داراست.</p>

<br><br>

- **دکمه ی پیغام** <br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/OK button.png" width="100%" height="100%"><br><br><p>این مورد ی تکست باتتن ویجت است که پس از فشرده شدن توسط کاربر، پیغام بسته می شود و برنامه به صفحه ی اول یا صفحه ی خوش آمد گویی بر می گردد.</p>

<br><a href="#Table_Of_Contents">[↑ برگشت ↑]</a>

<br>

### **<p id="review_functionality"><b>3.3 مرور عملکرد</b></p>**

برای مرور عملکرد اپلیکیشن به طور کلی، فیلم های پایین رو ببین:<br><br>

<video width="100%" height="100%" controls>
  <source src="../../Assets/Hi Flutter/Presentations/Final Videos/Galaxy S Ultra - Landscape.mp4" type="video/mp4">
</video><br><br>

https://github.com/MohammadHoseinAbootalebi/Flutter-Developer/assets/111989636/56efc17f-70f0-4fcc-9bcb-30bce6caa61c

<video width="100%" height="100%" controls>
  <source src="../../Assets/Hi Flutter/Presentations/Final Videos/S Ultra - Landscape - not Portrait.mp4" type="video/mp4">
</video><br><br>

https://github.com/MohammadHoseinAbootalebi/Flutter-Developer/assets/111989636/6786c4c6-a265-4a7c-997e-ff46333fce83

<video width="100%" height="100%" controls>
  <source src="../../Assets/Hi Flutter/Presentations/Final Videos/Note 10 Lite - Both View.mp4" type="video/mp4">
</video><br>

https://github.com/MohammadHoseinAbootalebi/Flutter-Developer/assets/111989636/22fc8944-4509-406f-835f-ec647ce56bc5

<br><a href="#Table_Of_Contents">[↑ برگشت ↑]</a>