<div align="center">

<img src="assets/logo.png" width="200" alt="Vesta Agent">

<a href="https://vesta-agent.github.io"><img src="https://img.shields.io/badge/Website-vesta--agent.github.io-6d5cff?style=for-the-badge" alt="Website"></a> <a href="https://t.me/VestaAgentSupportBot"><img src="https://img.shields.io/badge/%D9%BE%D8%B4%D8%AA%DB%8C%D8%A8%D8%A7%D9%86%DB%8C-Telegram-3b82f6?style=for-the-badge&logo=telegram&logoColor=white" alt="پشتیبانی در تلگرام"></a>

**وب‌سایت: [vesta-agent.github.io](https://vesta-agent.github.io/)**

# Vesta Agent

**دستیار هوش مصنوعی شخصی شما — روی دستگاه خودتان، با زبان خودتان**

[![Latest](https://img.shields.io/github/v/release/Vesta-Agent/vesta-agent-releases?label=%D9%86%D8%B3%D8%AE%D9%87&color=3b82f6&style=for-the-badge)](https://github.com/Vesta-Agent/vesta-agent-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Vesta-Agent/vesta-agent-releases/total?color=7c3aed&style=for-the-badge)](https://github.com/Vesta-Agent/vesta-agent-releases/releases)
![Platforms](https://img.shields.io/badge/Windows%20%7C%20Android%20%7C%20Linux-0b1220?style=for-the-badge)

ساخته‌شده توسط **Persian Studio** · [**English**](README.md)

</div>

<div dir="rtl">

## قابلیت‌ها

- **ایجنت‌های هوشمند** — با موس، با دستور یا هر دو، به انتخاب خودتان
- **دیدن صفحه** و **تماس صوتی** فارسی، با اجازه‌ی شما
- **حافظه‌ی هوشمند فقط روی دستگاه خودتان** — بدون هیچ سروری
- **چند کلید API برای هر ایجنت** — با تمام شدن یکی، خودکار سراغ بعدی می‌رود
- **تلگرام** — ربات یا حساب شخصی، با ارسال زمان‌بندی‌شده
- **پروکسی داخلی** با آموزش قدم‌به‌قدم برای کاربران ایران
- **آپدیت خودکار و بی‌صدا** · **۹ زبان** · **مرور امن** پیش از هر اقدام حساس

---

## دانلود و نصب

### ویندوز ۱۰ / ۱۱

**[ دانلود VestaAgent-1.4.0-windows-x64-setup.exe](https://github.com/Vesta-Agent/vesta-agent-releases/releases/latest/download/VestaAgent-1.4.0-windows-x64-setup.exe)**

1. فایل را دانلود و اجرا کنید.
2. اگر صفحه‌ی آبی «Windows protected your PC» آمد، روی **More info** و بعد **Run anyway** بزنید.
3. مراحل نصب را تا آخر بروید؛ Vesta Agent در منوی Start قرار می‌گیرد.

### ویندوز ۷ / ۸

**[ دانلود VestaAgent-1.4.0-windows7-8-legacy-setup.exe](https://github.com/Vesta-Agent/vesta-agent-releases/releases/latest/download/VestaAgent-1.4.0-windows7-8-legacy-setup.exe)**

1. فایل را اجرا کنید.
2. در هشدار SmartScreen روی **More info** > **Run anyway** بزنید.
3. نصب را کامل کنید. این نسخه آپدیت خودکار ندارد؛ نسخه‌های جدید را از همین صفحه بگیرید.

### اندروید

**[ دانلود VestaAgent-1.4.0-android.apk](https://github.com/Vesta-Agent/vesta-agent-releases/releases/latest/download/VestaAgent-1.4.0-android.apk)**

1. > اگر نسخه‌ی قدیمی **My Agent** زیر 1.2 نصب دارید، اول آن را حذف کنید.
2. فایل APK را باز کنید.
3. اگر پرسید، اجازه‌ی **نصب برنامه‌های ناشناس** (Install unknown apps) را برای مرورگر یا فایل‌منیجر روشن کنید.
4. **Install** را بزنید. اگر Play Protect هشدار داد، «Install anyway» را بزنید.

### لینوکس

**deb (اوبونتو / دبیان):** [ VestaAgent-1.4.0-linux-amd64.deb](https://github.com/Vesta-Agent/vesta-agent-releases/releases/latest/download/VestaAgent-1.4.0-linux-amd64.deb)

```bash
sudo apt install ./VestaAgent-1.4.0-linux-amd64.deb
# یا: sudo dpkg -i VestaAgent-1.4.0-linux-amd64.deb && sudo apt -f install
```

**AppImage (همه‌ی توزیع‌ها):** [ VestaAgent-1.4.0-linux-x86_64.AppImage](https://github.com/Vesta-Agent/vesta-agent-releases/releases/latest/download/VestaAgent-1.4.0-linux-x86_64.AppImage)

```bash
chmod +x VestaAgent-1.4.0-linux-x86_64.AppImage
./VestaAgent-1.4.0-linux-x86_64.AppImage
```

### VPS / سرور

> **به‌زودی.** نصب روی سرور (۲۴ ساعته روشن) در حال آماده‌سازی است و فعلاً نصب‌کننده‌ی آن غیرفعال است.

---

## راه‌اندازی اولیه

1. **کلید API رایگان بگیرید:**
 - **Google Gemini:** به [aistudio.google.com/apikey](https://aistudio.google.com/apikey) بروید و «Create API key» را بزنید.
 - **OpenRouter:** در [openrouter.ai/keys](https://openrouter.ai/keys) ثبت‌نام کنید و یک کلید بسازید (مدل‌های رایگان دارد).
2. کلید را در **تنظیمات > کلیدها** وارد کنید. می‌توانید چند کلید بگذارید.
3. **کاربران ایران:** در **تنظیمات > پروکسی** آدرس پروکسی را وارد کنید (مثلاً `127.0.0.1:10808` از v2rayN / v2rayNG / NekoBox) و دکمه‌ی **تست** را بزنید. آموزش کامل داخل برنامه است.

## سؤالات متداول

<details><summary>چطور کمک بگیرم یا مشکلی را گزارش کنم؟</summary>
به ربات پشتیبانی ما در تلگرام پیام بدهید: <a href="https://t.me/VestaAgentSupportBot">@VestaAgentSupportBot</a>. توضیح، عکس صفحه یا پیام صوتی بفرستید تا یک شماره‌ی تیکت بگیرید. جواب در همان چت می‌آید.
</details>

<details><summary>اطلاعات من کجا ذخیره می‌شود؟</summary>
همه‌چیز (چت‌ها، حافظه، ایجنت‌ها، کلیدها به‌صورت رمزدار) فقط روی دستگاه خودتان است. فقط پیام شما برای جواب گرفتن به سرویس هوش مصنوعی‌ای که کلیدش را گذاشته‌اید فرستاده می‌شود.
</details>

<details><summary>چرا ویندوز هشدار می‌دهد؟</summary>
چون برنامه هنوز گواهی امضای تجاری ندارد. فایل را فقط از همین صفحه بگیرید و با SHA256 بررسی کنید.
</details>

<details><summary>از نسخه‌ی 1.3 آپدیت خودکار نمی‌شود؟</summary>
آدرس آپدیت تغییر کرده؛ 1.4.0 را یک بار دستی نصب کنید. از آن به بعد آپدیت خودکار است.
</details>

<details><summary>بدون اینترنت کار می‌کند؟</summary>
بله، با Ollama می‌توانید مدل را روی خود کامپیوتر اجرا کنید.
</details>

## پشتیبانی

سؤال، مشکل یا پیشنهادی دارید؟ **[پشتیبانی در تلگرام: @VestaAgentSupportBot](https://t.me/VestaAgentSupportBot)**. یکی از دکمه‌های «گزارش مشکل»، «پرسیدن سؤال» یا «پیشنهاد» را بزنید یا مستقیم پیامتان را بنویسید. ارسال عکس، فایل و پیام صوتی هم امکان‌پذیر است.

## بررسی سلامت فایل (SHA256)

فایل [SHA256SUMS](https://github.com/Vesta-Agent/vesta-agent-releases/releases/latest/download/SHA256SUMS) را کنار فایل دانلودی بگذارید:

```bash
sha256sum -c SHA256SUMS --ignore-missing # لینوکس
```
```powershell
Get-FileHash .\VestaAgent-1.4.0-windows-x64-setup.exe -Algorithm SHA256 # ویندوز
```

## یادداشت‌های انتشار

[همه‌ی نسخه‌ها](https://github.com/Vesta-Agent/vesta-agent-releases/releases) · [نسخه‌ی 1.4.0](https://github.com/Vesta-Agent/vesta-agent-releases/releases/tag/v1.4.0)

</div>

<div align="center"><sub>© 2026 Persian Studio · این مخزن فقط فایل‌های نصبی را دارد.</sub></div>
