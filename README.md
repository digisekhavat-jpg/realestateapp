# املاک من — نسخه آنلاین

نسخه آنلاین با Node.js, Express, SQLite و JWT.

## اجرا

```bash
npm install
npm start
```

سپس: http://localhost:3000

## مدیر آزمایشی

ایمیل: `admin@melk.local`
رمز پیش‌فرض: `ChangeMe_12345`

برای محیط واقعی حتماً `ADMIN_PASSWORD` و `JWT_SECRET` را در Environment Variables تغییر بدهید.

## نکته

این نسخه MVP است و پیش از استفاده عمومی باید HTTPS، rate limiting، مدیریت امن secretها، بکاپ دیتابیس، ذخیره‌سازی امن تصاویر، پرداخت و سرویس‌های احراز هویت رسمی تکمیل شوند.
