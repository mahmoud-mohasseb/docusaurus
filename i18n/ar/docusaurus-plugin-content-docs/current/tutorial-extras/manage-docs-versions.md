-
sidebar_position: 1
-

# إدارة إصدارات المستندات

يمكن لـ Docusaurus إدارة إصدارات متعددة من مستنداتك.

## إنشاء نسخة من المستندات

حرر نسخة 1.0 من مشروعك:

"" باش
npm قم بتشغيل مستندات docusaurus: الإصدار 1.0
""

يتم نسخ مجلد "docs" إلى `versioned_docs / version-1.0` ويتم إنشاء` version.json`.

يحتوي محرر مستنداتك الآن على نسختين:

- `1.0` في` http: // localhost: 3000 / docs / `للإصدار 1.0 docs
- `current` في` http: // localhost: 3000 / docs / next / `** للمستندات القادمة التي لم يتم طرحها **

## إضافة نسخة منسدلة

للتنقل بسلاسة عبر الإصدارات ، أضف قائمة منسدلة للإصدار.

قم بتعديل ملف `docusaurus.config.js`:

"" عنوان js = "docusaurus.config.js"
module.exports = {
  themeConfig: {
    نافبار: {
      العناصر: [
        // تسليط الضوء على البداية
        {
          اكتب: "docsVersionDropdown" ،
        } ،
        // تسليط الضوء على النهاية
      ] ،
    } ،
  } ،
} ؛
""

تظهر القائمة المنسدلة لإصدار المستندات في شريط التنقل الخاص بك:

! [القائمة المنسدلة لإصدار المستندات] (./ img / docsVersionDropdown.png)

## تحديث نسخة موجودة

من الممكن تحرير المستندات التي تم إصدارها في المجلد الخاص بها:

- تحديثات `versioned_docs / version-1.0 / hello.md`` http: // localhost: 3000 / docs / hello`
- تحديثات `docs / hello.md`` http: // localhost: 3000 / docs / next / hello`