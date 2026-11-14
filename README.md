# EM-TECH-STUDIO

الموقع الرسمي لاستوديو EM-TECH-STUDIO (تطبيقات، ألعاب، أدوات، ومعلومات المطور) مع تقديم تطبيق العمارة.

## نشر الموقع على Cloudflare Workers

- اسم الـ Worker الحالي: `wild-shadow-ac76`
- المستودع: `emadmedo19/Emadmohamed`
- الفرع المعتمد للنشر: `main`
- داخل Cloudflare: Workers & Pages > wild-shadow-ac76 > Settings > Build
- Git repository: `emadmedo19/Emadmohamed`; Branch: `main`; Root directory: `/`
- Build command: اتركه فارغًا.
- Deploy command: `npx wrangler deploy`.
- ملفات الموقع داخل `public/`، وإعداد النشر في `wrangler.jsonc`.

نشر التعديلات على `main` يطلق بناء Cloudflare تلقائيًا عندما يكون اتصال GitHub مفعلًا.

> المجلد القديم الخاص بمشروع Flutter وملف `codemagic.yaml` محفوظان في المستودع ولم يتم تغييرهما. هذا الموقع التعريفي ليس نسخة ويب عاملة من تطبيق العمارة. لا تضع رابط Google Play للجمهور قبل الإطلاق العام.
