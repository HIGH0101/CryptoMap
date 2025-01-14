---
title: Cryptography algorithms
markmap:
  colorFreezeLevel: 3
  initialExpandLevel: 3
---

# <div align="center">**Cryptography**<br>**Algorithms**</div>

##  <div dir="rtl" align="right"><span title=" رمزنگاری کلاسیک نوعی رمزنگاری است که در گذشته مورد استفاده قرار می‌گرفت، شاید بتوان به لحاظ تاریخی گفت که الگوریتم‌های کلاسیک معمولا به رمزنگاری‌های تا جنگ حهانی دوم می‌گویند. اکنون بیشتر مواقع از این الگوریتم‌ها برای درک بهتر مبانی و اصول اولیه رمزنگاری استفاده می‌شود. برخلاف الگوریتم‌های رمزنگاری مدرن، اکثر رمزگذارهای کلاسیک می‌توانند دستی محاسبه و حل شوند.">**Classical**</span></div>

###  <div dir="rtl" align="right"><span title="این نوع از الگوریتم‌های کلاسیک با جابجایی  یا بهم ریختن ترتیب حروف یا گروهی از حرف‌های الفبا موجود در متن، آن را رمز می‌کند."> **Permutation**</span></div>

  - <div dir="rtl" align="right"><span title=" یک روش باستانی رمزنگاری که در آن با استفاده از یک ابزار استوانه‌ای شکل (مانند خودکار امروزی)،  با یک نوار پوستی که دور آن پیچیده شده، پیام روی نوار نوشته می‌شود. این کار باعث می‌شود که بعد از باز کردن نوار از دور استوانه حروف جابه‌جا (رمزی) روی آن نوشته شده باشند."><strong>Scytale cipher</strong></span></div>
  
  - <div dir="rtl" align="right"><span title="در این الگوریتم، حروف متن به صورت زیگزاگ روی دو یا چندین سطر نوشته می‌شوند و سپس سطرها به ترتیب نوشته می‌شوند تا متن رمز بدست آید. "><strong>Rail Fence cipher </strong></span></div>
  
  - <div dir="rtl" align="right"><span title="در این سیستم رمزنگاری ابتدا متن اصلی را در ردیف‌هایی به طول معین قرار می‌دهیم سپس جدول به دست آمده را به صورت ستونی اما به صورت درهم ریخته می‌خوانیم."><strong>Columnar Transpositio cipher</strong></span></div>

  - <div dir="rtl" align="right"><span title="این سیستم در سال 1902 توسط مایژوفسکی پیشنهاد شد. این  رمزنگاری مشابه جابه‌جایی ستونی است با این تفاوت که کلید در رمز جابه‌جایی ستونی در صورتی که حروف تکراری داشته باشد از سمت چپ کوچکترین عدد اختصاص داده می‌شود در حالی که در این سیستم به حروف یکسان عدد یکسانی داده می‌شود و هنگامی که می‌خواهیم متن رمز شده را تشکیل دهیم، ستون‌های به عدد یکسان را به صورت ردیفی می‌خوانیم "><strong>Myszkowski cipher</strong></span></div>

  - <div dir="rtl" align="right"><span title="سیستم رمزگذاری مارپیچی شامل نوشتن یک متن در یک ماتریس به شکل مارپیچ و خواندن آن به صورت سطری یا ستونی است."><strong>Spiral cipher</strong></span></div>

### <div dir="rtl" align="right"><span title="در این روش، هر حرف داخل متن را با حرف متفاوت دیگر یا یک نماد خاص، اغلب براساس یک اصول معین و ثابت جایگزین می‌شود. گرچه این روش قبلا به شکل تجربی استفاده می‌شد، اما اولین بار این روش توسط یک دانشمند عرب به نام «ابن الدريهم» در قرن 14 میلادی به شکل علمی در یک رساله تشریح و مطرح شده است ">**Substitution**</span></div>

  - <div dir="rtl" align="right"><span title="روش تک‌الفبایی، نوعی رمز جانشینی است که در آن هر حرف از متن پیام تنها با یک حرف متناظر، جایگزین می‌شود. این جانشنینی ممکن است در کل متن پیام با یک الگو ثابت یا یک کلید از قبل تعریف شده تعیین شود."><strong>Monoalphabetic</strong></span></div>
  
    - <div dir="rtl" align="right"><span title="در این الگوریتم رمزنگاری باستانی، هر حرف در متن آشکار با حرف دیگری با فاصله‌ای ثابت در الفبا جایگزین می‌شود؛ به این فاصلهٔ ثابت «مقدار انتقال» گفته می‌شود. برای مثال اگر مقدار انتقال برابر ۳ انتخاب شود و رمزنگاری روی متن با الفبای انگلیسی انجام شود، حرف D به جای حرف A می‌نشیند."><strong>Caesar cipher</strong></span></div>

    - <div dir="rtl" align="right"><span title="اولین رمزنگاری جانشینی دوتایی است که طرح آن اولین بار در سال 1854 توسط چارلز ویت‌استون اختراع شد ولی به دلیل ارتقای آن توسط لرد پلی‌فیر، نام آن رمز پلی‌فر است.این روش، از یک جدول &#x202B;5x5&#x202C; از حروف برای رمزگذاری استفاده می‌کند."><strong> Playfair cipher</strong></span></div>

    - <div dir="rtl" align="right"><span title=" یک روش ساده جانشینی است که در آن برای رمز کردن پیام حروف الفبا متن به شکل معکوس (حرف اول با آخر) جایگزین می‌شوند."><strong>Atbash ciphet</strong></span></div>


  - <div dir="rtl" align="right"><span title="نوعی رمز جانشینی که از چندین الفبای جایگزین برای رمزگذاری پیام استفاده می‌کند. این سیستم جایگزینی حروف را در نقاط مختلف متن تغییر می دهد و آن را در برابر تحلیل فراوانی مقاوم‌تر می کند. یک دانشمند عرب مصری به نام «ابوالعباس قلقشندی» قرن 14 میلادی در کتابی به نام «صبح الأعشى» در مورد این روش بحث کرده است. اما گمان می‌رود که شاید الکندی، دیگر دانشمند عرب مبدع، این نوع از رمزنگاری باشد."><strong>Polyalphabetic</strong></span></div>

    - <div dir="rtl" align="right"><span title="این روش از یک کلمه یا عبارت به عنوان  کلید و یک جدول ۲۶×۲۶  (تعداد حروف انگلیسی) برای تعیین جانشینی هر حرف استفاده می‌کند. این روش از یک حروف الفبای جایگزینی متفاوت در هر موقعیت استفاده می‌کند که شکستن آن را سخت‌تر می‌کند. این رمز، یک روش متداول و مؤثر برای مخفی‌سازی اطلاعات به‌ویژه در قرون ۱۵ تا ۱۹ میلادی بود."><strong>Vigenère cipher</strong></span></div>

    - <div dir="rtl" align="right"><span title="ایجاد شده توسط فرانسیس بوفور، رمز جایگزینی مشابه رمز Vigenère که به شکل جدولی و با کمی تغییر کار می‌کند. معروف‌ترین کاربرد این روش رمزنگاری در یک ماشین رمزگذاری مبتنی بر چرخانه (rotor)، مانند ماشین Hagelin M-209 بود."><strong>Beaufort cipher</strong></span></div>

    - <div dir="rtl" align="right"><span title="این الگوریتم جز رمزنگاری‌های Polygraphic است که در آن حروف پیام را به شکل بلوکی از حروف با استفاده از ضرب ماتریس‌ها و یک ماتریس کلید رمزگذاری می‌کند. در سال ۱۹۲۹ توسط لسترهیل اختراع شد."><strong>Hill cipher</strong></span></div>

    - <div dir="rtl" align="right"><span title="ماشین انیگما،  دستگاهی رمزنگار برای رمزگذاری پیام بود که از اوایل تا اواسط قرن بیستم توسط آلمان نازی، برای محافظت از ارتباطات تجاری، دیپلماتیک و نظامی مورد استفاده قرار می‌گرفت. بعدا در میانه جنگ جهانی دوم، پیام‌های رمز شده با این ماشین توسط انگلستان شکسته شد. این ماشین با استفاده از چرخانه و تغییرات مکرر مسیر الکتریکی از طریق درهم‌ساز انیگما یک رمز جانشینی چندالفبایی را پیاده‌سازی می‌کند تا امنیت انیگما را فراهم می‌کند."><strong>Enigma machine</strong></span></div>


