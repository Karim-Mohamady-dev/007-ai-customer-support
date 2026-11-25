# Relaydesk — 007-ai-customer-support

Relaydesk يرد على أسئلة العملاء الروتينية، ويجهز مسودات لفريقك، ويجمع كل المحادثات في صندوق واحد.

## ما هذا المشروع؟

صفحة هبوط ثنائية اللغة (العربية RTL والإنجليزية LTR) لـ Relaydesk. Relaydesk answers routine customer questions, drafts replies for your team, and keeps every conversation in one inbox.

## التشغيل محليا

```bash
npm install
npm run dev
npm run build
```

## المزايا

- مبدل لغة ظاهر، والتفضيل محفوظ في localStorage
- الترجمات في `locales/en/common.json` و `locales/ar/common.json`
- نموذج تجربة مجانية مع تحقق من البريد
- أقسام: البطل، المزايا، كيف يعمل، آراء نموذجية، الأسعار، الأسئلة الشائعة، الدعوة الأخيرة
- قسم كشف الشعار (tagline reveal) مع تحريك كلمة بكلمة
- الأسعار غير المؤكدة تظهر كعناصر نائبة `{{price}}`

## ملاحظات

- البيانات المعروضة تجريبية وموسومة كعينات.
- لا توجد أرقام أو شهادات مخترعة.
