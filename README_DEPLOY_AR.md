# ذرة سيف — نسخة Supabase + استضافة ثابتة

هذه النسخة لا تحتاج Node.js ولا Railway.

## التشغيل المحلي
افتح المجلد عبر VS Code واستخدم إضافة Live Server، أو:
```bash
python -m http.server 8080
```

## الروابط
- واجهة الموقع: `index.html`
- لوحة الإدارة: `admin.html`

## النشر
ارفع محتويات هذا المجلد إلى مستودع GitHub، ثم اربطه بـ Cloudflare Pages.
إعدادات Cloudflare:
- Framework preset: None
- Build command: اتركه فارغًا
- Build output directory: `/`

## مهم
بيانات الموقع والصور محفوظة في Supabase.
