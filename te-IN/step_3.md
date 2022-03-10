## పువ్వులకు రంగులు వేయండి

ఇప్పుడు, `tree`{:class="block3variables"} వేరియబుల్‌ని `set size to`{:class="block3looks"} బ్లాక్‌కి జోడించండి. ఇప్పుడు, మీరు పువ్వుల రంగును మార్చడానికి వేరియబుల్‌ని ఉపయోగించవచ్చు.

--- task ---

**flowers** sprite పై క్లిక్ చేసి, ఆపై `flowers` అనబడే`variable`{:class="block3variables"}ని సృష్టించండి. దీన్ని ఎలా చేయాలో మీకు గుర్తులేకపోతే, రిమైండర్ కోసం మునుపటి దశకు తిరిగి వెళ్లండి.

--- /task ---

--- task ---

`size`{:class="block3looks"}ని మార్చిన విధంగానే, పువ్వుల యొక్క `color effect`{:class="block3looks"}ని మార్చండి.

![పువ్వుల చిత్రంతో sprite](images/flowers-sprite.png)

```blocks3
when flag clicked
forever
set [color v] effect to [0]
```

--- /task ---

--- task ---

తర్వాత, మీ `flowers`{:class="block3variables"} వేరియబుల్‌ని జోడించండి.

![పువ్వుల చిత్రంతో sprite](images/flowers-sprite.png)

```blocks3
when flag clicked
forever
+ set [color v] effect to (flowers)
```

--- /task ---

సంఖ్యలను నిల్వ చేసే వేరియబుల్స్ ఎల్లప్పుడూ 0 కంటే ఎక్కువ విలువలను కలిగి ఉండవలసిన అవసరం లేదు. మీరు ఋణ సంఖ్యలను కూడా ఉపయోగించవచ్చు.

--- task ---

Stage పై `tree`{:class="block3variables"} స్లయిడర్‌పై రైట్-క్లిక్ చేసి, **change slider range** మీద క్లిక్ చేయండి.

ఇప్పుడు, **slider range** ని `-100` మరియు `100`మధ్యకు మార్చండి.

![flower వేరియబుల్ పరిధిని -100 కనిష్టంగా మరియు 100 గరిష్టంగా సర్దుబాటు చేయడానికి డైలాగ్ బాక్స్‌ను చూపుతున్న చిత్రం](images/flowers-range.png)

--- /task ---

--- task ---

ఆకుపచ్చ జెండాపై క్లిక్ చేసి, ఆపై `flowers`{:class="block3variables"} స్లయిడర్‌ని సర్దుబాటు చేయండి.

--- /task ---

--- save ---



