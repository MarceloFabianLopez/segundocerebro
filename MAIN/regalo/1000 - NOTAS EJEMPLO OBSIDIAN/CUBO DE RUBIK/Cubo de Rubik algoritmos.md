# Cómo resolver el cubo de Rubik mediante los circuitos de Emowe
El **cubo de Rubik o cubo mágico** se dice que es el juguete con más éxito y vendido del mundo, más de 450 millones de cubos vendidos y después de más de 40 años desde su invención, todavía sigue estando en la mayoría de hogares.  

El cubo está formado por 6 caras compuestas de 6 cuadrados en forma de 3x3. 

El cubo tiene tres piezas:
 - La **pieza central** que es fija, solo tiene una cara y está en el centro de cada cara del cubo. Hay seis caras centrales que son las que marcan el color de cada cara del cubo.
 - Las **piezas aristas**, tienen dos caras. Están en el centro de cada arista del cubo. Hay 12 piezas aristas.
 - Las **piezas esquinas**, tienen tres caras. Son las esquinas del cubo. Hay 8 piezas esquina.

Lo único que no se puede mover es la pieza central de cada cara. Estas piezas centrales son fijas. 

Para realizar los circuitos visuales recomiendo un cubo estándar u oficial. Donde la cara blanca esté opuesta a la amarilla.

# 7 Fases cómo resolver cubo de Rubik

## Fase 1. Cruz blanca junto con centros caras

### Objetivo
![[Pasted image 20210728083315.png]]

### Minutaje vídeo donde empieza esta fase
https://www.youtube.com/watch?v=Wyn7WwBbM0o&list=PLWUX-KZsnKXSNhFFFcjBjml0HEzb7ZLlp&index=7&t=432s

### Técnica
Esta fase se puede resolver fácilmente aplicando la lógica y con algunos trucos.

Nos centramos en alinear aristas blancas con su pieza central blanca y las piezas centrales de cada cara.

El principal truco está en localizar una arista en la capa superior, rotar la rodaja lateral sin romper el resto de cruz blanca para que la arista quede en la capa inferior y rotar la rodaja de la capa inferior hasta buscar la pieza central de su color. Una vez alineada, rotamos esa rodaja para llevarla a la capa superior.

## Fase 2. Completar la primera rodaja superior del cubo
### Objetivo
![[Pasted image 20210728084539.png]]

### Minutaje vídeo donde empieza esta fase
https://www.youtube.com/watch?v=Wyn7WwBbM0o&list=PLWUX-KZsnKXSNhFFFcjBjml0HEzb7ZLlp&index=7&t=541s
### Técnica
Nos centramos en colocar las esquinas de la cruz blanca cara superior aplicando la lógica. 

Primero debemos intentar colocar la cara blanca de cualquiera de las esquinas abajo del todo sin que quede en la cara inferior.

Colocamos la esquina blanca que queremos subir abajo del todo pero con el color blanco en el lateral, no en la parte inferior, y el color del otro lateral que coincida con su cara.
Y la cara que tiene el blanco la rotamos frontalmente moviéndola al otro lado y luego rotamos para juntar los blancos.

En esta fase siempre rotamos frontalmente la esquina que tenga cara blanca y luego juntamos.

Aquí el truco está en poner la esquina que queremos subir  con la blanca que no quede en la parte inferior y que la pieza tenga el mismo color que su cara, cuando decimos color de su cara siempre nos referimos a la pieza central. 

La apartamos un poco y rotamos la pareja de blancas. Al rotar la pareja de blancas teniendo su esquina en la misma rodaja se queda preparada para mover la fila inferior y alinearlas.

## Fase 3. Completar la rodaja central del cubo
Movemos las aristas que estén en la rodaja inferior a la rodaja central del cubo una a una. Unas habrá que moverlas a la izquierda, y otras a la derecha. Si están en la rodaja central posición errónea, habrá que aplicar el algoritmo en esa cara para quitarlas de ahí. Si podemos aprovechar para colocar ahí la correcta, podemos matar dos pájaros de un tiro.

