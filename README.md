
#   5تمرين - رقم
 **XO**لعبة الـ 

 
### خطوات 

1. افتح رابط الواجب من [هنا](https://github.com/kuwaitcodes/ios-cw-5)
2. لمجلد الواجب Fork قم بعمل
3. Open in GitHub Desktop قم بفتح الواجب عن طريق 
4. Xcode قم بإنشاء مشروع جديد بالـ
5. **XO** قم بتطبيق لعبةالـ
6. الفيديوهات  موجوده [هنا](https://app.code.kw/%D8%A8%D8%B1%D9%85%D8%AC%D8%A9-%D8%AA%D8%B7%D8%A8%D9%8A%D9%82%D8%A7%D8%AA-%D8%A7%D9%84%D8%A7%D9%8A%D9%81%D9%88%D9%86-%D9%85%D8%B9-%D8%B3%D9%88%D9%8A%D9%81%D8%AA-Swift-KFAS/ios-%D8%AA%D9%85%D8%A7%D8%B1%D9%8A%D9%86/ios-x-o/%D8%AA%D8%B5%D9%85%D9%8A%D9%85-%D9%88%D8%A7%D8%AC%D9%87%D8%A9-x-o) 

### بونص!!
1. **Image** قم بوضع صوره 
2. قم بجعل تصميم اللعبه اجمل 🤩

### Alert View
<div dir="ltr">

```Swift
func okAlert(title: String, message: String)
{
    let alertController = UIAlertController(title: title, message: message, preferredStyle: .alert)
    let okAction = UIAlertAction(title: "Ok", style: .cancel)
    alertController.addAction(okAction)
    present(alertController, animated: true)
}
```
يمكنك فقط استدعاء الدالة من خلال كتابة: 

```Swift
okAlert(title: "X Wins!", message: "مبرووووك X 😍")
```
</div>

آخر موعد لرفع الكود\
30/6/2020
