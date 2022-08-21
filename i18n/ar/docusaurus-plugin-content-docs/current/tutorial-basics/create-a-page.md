-
sidebar_position: 1
-

# إنشاء صفحة

أضف ملفات ** Markdown أو React ** إلى "src / pages" لإنشاء ** صفحة مستقلة **:

- `src / pages / index.js` →` localhost: 3000 / `
- `src / pages / foo.md` →` localhost: 3000 / foo`
- `src / pages / foo / bar.js` →` المضيف المحلي: 3000 / foo / bar`

## أنشئ صفحة رد الفعل الأولى

قم بإنشاء ملف في `src / pages / my-reaction-page.js`:

"` `jsx title =" src / pages / my-reaction-page.js "
استيراد رد فعل من "رد فعل" ؛
استيراد التخطيط من "@ theme / Layout" ؛

تصدير الوظيفة الافتراضية MyReactPage () {
  إرجاع (
    <التخطيط>
      <h1> صفحة رد الفعل الخاصة بي </ h1>
      <p> هذه صفحة React </p>
    </Layout>
  ) ؛
}
""

صفحة جديدة متاحة الآن على [http: // localhost: 3000 / my-reaction-page] (http: // localhost: 3000 / my-reaction-page).

## إنشاء صفحة Markdown الأولى الخاصة بك

قم بإنشاء ملف على `src / pages / my-markdown-page.md`:

`` mdx title = "src / pages / my-markdown-page.md"
# صفحة Markdown الخاصة بي

هذه صفحة Markdown
""

صفحة جديدة متاحة الآن على [http: // localhost: 3000 / my-markdown-page] (http: // localhost: 3000 / my-markdown-page).