---
title: Make an Image Responsive
localeTitle: جعل صورة مستجيبة
---
## جعل صورة مستجيبة

اتباع التعليمات:

أضف قواعد النمط لعلامة img لجعلها تستجيب لحجم الحاوية الخاصة بها. يجب أن يتم عرضه كعنصر على مستوى الكتلة ، يجب أن يلائم العرض الكامل للحاوية دون تمديد ، ويجب أن يحتفظ بنسبة العرض إلى الارتفاع الأصلية.

يصبح النمط:

```css
<style>
  img {
  max-width: 100%;
  display: block;
  height: auto;
}
</style>
```