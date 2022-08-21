-
موضع الشريط الجانبي: 2
-

# ترجم موقعك

دعنا نترجم `docs / intro.md` إلى الفرنسية.

## تكوين i18n

قم بتعديل `docusaurus.config.js` لإضافة دعم للغة` fr`:

"" عنوان js = "docusaurus.config.js"
module.exports = {
  i18n: {
    defaultLocale: 'en'،
    اللغات: ['en'، 'fr']،
  } ،
} ؛
""

## ترجمة وثيقة

انسخ ملف `docs / intro.md` إلى المجلد` i18n / fr`:

"" باش
mkdir -p i18n / fr / docusaurus-plugin-content-docs / current /

cp docs / intro.md i18n / fr / docusaurus-plugin-content-docs / current / intro.md
""

ترجمة "i18n / fr / docusaurus-plugin-content-docs / current / intro.md` باللغة الفرنسية.

## ابدأ موقعك المترجم

ابدأ موقعك باللغة الفرنسية:

"" باش
بدء تشغيل npm - --locale fr
""

يمكن الوصول إلى موقعك المترجم على [http: // localhost: 3000 / fr /] (http: // localhost: 3000 / fr /) ويتم ترجمة صفحة "البدء".

:::حذر

في التطوير ، يمكنك استخدام لغة واحدة فقط في نفس الوقت.

:::

## إضافة قائمة محلية منسدلة

للتنقل بسلاسة عبر اللغات ، أضف قائمة منسدلة للغة.

قم بتعديل ملف `docusaurus.config.js`:

"" عنوان js = "docusaurus.config.js"
module.exports = {
  themeConfig: {
    نافبار: {
      العناصر: [
        // تسليط الضوء على البداية
        {
          اكتب: "localeDropdown" ،
        } ،
        // تسليط الضوء على النهاية
      ] ،
    } ،
  } ،
} ؛
""

تظهر القائمة المنسدلة للغة الآن في شريط التنقل الخاص بك:

! [قائمة الإعدادات المحلية] (./ img / localeDropdown.png)

## بناء موقعك المترجم

قم ببناء موقعك للغة معينة:

"" باش
npm تشغيل البناء - --locale fr
""

أو أنشئ موقعك ليشمل جميع اللغات في وقت واحد:

"" باش
npm تشغيل البناء
""