### <div dir="rtl" align="right"><span title="این رویکرد ترکیبی از هر دو روش جانشینی Substitution و جابجایی Permutation را برای رمزکردن را استفاده می‌کند. این رمزنگاری‌های ترکیبی در واقع اولین ایده‌ها برای رمزنگاری‌های مدرن و قدرتمندتر آینده بودند.">**Hybrid**</span></div>

  - <div dir="rtl" align="right"><span title="ADFGX یک سیستم رمزگذاری آلمانی مربوط به دوران جنگ جهانی اول است که از یک جدول مربعی ۵×۵ و مکانیزم دوگانه جایگزینی و سپس جابجایی استفاده می‌کند."><strong>ADFGX cipher</strong></span></div>

  - <div dir="rtl" align="right"><span title="این رمزنگاری در واقع بسط و توسعه روی رمزنگاری قبلی بود که در آن یک حرف اضافی، V، به حروف رمز اضافه شد و جدول آن به ۶×۶ گسترش یافت تا امکان استفاده از 26 حرف لاتین و ارقام 0 تا 9 در پیام را فراهم کند. در نهایت، این روش توسط ستوان ارتش فرانسه «ژرژ پینوین» مورد تجزیه و تحلیل قرار گرفت و این الگوریتم در سال ۱۹۱۸ شکسته شد."><strong>ADFGVX cipher</strong></span></div>

  - <div dir="rtl" align="right"><span title="رمز Bifid الگوریتمی است که جانشینی حروف در جدول مربعی را با جابه‌جایی ترکیب می‌کند. این روش در حدود سال ۱۹۰۱ توسط فلیکس «دلاستل پینوین» فرانسوی اختراع شد."><strong>Bifid cipher</strong></span></div>


## <div dir="rtl" align="right"><span title="رمزنگاری مدرن به شدت مبتنی بر ریاضیات، نظریه اطلاعات و علوم کامپیوتر است. الگوریتم‌های رمزنگاری حول مفروضات سختی محاسباتی طراحی شده‌اند که شکستن چنین الگوریتم‌هایی را در عمل حتی توسط کامپیوتر سخت می‌کند.">**Modern**</span></div>
  
### <div dir="rtl" align="right"><span title="الگوریتم‌های متقارن از یک کلید رمزنگاری یکسان، هم برای رمزگذاری متن پیام و هم برای رمزگشایی متن رمز استفاده می‌کنند. این نوع رمزنگاری‌ها معمولا سرعت محاسباتی بالاتر و سربار کمتری نسبت به روش‌های نامتقارن دارند.">**Symmetric**</span></div>

  - <div dir="rtl" align="right"><span title="این نوع از رمزنگاری که به دنباله‌ای معروف است در هر لحظه، هر بیت (بایت) متن پیام با استفاده از بیت (بایت) متناظر از کلید یک به یک رمزگذاری می‌شود تا دنباله‌ای از متن رمزگذاری شده حاصل شود."><strong>Stream Ciphers</strong></span></div>

    - <div dir="rtl" align="right"><span title="رمزنگاری است که در سال ۲۰۰۸ معرفی شد. آن عملکرد نرم‌افزاری سریعی دارد و معمولا سریع‌تر از AES-GCM است. ChaCha20 در بسیاری از پروتکل‌ها از جمله IPsec، SSH/TLS, WireGuard، OTRv4 و چندین پروتکل دیگر پیاده‌سازی شده است."><strong>ChaCha20</strong></span></div>

    - <div dir="rtl" align="right"><span title="Salsa20 از لحاظ ساختاری نزدیک به ChaCha است به شکلی که رمزها با استفاده تابع شبه تصادفی و براساس عملیات add ،rotate ،XOR ساخته تولید می‌شوند."><strong>Salsa20</strong></span></div>

    - <div dir="rtl" align="right"><span title="یکی از معروف‌ترین رمزهای دنباله‌ای است. در حالی که سادگی ساختاری و سرعت آن در نرم‌افزار قابل‌توجه است، اما آسیب‌پذیری‌های متعددی در RC4 کشف شده است. این رمزنگاری در پروتکل قدیمی WEP مورد استفاده در شبکه‌های Wi-Fi به کار گرفته شده بود."><strong>RC4</strong></span></div>


  - <div dir="rtl" align="right"><span title="در این روش پیام بعد تبدیل به رشته بیت آن را در به شکل بلوک‌ بلوک با اندازه ثابت (به عنوان مثال، 64 یا 128 بیت) رمزگذاری می‌کند. اساس این روش‌ها معمولا عمل جابجایی و جانشینی کاراکتر در دفعات زیاد استوار است."><strong>Block Ciphers</strong></span></div>

    - <div dir="rtl" align="right"><span title="ساختاری پایه‌ای و پدر معنوی بسیاری از الگوریتم‌ها بلوکی فعلی است. در آن داده‌ها به دو نیمه تقسیم شده و طی چندین دور، با استفاده از کلیدهای فرعی مشتق شده از کلید اصلی و جابه‌جایی نیمه‌ها، رمزنگاری و رمزگشایی انجام می‌شود."><strong>Feistel</strong></span></div>

    - <div dir="rtl" align="right"><span title="اولین الگوریتم رمزنگاری بلوکی استاندارد که از کلید 56 بیتی استفاده می‌کند؛ امنیت آن به دلیل اندازه کوچک کلید امروزه ضعیف تلقی می‌شود."><strong>DES</strong></span></div>

    - <div dir="rtl" align="right"><span title="نسخه تقویت شده DES که داده‌ها را سه بار رمزنگاری می‌کند و از کلیدهای 112 یا 168 بیتی استفاده می‌کند؛ امنیت بهتری نسبت به DES دارد اما کندتر است."><strong>DES3</strong></span></div>

    - <div dir="rtl" align="right"><span title="الگوریتم استاندارد رمزنگاری حال حاضر با کلیدهای 128، 192 یا 256 بیتی؛ امنیت و کارایی بالایی دارد و برای رمزنگاری داده‌ها در بسیاری از سیستم‌ها استفاده می‌شود."><strong>AES</strong></span></div>

    - <div dir="rtl" align="right"><span title="الگوریتم بلوکی سریع و امن با اندازه کلید متغیر از 32 تا 448 بیت؛ مناسب برای کاربردهای متنوع و به عنوان جایگزینی برای DES معرفی شد."><strong>Blowfish</strong></span></div>

    - <div dir="rtl" align="right"><span title="نسخه پیشرفته Blowfish و یکی از کاندیداهای استاندارد شدن با اندازه کلیدهای 128 تا 256 بیت. آن امنیت و کارایی بالا داشته و در سیستم‌های با منابع محدود به‌کار می‌رود."><strong>Twofish</strong></span></div>


  - <div dir="rtl" align="right"><span title="تکنیکی برای رمزنگاری ایمن پیام طولانی و بزرگ (بزرگتر از یک بلوک) است تا اثر پیام ثابت را در رمز حفظ نکند. "><strong>Modes of Operation</strong></span></div> 

    - <div dir="rtl" align="right"><span title="در حالت ECB (Electronic CodeBook) هر بلوک به طور مستقل با استفاده از همان کلید رمزگذاری می‌شود. با این حال، در برابر تکرار الگو آسیب‌پذیر است، زیرا بلوک‌های متن یکسان بلوک‌های متن رمزی یکسانی تولید می‌کنند."><strong>ECB</strong></span></div>

    - <div dir="rtl" align="right"><span title="در  Cipher Block Chaining (CBC) هر بلوک متن پیام قبل از رمزگذاری با بلوک متن رمز قبلی XOR می شود، که الگوها را پنهان می‌کند. بلوک اول از یک بردار اولیه (IV) برای تصادفی بودن استفاده می‌کند. "><strong>CBC</strong></span></div>
    - <div dir="rtl" align="right"><span title="این حالت (CFB) Cipher FeedBack یک رمز بلوکی را با رمزگذاری یک IV و XOR کردن نتیجه با متن ساده برای تولید متن رمز و سپس جابجایی IV، به یک رمز جریان تبدیل می‌کند. "><strong>CFB</strong></span></div>

    - <div dir="rtl" align="right"><span title=" این حالت (Output FeedBack) شبیه CFB است، اما با رمزگذاری IV و استفاده از آن در عملیات XOR، جریان کلید را از قبل تولید می‌کند و آن را مستقل از پیام، رمز می‌کند."><strong>OFB</strong></span></div>

    - <div dir="rtl" align="right"><span title="در حالت Counter Mode (CTR) هر  بلوک با ترکیب یک مقدار شمارنده (که برای هر بلوک افزایش می‌یابد با یک nonce  رمزگذاری می‌شود. متن پیام با کلید XOR شده است. این روش در صورت پیاده‌سازی درست بسیارامن و کارامد است."><strong>CTR</strong></span></div>


