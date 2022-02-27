

# <p dir="rtl">
فيديوهات الدرس</p>


* [الخطوط](https://youtu.be/OLRtp1v_IjQ)


* [ال stacks](https://youtu.be/7M7zPyycC8o)  


# <p dir="rtl">

استخدام انواع ال stacks ال ٣</p>




   * ال ZStack لنستطيع اضافة لون كخلفية 


   ```
ZStack {
  Color.blue.ignoresSafeArea()
  VStack {
    ...
  }}
```

 <p dir="rtl">
   * وثم نضيف بداخل الـ VStack مكونات الصفحة 
</p>

<p dir="rtl">
* نستطيع أن نضيف بعض الاشياء لتحسين شكل ال text 
</p>

```
Text("hello my name is Fatma")
    .font(.title)
    .fontWeight(.bold)
    .foregroundColor(Color.white)
```


* بإضافة ال spacers يمكننا وضع مسافات بين العناصر 

```  
Spacer()
```


* لتضيف ايموجي قم بالضغط على control + command + space  ثم أضفها بهذا الشكل 

 ```
Text("🐈‍⬛")
```




---

<p dir="rtl">
<strong>تمرين <a href="https://github.com/kuwaitcodes/ios-cw-2">(github link )</a></strong></p>


<p dir="rtl">
نبي نتعرف عليك اكثر من هذا التمرين</p>




1.  قم بإضافة Zstack لتستطيع إضافة لون في الخلفية 

2. بعد إضافة اللون قم بإضافة Vstack 

3. قم بإضافة مكونات الصفحة بداخل الـ VStack 

4. قم بكتابة بعض الجمل التعريفية عنك 

5. قم بإضافة Hstack لتضيف بعض النصوص ثم قم باختيار  الإيموجي 

6. استخدم spacers بين الايموجيز


<p dir="rtl">
<strong>بونص✨</strong>: قم بتغيير الـ opacity لجعل الالوان اجمل </p>

