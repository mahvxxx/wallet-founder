# 🔍 Wallet Founder crated by Mahvxxx™
# Version : 2.5


**Wallet Founder** یک اسکریپت خودکار برای تولید و بررسی کیف پول‌های بیتکوین است. این ابزار آدرس‌های بیتکوین را به‌صورت تصادفی ایجاد کرده و موجودی آن‌ها را بررسی می‌کند. همچنین با استفاده از یک ربات تلگرامی، گزارش‌های وضعیت و هشدارها را برای شما ارسال می‌کند.  

🚀 **ویژگی‌ها:** بررسی سریع، گزارش‌دهی هوشمند، هشدار در صورت بروز مشکل، و اجرای آسان روی ویندوز، لینوکس و مک.  

---
## ✨ ویژگی‌های برجسته  

✅ **بررسی خودکار کیف پول‌های بیتکوین** – تولید و بررسی بی‌نهایت آدرس بیتکوین به‌صورت خودکار.  
✅ **اتصال به تلگرام** – ارسال گزارش‌های وضعیت و هشدارها از طریق ربات تلگرامی و تست وضعیت اسکریپت.  
✅ **ثبت لاگ‌های بررسی و خطاها** – ذخیره اطلاعات کیف پول‌های بررسی‌شده، خطاها و ولت‌های دارای موجودی.  
✅ **سیستم گزارش‌دهی هوشمند** – ارسال گزارش کامل از تعداد بررسی‌ها، خطاها و کیف پول‌های معتبر هر ۶ ساعت.  
✅ **شناسایی مشکلات در اجرا** – در صورتی که بیش از ۱ ساعت هیچ کیف پولی بررسی نشود، هشدار ارسال می‌شود.  
✅ **نصب آسان** – تنها با اجرای یک دستور، تمام وابستگی‌ها نصب شده و پروژه آماده اجرا می‌شود.  
✅ **سازگاری با تمام سیستم‌عامل‌ها** – قابل اجرا در ویندوز، لینوکس و مک.  

# آموزش اجرا 
## دانلود ریپازیتوری
### 🔹 روی لینوکس و مک:



برای دانلود ریپازیتوری ، کافی است دستور زیر را در ترمینال خود در جایی که میخواهید دانلود شود وارد کنید:

```bash
curl -sSL https://raw.githubusercontent.com/mahvxxx/wallet-founder/main/setup.sh | bash
```
پوشه wallet-founder در دایرکتوری شما دانلود شد

### 🔹 روی ویندوز:
برای دانلود ریپازیتوری ، کافی است اقدامات زیر را انجام دهید :

1. ابتدا یک Command Prompt (CMD) باز کنید.

2. سپس دستور زیر را وارد کنید:

   ```batch
   powershell -Command "Invoke-WebRequest -Uri 'https://github.com/mahvxxx/wallet-founder/raw/main/setup.bat' -OutFile 'setup.bat'; Start-Process 'setup.bat'"
   ```

## 🚀 تنظیمات ربات تلگرام  

برای دریافت پیام‌های وضعیت و هشدارها در تلگرام، ابتدا باید توکن ربات و Chat ID خود را در فایل **TelegramBot-config.txt** تنظیم کنید.  

### 1️⃣ دریافت توکن ربات  
اگر ربات تلگرام ندارید، مراحل زیر را دنبال کنید:  
1. به **[@BotFather](https://t.me/BotFather)** در تلگرام پیام دهید.  
2. دستور `/newbot` را ارسال کنید و یک نام برای ربات خود انتخاب کنید.  
3. توکن ارائه‌شده را کپی کنید (چیزی شبیه به `123456789:ABCDEF...`).  

### 2️⃣ دریافت Chat ID  
برای دریافت Chat ID خود، این مراحل را طی کنید:  
1. به ربات **[@userinfobot](https://t.me/useridinfobot)** پیام دهید.  
2. Chat ID شما نمایش داده خواهد شد.  

### 3️⃣ تنظیم فایل `TelegramBot-config.txt`  
حالا فایل **TelegramBot-config.txt** را باز کرده و اطلاعات خود را به این شکل وارد کنید:  

📌 **نکته:** این فایل را به اشتراک نگذارید، چون اطلاعات خصوصی شما را در خود دارد!  

## ▶️ اجرای اسکریپت  

بعد از دانلود و تنظیم ربات تلگرام، می‌توانید اسکریپت را اجرا کنید.  

### 🔹 روی لینوکس و مک:
ترمینال را باز کنید و دستورات زیر را وارد کنید:  

```bash
cd wallet-founder
python3 wallet-founder.py
```
### 🔹 روی ویندوز:
ترمینال را باز کنید و دستورات زیر را وارد کنید: 
```cmd
cd wallet-founder
python wallet-founder.py
```
