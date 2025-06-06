عنوان: 
طراحی و پیاده‌سازی ماشین حساب ساده با استفاده از کی‌پد ماتریسی و آردوینو
هدف آزمایش:
هدف اصلی این آزمایش، طراحی و پیاده‌سازی یک ماشین حساب ساده با استفاده از کی‌پد ماتریسی 4x4 و برد آردوینو UNO است که قادر به دریافت دو عدد و یک عملگر (+، -، *، /) از طریق کی‌پد بوده و نتیجه‌ی عملیات را از طریق ارتباط سریال به کامپیوتر ارسال کند.
تئوری آزمایش:
•	برد آردوینو UNO به عنوان میکروکنترلر اصلی، وظیفه‌ی خواندن ورودی از کی‌پد، انجام محاسبات و ارسال خروجی از طریق پورت سریال را بر عهده دارد.
•	کی‌پد ماتریسی 44 x :یک رابط ورودی است که به کاربر اجازه می‌دهد اعداد و عملگرهای مورد نظر خود را وارد کند. فشردن هر کلید، اتصال الکتریکی بین یک ردیف و یک ستون خاص را برقرار می‌کند که توسط آردوینو تشخیص داده می‌شود.
•	کتابخانه Keypad این کتابخانه توابع لازم برای برقراری ارتباط و خواندن کلیدهای فشرده شده از کی‌پد ماتریسی را فراهم می‌کند و فرآیند کار با کی‌پد را تسهیل می‌بخشد.
•	ارتباط سریال: برای ارسال داده‌ها (اعداد ورودی، عملگر و نتیجه‌ی محاسبات) از آردوینو به کامپیوتر استفاده می‌شود. از Serial Monitor در محیط Arduino IDE می‌توان برای مشاهده‌ی این داده‌ها استفاده کرد.
•	متغیرها: در این برنامه از متغیرهای num1 و num2 برای ذخیره‌سازی اعداد ورودی به صورت رشته‌ای، متغیر op برای ذخیره‌سازی عملگر انتخاب شده و متغیر enteringSecondNumber برای تعیین وضعیت ورود عدد دوم استفاده شده است.
•	ساختار شرطی و سوییچ: از ساختارهای شرطی (if و else if) برای تشخیص نوع کلید فشرده شده (عدد یا عملگر) و از ساختار switch برای انجام عملیات محاسباتی بر اساس عملگر انتخاب شده استفاده شده است.
شرح مدار و قطعات مورد استفاده:
•	 برد آردوینو UNO
•	1 عدد کی‌پد ماتریسی 44 x 
•	 سیم‌های مخابراتی 

روش انجام آزمایش:
1.	اتصالات سخت افزاری

•	کی‌پد ماتریسی را روی برد بورد قرار می‌دهیم.
•	پین‌های ردیف‌های کی‌پد (ROWS) را با استفاده از سیم‌های مخابراتی به پین‌های دیجیتال 9، 8، 7 و 6 برد آردوینو متصل می‌کنیم. (به ترتیب با سیم های سفید، نارنجی ، بنفش ،قرمز)
•	پین‌های ستون‌های کی‌پد (COLS) را با استفاده از سیم‌های مخابراتی به پین‌های دیجیتال 5، 4، 3 و 2 برد آردوینو متصل می‌کنیم. (به ترتیب با سیم های مشکی ، آبی ، زرد ، سبز)
•	ترتیب اتصال ردیف‌ها و ستون‌ها به پین‌های آردوینو باید با آرایه‌های rowPins و colPins در کد آردوینو مطابقت داشته باشد.

نتیجه گیری:
نتیجه‌گیری کلی آزمایش: در این آزمایش، یک ماشین حساب ساده با استفاده از کی‌پد ماتریسی 4x4 و برد آردوینو UNO با موفقیت طراحی و پیاده‌سازی شد. کاربران توانستند با وارد کردن دو عدد و یک عملگر از طریق کی‌پد، نتیجه‌ی عملیات را بر روی Serial Monitor مشاهده کنند. این پروژه نشان می‌دهد که چگونه می‌توان از کی‌پد ماتریسی به عنوان یک رابط ورودی برای ایجاد برنامه‌های تعاملی با آردوینو استفاده کرد و مفاهیم اولیه‌ی دریافت ورودی، انجام محاسبات و نمایش خروجی را به صورت عملی تجربه نمود. قابلیت‌هایی مانند مدیریت خطا در تقسیم بر صفر و پاک کردن ورودی نیز در این ماشین حساب پیاده‌سازی شده است.




https://github.com/user-attachments/assets/2377d4cd-d6dc-402a-bbdd-8b4dbf02ae39

![photo18529385189](https://github.com/user-attachments/assets/c076f83e-13b9-4bfb-a674-71b75b713660)
![keypad - Calculator](https://github.com/user-attachments/assets/6eeb010c-4ca7-41df-ae8b-7ceda5aa3215)
[keypad - Calculator.pdf](https://github.com/user-attachments/files/20194216/keypad.-.Calculator.pdf)
[keypad - Calculator.docx](https://github.com/user-attachments/files/20194215/keypad.-.Calculator.docx)
