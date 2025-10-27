# نسار – سامانه نمایش شماره صندلی آزمون‌های پیام نور

<div dir="rtl">

**نِسار** یک وب‌اپلیکیشن پیشرفته و مدرن است که با بهره‌گیری از طراحی مبتنی بر **تجربه کاربری نوین** و سبک **گلس‌مورفیسم (Glassmorphism)**، به دانشجویان دانشگاه پیام نور این امکان را می‌دهد تا **برنامه امتحانات، شماره صندلی، محل برگزاری و وضعیت آزمون‌های خود را به‌صورت یکپارچه و متمرکز** مشاهده و مدیریت کنند.

## دمو دانشجو :
https://Seat.PnuBijar.ac.ir

- User : 970100001
- Pass : 1234567890


## دمو ادمین :
https://Seat.PnuBijar.ac.ir

- User : admin2902
- Pass : 2M0M20SEEEM0YEZ2X195YCS9V2TD8K10

## مهم‌ترین قابلیت‌ها

- 🪟 **رابط کاربری شیشه‌ای**: تم iOS–style با بلور، گرادیان و انیمیشن‌های نرم در کارت‌ها و فرم‌ها
- � **هشدارهای تعاملی**: SweetAlert2 با شمارنده‌ی معکوس مینیمال، واکنش‌گرا و هماهنگ با تم
- 📱 **PWA کامل**: نصب روی موبایل/دسکتاپ، آیکن‌های جدید `pwa-icons/` و پشتیبانی از حالت آفلاین
- ⚡ **کش هوشمند**: Service Worker با استراتژی‌های به‌روزشده (Network-first برای منابع اصلی و Cache-first برای بقیه)
- 🔐 **امنیت و حریم خصوصی**: رمزگذاری شناسه‌ها، نشست ۳۰ روزه با تشخیص هوشمند نمایش/مخفی‌سازی لوگو
- 🌐 **RTL و فونت فارسی**: استفاده از Vazir با ارقام هم‌عرض (tabular) برای خوانایی بهتر تایمر و داده‌ها



## تغییرات نسخه ۲.۳.۱
- اصلاح مستندات و هماهنگی شماره نسخه با سورس و ورک‌فلو
- بهبود توضیحات نصب و وابستگی‌ها
- تگ‌گذاری و انتشار نسخه جدید


## معماری و راه‌اندازی سریع

### راه‌اندازی با Docker (توصیه‌شده)

اگر Docker و Docker Compose روی سیستم شما نصب است، این روش سریع‌ترین راه برای راه‌اندازی است. تمام وابستگی‌ها (PHP، MySQL، phpMyAdmin) در کانتینرها اجرا می‌شوند.

#### پیش‌نیازها

- پورت‌های 18080 (وب‌سایت)، 3306 (MySQL)، 18081 (phpMyAdmin) آزاد باشند.

#### نصب Docker و Docker Compose (اگر نصب نیست)

```bash
sudo apt update
sudo apt install apt-transport-https ca-certificates curl gnupg lsb-release
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt update
sudo apt install docker-ce docker-ce-cli containerd.io docker-compose-plugin
sudo systemctl start docker
sudo systemctl enable docker
```

#### مراحل راه‌اندازی

**گزینه سریع**: اجرای اسکریپت خودکار:
```bash
curl -fsSL https://raw.githubusercontent.com/MehdiHassaniir/PnuSeatPublic/master/setup.sh | bash
```
یا دانلود و اجرای دستی:
```bash
wget https://raw.githubusercontent.com/MehdiHassaniir/PnuSeatPublic/master/setup.sh
chmod +x setup.sh
./setup.sh
```

پروژه تحت مجوز MIT ارائه شده است. برای گزارش باگ یا پیشنهاد، Pull Request یا Issue در GitHub باز کنید.

---

**نسار** – مهدی حسنی

</div>
