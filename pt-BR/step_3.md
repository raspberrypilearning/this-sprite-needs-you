## Construir e testar

Agora é hora de fazer seu projeto. Comece pequeno e acrescente mais ao seu projeto se tiver tempo.

![](images/step3_image.png)

**Dica:** Lembre-se de testar seu projeto sempre que adicionar algo. É muito mais fácil localizar e corrigir bugs antes de fazer mais alterações.

--- task ---

Você precisará decidir em que ordem construir seu projeto. Você poderia:

+ Criar uma variável e permitir que o usuário a controle. Adicionar animações, fantasias, sons, efeitos e conversas para dar vida ao ator
+ Criar múltiplas variáveis com maneiras simples para o usuário controlá-las e adicionar mais efeitos posteriormente

Adicionar um ator e depois criar uma `variável`{:class="block3variables"} é um ótimo começo.

--- /task ---

Você desenvolveu algumas habilidades realmente úteis. Aqui está um lembrete para ajudá-lo a fazer seu projeto:

### Usando variáveis

```blocks3
set [my variable v] to (0)
```

[[[scratch3-create-set-variable]]]

[[[scratch3-set-variable-with-button]]]

[[[scratch3-change-variable-in-loop]]]

### Verificando condições

```blocks3
if <(my variable) = (0)> then
```

[[[scratch3-forever-condition]]]

[[[scratch3-operators-conditions]]]

[[[scratch3-if-then-else]]]

[[[scratch3-set-block-input-colour-with-eyedropper]]]

### Transmitir e receber mensagens

```blocks3
broadcast [mensagem1 v]
```

[[[generic-scratch3-broadcast-message]]]

### Trabalhando com texto:

```blocks3
say (join[Olá ](nome)) for (2) seconds
```

[[[scratch3-emoji-text]]]

[[[scratch3-ask-answer-chat]]]

[[[scratch3-join-text]]]

### Cenários, movimento e efeitos gráficos

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

### Som:

```blocks3
start sound (Pop v)
```

[[[scratch3-add-sound]]]

[[[scratch3-record-sound]]]

[[[scratch3-text-to-speech]]]

### O editor Paint — cenários e fantasias

[[[scratch3-paint-a-new-backdrop-extended]]]

[[[scratch3-backdrops-and-sprites-using-shapes]]]

[[[scratch3-use-text-tool]]]

[[[scratch3-copy-parts-between-sprite-costumes]]]

[[[scratch3-add-costumes-to-a-sprite]]]

### O editor Scratch

[[[scratch3-copy-code]]]

[[[scratch3-full-screen]]]

[[[scratch3-duplicate-sprite]]]

[[[scratch-backpack]]]


--- task ---

**Teste:** Mostre seu projeto a outra pessoa e peça sua opinião. Quer fazer alguma alteração no seu jogo?

--- /task ---

--- task ---

**Depurar:** Talvez você encontre alguns bugs em seu projeto que precisam de correção. Aqui estão alguns bugs comuns.


--- collapse ---

---
title: Variáveis não estão atualizando corretamente
---

Um erro comum é confundir os blocos `adicione`{:class="block3variables"} e `mude`{:class="block3variables"}.

+ `mude`{:class="block3variables"} substitui o valor de uma variável por um novo valor.
+ `adicione`{:class="block3variables"} adiciona um número a uma variável. Se você alterar `adicione a`{:class="block3variables"} por um número positivo, o valor da variável ficará maior. Se você alterar `adicione a`{:class="block3variables"} por um número negativo, o valor da variável ficará menor.


Outro problema comum é digitar o nome de uma variável em vez de arrastá-la do menu de blocos `Variáveis`{:class="block3variables"}. As variáveis devem ser laranja:

```blocks3
say (nome) for (2) seconds
```

**não**:

```blocks3
say [nome] for (2) seconds
```

--- /collapse ---

--- collapse ---

---
title: A mudança só acontece uma vez em vez de para sempre
---

Certifique-se de ter colocado blocos de código que precisam continuar em execução dentro de um bloco `sempre`{:class="block3control"}. É muito comum esquecer de fazer isso!

--- /collapse ---

--- collapse ---

---
title: As condições de comparações de números não estão funcionando
---

Tem certeza de que usou os operadores `>`{:class="block3operators"} (maior que) e `<`{:class="block3operators"} (menor que) da maneira correta?

```blocks3
<(saúde) > (0)> // significa que a variável de saúde deve ser maior que 0
<(saúde) < (5)> // significa que a variável de saúde deve ser menor que 5
```

**Dica:** O número que deve ser maior fica no lado mais largo (maior) do símbolo do operador.

--- /collapse ---

--- collapse ---

---
title: Nada acontece quando eu transmito uma mensagem
---

Certifique-se de ter um bloco `quando eu receber`{:class="block3events"} correspondente que faz algo quando você `transmite`{:class="block3events"} uma mensagem. Verifique se os nomes das mensagens correspondem.

--- /collapse ---

Talvez você encontre um bug que não esteja listado aqui. Você consegue descobrir como consertá-lo?

Se você tiver dúvidas, tente ler seu código em voz alta ou explicar o problema a um amigo. Talvez você identifique o problema.

Adoraríamos saber sobre seus bugs e como você os corrigiu. Use o botão Enviar comentários na parte inferior desta página e nos diga se você encontrou um bug diferente em seu projeto.

--- /task ---


--- save ---

