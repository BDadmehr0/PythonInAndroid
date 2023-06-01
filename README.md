# PythonInAndroid
Create Android App with Python Framework Kivy


برای تبدیل این کد ساده print('hello') به یک برنامه گرافیکی برای اندروید، می‌توان از چندین روش استفاده کرد. این‌جا یکی از روش‌های ممکن با استفاده از کتابخانه Kivy را برای شما توضیح می‌دهم:

ابتدا، نصب Kivy را در سیستم خود انجام دهید. برای نصب، می‌توانید از دستور زیر استفاده کنید:

```pip install kivy```

سپس، یک فایل با پسوند .py ایجاد کنید و محتوای زیر را در آن قرار دهید

سپس، برای تبدیل برنامه به فرمت APK از طریق Kivy Buildozer، شما می‌توانید از دستورات زیر استفاده کنید

نصب Buildozer:

```pip install buildozer```

ایجاد یک فایل به نام buildozer.spec در همان دایرکتوری و اضافه کردن تنظیمات زیر به آن:
    
سپس، اجرای دستور زیر برای ساخت فایل APK:
```buildozer android debug```