### <div dir="rtl" align="right"><span title="الگوریتم‌های نامتقارن از یک جفت کلید (یک کلید عمومی و یک کلید خصوصی) که براساس ریاضی با هم مرتبط‌اند، برای رمز کردن استفاده می‌کنند. این روش امنیت بالاتر اما سرعت محاسباتی کمتری نسبت به روش متقارن دارد.">**Asymmetric**</span></div>

  - <div dir="rtl" align="right"><span title="فرآیندی که از کلید عمومی برای رمزگذاری و کلید خصوصی مرتبط با آن برای رمزگشایی پیام استفاده می‌کند. این فرایند برای مخفی کردن پیام و ارسال به شکل محرمانه استفاده می‌شود."><strong>Encryption</strong></span></div>

    - <div dir="rtl" align="right"><span title="الگوریتم RSA (Rivest–Shamir–Adleman) رمزنگاری نامتقارن مبتنی بر سختی تجزیه (factorization) اعداد بزرگ (بیش از ۵۱۲ بیت) به عوامل اول آن است که در سال ۱۹۷۷ معرفی شد. سادگی و کارآمدی آن باعث استفاده گسترده در بسیاری از پروتکل‌ها شده است."><strong>RSA</strong></span></div>

    - <div dir="rtl" align="right"><span title=" رمزنگاریِ کوله‌پشتی مرکل-هلمن یکی از اولین رمزنگاری‌های کلید عمومی است که توسط رالف مرکل و مارتین هلمن در سال ۱۹۷۸ ارائه شد. این بر اساس مسئله «جمع زیرمجموعه‌ها» است (مورد خاصی از مسئله کوله پشتی). سرانجام، یک حمله توسط shamir  در سال ۱۹۸۴ منتشر شد باعث شد این رمزنگاری اکنون ناامن در نظر گرفته شود."><strong>Merkle–Hellman knapsack</strong></span></div>

    - <div dir="rtl" align="right"><span title="یک الگوریتم نامتقارن برای رمزنگاری و امضای دیجیتال است. امنیت آن بر پایه سختی مسئله لگاریتم گسسته (Discrete logarithms) در گروه‌های دوری (Cyclic group) است. این الگوریتم یک رمزنگاری احتمالاتی است که یک پیام ثابت ممکن است به رمزهای متفاوت تبدیل شود. از این رو امنیت خوبی دارد اما طول پیام‌های رمزنگاری‌شده نسبت به دیگر الگوریتم‌ها بزرگ‌تر است."><strong>ElGamal</strong></span></div>

    - <div dir="rtl" align="right"><span title="الگوریتم‌های ECC (Elliptic-Curve Cryptography) براساس ساختارهای جبری روی منحنی‌های بیضوی متفاوت در میدان‌های متناهی است. ECC به کلیدهای با اندازه کوچکتر اجازه می‌دهد تا همان امنیت معادل با سیستم‌های رمزنگاری مانند RSA و ElGamal را فراهم کند که نشان‌دهنده کارآمدی این نوع رمزنگاری است."><strong>ECC</strong></span></div>

      - <div dir="rtl" align="right"><span title="در رمزنگاری، Curve25519 یک منحنی بیضوی (y^{2}=x^{3}+486662x^{2}+x) است که در رمزنگاری منحنی بیضوی (ECC) استفاده می‌شود که 128 بیت امنیت (اندازه کلید 256 بیت) ارائه می‌کند. این یکی از سریع‌ترین منحنی ها در ECC است."><strong>Curve25519</strong></span></div>

      - <div dir="rtl" align="right"><span title="P-256 که با نام secp256r1 نیز شناخته می‌شود، یک منحنی بیضوی پرکاربرد در رمزنگاری است که امنیت 128 بیتی را ارائه می‌دهد. این منحنی در پروتکل‌هایی مانند TLS، SSL و امضاهای دیجیتال استفاده می‌شود و تعادلی از امنیت و کارایی قوی با اندازه کلید 256 بیتی را فراهم می‌کند."><strong>P-256</strong></span></div>
      
  - <div dir="rtl" align="right"><span title="در این روش، از رمزنگاری نامتقارن و جفت کلید آن برای تبادل امن یک کلید متقارن (مثلا کلید AES)  در یک کانال ناامن استفاده می‌شود."><strong>Key Exchange</strong></span></div> 
    
    - <div dir="rtl" align="right"><span title=" روش مبادله کلید Diffie–Hellman (DH) مبتنی بر رمزنگاری نامتقارن بر دشواری مسئله لگاریتم گسسته متکی است، که تضمین می‌کند حتی اگر مهاجم داده‌های مبادله شده را رهگیری کند، نمی‌تواند به راحتی کلید مشترک را محاسبه کند. با این حال این روش نمی‌تواند احراز هویت طرفین مبادله را تصدیق کند."><strong>DH</strong></span></div> 
    
    - <div dir="rtl" align="right"><span title=" گونه‌ای از DH است که از رمزنگاری منحنی بیضوی (ECC)  برای تبادل کلید استفاده می‌کند. این گونه کارکرد مشابه DH ، اما با اندازه‌ کلید کوچک‌تر ارائه می‌کند. ECDH به طور گسترده در پروتکل‌های مدرن مانند TLS و Signal  برای ارتباطات ایمن استفاده می‌شود."><strong>ECDH</strong></span></div> 

  - <div dir="rtl" align="right"><span title="در این الگوریتم‌ها می‌توان تایید هویت پیام یا اسناد دیجیتال را بررسی کنید. در این الگوریتم‌ها با کلید خصوصی عمل امضا صورت می‌گیرد و با استفاده از کلید عمومی مرتبط‌ اش، امضا قابل اعتبارسنجی است."><strong>Signature</strong></span></div>

    - <div dir="rtl" align="right"><span title=" امضای RSA همان ساختار روش رمزنگاری آن را دارد اما از کلید خصوصی برای امضای پیام استفاده می‌کند تا صحت و یکپارچگی پیام امضا شده را تضمین کند. سپس با رمزگشایی امضا با کلید عمومی و مقایسه آن با پیام، آن امضا را تأیید می‌کند. امضای RSA در برابر حمله Chosen-Message آسیب‌پذیر است."><strong>RSA</strong></span></div>

    - <div dir="rtl" align="right"><span title="اساس امضای ElGamal همان روش رمزنگاری آن یعنی لگاریتم گسسته است. از کلید خصوصی برای امضا کردن و از کلید عمومی برای اعتبارسنجی آن استفاده می‌شود. این الگوریتم به ندرت به شکل عملی استفاده می‌شود."><strong>ElGamal</strong></span></div>

    - <div dir="rtl" align="right"><span title="امضای Digital Signature Algorithm (DSA)، بر پایه مفهوم ریاضی توان‌رسانی پیمانه‌ای و مسئله لگاریتم گسسته است. آن در واقع گونه‌ای از امضای الجمال است که در سال ۱۹۹۱ توسط NIST به عنوان امضای استاندارد در نظر گرفت."><strong>DSA</strong></span></div> 

    - <div dir="rtl" align="right"><span title="گونه‌ای از DSA  با اندازه‌ کلید کوچکتر و کارایی بالاتر در مقایسه با DSA  که از رمزنگاری منحنی بیضوی استفاده می‌کند. ECDSA به طور گسترده در پروتکل های ارتباطی امن مانند SSL/TLS و بیت کوین برای تأیید تراکنش‌ها استفاده می‌شود."><strong>ECDSA</strong></span></div>

    - <div dir="rtl" align="right"><span title=" امضای Schnore به دلیل سادگی، کارایی و امنیت قوی بر اساس دشواری مسئله لگاریتم گسسته شناخته شده است. امضاهای کوتاه تولید می کند. Schnorr کارآمدتر از DSA و ECDSA است و مبنایی برای طرح‌های چندامضایی است که در بیت کوین Taproot با مجتمع کردن امضاها باعث مقیاس‌پذیری (Scalability) می‌شود."><strong>Schnorr</strong></span></div>  


