# Utilización didáctica de Geogebra

## Contruyamos un cuadrado

### Vaya cosa más fácil, ¿no?

Depende de cómo realicemos una construcción, estaremos ante lo que pretendíamos construir... o no. Supongamos que queremos hacer un cuadrado y nos encontramos con lo siguiente:

![](/geogebra/assets/cuadrado_no1.png)

Parece un cuadrado, ¿verdad? Tiene cuatro lados que, además, son iguales... Los ángulos son también iguales... Es más, podemos decir que su lado son 5 unidades. Todo correcto, ¿no? Pues resulta que en Geogebra, eso que muestra la figura anterior, no es un cuadrado. Si tomamos un punto cualquiera y lo desplazamos, veremos que ocurre algo similar a esto:

![](/geogebra/assets/cuadrado_no2.png)

¡Eso no es cuadrado! ¡Hemos descubierto el engaño! Eso es debido a que para construir el «cuadrado» de la primera figura no nos hemos basado en las características esenciales de la figura a construir. Lo único que hemos hecho es disponer 4 puntos libres en la trama y unirlos con segmentos. Al ser puntos libres, se pueden desplazar como queramos, sin influir en el resto de objetos. La única restricción, si acaso, es que los segmentos dibujados siempre tienen como vértices A, B, C y D. Pero nada más.

### Pero, ¿no hay una herramienta para hacer polígonos?

Sí, la hay. Usémosla para hacer nuestro cuadrado.

![](/geogebra/assets/cuadrado_no3.png)

Qué bien ha quedado nuestro cuadrado, ¿no? Además, esta vez ha salido con un relleno sólido que le da más empaque. Veamos, lo del colorcillo es porque lo que tenemos ahora es un polígono, otro tipo de objeto distinto a los meros puntos y segmentos del apartado anterior. Sin embargo, hagamos la prueba de mover un vértice:

![](/geogebra/assets/cuadrado_no4.png)![](/geogebra/assets/tonteria2.png)

Nuestro gozo en un pozo, sigue pareciéndose a una cosa rara que salía en la primera de la _Guerra de las galaxias_... Entonces, ¿qué podemos hacer?

### Un cuadrado de verdad

Pensemos un poquito sobre por qué un cuadrado es un cuadrado. Es un cuadrilátero, por lo que tiene 4 vértices y 4 lados. Sus lados son iguales y perpendiculares entre sí. Y...bueno, con eso ya es suficiente. Conste que podríamos partir de otras propiedades que solamente cumplen los cuadrados, pero con las que hemos dicho, nos vale.

* Creamos dos puntos libres, que serán A y B, y los unimos con un segmento, que será uno de los lados del futuro cuadrado.
* Utilizamos la herramienta «Recta perpendicular» para crear dos rectas perpenciculares a AB pasando por A y por B, respectivamente.
* Utilizamos la herramienta «Circunferencia \(centro, punto\)» para encontrar un tercer vértice. Pinchamos nuestro compás en B y lo abrimos hasta A. Al punto de corte de esa circunferencia con la recta perpendicular a AB que pasa por B, lo llamamos C. Para bautizarlo en Geogebra tenemos que crearlo. Y eso se hace con la herramienta «Intersección»
* Nos falta nuestro D, que podemos hacerlo igual que hemos hecho para C, o creando una perpendicular a AC que pasa por C y creando el punto de corte de esa recta nueva con la perpendicular a AB que pasa por A.

![](/geogebra/assets/cuadrado_verdad_1.png)Ya está, ABCD es nuestro cuadrado, y si desplazamos A, sigue siendo un cuadrado:

![](/geogebra/assets/cuadrado_verdad2.png)

Hemos dejado la hoja llena de objetos que ya no nos hacen falta y queríamos hacer un cuadrado, no rectas y circunferencias de regalo. Bien, es verdad, entonces basta con crear un polígono sobre A, B, C y D y ocultar todos los objetos menos ese nuevo polígono:

![](/geogebra/assets/cuadrado_verdad_final.png)El archivo .ggb correspodiente puede descargarse [aquí](/geogebra/assets/geogebra-cuadrado.ggb).

### Algunas conclusiones sobre esto del cuadrado

Desde el punto de vista de la didáctica de la geometría, esto que acabamos de hacer con el cuadrado es esencial. Para hacer un simple cuadrado de verdad hemos tenido que reflexionar sobre qué hace que un cuadrado sea un cuadrado. Esto es, las propiedades necesarias y suficientes que ha de tener un cuadrilátero para poder ser considerado como un cuadrado.

A partir de aquí, las actividades obvias pasan por la definición de cuadriláteros y otras figuras geométricas. Si se complementa con las obligatorias reflexiones sobre lo que se está haciendo, estamos ante un recurso excelente y que, por otro lado, no tiene equivalente con lápiz y papel.  

## Conjeturemos

Geogebra fomenta que, con tareas adecuadas, los alumnos conjeturen.

