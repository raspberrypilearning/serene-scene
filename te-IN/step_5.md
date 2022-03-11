## జంతుజాలం కదిలేలా చేయండి

**జంతుజాలం** అంటే **జంతువులు**. ఈ దశలో, మీరు మీ నిర్మలమైన దృశ్యానికి కదిలే మిడతను జోడిస్తారు.

--- task ---

**Grasshopper** sprite ను సెటప్ చేయండి, తద్వారా అది ఎడమ నుండి కుడికి కదులుతుంది మరియు చెట్టు మరియు పువ్వుల వెనుక కనిపిస్తుంది.

![grasshopper sprite యొక్క చిత్రం](images/grasshopper-sprite.png)

```blocks3
when flag clicked
go to [back v] layer
set rotation style [left-right v]
```

--- /task ---

--- task ---

ఇప్పుడు, మీ **Grasshopper** sprite ని Stageలో ముందుకు వెనుకకు కదిలేలా చేయండి.

![grasshopper sprite యొక్క చిత్రం](images/grasshopper-sprite.png)

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

**Grasshopper** sprite ప్రస్తుతానికి కొంచెం వేగంగా కదులుతోంది, కానీ మీరు దానిని నెమ్మదించడానికి `variable`{:class="block3variables"} మరియు `wait`{:class="block3control"} బ్లాక్‌ని ఉపయోగించవచ్చు.

--- task ---

`grasshopper` అని పిలువబడే కొత్త `variable`{:class="block3variables"}ని సృష్టించండి మరియు దానిని **slider** కు మార్చండి.

--- /task ---

--- task ---

ఇప్పుడు, మీరు `wait`{:class="block3control"} బ్లాక్‌ని ఉపయోగించి మిడత వేగాన్ని తగ్గించవచ్చు.

![grasshopper sprite యొక్క చిత్రం](images/grasshopper-sprite.png)

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

మీరు ఆకుపచ్చ జెండాపై క్లిక్ చేసి, స్లైడర్‌ను కదిలిస్తే, మిడత చాలా నెమ్మదిగా కదులుతున్నట్లు మీరు గమనించవచ్చు. దీన్ని పరిష్కరించడానికి, మీరు `grasshopper`{:class="block3variables"} వేరియబుల్ పరిధిని చాలా తక్కువ పరిధికి మార్చాలి.

--- task ---

`grasshopper`{:class="block3variables"} వేరియబుల్‌పై రైట్-క్లిక్ చేసి `0.0` మరియు పరిధిని `1.0`మధ్యకు మార్చండి.

![మిడత పరిధి యొక్క చిత్రం](images/grasshopper-range.png)

--- /task ---

--- task ---

ఆకుపచ్చ జెండాపై క్లిక్ చేసి, ఆపై **grasshopper** sprite వేగంలో మార్పు వచ్చేలా `grasshopper`{:class="block3variables"} స్లయిడర్‌ని సర్దుబాటు చేయండి.

--- /task ---