##  <div dir="rtl" align="right"><span title="رمزنگاری پساکوانتمی (PQC)، توسعه الگوریتم‌هایی برای  رمزنگاری (معمولاً الگوریتم‌های کلید عمومی) است که در برابر حملات مبتنی رایانه‌های کوانتومی ایمن هستند. رمزنگاری‌های PQC، اگرچه براساس مبانی کلاسیک ریاضی و مسائل NP-hard شناخته شده فعلی است، اما می‌توانند در مقابل حملات کوانتومی مقاومت کند. این الگوریتم‌ها همچنین قابل اجرا بر روی رایانه‌های فعلی است و نیازی به هیچ سخت‌افزار جدیدی ندارند و معمولا اندازه کلید بزرگی دارند. پزوهش‌‌ها روی رمزنگاری پساکوانتومی، بیشتر بر روی پنج رویکرد مختلف متمرکز است.">**Post-quantum**</span></div>

### <div dir="rtl" align="right"><span title="رمزنگاری مشبک-مبنا (Lattice -based) شاخه‌ای از رمزنگاری نامتقارن است.این نوع رمزنگاری از یکی گزینه‌های اصلی برای رمزنگاری پساکوانتومی است. این رمزنگاری بر مسائل سختی مانند مسئله یادگیری با خطا (LWE) با مسئله کوتاه‌ترین بردار (ُSVP) استوار هستند.">**Lattice-based**</span></div>

  - <div dir="rtl" align="right"><span title="کپسوله کردن کلید (KEM)، یک سیستم رمزنگاری نامتقارن است که به فرستنده اجازه می‌دهد تا علی‌رغم شنود متخاصم، یک کلید مخفی تولید کرده و به طور ایمن آن را به گیرنده ارسال کند. تفاوت بین طرح‌های رمزنگاری نامتقارن و KEM در این است که یک رمزنگاری نامتقارن به فرستنده اجازه می‌دهد تا یک پیام دلخواه را انتخاب کند، در حالی که یک KEM کلید مخفی را به طور تصادفی توسط الگوریتم تولید و برای فرستنده ارسال می‌کند این کپسوله کردن در رمزنگاری‌های پساکوانتمی بکار می‌روند.."><strong>Key Encapsulation</strong></span></div>

    - <div dir="rtl" align="right"><span title="NTRU یک سیستم رمزنگاری کلید عمومی منبع باز است. اولین نسخه از نوع که NTRU نام داشت در سال 1996 توسط ریاضیدانان جفری هافستاین، جیل پیفر و جوزف سیلورمن توسعه یافت. NTRUencrypt ثبت اختراع شده است، اما در سال 2017 در معرض مالکیت عمومی قرار گرفت."><strong>NTRUEncrypt</strong></span></div>  

    - <div dir="rtl" align="right"><span title="یک سازوکار کپسوله سازی کلید (KEM) طراحی شده برای مقاومت در برابر رایانه های کوانتومی قدرتمند آینده است. از آن برای ایجاد یک کلید مخفی مشترک بین دو طرف در ارتباط استفاده می شود تا یک مهاجم با شرایط (IND-CCA2) در سیستم انتقال قادر به رمزگشایی آن نباشد. این سیستم بر اساس مسئله گونه پیمانه‌ای از LWE به نام (M-LWE)است."><strong>Kyber</strong></span></div>  

    - <div dir="rtl" align="right"><span title=" FrodoKEM یک خانواده از سازوکارهای کپسوله‌سازی کلید است که به گونه‌ای طراحی شده‌اند که کاربردی باشد. امنیت آن از پارامتری کردن محتاطانه در مسئله LWE ناشی می‌شود. FrodoKEM برای امنیت IND-CCA در سه سطح طراحی شده است: FrodoKEM-640 که سطح 1 را هدف قرار می دهد. FrodoKEM-976 که سطح 3 را هدف قرار می‌دهد. FrodoKEM-1344 که سطح 5 را هدف قرار می دهد"><strong>FrodoKEM</strong></span></div> 

  - <div dir="rtl" align="right"><span title="الگوریتم‌های پساکوانتمی مشبکه-مبنا نیز برای امضای دیجیتال نیز وجود دارند. "><strong>Signature</strong></span></div> 

    - <div dir="rtl" align="right"><span title="Dilithium یک طرح امضای دیجیتال است که تحت حملات پیام انتخاب شده (CMA) ایمن است اساس سختی آن بر مسئله مشبکه‌های پیمانه‌ای (Module Lattice) استوار است. این الگوریتم در سال ۲۰۲۴ به عنوان یک امضا استاندارد تحت عنوان ML-DSA انتخاب شده است  که در آینده در پروتکل‌ها و نرم‌افزارها تحت این نام شناخته و استفاده خواهد شد.این امضا در سه سطح امنیتی Dilithium۲،Dilithium ۳،Dilithium ۵ ارائه شده است. "><strong>Dilithium</strong></span></div> 

    -  <div dir="rtl" align="right"><span title="فالکون یک طرح امضای پساکوانتومی است که توسط NIST برای دور چهارم فرآیند استانداردسازی پساکوانتومی یکی از گزینه‌ها است. این تکنیک بر روی چارچوب Gentry، Peikert و Vaikuntanathan بر روی شبکه‌های NTRU متکی است. نام فالکون مخفف امضاهای فشرده مبتنی بر شبکه فوریه سریع بر روی NTRU است. این امضا در دو حالت Falcon-512 و Falcon-1024 ارائه شده که به ترتیب دارای سطح امنیتی ۱و ۵ هستند."><strong>Falcon</strong></span></div> 
 

