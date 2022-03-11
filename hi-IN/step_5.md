## जीव जंतुओं को हिलाएँ

**जीव जंतुओं** का अर्थ है **जानवर**। इस चरण में, आप अपने शांत दृश्य में एक चलती हुई टिड्डी जोड़ेंगे।

--- task ---

**Grasshopper** स्प्राइट सेट करें ताकि वह बाएं से दाएं घूमे और पेड़ और फूलों के पीछे से दिखाई दे।

![टिड्डी स्प्राइट की छवि](images/grasshopper-sprite.png)

```blocks3
when flag clicked
go to [back v] layer
set rotation style [left-right v]
```

--- /task ---

--- task ---

अब, अपने टिड्डी **Grasshopper** स्प्राइट को पूरे मंच पर आगे-पीछे करें।

![टिड्डी स्प्राइट की छवि](images/grasshopper-sprite.png)

```blocks3
when flag clicked
go to [back v] layer
set rotation style [left-right v]
+ forever
move [5] steps
next costume
if on edge, bounce
```
--- /task ---

**Grasshopper** स्प्राइट इस समय थोड़ी तेज़ी से आगे बढ़ रहा है, लेकिन आप `variable`{:class="block3variables"} और `wait` ब्लॉक का उपयोग कर सकते हैं {:class="block3control"} इसे धीमा करने के लिए।

--- task ---

एक नया `variable`{:class="block3variables"} बनाएं जिसे `grasshopper` कहा जाता है और इसे **slider** पर स्विच करें।

--- /task ---

--- task ---

अब, आप टिड्डे को धीमा करने के लिए `wait`{:class="block3control"} ब्लॉक का उपयोग कर सकते हैं।

![टिड्डी स्प्राइट की छवि](images/grasshopper-sprite.png)

```blocks3
when flag clicked
go to [back v] layer
set rotation style [left-right v]
forever
move [5] steps
next costume
if on edge, bounce
+ wait (grasshopper) seconds
```

--- /task ---

यदि आप हरे झंडे पर क्लिक करते हैं और स्लाइडर को हिलाते हैं, तो आप देखेंगे कि टिड्डा बहुत धीमी गति से चलता है। इसे ठीक करने के लिए, आपको `grasshopper`{:class="block3variables"} चर की सीमा को बहुत छोटी संख्या में बदलने की आवश्यकता है।

--- task ---

स्टेज पर, `grasshopper`{:class="block3variables"} वेरिएबल पर राइट-क्लिक करें और स्लाइडर रेंज को `0.0` और `1.0` के बीच में बदलें।.

![टिड्डी स्प्राइट की छवि](images/grasshopper-range.png)

--- /task ---

--- task ---

हरे झंडे पर क्लिक करें, फिर **grasshopper** स्प्राइट परिवर्तन गति देखने के लिए अपने `grasshopper`{:class="block3variables"} स्लाइडर को समायोजित करें।

--- /task ---



