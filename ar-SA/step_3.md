## بناء واختبار

حان الوقت الآن لإنشاء مشروعك. ابدأ بمشروع صغير ، وأضف المزيد إلى مشروعك إذا كان لديك الوقت.

![](images/step3_image.png)

**نصيحة:** تذكر أن تختبر مشروعك في كل مرة تضيف شيئًا. من الأسهل بكثير العثور على الأخطاء وإصلاحها قبل إجراء المزيد من التغييرات.

--- task ---

سوف تحتاج إلى أن تقرر في أي ترتيب لبناء مشروعك. يمكنك:

+ أنشئ متغيرًا واحدًا واسمح للمستخدم بالتحكم فيه. أضف الرسوم المتحركة والأزياء والأصوات والمؤثرات والمحادثة لجعل الكائن ينبض بالحياة
+ قم بإنشاء متغيرات متعددة بطرق بسيطة يمكن للمستخدم التحكم فيها ، ثم إضافة المزيد من التأثيرات لاحقًا

تعد إضافة كائن ثم إنشاء متغير ``{: class = "block3variables"} بداية رائعة.

--- /task ---

لقد اكتسبت بعض المهارات المفيدة حقًا. إليك تذكير لمساعدتك في صنع مشروعك:

### استخدام المتغيرات

```blocks3
set [my variable v] to (0)
```

[[[scratch3-create-set-variable]]]

[[[scratch3-set-variable-with-button]]]

[[[scratch3-change-variable-in-loop]]]

### التحقق من الشروط

```blocks3
if <(my variable) = (0)> then
```

[[[scratch3-forever-condition]]]

[[[scratch3-operators-conditions]]]

[[[scratch3-if-then-else]]]

[[[scratch3-set-block-input-colour-with-eyedropper]]]

### بث واستقبال الرسائل

```blocks3
broadcast [message1 v]
```

[[[generic-scratch3-broadcast-message]]]

### العمل مع النص:

```blocks3
say (join[Hello ](name)) for (2) seconds
```

[[[scratch3-emoji-text]]]

[[[scratch3-ask-answer-chat]]]

[[[scratch3-join-text]]]

### الخلفيات والحركة والمؤثرات الرسومية

```blocks3
set [ghost v] effect to (0)
```

[[[scratch3-glide-to-object]]]

[[[scratch3-changing-backdrops-pages-levels]]]

[[[scratch3-change-costumes-to-show-mood]]]

[[[scratch3-animate-movement-costumes]]]

[[[scratch3-graphic-effects]]]

[[[scratch3-show-hide-sprites-backdrops]]]

[[[scratch3-positioning-with-layers]]]

[[[scratch3-jiggle-a-sprite]]]

### الصوت:

```blocks3
start sound (Pop v)
```

[[[scratch3-add-sound]]]

[[[scratch3-record-sound]]]

[[[scratch3-text-to-speech]]]

### محرر الرسام - الخلفيات والأزياء

[[[scratch3-paint-a-new-backdrop-extended]]]

[[[scratch3-backdrops-and-sprites-using-shapes]]]

[[[scratch3-use-text-tool]]]

[[[scratch3-copy-parts-between-sprite-costumes]]]

[[[scratch3-add-costumes-to-a-sprite]]]

### محرر سكراتش

[[[scratch3-copy-code]]]

[[[scratch3-full-screen]]]

[[[scratch3-duplicate-sprite]]]

[[[scratch-backpack]]]


--- task ---

**اختبار:** اعرض مشروعك على شخص آخر واطلب منه إبداء الرأي. هل تريد إجراء أي تغييرات على لعبتك؟

--- /task ---

--- task ---

**تصحيح:** قد تجد بعض الأخطاء في مشروعك والتي تحتاج إلى إصلاحها. فيما يلي بعض الأخطاء الشائعة.


--- collapse ---

---
العنوان: لا يتم تحديث المتغيرات بشكل صحيح
---

أحد الأخطاء الشائعة هو الخلط بين المقاطع البرمجية `غير`{: class = "block3variables"} و `اجعل`{: class = "block3variables"}.

+ `مجموعة`{: class = "block3variables"} تستبدل قيمة متغير بقيمة جديدة.
+ `غير`{: class = "block3variables"} يضيف رقمًا إلى متغير. إذا غيّرت `بمقدار`{: class = "block3variables"} رقمًا موجبًا ، فإن قيمة المتغير تكبر. إذا غيّرت `بمقدار`{: class = "block3variables"} رقمًا سالبًا ، فإن القيمة المتغيرة تصبح أصغر.


هناك مشكلة شائعة أخرى وهي كتابة اسم متغير بدلاً من سحب المتغير من قائمة المقاطع البرمجية `المتغيرات`{: class = "block3variables"}. يجب أن تكون المتغيرات باللون البرتقالي:

```blocks3
say (name) for (2) seconds
```

**ليس**:

```blocks3
say [name] for (2) seconds
```

--- /collapse ---

--- collapse ---

---
العنوان: التغيير يحدث مرة واحدة فقط وليس إلى الأبد
---

تأكد من وضع المقاطع البرمجية التي يجب أن تستمر في العمل داخل مقطع البرمجي `للأبد`{: class = "block3control"}. من الشائع حقًا أن تنسى القيام بذلك!

--- /collapse ---

--- collapse ---

---
العنوان: شروط مقارنات الأرقام لا تعمل
---

هل أنت متأكد من أنك استخدمت عامل التشغيل `>`{: class = "block3operators"} (أكبر من) و `<`{: class = "block3operators"} (أقل من) عامل التشغيل بالطريقة الصحيحة؟

```blocks3
<(health) > (0)> // means the health variable must be bigger than 0
<(health) < (5)> // means the health variable must be smaller than 5
```

**نصيحة:** الرقم الذي يجب أن يكون أكبر يذهب إلى الجانب الأوسع (الأكبر) من رمز العملية الرياضية.

--- /collapse ---

--- collapse ---

---
العنوان: لا شيء يحدث عندما أبث رسالة
---

تأكد من أن لديك مقطع برمجي `عندما أتلقى `{: class = "block3events"} تقوم بشيء ما عندما تقوم `ببث`{: class = "block3events"} رسالة. تحقق من تطابق أسماء الرسائل.

--- /collapse ---

قد تجد خطأ غير مدرج هنا. هل يمكنك معرفة كيفية إصلاحه؟

إذا واجهتك مشكلة ، فحاول قراءة النص البرمجي الخاص بك بصوت عالٍ أو شرح المشكلة لصديق. قد تكتشف المشكلة.

نحن نحب أن نسمع عن أخطائك وكيفية إصلاحها. استخدم إرسال ملاحظات في أسفل هذه الصفحة وأخبرنا إذا وجدت خطأً مختلفًا في مشروعك.

--- /task ---


--- save ---

