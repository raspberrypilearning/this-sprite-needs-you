## Adeiladu a phrofi

Nawr mae'n bryd creu dy brosiect. Dechreua yn fach, ac ychwanegu mwy at dy brosiect os oes gen ti amser.

![](images/step3_image.png)

**Awgrym:** Cofia brofi dy brosiect bob tro y byddi di'n ychwanegu rhywbeth. Mae'n llawer haws dod o hyd i chwilod a'u trwsio cyn i ti wneud mwy o newidiadau.

--- task ---

Bydd angen i ti benderfynu ym mha drefn rwyt ti am adeiladu dy brosiect. Gallet ti:

+ Creu un newidyn a chaniatáu i'r defnyddiwr ei reoli. Ychwanega animeiddiadau, gwisgoedd, sain, effeithiau, a sgwrs i wneud i'r corlun ddod yn fyw
+ Creu mwy nag un newidyn gyda ffyrdd syml i'r defnyddiwr eu rheoli, ac yna ychwanegu mwy o effeithiau yn nes ymlaen

Mae ychwanegu corlun ac yna creu `newidyn`{:class="block3variables"} yn ddechrau gwych.

--- /task ---

Rwyt ti wedi meithrin sgiliau defnyddiol iawn. Dyma dy atgoffa i dy helpu i greu dy brosiect:

### Defnyddio newidynnau

```blocks3
set [my variable v] to (0)
```

[[[scratch3-create-set-variable]]]

[[[scratch3-set-variable-with-button]]]

[[[scratch3-change-variable-in-loop]]]

### Gwirio amodau

```blocks3
if <(my variable) = (0)> then
```

[[[scratch3-forever-condition]]]

[[[scratch3-operators-conditions]]]

[[[scratch3-if-then-else]]]

[[[scratch3-set-block-input-colour-with-eyedropper]]]

### Darlledu a derbyn negeseuon

```blocks3
broadcast [message1 v]
```

[[[generic-scratch3-broadcast-message]]]

### Gweithio gyda thestun:

```blocks3
say (join[Hello ](name)) for (2) seconds
```

[[[scratch3-emoji-text]]]

[[[scratch3-ask-answer-chat]]]

[[[scratch3-join-text]]]

### Cefnlenni, symud, ac effeithiau graffeg

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

### Sain:

```blocks3
start sound (Pop v)
```

[[[scratch3-add-sound]]]

[[[scratch3-record-sound]]]

[[[scratch3-text-to-speech]]]

### Y Golygydd Paent - cefnlenni a gwisgoedd

[[[scratch3-paint-a-new-backdrop-extended]]]

[[[scratch3-backdrops-and-sprites-using-shapes]]]

[[[scratch3-use-text-tool]]]

[[[scratch3-copy-parts-between-sprite-costumes]]]

[[[scratch3-add-costumes-to-a-sprite]]]

### Golygydd Scratch

[[[scratch3-copy-code]]]

[[[scratch3-full-screen]]]

[[[scratch3-duplicate-sprite]]]

[[[scratch-backpack]]]


--- task ---

**Profi:** Dangosa dy brosiect i rywun arall a gofyn am eu hadborth. Wyt ti am wneud unrhyw newidiadau i dy gêm?

--- /task ---

--- task ---

**Difa chwilod:** Efallai bydd angen i ti drwsio chwilod yn dy brosiect. Dyma rai chwilod cyffredin.


--- collapse ---

---
title: Dydy newidynnau ddim yn cael eu diweddaru'n gywir
---

Un camgymeriad cyffredin yw drysu rhwng y blociau `newid`{:class="block3variables"} a `gosod`{:class="block3variables"}.

+ Mae `gosod`{:class="block3variables"} yn disodli gwerth newidyn gyda gwerth newydd.
+ Mae `newid`{:class="block3variables"} yn ychwanegu rhif at newidyn. Os wyt ti'n `newid gan`{:class="block3variables"} rhif positif, bydd gwerth y newidyn yn mynd yn fwy. Os wyt ti'n `newid gan`{:class="block3variables"} rhif negatif, bydd gwerth y newidyn yn mynd yn llai.


Problem gyffredin arall yw teipio enw newidyn yn lle llusgo'r newidyn o'r ddewislen blociau `Newidynnau`{:class="block3variables"}. Dylai newidynnau fod yn oren:

```blocks3
say (name) for (2) seconds
```

**nid**:

```blocks3
say [name] for (2) seconds
```

--- /collapse ---

--- collapse ---

---
title: Dim ond unwaith mae newid yn digwydd, dim am byth
---

Gwna'n siŵr dy fod ti wedi gosod blociau cod sydd angen dal ati i redeg y tu mewn i floc `am byth`{:class="block3control"}. Mae'n gyffredin iawn anghofio gwneud hyn!

--- /collapse ---

--- collapse ---

---
teitl: Dydy amodau cymharu rhifau ddim yn gweithio
---

Wyt ti'n siŵr dy fod ti wedi defnyddio'r gweithredwyr `>`{:class="block3operators"} (mwy na) a `<`{:class="block3operators"} (llai na) yn y drefn gywir?

```blocks3
<(health) > (0)> // means the health variable must be bigger than 0
<(health) < (5)> // means the health variable must be smaller than 5
```

**Awgrym:** Mae'r rhif sy'n gorfod bod yn fwy yn mynd ar ochr lletach (mwy) y symbol gweithredu.

--- /collapse ---

--- collapse ---

---
title: Does dim byd yn digwydd pan dwi'n darlledu neges
---

Gwna'n siŵr fod gen ti floc `pan fyddaf yn derbyn`{:class="block3events"} cyfatebol sy'n gwneud rhywbeth pan fyddi di'n `darlledu`{:class="block3events"} neges. Gwiria fod enwau'r negeseuon yn cyfateb.

--- /collapse ---

Efallai byddi di'n dod o hyd i chwilen sydd ddim wedi'i rhestru yma. Alli di weithio allan sut i'w thrwsio?

Os wyt ti'n cael trafferth, rho gynnig ar ddarllen dy god yn uchel neu esbonio'r broblem i ffrind. Efallai gweli di'r broblem.

Rydyn ni wrth ein bodd yn clywed am eich chwilod chi a sut gwnaethoch chi eu trwsio. Defnyddia'r botwm Adborth ar waelod y dudalen hon os wnes di ddod ar draws chwilen wahanol yn dy brosiect.

--- /task ---


--- save ---