### Objetivo y técnica visual del circuito mover arista a la derecha
![[Pasted image 20210728085547.png]]
Este es el circuito más complicado de todos. Paciencia es la madre de la Ciencia. 

**Truco mnemónico:** el circuito son unas gafas con un lazo cuadrado. El circuito a recordar es curioso que coincide la arista que queremos mover con el lazo de las gafas en forma de cubo y las gafas están una posición por encima del lazo en forma de cubo y a la derecha, justo donde queremos dejar la arista central de la capa inferior.

O sea, el lazo cuadrado sería la arista que queremos mover y las gafas el destino final de la arista. Hay un dicho que dice donde pongo el ojo, pongo la bala. En este caso donde pongo las gafas, pongo la arista de la rodaja inferior.

**Dedo gordo:** el dedo gordo es la posición del dedo en el cubo donde debemos aplicar el circuito. En este caso, como queremos mover la arista a la derecha, lo colocaremos en la rodaja inferior derecha, que es azul.

Azul: para ayudarte a recordarlo este color es el de un partido político de derechas. No se me ocurre ningún otra simbología para representar izquierda y derecha con colores.

**Posición inicial:** situamos frontalmente la cara donde esté la arista que queremos mover.

#### Minutaje vídeo donde empieza esta situación
https://www.youtube.com/watch?v=Wyn7WwBbM0o&list=PLWUX-KZsnKXSNhFFFcjBjml0HEzb7ZLlp&index=7&t=684s
### Objetivo y técnica visual del circuito mover arista a la izquierda
Simétrico al anterior.

![[Pasted image 20210728091221.png]]

**Truco mnemónico:** el circuito son unas gafas con un lazo cuadrado. Es simétrico al anterior porque aqui hacemos lo mismo pero a la izquierda, por eso ahora el circuito es de color rojo (partido político de izquierdas).

O sea, el lazo cuadrado sería la arista que queremos mover y las gafas el destino final de la arista. Hay un dicho que dice donde pongo el ojo, pongo la bala. En este caso donde pongo las gafas, pongo la arista de la rodaja inferior, ahora a la izquierda.

**Posición inicial:** situamos frontalmente la cara donde esté la arista que queremos mover.




## Fase 4. Bucle hasta crear cruz amarilla
Aplicaremos el algoritmo tantas veces hasta conseguir la cruz amarilla. En esta fase da igual que las aristas de la cruz amarilla no coincidan con las caras del cubo lateral. Esto lo solucionaremos en la siguiente fase.

### Objetivo y técnica visual del circuito 
![[Pasted image 20210728092550.png]]

**Truco mnemónico:** el circuito es un candado invertido. Como este algoritmo es para formar una cruz amarilla, que serían como una jaula amarilla, necesitamos abrir el candado dándole la vuelta. 

El circuito comienza en la punta del candado hacia abajo.

Como a partir de ahora estamos trabajando en la cara superior, cambiamos de posición donde pondremos el dedo gordo para aplicar el circuito, en este caso es en la parte superior derecha (verde como otro partido político de derechas).

Como ahora trabajaremos en los siguientes algoritmos en la rodaja superior, los colores en los siguientes algoritmos serán verdes o morados, a excepción del último.

#### Posiciones iniciales
En esta fase para buscar la posición inicial hay que tener en cuenta algún escenario más.

La cara amarilla debe estar siempre en la parte superior y aplicar el algoritmo sucesivas veces según desde que paso estés. Puede que tu cubo al llegar a esta fase ya esté en el paso 2 o 3 y tengas que aplicar este algoritmo menos veces.
 1. Punto amarillo, da igual posición frontal siempre que la cara amarilla esté en la parte superior.
 2. Teniendo la ele amarilla mirando a la izquierda de forma invertida.
 3. Teniendo la línea amarilla de forma paralela a nosotros, es decir, que vaya de izquierda a derecha.

![[Pasted image 20210728092332.png|400x500]]

### Minutaje vídeo donde empieza esta fase
https://www.youtube.com/watch?v=Wyn7WwBbM0o&list=PLWUX-KZsnKXSNhFFFcjBjml0HEzb7ZLlp&index=7&t=1268s
## Fase 5. Aristas cruz amarilla con color de las caras
En esta fase conseguiremos que las aristas que forman la cruz amarilla coincidan con los colores de las caras del cubo.



