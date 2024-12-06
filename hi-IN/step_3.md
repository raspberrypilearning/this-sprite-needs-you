## निर्माण और परीक्षण करें

अब आपका प्रोजेक्ट बनाने का समय आ गया है। छोटा शुरू करें, और यदि आपके पास समय है तो अपने प्रोजेक्ट में अधिक जोड़ें।

![](images/step3_image.png)

**युक्ति:** याद रखें कि आप हर बार कुछ जोड़ते हैं तो अपने प्रोजेक्ट का परीक्षण करें। अधिक बदलाव करने से पहले बग को खोजना और ठीक करना बहुत आसान है।

--- task ---

आपको यह तय करना होगा कि अपने प्रोजेक्ट को किस क्रम में बनाया जाए। आप यह कर सकते हैं:

+ एक वेरिएबल बनाएं और उपयोगकर्ता को इसे नियंत्रित करने की अनुमति दें। स्प्राइट को वास्तव में जीवन में लाने के लिए एनीमेशन, पोशाक, आवाज़, प्रभाव और बातचीत जोड़ें
+ उपयोगकर्ता को नियंत्रित करने के सरल तरीकों के साथ एकाधिक चर बनाएं, और फिर बाद में अधिक प्रभाव जोड़ें

स्प्राइट जोड़ना और फिर `variable`{:class="block3variables"} बनाना एक शानदार शुरुआत है।

--- /task ---

आपने वास्तव में कुछ उपयोगी कौशल बनाए हैं। आपको अपना प्रोजेक्ट बनाने में मदद करने के लिए एक अनुस्मारक यहाँ दिया गया है:

### वेरिएबल्स का उपयोग करना

```blocks3
set [my variable v] to (0)
```

[[[scratch3-create-set-variable]]]

[[[scratch3-set-variable-with-button]]]

[[[scratch3-change-variable-in-loop]]]

### स्थितियों की जाँच करना

```blocks3
if <(my variable) = (0)> then
```

[[[scratch3-forever-condition]]]

[[[scratch3-operators-conditions]]]

[[[scratch3-if-then-else]]]

[[[scratch3-set-block-input-colour-with-eyedropper]]]

### संदेश प्रसारित और प्राप्त करना

```blocks3
broadcast (message1 v)
```

[[[generic-scratch3-broadcast-message]]]

### टेक्स्ट के साथ काम करना:

```blocks3
say (join[Hello ](name)) for (2) seconds
```

[[[scratch3-emoji-text]]]

[[[scratch3-ask-answer-chat]]]

[[[scratch3-join-text]]]

### बैकड्रॉप, गतिविधि और ग्राफिक प्रभाव

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

### ध्वनि:

```blocks3
start sound (Pop v)
```

[[[scratch3-add-sound]]]

[[[scratch3-record-sound]]]

[[[scratch3-text-to-speech]]]

### पेंट संपादक - बैकड्रॉप और पोशाकें

[[[scratch3-paint-a-new-backdrop-extended]]]

[[[scratch3-backdrops-and-sprites-using-shapes]]]

[[[scratch3-use-text-tool]]]

[[[scratch3-copy-parts-between-sprite-costumes]]]

[[[scratch3-add-costumes-to-a-sprite]]]

### Scratch एडिटर

[[[scratch3-copy-code]]]

[[[scratch3-full-screen]]]

[[[scratch3-duplicate-sprite]]]

[[[scratch-backpack]]]


--- task ---

**परीक्षण:** अपने प्रोजेक्ट को किसी और को दिखाएँ और अपनी प्रतिक्रिया प्राप्त करें। क्या आप अपने खेल में कोई बदलाव करना चाहते हैं?

--- /task ---

--- task ---

**डीबग:** आपको अपने प्रोजेक्ट में कुछ बग मिल सकते हैं जिन्हें आपको ठीक करने की आवश्यकता है। यहाँ कुछ सामान्य बग हैं।


--- collapse ---

---
title: वेरिएबल सही ढंग से अपडेट नहीं हो रहे हैं
---

एक आम गलती `change`{:class="block3variables"} और `set`{:class="block3variables"} ब्लॉक को भ्रमित करना है।

+ `set`{:class="block3variables"} एक वेरिएबल के मूल्य को एक नए मान से बदलता है।
+ `change`{:class="block3variables"} एक वेरिएबल में एक संख्या जोड़ता है। यदि आप एक धनात्मक संख्या `change by`{:class="block3variables"} करते हैं, तो वेरिएबल मान बड़ा हो जाता है। यदि आप एक ऋणात्मक संख्या `change by`{:class="block3variables"} करते हैं, तो वेरिएबल मान छोटा हो जाता है।


एक अन्य सामान्य समस्या `variables`{:class="block3variables"} ब्लॉक मेन्यू से वेरिएबल खींचने के बजाय वेरिएबल का नाम टाइप कर रही है। वेरिएबल्स नारंगी होना चाहिए:

```blocks3
say (name) for (2) seconds
```

**not**:

```blocks3
say [name] for (2) seconds
```

--- /collapse ---

--- collapse ---

---
title: बदलाव हमेशा के बजाय केवल एक बार होता है
---

सुनिश्चित करें कि आपने ऐसे कोड ब्लॉक रखे हैं जिन्हें `forever`{:class="block3control"} ब्लॉक के अंदर चलते रहने की आवश्यकता है। ऐसा करना भूल जाना वास्तव में आम बात है!

--- /collapse ---

--- collapse ---

---
title: संख्या तुलना शर्तें काम नहीं कर रही हैं
---

क्या आप वाकई `>`{:class="block3operators"} (इससे बड़ा) और `<`{:class="block3operators"} (इससे कम) ऑपरेटरों को सही तरीके से उपयोग कर रहे हैं?

```blocks3
<(health) > (0)> // means the health variable must be bigger than 0
<(health) < (5)> // means the health variable must be smaller than 5
```

**tp:** वह संख्या जो बड़ी होनी चाहिए, ऑपरेटर प्रतीक के व्यापक (बड़ा) तरफ जाती है।

--- /collapse ---

--- collapse ---

---
title: जब मैं संदेश प्रसारित करता हूँ तो कुछ नहीं होता है
---

सुनिश्चित करें कि आपके पास एक मेल `when I receive`{:class="block3events"} ब्लॉक है जो आपके `broadcast`{:class="block3events"} संदेश के दौरान कुछ करता है। जांचें कि संदेश के नाम मेल खाते हैं।

--- /collapse ---

आपको एक बग मिल सकता है जो यहाँ सूचीबद्ध नहीं है। क्या आप इसे ठीक करने का तरीका समझ सकते हैं?

यदि आप अटक जाते हैं, तो अपने कोड को जोर से पढ़ने का प्रयास करें या किसी दोस्त को समस्या के बारे में बताने का प्रयास करें। आप समस्या को देख सकते हैं।

हमें आपके बग्स के बारे में सुनना अच्छा लगता है और आपने उन्हें कैसे ठीक किया है। यदि आपको अपने प्रोजेक्ट में एक अलग बग मिलता है, तो इस पेज के नीचे प्रतिक्रिया बटन का उपयोग करें।

--- /task ---


--- save ---

