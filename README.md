# منصة التحقق من الحسابات المالية

منصة متكاملة للتحقق من موثوقية الحسابات المالية عبر الإنترنت وتوثيق المعاملات.

## المميزات

- تسجيل وتوثيق المستخدمين
- البحث عن الحسابات المالية
- تقييم وتصنيف الحسابات
- نظام الإبلاغ عن الاحتيال
- دعم متعدد اللغات (العربية، الفرنسية، الإنجليزية)
- لوحة تحكم للمستخدمين
- نظام تذاكر الدعم الفني

## المتطلبات الأساسية

- Node.js (v14 أو أحدث)
- PostgreSQL (v12 أو أحدث)
- npm أو yarn

## التثبيت

1. استنسخ المستودع:
```bash
git clone https://github.com/yourusername/account-verification-platform.git
cd account-verification-platform
```

2. قم بتثبيت التبعيات:
```bash
npm run install-all
```

3. قم بإعداد ملف البيئة:
- انسخ ملف `.env.example` إلى `.env`
- قم بتحديث المتغيرات البيئية حسب إعداداتك

4. قم بإنشاء قاعدة البيانات:
```bash
psql -U postgres -c "CREATE DATABASE account_verification"
psql -U postgres -d account_verification -f server/db/schema.sql
```

5. ابدأ التطبيق:
```bash
npm run dev
```

## البيئة الإنتاجية

1. قم ببناء التطبيق:
```bash
npm run build
```

2. ابدأ الخادم:
```bash
npm start
```

## المساهمة

نرحب بمساهماتكم! يرجى اتباع هذه الخطوات:
1. Fork المستودع
2. إنشاء فرع لميزتك (`git checkout -b feature/amazing-feature`)
3. Commit التغييرات (`git commit -m 'إضافة ميزة رائعة'`)
4. Push إلى الفرع (`git push origin feature/amazing-feature`)
5. فتح Pull Request

## الترخيص

هذا المشروع مرخص تحت رخصة MIT - انظر ملف [LICENSE](LICENSE) للتفاصيل.

## الاتصال

- الموقع: [your-website.com](https://your-website.com)
- البريد الإلكتروني: your-email@example.com
