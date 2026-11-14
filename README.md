# Wiunix Terminal — Free Persian RTL Terminal for Windows

[فارسی](#فارسی) · [English](#english) · [Releases](https://github.com/wiunix/wiunix-rtlterminal/releases)

## فارسی

**ویونیکس ترمینال یک ترمینال رایگان ویندوز برای خواندن و نوشتن متن فارسی راست‌به‌چپ است.** وقتی یک پیام فارسی کنار دستور انگلیسی، مسیر فایل یا عدد می‌آید، نمایش دوجهته (BiDi) کمک می‌کند هر قسمت را در جهت خودش بخوانید. عربی و عبری هم پشتیبانی می‌شوند. برنامه برای توسعه‌دهنده‌ها و مدیران سیستمی طراحی شده که با خروجی فارسی، PowerShell، خط فرمان ویندوز، WSL یا SSH کار می‌کنند.

### دانلود رایگان برای ویندوز

برای رایانه‌های x64 با ویندوز ۱۱ یا ویندوز ۱۰ از بیلد ۱۹۰۴۱ به بعد.

- [دانلود نسخهٔ قابل‌حمل ۰٫۱۱٫۱ از GitHub](https://github.com/wiunix/wiunix-rtlterminal/releases/download/v0.11.1/WiunixTerminal-0.11.1-x64-portable.zip) · [فایل بررسی SHA‑256](https://github.com/wiunix/wiunix-rtlterminal/releases/download/v0.11.1/SHA256.txt)
- [نصب رایگان از Microsoft Store](https://apps.microsoft.com/detail/9P8N73LVMHP8) برای دریافت به‌روزرسانی‌ها از فروشگاه و دسترسی به ابزارهای اختیاری PowerShell.
- [صفحهٔ فارسی محصول و دانلود از سایت ویونیکس](https://wiunix.ir/products/terminal/#download)

برای اجرای نسخهٔ قابل‌حمل، همهٔ فایل‌های ZIP را در پوشه‌ای که اجازهٔ نوشتن در آن دارید از حالت فشرده خارج کنید و `WiunixTerminal.exe` را باز کنید. تنظیمات در همان پوشه می‌مانند. برای به‌روزرسانی این نسخه، انتشارهای GitHub را بررسی کنید.

### نمایش فارسی و کار با شل‌ها

- **جهت متن برای هر پروفایل.** از تنظیمات پروفایل، حالت Auto را برای تشخیص خودکار انتخاب کنید. RTL جهت پایه را راست‌به‌چپ می‌گذارد، LTR آن را چپ‌به‌راست می‌کند و Off نمایش دوجهته را خاموش می‌کند.
- **متن فارسی کنار خروجی فنی.** برای نمونه، می‌توانید خطی مثل «گزارش آماده شد | D:/Work/app | ۳ فایل» را در کنار فرمان‌های انگلیسی بخوانید. همین قابلیت برای متن عربی و عبری هم کاربرد دارد.
- **چند شل در یک پنجره.** PowerShell، Command Prompt، WSL و نشست‌های SSH را در تب یا پنل جدا باز کنید. فونت، تم، میانبر، پروفایل و فهرست فرمان‌ها را مطابق شیوهٔ کارتان تنظیم کنید. برای WSL و شل‌های دیگر، ابتدا خود آن ابزار را روی ویندوز آماده کنید.

### ابزارهای توسعه در نسخهٔ Store

این ابزارها با فعال‌کردن اختیاری یکپارچه‌سازی PowerShell در دسترس‌اند. PowerShell 7 پیشنهاد می‌شود و Windows PowerShell 5.1 هم پشتیبانی می‌شود. بخش Developer Hub ابزارها را در تب ترمینال باز می‌کند.

| قابلیت | کاربرد |
| --- | --- |
| پروژه‌ها، نشست‌ها و وظایف | مسیر و تب‌های پروژه را ذخیره کنید، نشست نام‌دار را دوباره باز کنید و وظایف npm، .NET، Cargo و Python را قبل از اجرا ببینید. |
| تاریخچه و نتیجهٔ فرمان | فرمان‌ها را بر اساس پروژه، زمان، مدت اجرا یا نتیجه پیدا کنید. فرمان‌های پرکاربرد را نگه دارید و ثبت دستورهای حساس را محدود کنید. بلاک‌های فرمان می‌توانند کد خروج و مدت اجرا را نشان دهند. |
| Git، SSH و پورت‌ها | شاخه، تغییرات فایل و وضعیت همگام‌سازی Git را ببینید. میزبان‌ها را از تنظیمات SSH بخوانید و فرایندی را که روی یک پورت گوش می‌دهد پیدا کنید. توقف فرایند تأیید می‌خواهد. |
| ابزارهای روزمره | مصرف CPU، RAM و دیسک را ببینید، JSON را مرتب کنید، لاگ‌ها را فیلتر کنید، دستور چندخطی را در ویرایشگر باز کنید و برای کارهای طولانی اعلان پایان بگیرید. گردش‌کارهای محلی قابل استفادهٔ دوباره‌اند. |
| تنظیمات و محیط توسعه | وضعیت Git، SSH، WSL، .NET، Node.js، Python، Docker و PowerShell را بررسی کنید. اصلاح چیدمان صفحه‌کلید و تقویم‌های جلالی، هجری، عبری و میلادی برای اعلانِ خط فرمان اختیاری‌اند. تنظیمات را می‌توانید بدون کلیدهای محرمانه به JSON منتقل کنید. |

بعد از فعال‌کردن یکپارچه‌سازی، `wx help` فهرست دستورها را نشان می‌دهد. برای نمونه، `wx git` وضعیت Git پروژه را باز می‌کند و `wx doctor` ابزارهای محیط توسعه را بررسی می‌کند.

### دستیار فرمان و حریم خصوصی

دستیار اختیاری است و از ابتدا خاموش است. می‌توانید از قواعد آفلاین، مدل محلی Ollama یا ارائه‌دهنده‌ای مثل OpenAI، Gemini یا Claude استفاده کنید. پیشنهاد دستور با سطح ریسک و دلیل آن نمایش داده می‌شود و اجرای آن با شماست. اگر درخواست آنلاین بفرستید، متن و زمینه‌ای که ارسال می‌کنید به سرویس انتخابی می‌رسد. کلیدها در فضای محافظت‌شدهٔ ویندوز نگه‌داری می‌شوند یا از متغیر محیطی خوانده می‌شوند و در خروجی تنظیمات نمی‌آیند. **خود ترمینال رایگان است.** سرویس آنلاین اختیاری ممکن است هزینهٔ مصرف جداگانه داشته باشد. [حریم خصوصی ویونیکس](https://wiunix.com/privacy/)

## English

**Wiunix Terminal is a free RTL terminal for Windows built for people who work with Persian text and English shell commands.** Native bidirectional rendering helps you read a Persian message beside a Latin path, command or number on the same line. Arabic and Hebrew are also supported. It fits Windows-based development and administration with PowerShell, Command Prompt, WSL or SSH.

### Free Windows download

Requires an x64 PC with Windows 11 or Windows 10 build 19041 or newer.

- [Download the 0.11.1 portable ZIP from GitHub](https://github.com/wiunix/wiunix-rtlterminal/releases/download/v0.11.1/WiunixTerminal-0.11.1-x64-portable.zip) · [SHA‑256 checksum](https://github.com/wiunix/wiunix-rtlterminal/releases/download/v0.11.1/SHA256.txt)
- [Install free from Microsoft Store](https://apps.microsoft.com/detail/9P8N73LVMHP8) for Store-managed updates and access to the optional PowerShell tools.
- [English product page and direct download from Wiunix](https://wiunix.com/products/terminal/#download)

For portable use, extract the entire ZIP to a writable folder and open `WiunixTerminal.exe`. Settings stay in that folder. Check GitHub Releases for new portable builds.

### Read Persian output in your Windows shells

- **Control text direction per profile.** Choose Auto to detect direction, RTL for a right-to-left base direction, LTR for a left-to-right base direction, or Off to disable bidirectional rendering.
- **Keep mixed output readable.** A Persian build message such as «گزارش آماده شد» can share a line with a path such as `D:/Work/app`. The same rendering support applies to Arabic and Hebrew text.
- **Work across shells.** Open PowerShell, Command Prompt, WSL and SSH in tabs and split panes. Customize profiles, fonts, themes and shortcuts, or find actions in the command palette. WSL and other shells use the tools already installed on your PC.

### Developer tools in the Store edition

Enable the optional PowerShell integration to use these tools. PowerShell 7 is recommended, and Windows PowerShell 5.1 is also supported. Developer Hub opens the tools in terminal tabs.

| Feature | What you can do |
| --- | --- |
| Project workspaces and tasks | Save project paths and tabs, reopen named sessions, and preview detected npm, .NET, Cargo or Python tasks before running them. |
| Searchable command history | Find commands by project, time, duration or result, save favorites and exclude sensitive commands. Command blocks can show exit status and elapsed time. |
| Git, SSH and ports | Check Git branch, changes and ahead/behind status, use hosts from SSH config, and find the process listening on a port. Process stops require confirmation. |
| Output, monitoring and workflows | View CPU, memory and disk usage, format JSON, filter logs, edit multiline commands, get completion notifications and reuse parameterized local workflows. |
| Settings and environment checks | Check PowerShell, Git, SSH, WSL, .NET, Node.js, Python and Docker. Opt into keyboard-layout correction or a Jalali, Hijri, Hebrew or Gregorian prompt calendar. Export settings without provider credentials. |

After enabling integration, open `wx help` for the command list. Start with `wx git` for the project’s Git view or `wx doctor` to check your development environment.

### Optional command assistance and privacy

Command assistance starts disabled. Choose offline rules, a local Ollama model or an online provider such as OpenAI, Gemini or Claude. Review the suggestion, its risk level and reasons before copying or inserting it. You decide whether to run it. Online requests send the prompt and context you submit to the selected provider. Provider keys use protected Windows storage or a configured environment variable and stay out of settings exports. **The terminal is free.** An optional online provider can charge for its own usage. [Wiunix privacy notice](https://wiunix.com/privacy/)

Wiunix Terminal is independently developed by Wiunix Ltd and derives from MIT-licensed Microsoft Windows Terminal. The portable ZIP includes the MIT license and third-party notices.