### <div dir="rtl" align="right"><span title="سیستم‌های رمزنگاری PQC که امنیت آنها تا حدی یا به طور کامل به دشواری رمزگشایی یک کد تصحیح خطای خطی (linear error-correcting) مانند کد Goppa باینری بستگی دارد الگوریتم‌های پساکوانتمی کد-مبنا می‌گویند.">**Code-based**</span></div>   

  - <div dir="rtl" align="right"><span title="کپسوله کردن کلید (KEM)، یک سیستم رمزنگاری نامتقارن است که به فرستنده اجازه می‌دهد تا علی‌رغم شنود متخاصم، یک کلید مخفی تولید کرده و به طور ایمن آن را به گیرنده ارسال کند. تفاوت بین طرح‌های رمزنگاری نامتقارن و KEM در این است که یک رمزنگاری نامتقارن به فرستنده اجازه می‌دهد تا یک پیام دلخواه را انتخاب کند، در حالی که یک KEM کلید مخفی را به طور تصادفی توسط الگوریتم تولید و برای فرستنده ارسال می‌کند این کپسوله کردن در رمزنگاری‌های پساکوانتمی بکار می‌روند.."><strong>Key Encapsulation</strong></span></div>

    -  <div dir="rtl" align="right"><span title="رمزنگاری McEliece یک الگوریتم رمزگذاری نامتقارن است که در سال ۱۹۷۸ توسط رابرت مک الیس توسعه یافت. این اولین طرحی بود که از مفهوم تصادفی سازی در فرآیند رمزگذاری استفاده کرد. این الگوریتم در آن زمان هرگز مقبولیت زیادی در جامعه رمزنگاری به دست نیاورد، اما اخیرا یکی از کاندیدای کپسوله سازی پساکوانتومی کد-مبنا برای استاندارد NIST است. کلید عمومی آن با یک کد Goppa باینری تصادفی را مشخص می‌شود. متن رمز خروجی شامل رمز و خطاهای تصادفی اقزوده به آن است. با کلید خصوصی آن امکان رمزگشایی کارآمد یعنی  استخراج کلمه رمز از متن رمزگذاری شده، شناسایی و حذف خطاها را فراهم می‌کند."><strong>Classic McEliece</strong></span></div> 

    -  <div dir="rtl" align="right"><span title=" سیستم رمزنگاری Niederreiter گونه‌ای از سیستم رمزنگاری McEliece است که در سال ۱۹۸۶ توسط هارآلد نیدرایتر توسعه یافت. این همان ایده را روی یک «ماتریس بررسی توازن» به نام H، یک کد خطی اعمال می‌کند. Niederreiter از نظر امنیتی معادل McEliece است. رمزگذاری Niederreiter حدود ده برابر سریع‌تر از رمزگذاری McEliece است و می‌تواند برای ساخت یک طرح امضای دیجیتال استفاده شود."><strong>Niederreiter</strong></span></div> 

    -  <div dir="rtl" align="right"><span title="BIKE یک سازوکار کپسوله‌سازی کلید مبتنی بر کد است که بر اساس کدهای QC-MDPC (بررسی توازن چگالی متوسط ​​شبه چرخه‌ای) بوده و یکی از طرح‌های ارائه شده برای  استانداردسازی رمزنگاری پساکوانتومی NIST بوده است."><strong>Bike</strong></span></div> 

  - <div dir="rtl" align="right"><span title="الگوریتم‌های پساکوانتمی کد-مبنا نیز برای امضای دیجیتال نیز وجود دارند. "><strong>Signature</strong></span></div> 

    - <div dir="rtl" align="right"><span title=" سیستم رمزنگاری Niederreiter گونه‌ای از سیستم رمزنگاری McEliece است که در سال ۱۹۸۶ توسط هارآلد نیدرایتر توسعه یافت. این همان ایده را روی یک «ماتریس بررسی توازن» به نام H، یک کد خطی اعمال می‌کند. Niederreiter از نظر امنیتی معادل McEliece است. رمزگذاری Niederreiter حدود ده برابر سریع‌تر از رمزگذاری McEliece است و می‌تواند برای ساخت یک طرح امضای دیجیتال استفاده شود."><strong>Niederreiter</strong></span></div> 

