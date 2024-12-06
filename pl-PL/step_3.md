## Buduj i testuj

Nadszedł czas na wykonanie projektu. Zacznij od czegoś małego i dodaj więcej do swojego projektu, jeśli masz czas.

![](images/step3_image.png)

**Wskazówka:** Pamiętaj, aby testować swój projekt za każdym razem, gdy coś dodasz. Znacznie łatwiej jest znaleźć i naprawić błędy zanim wprowadzisz więcej zmian.

--- task ---

Będziesz musiał zdecydować, w jakiej kolejności zbudujesz swój projekt. Możesz:

+ Utwórz jedną zmienną i pozwól użytkownikowi nią sterować. Dodaj animacje, kostiumy, dźwięki, efekty i rozmowy, aby duszek naprawdę ożył
+ Utwórz wiele zmiennych, którymi użytkownicy będą mogli sterować w prosty sposób, a później dodaj efekty

Dodanie duszka, a następnie utworzenie `zmiennej`{:class="block3variables"} to świetny początek.

--- /task ---

Zdobyłeś kilka naprawdę przydatnych umiejętności. Oto przypomnienie, które pomoże Ci w tworzeniu projektu:

### Używanie zmiennych

```blocks3
set [my variable v] to (0)
```

[[[scratch3-create-set-variable]]]

[[[scratch3-set-variable-with-button]]]

[[[scratch3-change-variable-in-loop]]]

### Sprawdzanie warunków

```blocks3
if <(my variable) = (0)> then
```

[[[scratch3-forever-condition]]]

[[[scratch3-operators-conditions]]]

[[[scratch3-if-then-else]]]

[[[scratch3-set-block-input-colour-with-eyedropper]]]

### Nadawanie i odbieranie wiadomości

```blocks3
broadcast (message1 v)
```

[[[generic-scratch3-broadcast-message]]]

### Praca z tekstem:

```blocks3
say (join[Hello ](name)) for (2) seconds
```

[[[scratch3-emoji-text]]]

[[[scratch3-ask-answer-chat]]]

[[[scratch3-join-text]]]

### Tła, ruch i efekty graficzne

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

### Dźwięk:

```blocks3
start sound (Pop v)
```

[[[scratch3-add-sound]]]

[[[scratch3-record-sound]]]

[[[scratch3-text-to-speech]]]

### Edytor Malowania— tła i kostiumy

[[[scratch3-paint-a-new-backdrop-extended]]]

[[[scratch3-backdrops-and-sprites-using-shapes]]]

[[[scratch3-use-text-tool]]]

[[[scratch3-copy-parts-between-sprite-costumes]]]

[[[scratch3-add-costumes-to-a-sprite]]]

### Edytor Scratch

[[[scratch3-copy-code]]]

[[[scratch3-full-screen]]]

[[[scratch3-duplicate-sprite]]]

[[[scratch-backpack]]]


--- task ---

**Test:** Pokaż komuś swój projekt i poproś o jego opinię. Czy chcesz wprowadzić jakieś zmiany w swojej grze?

--- /task ---

--- task ---

**Debugowanie:** Być może znajdziesz błędy w swoim projekcie, które musisz naprawić. Oto kilka typowych błędów.


--- collapse ---

---
Zmienne nie aktualizują się poprawnie
---

Częstym błędem jest mylenie bloków `zmień`{:class="block3variables"} i `ustaw`{:class="block3variables"}.

+ `set`{:class="block3variables"} zastępuje wartość zmiennej nową wartością.
+ `zmień`{:class="block3variables"} dodaje liczbę do zmiennej. Jeśli `zmienisz o`{:class="block3variables"} liczbę dodatnią, wartość zmiennej wzrośnie. Jeśli `zmienisz o`{:class="block3variables"} liczbę ujemną, wartość zmiennej będzie mniejsza.


Innym częstym problemem jest wpisywanie nazwy zmiennej zamiast przeciągania zmiennej z menu bloków `Zmienne`{:class="block3variables"}. Zmienne powinny być koloru pomarańczowego:

```blocks3
say (name) for (2) seconds
```

nie:

```blocks3
say [name] for (2) seconds
```

--- /collapse ---

--- collapse ---

---
tytuł: Zmiana następuje tylko raz, a nie zawsze
---

Upewnij się, że umieściłeś bloki kodu, które muszą działać, w bloku `zawsze`{:class="block3control"}. Bardzo często zdarza się, że o tym zapominamy!

--- /collapse ---

--- collapse ---

---
tytuł: Warunki porównań liczb nie działają
---

Czy na pewno użyłeś operatorów `>`{:class="block3operators"} (większy niż) i `<`{:class="block3operators"} (mniejszy niż) we właściwy sposób?

```blocks3
<(health) > (0)> // means the health variable must be bigger than 0
<(health) < (5)> // means the health variable must be smaller than 5
```

**Wskazówka:** Liczba, która musi być większa, znajduje się po szerszej (większej) stronie symbolu operatora.

--- /collapse ---

--- collapse ---

---
tytuł: Nic się nie dzieje, gdy wysyłam wiadomość
---

Upewnij się, że masz blok `kiedy otrzymam wiadomość` {:class="block3events"}, który robi coś, gdy blok `nadaj komunikat`{:class="block3events"} nada wiadomość. Sprawdź, czy nazwy wiadomości są zgodne.

--- /collapse ---

Możesz też znaleźć błąd, który nie został tutaj wymieniony. Czy wymyślisz, jak go naprawić?

Jeśli utkniesz, spróbuj przeczytać kod na głos lub wyjaśnić problem znajomemu. Być może zauważysz problem.

Uwielbiamy słuchać o błędach jakie znalazłeś i o tym, jak je naprawiłeś. Użyj przycisku Prześlij opinię na dole tej strony i poinformuj nas, czy w Twoim projekcie pojawił się inny błąd.

--- /task ---


--- save ---

