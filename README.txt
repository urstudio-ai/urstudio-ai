UR. studio website
==================

افتحي الموقع إزاي:
1) أسهل طريقة تنشريه أونلاين ببلاش: ادخلي https://app.netlify.com/drop
   واسحبي فولدر UR_studio_website كله وحطيه في الصفحة. هيديكي لينك للموقع على طول.
2) لو فتحتي index.html بالدبل كليك من الكمبيوتر، الموقع هيفتح في "العرض السريع" من غير الـ 3D،
   لأن المتصفح بيمنع تأثيرات الـ 3D والفيديوهات من ملفات على الجهاز. على أي استضافة هيشتغل كامل.
3) الموقع محتاج إنترنت عشان يحمّل مكتبة الـ 3D (three.js) والخطوط من جوجل.

التعديل:
- كل الكلام (إنجليزي وعربي) موجود في index.html جوه const T = { en:{...}, ar:{...} }
- الريلز موجودة في const REELS = [...] والفيديوهات والصور في فولدر media

لسه ناقص:
- فورم الـ audit وقائمة الانتظار مش متوصلين بإيميل (ممكن توصليهم بـ Formspree أو Google Sheets)
- المساعد (Concierge) أسئلة جاهزة، مش AI حقيقي لسه
- الصوت في الفيديوهات بيشتغل لما الزائر يدوس على الفيديو

How to open (English):
- Drag the whole UR_studio_website folder onto https://app.netlify.com/drop to get a live link.
- Opening index.html directly from your computer shows the Quick view (no 3D), because browsers
  block 3D video textures from local files. On any web host the full 3D version runs.