###  <div dir="rtl" align="right"><span title="ایده قدیمی و اصطلاح عمومی برای رمزنگاری  بر اساس امنیت توابع Hash ست که به عنوان نوعی رمزنگاری پسا کوانتومی مورد توجه است. این نوع برای ارائه طرح‌های امضای دیجیتال مانند طرح امضای مرکل استفاده می‌شود. ">**Hash-based Signatures**</span></div>

  - <div dir="rtl" align="right"><span title="طرح امضای مبتنی بر هش (XMSS (EXtended Merkle Signature است که  درواقع نوعی بسط از  طرح امضای مرکل است. این امضا یکی از اولین امضاهای دیجیتال بوده که با شماره  NIST SP 800-208 به عنوان امضای دیجیتال استندارد در NIST ثبت شده است. "><strong>XMSS</strong></span></div> 

  - <div dir="rtl" align="right"><span title="+SPHINCS یک طرح امضای مبتنی بر هش بدون حالت (stateless) است. این امضا با سه تابع هش SHAKE256، SHA-256، و Haraka نمونه‌سازی شده که براساس نیاز کاربر قابل انتخاب است. این امضا نیز یکی از طرح‌های امضا دیجیتال پساکوانتمی استاندارد در NIST است."><strong>+sphincs</strong></span></div> 


### <div dir="rtl" align="right"><span title=" رمزنگاری چندمتغیره (Multivariate) اصطلاحی برای نوعی رمزنگاری‌های نامتقارن بر اساس چند جمله‌ای‌های با چند متغیر در یک میدان متناهی F است. ">**Multivariate-based**</span></div>

  - <div dir="rtl" align="right"><span title="کپسوله کردن کلید (KEM)، یک سیستم رمزنگاری نامتقارن است که به فرستنده اجازه می‌دهد تا علی‌رغم شنود متخاصم، یک کلید مخفی تولید کرده و به طور ایمن آن را به گیرنده ارسال کند. تفاوت بین طرح‌های رمزنگاری نامتقارن و KEM در این است که یک رمزنگاری نامتقارن به فرستنده اجازه می‌دهد تا یک پیام دلخواه را انتخاب کند، در حالی که یک KEM کلید مخفی را به طور تصادفی توسط الگوریتم تولید و برای فرستنده ارسال می‌کند این کپسوله کردن در رمزنگاری‌های پساکوانتمی بکار می‌روند.."><strong>Key Encapsulation</strong></span></div>

    - <div dir="rtl" align="right"><span title="  این یکی از قدیمی ترین (۱۹۸۸) سیستم های رمزنگاری کلید عمومی چند متغیره است. ایده اصلی آن استفاده از فضای برداری و ساختار میدان پنهان k^n است، جایی که k یک میدان متناهی است."><strong>Matsumoto-Imai</strong></span></div>
    
    - <div dir="rtl" align="right"><span title="معادلات میدان های پنهان (Hidden Field Equations)  به اختصارHFE، یک سیستم رمزنگاری کلید عمومی است که در Eurocrypt در سال 1996 معرفی شد و توسط ژاک پاتارین پیشنهاد شد. این رمزنگاری بر اساس چندجمله‌ای ها در میدان های متناهی با اندازه‌های مختلف است تا رابطه بین کلید خصوصی و کلید عمومی را پنهان کند."><strong>HFE</strong></span></div>
  
  - <div dir="rtl" align="right"><span title="تعدادی الگوریتم پساکوانتمی امضای دیجیتال با مبنای چندمتغیره نیز وحود دارند. "><strong>Signature</strong></span></div>
    
    - <div dir="rtl" align="right"><span title=" علاوه بر رمزنگاری  طرح امضای دیجیتال این الگوریتم هم طراحی شده است."><strong>Matsumoto-Imai</strong></span></div>
    
    - <div dir="rtl" align="right"><span title="امضای Rainbow (رنگین کمان) متعلق به خانواده سیستم های رمزنگاری کلید عمومی چند متغیره است. رنگین کمان در سال ۲۰۰۴ توسط Jintai Ding و Dieter Schmidt طراحی شد و بر اساس طرح امضای روغن-سرکه(oil-vinegar) ساخته شده است. امنیت نظری Rainbow مبتنی بر این واقعیت است که حل مجموعه ای از سیستم های درجه دوم چند متغیره تصادفی یک مسئله NP-hard است."><strong>Rainbow</strong></span></div>

###  <div dir="rtl" align="right"><span title="نوعی رمزنگاری نسبتا جدید در بین الگوریتم‌های پساکوانتمی است که اساس آن منحنی‌های بیضوی است و امنیت آن بر  پایه (تجسم‌های مختلف) سخت بودن یافتن یک isogeny صریح بین دو منحنی بیضوی فوق‌منفرد (supersingular elliptic curves) روی یک میدان متناهی F متکی است.">**Isogeny-based**</span></div>
  
  - <div dir="rtl" align="right"><span title="کپسوله کردن کلید (KEM)، یک سیستم رمزنگاری نامتقارن است که به فرستنده اجازه می‌دهد تا علی‌رغم شنود متخاصم، یک کلید مخفی تولید کرده و به طور ایمن آن را به گیرنده ارسال کند. تفاوت بین طرح‌های رمزنگاری نامتقارن و KEM در این است که یک رمزنگاری نامتقارن به فرستنده اجازه می‌دهد تا یک پیام دلخواه را انتخاب کند، در حالی که یک KEM کلید مخفی را به طور تصادفی توسط الگوریتم تولید و برای فرستنده ارسال می‌کند این کپسوله کردن در رمزنگاری‌های پساکوانتمی بکار می‌روند."><strong>Key Encapsulation</strong></span></div>
    
    - <div dir="rtl" align="right"><span title="SIKE یک الگوریتم کپسوله‌سازی کلید مبتنی بر Isogeny است که بر اساس شبه تصادفی در نمودارهای Isogeny  فوق منفرد است. این روش یکی از کاندید برای فرآیند استانداردسازی NIST در رمزنگاری پس کوانتومی ارائه شده  بود اما به دلیل ضعف امنیتی که منجر به شکستن این الگوریتم شد از دور رقابت کنار رفت. بنابراین SIKE و نمونه مبتنی بر دیفی-هلمن آن (SIDH) ناامن هستند و نباید استفاده شوند."><strong>SIKE</strong></span></div>
    


  - <div dir="rtl" align="right"><span title="تعدادی طرح‌های امضای دیجیتال نیز برای این نوع امضای پساکوانتمی وجود دارد."><strong>Signature</strong></span></div>
    
    - <div dir="rtl" align="right"><span title="یک طرح امضای جدید برای Isogeny که کلاس مربوط به عملیات گروهی CSIDH را با مفهوم fiat-shamir ترکیب می‌کند."><strong>SeaSign</strong></span></div>
    
    - <div dir="rtl" align="right"><span title=" QISign کوتاه شده‌ی (Short Quaternion and Isogeny Signature) از نمودارهای isogeny منحنی بیضوی فوق منفرد است. طرح امضا از یک پروتکل شناسایی تعاملی یک دوری، با سلامت بالا، مشتق شده است."><strong>SQIsign</strong></span></div>

##  <div dir="rtl" align="right"><span title="توابع درهم ساز(hash) توابعی یک طرفه هستند که می‌توانند برای نگاشت داده‌هایی با اندازه دلخواه به مقادیر با اندازه ثابت استفاده شوند. آن‌ها الگوریتم‌های معکوس‌ناپذیر هستند و احتمال اینکه دو متن به یک مقدار نگاشت شود بسیار بسیار کم است.">**Hash-based**</span></div> 


