## Construye y prueba

Ahora es el momento de hacer tu proyecto. Empieza poco a poco y agrega más a tu proyecto si tienes tiempo.

![](images/step3_image.png)

**Consejo:** Recuerda probar tu proyecto cada vez que agregues algo. Es mucho más fácil encontrar y corregir errores antes de hacer más cambios.

--- task ---

Deberás decidir en qué orden construir tu proyecto. Tú podrías:

+ Crea una variable y permite que el usuario la controle. Agrega animaciones, disfraces, sonido, efectos y conversación para que el objeto realmente cobre vida
+ Crea múltiples variables con formas simples para que el usuario las controle y luego agregue más efectos más tarde

Agregar un objeto y luego crear una `variable`{:class="block3variables"} es un gran comienzo.

--- /task ---

Has desarrollado algunas habilidades realmente útiles. Aquí hay un recordatorio para ayudarte a hacer tu proyecto:

### Usando variables

```blocks3
set [my variable v] to (0)
```

[[[scratch3-create-set-variable]]]

[[[scratch3-set-variable-with-button]]]

[[[scratch3-change-variable-in-loop]]]

### Comprobación de condiciones

```blocks3
if <(my variable) = (0)> then
```

[[[scratch3-forever-condition]]]

[[[scratch3-operators-conditions]]]

[[[scratch3-if-then-else]]]

[[[scratch3-set-block-input-colour-with-eyedropper]]]

### Envío y recepción de mensajes

```blocks3
broadcast [message1 v]
```

[[[generic-scratch3-broadcast-message]]]

### Trabajando con texto:

```blocks3
say (join[Hola ](nombre)) for (2) seconds
```

[[[scratch3-emoji-text]]]

[[[scratch3-ask-answer-chat]]]

[[[scratch3-join-text]]]

### Fondos, movimiento y efectos gráficos

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

### Sonido:

```blocks3
start sound (Pop v)
```

[[[scratch3-add-sound]]]

[[[scratch3-record-sound]]]

[[[scratch3-text-to-speech]]]

### El Editor de dibujo — fondos y vestuarios

[[[scratch3-paint-a-new-backdrop-extended]]]

[[[scratch3-backdrops-and-sprites-using-shapes]]]

[[[scratch3-use-text-tool]]]

[[[scratch3-copy-parts-between-sprite-costumes]]]

[[[scratch3-add-costumes-to-a-sprite]]]

### Editor de Scratch

[[[scratch3-copy-code]]]

[[[scratch3-full-screen]]]

[[[scratch3-duplicate-sprite]]]

[[[scratch-backpack]]]


--- task ---

**Prueba:** Muestra tu proyecto a otra persona y obtén sus comentarios. ¿Quieres hacer algún cambio en tu juego?

--- /task ---

--- task ---

**Depuración:** Es posible que encuentres algunos errores en su proyecto que necesites corregir. A continuación, se muestran algunos errores comunes.


--- collapse ---

---
title: Las variables no se actualizan correctamente
---

Un error común es confundir los bloques `cambiar`{:class="block3variables"} y `fijar`{:class="block3variables"}.

+ `fijar`{:class="block3variables"} reemplaza el valor de una variable con un nuevo valor.
+ `cambiar`{:class="block3variables"} agrega un número a una variable. Si `cambias por`{:class="block3variables"} un número positivo, el valor de la variable aumenta. Si `cambias por`{:class="block3variables"} un número negativo, entonces el valor de la variable se vuelve más pequeño.


Otro problema común es escribir el nombre de una variable en lugar de arrastrar la variable desde el menú de bloques `Variables`{:class="block3variables"}. Las variables deben ser de color naranja:

```blocks3
say (nombre) for (2) seconds
```

**no**:

```blocks3
say [nombre] for (2) seconds
```

--- /collapse ---

--- collapse ---

---
title: Un cambio solo ocurre una vez en lugar de para siempre
---

Asegúrate de haber colocado bloques de código que deben seguir ejecutándose dentro de un bloque `por siempre`{:class="block3control"}. ¡Es muy común olvidarse de hacer esto!

--- /collapse ---

--- collapse ---

---
title: Las condiciones de comparación de números no funcionan
---

¿Está seguro de que ha utilizado los operadores `>`{:class="block3operators"} (mayor que) y `<`{:class="block3operators"} (menor que) en el sentido correcto?

```blocks3
<(salud) > (0)> // significa que la variable de salud debe ser mayor que 0
<(salud) < (5)> // significa que la variable de salud debe ser menor que 5
```

**Sugerencia:** El número que debe ser mayor va en el lado más ancho (más grande) del símbolo del operador.

--- /collapse ---

--- collapse ---

---
title: No pasa nada cuando transmito un mensaje
---

Asegúrate de tener un bloque `al recibir`{:class="block3events"} que hace algo cuando `envías`{:class="block3events"} un mensaje. Comprueba que los nombres de los mensajes coincidan.

--- /collapse ---

Es posible que encuentre un error que no aparece aquí. ¿Puedes averiguar cómo corregirlo?

Si te quedas atascado, intenta leer tu código en voz alta o explicarle el problema a un amigo. Es posible que detectes el problema.

Nos encanta conocer tus errores y cómo los solucionaste. Usa el botón Enviar comentarios en la parte inferior de esta página si encontraste un error diferente en tu proyecto.

--- /task ---


--- save ---

