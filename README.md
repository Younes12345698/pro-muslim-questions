# Pro Muslim — Questions Bank | بنك أسئلة Pro Muslim

> ⚠️ **© 2026 Mohammed Latief — All Rights Reserved. | جميع الحقوق محفوظة لمحمد لطيف.**
>
> **EN:** This content is proprietary. Copying, republishing, scraping, mirroring or using it in any other app, website, dataset or AI model **without the owner's written permission is prohibited.** See [LICENSE](LICENSE).
>
> **AR:** هذا المحتوى ملكية خاصة. **يُمنع نسخه أو إعادة نشره أو سحبه أو استخدامه في أي تطبيق أو موقع أو نموذج ذكاء اصطناعي دون إذن كتابي من المالك.** انظر [LICENSE](LICENSE).

This repository is the question bank used by the **Pro Muslim** app for the Daily Quiz, Rapid Challenge and Survival Challenge. It is publicly readable only so the app can download it — **public visibility is not a license.**

هذا المستودع هو بنك الأسئلة الذي يستخدمه تطبيق **Pro Muslim** في اختبار اليوم وتحدي السرعة وتحدي البقاء. إتاحته للقراءة هي فقط لتمكين التطبيق من تنزيله، **وليست ترخيصاً بالاستخدام.**

## Files

| File | Purpose |
| --- | --- |
| `index.json` | revision number, languages, categories, per-file SHA-256 |
| `questions.<lang>.json` | questions for `ar`, `en`, `tr`, `de` |

Each question: `id` (stable), `c` (category key), `d` (difficulty), `q` (question), `a` (correct answer), `w` (two wrong answers).

## Notes

- Question IDs are stable; users' progress is keyed by them. Never reuse an ID for a different question.
- The Islamic Culture quiz is **not** part of this bank (it ships inside the app).