### <div dir="rtl" align="right"><span title=" الگوریتم‌های مختلفی هستند که خاصیت درهم‌سازی و نگاشت رشته متنی به مقدار ثابت را با تمام ویژگی‌های موردنیاز دارند.">**Hash Functions**</span></div> 

  - <div dir="rtl" align="right"><span title="الگوریتم درهم‌ساز پیام MD5 یک تابع hash پرکاربرد است که مقدار خروجی با طول 128 بیت را تولید می‌کند. امروزه این الگوریتم امنیت کافی برای تولید مقدار hash از یک متن ورودی را ندارد و باید از گزینه‌های جدیدتری استفاده نمود. MD5 توسط Ronald Rivest در سال ۱۹۹۱ طراحی شد تا جایگزین یک تابع MD4 قبلی شود."><strong>MD5</strong></span></div> 
    
  - <div dir="rtl" align="right"><span title="آن یک تابع درهم‌سازی در مقولهٔ رمزنگاری است که یک ورودی می‌گیرد و یک مقدار درهم ۱۶۰ بیتی (۲۰ بایت) به نام hash آن را تولید می‌کند. اگرچه این الگوریتم نسبت به نمونه‌های قبلی امنیت بیشتری دارد اما از سال ۲۰۰۵ نیز جز الگوریتم‌های کاملا امن محسوب نمی‌شود."><strong>SHA-1</strong></span></div> 

  - <div dir="rtl" align="right"><span title=".این تابع درهم‌ساز توسط آژانس امنیت ملی ایالات متحده طراحی و توسط مؤسسه ملی فناوری و استانداردها در سال ۲۰۰۱ به عنوان استاندارد پردازش اطلاعات انتشار یافت. این الگوریتم براساس مقدار خروجی خود به ۴ دسته تقسیم می‌شود"><strong>SHA_2</strong></span></div>

    - <div dir="rtl" align="right"><span title=""><strong>SHA2-224</strong></span></div>

    - <div dir="rtl" align="right"><span title=""><strong>SHA2-256</strong></span></div>

    - <div dir="rtl" align="right"><span title=""><strong>SHA2-384</strong></span></div>

    - <div dir="rtl" align="right"><span title=""><strong>SHA2-512</strong></span></div>

  - <div dir="rtl" align="right"><span title="آخرین عضو خانواده الگوریتم امن درهم‌ساز است که توسط مؤسسه ملی فناوری و استانداردها در سال ۲۰۱۵ منتشر شد. SHA-3 یک زیر مجموعه از خانواده گسترده‌تر به نام Keccak است. این روش نیز براساس اندازه خروجی به ۴ دسته تقسیم می‌شود و همان‌گونه که پرواضح است الگوریتم با طول ۵۱۲ امن‌ترین آن است "><strong>SHA_3 (Keccak)</strong></span></div>

    - <div dir="rtl" align="right"><span title=" "><strong>SHA3-224</strong></span></div>

    - <div dir="rtl" align="right"><span title=" "><strong>SHA3-256</strong></span></div>

    - <div dir="rtl" align="right"><span title=" "><strong>SHA3-384</strong></span></div>

    - <div dir="rtl" align="right"><span title=" "><strong>SHA3-512</strong></span></div>
  
  - <div dir="rtl" align="right"><span title="BLAKE2 یک تابع درهم‌ساز رمزنگاری مبتنی بر BLAKE است و در سال ۲۰۱۲ معرفی شد. براساس ادعای BLAKE2b، این الگوریتم سریعتر از MD5، SHA-1، SHA-2، و SHA-3 در معماری های 64 بیتی x86-64 و ARM است. همچنین امنیت بهتری نسبت به SHA-2 و مشابه SHA-3 فراهم می‌کند."><strong>BLAKE2</strong></span></div>

### <div dir="rtl" align="right"><span title="کد اصالت سنجی پیام یا کد احراز هویت پیام ( کوتاه شده Message authentication code) عبارتست از تکهٔ کوچکی از خود اطلاعات است که برای اصالت‌سنجی یک پیام استفاده می‌شود. مقدار MAC همزمان از صحت دادهٔ پیام و اصالت آن(تاییدی بر شخص ارسال کننده) محافظت می‌کند. این الگوریتم‌های رمزنگاری عمدتا بر پایه الگوریتم‌های درهم ساز(hash) هستند.">**MAC**</span></div>

  - <div dir="rtl" align="right"><span title="یک نمونه الگوریتم HMAC بر پایه الگوریتم SHA256"><strong>HMAC-SHA256</strong></span></div>  
  
  - <div dir="rtl" align="right"><span title="یک نمونه الگوریتم HMAC بر پایه الگوریتم SHA1"><strong>HMAC-SHA1</strong></span></div> 



### <div dir="rtl" align="right"><span title="تابع اشتقاق کلید (Key Derivation Function) نوعی از توابع مبتنی بر hash هستند که از طریق آن‌ها می‌توان یک یا چند کلید را از یک مقدار مخفی مثل کلید اصلی استخراج (مشتق) کرد. استفاده اصلی برای KDF، تولید کلیدهای امن مختلف از یک عبارت یا رمزعبور است.">**KDF**</span></div>
  
  - <div dir="rtl" align="right"><span title="HKDF یک تابع مشتق کلید ساده  بر اساس کد احراز هویت پیام HMAC است. HKDF ترکیبی از دو تابع HKDF-Extract و HKDF-Expand است و به طور رسمی در RFC 5869 توضیح داده شده است."><strong>HKDF</strong></span></div> 
  - <div dir="rtl" align="right"><span title=" تایع اشتقاق کلید برمبنای رمزعبور (Password-Based Key Derivation Function) دارای دو نوع ۱ و ۲ است. PBKDF2 بخشی از سری استانداردهای رمزنگاری کلید عمومی (PKCS) به‌ویژه PKCS #5 v2.0 است که به‌عنوان RFC 2898 نیز منتشر شده است.  ورودی این تابع یک رمزعبور، نمک (salt)، تابع تولید عدد تصادفی و طول کلید خروجی است." ><strong>PBKDF</strong></span></div> 
  - <div dir="rtl" align="right"><span title="Bcrypt یک الگوریتم بر پایه تابع درهم‌ساز رمزنگاری است که برای hash کردن رمزعبور و ذخیره ایمن آن‌ها در برنامه‌ها به گونه ای طراحی شده است که کمتر در معرض حملات سایبری مبتنی بر فرهنگ لغت(Dictionary) است. این الگوریتم در سال ۱۹۹۹ توسط Niels Provos ساخته شد"><strong>bcrypt</strong></span></div> 
  - <div dir="rtl" align="right"><span title="Argon2 یک تابع مشتق کلید است که به عنوان برنده مسابقه درهم سازی(hash) رمزعبور در سال ۲۰۱۵ انتخاب شد. طراحی آن توسط الکس بریوکوف، دانیل دینو و دیمیتری خوراتوویچ از دانشگاه لوکزامبورگ انجام شده است. با این حال حملات موفقی روی این الگوریتم ارائه شده که امنیت رآن را به چالش کشیده است."><strong>Argon2</strong></span></div>  
    