### Objetivo y técnica visual del circuito 
![[Pasted image 20210728093811.png]]

**Truco mnemónico:** este circuito se parece a una ballena con la cola levantada. El circuito comienza donde empieza la flecha. ¿Y dónde está la flecha? Pues en la parte de la ballena que tiene forma de flecha y es en su cola. El circuita va desde la zona superior y luego inferior de la ballena.

El dedo gordo lo aplicaremos también en la zona superior derecha (verde).

**Posición inicial:** buscar que la cruz amarilla coincida en color con dos caras del cubo contiguas. Ir girando la cara superior hasta encontrarlas. Colocar las dos caras contiguas, una frontal a ti y la otra a la derecha. 

Aquí solo aplicaremos el algoritmo una única vez, si están las dos aristas de la cruz amarilla con el mismo color de la cara del cubo y son contiguas. En caso contrario, repetir hasta conseguir esta situación.

Si estuviera la segunda arista que coincide en el lado opuesto, en vez de contigua, hay que aplicar este mismo algoritmo hasta que queden contiguas. Si no hubiera ninguna aplicar también este mismo algoritmo.

### Minutaje vídeo donde empieza esta fase
https://www.youtube.com/watch?v=Wyn7WwBbM0o&list=PLWUX-KZsnKXSNhFFFcjBjml0HEzb7ZLlp&index=7&t=1485s
## Fase 6. Conmutar las esquinas a su posición aunque sin orientar
En esta fase colocaremos las esquinas de la cara amarilla en su posición correcta, aunque estén mal orientadas. Aunque la cara amarilla de la esquina no quede en la cara superior del cubo.

### Objetivo y técnica visual del circuito 
![[fase 6.jpg]]

**Truco mnemónico:** como tenemos que conmutar las esquinas saltando de una esquina del cuadrado al otro es como si dibujásemos dos cuadrados formando un circuito de un ocho. 

Este ocho está formado por un 7 morado y el resto verde. En función del color del tramo debemos colocar en la zona superior derecha (verde) o en la zona superior izquierda (roja).

Actualizado posterioridad al vídeo: en mi caso usé el 7 morado por un evento personal que relaciona el 7 con este color, pero también puedes usar el 1 morado y 3 invertido verde. En el caso de la fila superior daría igual para el tramo superior si se realiza desde la pieza izquierda o derecha superior. Por tanto ese tramo puede ser verde o morado, según os convenga para vuestra memoria u os sea más fácil.

![[Pasted image 20210729165347.png|100x150]]

![[Pasted image 20210729165438.png|100x150]]

**Posición inicial:** buscar alguna esquina que esté en su sitio aunque esté mal orientada y la colocamos a la derecha. Si no hay ninguna aplicamos igualmente este algoritmo para forzar esta posición inicial.

### Minutaje vídeo donde empieza esta fase
https://www.youtube.com/watch?v=Wyn7WwBbM0o&list=PLWUX-KZsnKXSNhFFFcjBjml0HEzb7ZLlp&index=7&t=1596s

## Fase 7 y final. Orientar esquinas cara amarilla
En esta última fase debemos acomodar las esquinas del cubo, para ello hay que realizar un bucle hasta orientar cada esquina y finalizar el cubo.

### Objetivo y técnica visual del circuito 
![[fase 7.jpg]]

**Truco mnemónico:** el más sencillo. Un circuito con forma de cuadrado, como el cubo para terminar resolviéndolo.

El dedo gordo lo aplicaremos también en la zona inferior derecha (azul) porque usamos la capa inferior para orientar las esquinas que nos iremos bajando.

**Posición inicial:** la esquina que queremos orientar la colocaremos a la derecha.

### Minutaje vídeo donde empieza esta fase
https://www.youtube.com/watch?v=Wyn7WwBbM0o&list=PLWUX-KZsnKXSNhFFFcjBjml0HEzb7ZLlp&index=7&t=1860s

¡Enhorabuena si has llegado hasta aquí!

![[Pasted image 20210728101648.png|500x600]]