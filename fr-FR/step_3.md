## Construire et tester

Maintenant, il est temps de créer ton projet. Commence doucement et développe ton projet si tu as le temps.

![](images/step3_image.png)

**Astuce :** N'oublie pas de tester ton projet à chaque fois que tu ajoutes quelque chose. Il est beaucoup plus facile de trouver et de corriger les bogues avant d'apporter d'autres modifications.

--- task ---

Tu vas devoir décider dans quel ordre construire ton projet. Tu pourrais :

+ Créer une variable et permettre à l'utilisateur de la contrôler. Ajouter des animations, des costumes, du son, des effets et des conversations pour donner vie au sprite
+ Créer plusieurs variables avec des moyens simples pour l'utilisateur de les contrôler, puis ajouter plus d'effets plus tard

Ajouter un sprite puis créer une `variable`{:class="block3variables"} est un bon début.

--- /task ---

Tu as acquis des compétences vraiment utiles. Voici un rappel pour t'aider à réaliser ton projet :

### Utiliser des variables

```blocks3
set [my variable v] to (0)
```

[[[scratch3-create-set-variable]]]

[[[scratch3-set-variable-with-button]]]

[[[scratch3-change-variable-in-loop]]]

### Vérifier les conditions

```blocks3
if <(my variable) = (0)> then
```

[[[scratch3-forever-condition]]]

[[[scratch3-operators-conditions]]]

[[[scratch3-if-then-else]]]

[[[scratch3-set-block-input-colour-with-eyedropper]]]

### Envoyer et recevoir des messages

```blocks3
broadcast [message1 v]
```

[[[generic-scratch3-broadcast-message]]]

### Travailler avec du texte :

```blocks3
say (join[Bonjour ](nom)) for (2) seconds
```

[[[scratch3-emoji-text]]]

[[[scratch3-ask-answer-chat]]]

[[[scratch3-join-text]]]

### Décors, mouvement et effets graphiques

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

### Effets sonores :

```blocks3
start sound (Pop v)
```

[[[scratch3-add-sound]]]

[[[scratch3-record-sound]]]

[[[scratch3-text-to-speech]]]

### L'éditeur d'images — arrière-plans et costumes

[[[scratch3-paint-a-new-backdrop-extended]]]

[[[scratch3-backdrops-and-sprites-using-shapes]]]

[[[scratch3-use-text-tool]]]

[[[scratch3-copy-parts-between-sprite-costumes]]]

[[[scratch3-add-costumes-to-a-sprite]]]

### L'éditeur Scratch

[[[scratch3-copy-code]]]

[[[scratch3-full-screen]]]

[[[scratch3-duplicate-sprite]]]

[[[scratch-backpack]]]


--- task ---

**Test :** Montre ton projet à quelqu'un et demande-lui son avis. Souhaites-tu apporter des modifications à ton jeu ?

--- /task ---

--- task ---

**Débogage :** Il est possible que tu trouves des bogues dans ton projet que tu dois corriger. Voici quelques bogues assez courants.


--- collapse ---

---
title: Les variables ne sont pas mises à jour correctement
---

Une erreur courante consiste à confondre les blocs `ajouter`{:class="block3variables"} et `mettre`{:class="block3variables"}.

+ `mettre`{:class="block3variables"} remplace la valeur d'une variable par une nouvelle valeur.
+ `ajouter`{:class="block3variables"} ajoute un nombre à une variable. Si tu `ajoutes`{:class="block3variables"} un nombre positif, la valeur de la variable augmente. si tu `ajoutes`{:class="block3variables"} un nombre négatif, la valeur de la variable diminue.


Un autre problème courant consiste à taper le nom d'une variable au lieu de faire glisser la variable depuis le menu des blocs `Variables`{:class="block3variables"}. Les variables doivent être orange :

```blocks3
say (nom) for (2) seconds
```

**et pas** :

```blocks3
say [nom] for (2) seconds
```

--- /collapse ---

--- collapse ---

---
title: Un changement ne se produit qu'une seule fois au lieu de toujours
---

Assure-toi d'avoir placé des blocs qui doivent continuer à être exécutés en boucle dans un bloc `répéter indéfiniment`{:class="block3control"}. C'est très courant d'oublier de le faire !

--- /collapse ---

--- collapse ---

---
title: Les conditions de comparaison de nombres ne fonctionnent pas
---

Es-tu sûr d'avoir utilisé les opérateurs `>`{:class="block3operators"} (supérieur à) et `<`{:class="block3operators"} (inférieur à) dans le bon sens ?

```blocks3
<(santé) > (0)> // signifie que la variable de santé doit être supérieure à 0
<(santé) < (5)> // signifie que la variable de santé doit être inférieure à 5
```

**Astuce :** Le nombre qui doit être plus grand va sur le côté le plus large (le plus grand) du symbole de l'opérateur.

--- /collapse ---

--- collapse ---

---
title: Rien ne se passe lorsque j'envoie à tous un message
---

Assure-toi d'avoir un bloc correspondant `quand je reçois`{:class="block3events"} qui fait quelque chose lorsqu'un message est`envoyé à tous`{:class="block3events"}. Vérifie que les noms des messages correspondent.

--- /collapse ---

Tu pourrais trouver un bogue qui n'est pas répertorié ici. Peux-tu trouver comment le réparer ?

Si tu es bloqué, essaye de lire ton code à haute voix ou d'expliquer le problème à un ami. Tu pourras peut-être repérer le problème.

Nous aimons avoir des nouvelles de tes bogues et de la façon dont tu les as corrigés. Utilise le bouton de commentaires au bas de cette page si tu as trouvé un bogue différent dans ton projet.

--- /task ---


--- save ---