## <div dir="rtl" align="right"><span title=" الگوریتم‌های مهم و کاربردی دیگر که در دسته‌بندی‌های بالا قرار نمی‌گیرند در اینجا قرار دارند.">**Misc**</span></div>
  
### <div dir="rtl" align="right"><span title="رمزنگاری همریخت شکلی از رمزنگاری با قابلیت انجام محاسبات (ضرب یا جمع) روی چند متن رمزگذاری شده بدون دسترسی به کلید مخفی یا رمزنگشایی داده‌ها است که برای حفظ حریم خصوصی کاربردی است.">**Homomorphic Encryption**</span></div> <!-- markmap: fold -->

  - <div dir="rtl" align="right"><span title="رمزگذاری نیمه همریخت به نوعی طرح‌های رمزنگاری اطلاق می‌شود که تنها یک نوع عملگر ریاضی را ارزیابی می‌کند. به عنوان مثال فقط روی عمل جمع(+) یا فقط روی عمل ضرب(*) توانایی همریختی را دارد."><strong>Partial Homomorphic (PHE)</strong><strong></strong></span></div>

    - <div dir="rtl" align="right"><span title="یکی دیگر از ویژگی‌های جالب الگوریتم RSA این است که روی عمل ضرب خاصیت همریختی(Homomorphism) دارد بدین معنا که می‌توان دو متن رمز را با هم ضرب کرد و نتیجه ضرب را بعد از رمزگشایی روی پیام نیز بدست آورد. به عبارت دیگر c1*c2=E(m1*m2) "><strong>RSA</strong></span></div>  
    - <div dir="rtl" align="right"><span title="این طرح یک سیستم رمزنگاری همریختی روی عملگر جمع(+) است. این بدان معنی است که با در اختیار داشتن به کلید عمومی و رمزهای همریخت دو پیام یعنی c1 و c2، می توان عمل جمع را روی مقادیر رمز اعمال کرد و مقدار رمزگذاری شده‌ی دو مقدار m1+m2 را محاسبه کرد. به عبارت دیگر  c1+c2=E(m1+m2)"><strong>Paillier</strong></span></div> 
    
  - <div dir="rtl" align="right"><span title="رمزگذاری کاملا همریخت (FHE) نسل جدیدتری از رمزگذاری همریختی است  که الگوریتم‌های رمزنگاری را قادر می‌سازد روی چندین نوع عمل ریاضی، انجام محاسبات را انجام دهند. این الگوریتم‎‌های همریخت معمولا برپایه ریاضیات مشبکه (lattice) هستند."><strong>Fully Homomorphic (FHE)</strong></span></div> 
      
    - <div dir="rtl" align="right"><span title="نوعی رمزنگاری کاملا همریخت (FHE) است به شکل خاصی با استفاده از <محاسبات تقریبی> روی اعداد ممیز شناور رمزگذاری شده طراحی شده است، و آن را برای محاسبات عددی حفظ حریم خصوصی جذاب می‌کند. "><strong>CKKS</strong></span></div>

    - <div dir="rtl" align="right"><span title="طرح BFV به عنوان یکی از رمزنگاری‌های نسل دوم کاملا همریخت در نظر گرفته می‌شود که اساس آن بر مسائل سخت در ریاضیات مشبکه یعنی مسئله یادگیری حلقه‌ای با خطا (LWE) ساخته شده است."><strong>BFV</strong></span></div> 

### <div dir="rtl" align="right"><span title="تسهیم راز، روش‌هایی است برای توزیع یک راز (متن یا کلید مخفی) در میان یک گروه، به گونه‌ای که هیچ فردی از گروه اطلاعات قابل فهمی درباره راز در اختیار نداشته باشد، اما زمانی که تعداد کافی از افراد «سهم» خود را ترکیب کنند، راز امکان بازسازی داشته باشد. ">**Secret Sharing**</span></div> 

  - <div dir="rtl" align="right"><span title="الگوریتم shamir از رایج‌ترین الگوریتم‌های تسهیم راز (k ,n) است که در برخی برنامه‌ها برای اشتراک‌گذاری و تسهیم  کلیدهای دسترسی به یک راز اصلی استفاده می‌شود. منظور از آن این است که برای دسترسی به یک راز به حداقل k سهم از مجموع n سهم نیاز است. باید دانست که اساس ریاضی این طرح از «قضیه درونیابی لاگرانژ» بهره برداری می‌گیرد."><strong>Shamir</strong></span></div> 
  - <div dir="rtl" align="right"><span title="یک الگوریتم قدیمی و نه چندان مشهور تسهیم راز است که در سال ۱۹۷۹ معرفی شد. این الگوریتم به دلیل فضای حالت بیش از حد بزرگ کارآمد نیست."><strong>Balkley</strong></span></div> 


### <div dir="rtl" align="right"><span title="اثبات صفردانش، روشی است که یک طرف (اثبات‌کننده) می‌تواند به طرف دیگر (تصدیق‌کننده) ثابت کند بیانیهٔ ارائه‌شده صحیح است. اثبات‌کننده (P) سعی می‌کند تصدیق‌کننده (V) را متقاعد کند که ادعایش صحیح است. در حالت عادی، P در این ارتباط یک‌سری اطلاعات به V می‌دهد و V با انجام محاسباتی صحت ادعای P را می‌پذیرد. به عنوان مثال: آلیسان باید بابک را قانع کند که x درست است، امّا طوری‌ که بابک نتواند اطلاعات دیگری خارج از فرایند قانع شدن از آلیسان به‌ دست‌ آورد.">**Zero-Knowledge Proofs**</span></div> 

  - <div dir="rtl" align="right"><span title="این الگوریم یکی از روش‌های استفاده از اثبات صفردانش اس."><strong>Bulletproofs</strong></span></div> 
  
  - <div dir="rtl" align="right"><span title="یکی از پروتکل های اثبات صفر دانش و کوتاه شده Zero Knowledge Succinct Non-Interactive Argument of Knowledge است که بلاکچین هایی Zerocash پیاده‌سازی شده است."><strong>zk-SNARK</strong></span></div>
  
  - <div dir="rtl" align="right"><span title="یکی از پروتکل‌های اثبات صفر دانش و کوتاه شده Zero Knowledge Scalable Transparent Argument of Knowledge است."><strong>zk-STARK</strong></span></div>

### <div dir="rtl" align="right"><span title="در محاسبات، یک رجیستر تغییر بازخورد خطی (LFSR) یک رجیستر شیفتی (انتقالی) است که بیت ورودی آن تابعی خطی از حالت قبلی آن است.از این توابع برای رمزنگاری نیز استفاده می‌شود">**Linear Feedback Shift Register (LFSR)**</span></div>  
  
### <div dir="rtl" align="right"><span title="طرح تعهدی نوعی رمزنگاری بدوی است که به اشخاص این قابلیت را می‌دهد که به یک مقدار انتخابی متعهد شوند در حالی که آن مقدار انتخابی برای دیگران مخفی است، با این حال امکان آشکار کردن مقدار انتخابی بعداً وجود خواهد داشت. ">**Commitment scheme**</span></div>
    
  - <div dir="rtl" align="right"><span title=" "><strong>Pedersen Commitment</strong></span></div> 



