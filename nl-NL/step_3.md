## Bouwen en testen

Nu is het tijd om je project te maken. Begin klein en voeg meer toe aan je project als je tijd hebt.

![](images/step3_image.png)

**Tip:** Denk eraan om je project elke keer dat je iets toevoegt, te testen. Het is veel gemakkelijker om fouten te vinden en op te lossen voordat je meer wijzigingen aanbrengt.

--- task ---

Je moet beslissen in welke volgorde je je project wilt bouwen. Je kunt:

+ één variabele maken en de gebruiker deze laten beheren. Voeg animaties, uiterlijken, geluid, effecten en conversatie toe om de sprite echt tot leven te laten komen
+ meerdere variabelen maken met eenvoudige manieren om ze te besturen en later meer effecten toevoegen

Het toevoegen van een sprite en vervolgens het maken van een `variabele`{:class="block3variables"} is een geweldig begin.

--- /task ---

Je hebt een aantal echt nuttige vaardigheden opgebouwd. Hier is een herinnering om je te helpen bij het maken van je project:

### Variabelen gebruiken

```blocks3
set [my variable v] to (0)
```

[[[scratch3-create-set-variable]]]

[[[scratch3-set-variable-with-button]]]

[[[scratch3-change-variable-in-loop]]]

### Omstandigheden controleren

```blocks3
if <(my variable) = (0)> then
```

[[[scratch3-forever-condition]]]

[[[scratch3-operators-conditions]]]

[[[scratch3-if-then-else]]]

[[[scratch3-set-block-input-colour-with-eyedropper]]]

### Berichten verzenden en ontvangen

```blocks3
broadcast [message1 v]
```

[[[generic-scratch3-broadcast-message]]]

### Werken met tekst:

```blocks3
say (join[Hallo ](naam)) for (2) seconds
```

[[[scratch3-emoji-text]]]

[[[scratch3-ask-answer-chat]]]

[[[scratch3-join-text]]]

### Achtergronden, beweging en grafische effecten

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

### Geluid:

```blocks3
start sound (Pop v)
```

[[[scratch3-add-sound]]]

[[[scratch3-record-sound]]]

[[[scratch3-text-to-speech]]]

### De Paint-editor — achtergronden en uiterlijken

[[[scratch3-paint-a-new-backdrop-extended]]]

[[[scratch3-backdrops-and-sprites-using-shapes]]]

[[[scratch3-use-text-tool]]]

[[[scratch3-copy-parts-between-sprite-costumes]]]

[[[scratch3-add-costumes-to-a-sprite]]]

### De Scratch-editor

[[[scratch3-copy-code]]]

[[[scratch3-full-screen]]]

[[[scratch3-duplicate-sprite]]]

[[[scratch-backpack]]]


--- task ---

**Test:** Laat iemand anders je project zien en vraag feedback. Wil je wijzigingen aanbrengen in je spel?

--- /task ---

--- task ---

**Debug:** Mogelijk vindt je enkele fouten in jouw project die je moet oplossen. Hier zijn enkele veelvoorkomende fouten.


--- collapse ---

---
title: Variabelen worden niet correct bijgewerkt
---

Een veel voorkomende fout is het verwarren van de `verander`{:class="block3variables"} en `maak`{:class="block3variables"} blokken.

+ `maak`{:class="block3variables"} vervangt de waarde van een variabele door een nieuwe waarde.
+ `verander`{:class="block3variables"} voegt een getal toe aan een variabele. Als je een positief getal in het `verander met`{:class="block3variables"} blok gebruikt, wordt de waarde van de variabele groter. Als je een negatief getal in het `verander met`{:class="block3variables"} blok gebruikt, wordt de variabele waarde kleiner.


Een ander veel voorkomend probleem is het typen van de naam van een variabele in plaats van het slepen van de variabele uit het menu `variabelen`{:class="block3variables"} blokken. Variabelen moeten oranje zijn:

```blocks3
say (naam) for (2) seconds
```

**niet**:

```blocks3
say [naam] for (2) seconds
```

--- /collapse ---

--- collapse ---

---
title: Een verandering gebeurt slechts eenmaal in plaats van voor altijd
---

Zorg ervoor dat je codeblokken hebt geplaatst die moeten blijven draaien in een `herhaal`{:class="block3control"} blok. Het is heel gewoon om dit te vergeten!

--- /collapse ---

--- collapse ---

---
title: Voorwaarden voor het vergelijken van getallen werken niet
---

Weet je zeker dat je de `>`{:class="block3operators"} (groter dan) en `<`{:class="block3operators"} (minder dan) operators op de juiste manier hebt gebruikt?

```blocks3
<(gezondheid) > (0)> // betekent dat de gezondheidsvariabele groter moet zijn dan 0
<(gezondheid) < (5)> // betekent dat de gezondheidsvariabele kleiner moet zijn dan 5
```

**Tip:** het getal dat groter moet zijn, gaat aan de bredere (grotere) kant van het functie symbool.

--- /collapse ---

--- collapse ---

---
title: Er gebeurt niets wanneer ik een bericht uitzend
---

Zorg ervoor dat je een overeenkomstig `wanneer ik signaal ontvang`{:class="block3events"} blok hebt dat iets doet wanneer je `zend signaal`{:class="block3events"} blok een bericht uitzendt. Controleer of de berichtnamen overeenkomen.

--- /collapse ---

Mogelijk vind je een bug die hier niet wordt vermeld. Kun je erachter komen hoe je het kunt oplossen?

Als je vast komt te zitten, probeer je code hardop te lezen of het probleem uit te leggen aan een vriend. Je zou het probleem kunnen ontdekken.

We horen graag over je fouten en hoe je ze hebt opgelost. Gebruik de feedback knop onderaan deze pagina als je een andere bug in je project hebt gevonden.

--- /task ---


--- save ---

