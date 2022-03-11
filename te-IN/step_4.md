## సన్నివేశాన్ని సెట్ చేయండి

Scratch లో, మీరు sprite కి కాకుండా **Stage** కి కూడా కోడ్‌ని జోడించవచ్చు. ఈ దశలో, మీరు నేపధ్యం ప్రకాశాన్ని మారుస్తారు మరియు కొన్ని వినసొంపైన సౌండ్ ఎఫెక్ట్‌లను జోడిస్తారు.

--- task ---

Stage paneకి వెళ్లి, **backdrop**పై క్లిక్ చేయండి. మీరు ఇప్పుడు Code ప్రదేశంలో **backdrop** కోసం ప్రోగ్రామ్‌ను అభివృద్ధి చేస్తారు.

![బ్యాక్‌డ్రాప్ ఎంపిక యొక్క చిత్రం](images/backdrop.png)

`Variables`{:class="block3variables"} బ్లాక్స్ మెనులో, **Make a Variable** పై క్లిక్ చేసి, కొత్త వేరియబుల్ ను `light` అని పిలవండి. వేరియబుల్ ను `-40` మరియు `40` మధ్య పరిధితో **slider** పై మార్చండి.

--- /task ---

--- task ---

మునుపటిలాగే, బ్యాక్‌డ్రాప్ రూపాన్ని మార్చడానికి మీరు ఈ వేరియబుల్‌ని ఉపయోగించవచ్చు.

`set color effect`{:class="block3looks"} బ్లాక్‌ ని ఉపయోగించండి, కానీ `color`{:class="block3looks"}ని `brightness`{:class="block3looks"}కి మార్చడానికి డ్రాప్-డౌన్ మెనుని ఉపయోగించండి.

![లుక్స్ ఎఫెక్ట్ బ్లాక్ కోసం ఎంపికను చూపుతున్న చిత్రం](images/brightness.png)

![నేపథ్య చిత్రం](images/backdrop-sprite.png)

```blocks3
when flag clicked
forever
set [brightness v] effect to (light)
```

--- /task ---

ఇప్పుడు, మీరు `light`{:class="block3variables"} స్లయిడర్‌ని సర్దుబాటు చేసినప్పుడు, అడవి చీకటి సాయంత్రం లేదా ప్రకాశవంతమైన వేసవి రోజులా కనిపించేలా దాని ప్రకాశాన్ని మార్చడాన్ని మీరు చూడగలగాలి.

**Stage**కి సౌండ్ ఎఫెక్ట్‌లను కూడా జోడించవచ్చు.

--- task ---

ఇందు కోసం, **Sounds** ట్యాబ్‌పై క్లిక్ చేయండి.

![sounds ట్యాబ్‌ని చూపుతున్న చిత్రం ఎంచుకోబడింది](images/sounds-tab.png)

--- /task ---

--- task ---

ధ్వనిని ఎంచుకోవడానికి స్క్రీన్ దిగువ ఎడమవైపు మూలలో **Choose a Sound** చిహ్నంపై క్లిక్ చేయండి.

![add sound చిహ్నాన్ని చూపుతున్న చిత్రం](images/add-sound.png)

--- /task ---

--- task ---

మీరు ఇప్పుడు శబ్దాల కోసం శోధించవచ్చు. ఈ ప్రాజెక్ట్‌లో, మనము **Rain** సౌండ్‌ని ఉపయోగిస్తాము, కానీ మీరు మీకు నచ్చినదాన్ని ఎంచుకోవచ్చు. ధ్వనిని ఎంచుకోవడానికి **Rain** చిహ్నంపై క్లిక్ చేయండి.

![వర్షపు ధ్వని యొక్క శోధన మరియు ఎంపికను చూపుతున్న చిత్రం](images/rain.png)

--- /task ---

--- task ---

`Rain`{:class="block3variables"} వేరియబుల్‌ని సృష్టించండి మరియు దానిని **slider** వలె కనిపించేలా చేయండి.

--- /task ---

--- task ---

`play`{:class="block3sound"} `Rain`{:class="block3sound"} ధ్వని `forever`{:class="block3control"} కి కోడ్ ను జోడించండి మరియు `volume`{:class="block3sound"} విలువకి, `Rain`{:class="block3variables"} వేరియబుల్ ను `set`{:class="block3sound"} చేయండి.

![నేపథ్య చిత్రం](images/backdrop-sprite.png)

```blocks3
when flag clicked
forever
play sound [Rain v] until done

when flag clicked
forever
set volume to (rain) %
```

--- /task ---

మీ కోడ్‌ని అమలు చేయడానికి మరియు స్లయిడర్‌తో వర్షం యొక్క వాల్యూమ్‌ను మార్చడానికి ఆకుపచ్చ జెండాపై క్లిక్ చేయండి.

--- save ---
