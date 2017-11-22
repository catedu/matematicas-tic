# Scratch

Si bien Geogebra es un software esencialmente matemático, [Scratch ](https://scratch.mit.edu/)es una aplicación que ha ido ganando mucha popularidad en diferentes ámbitos y que tiene también un potencial enorme en la enseñanza y el aprendizaje de ciertos contenidos propios de las matemáticas. Normalmente, Scratch se asocia a lo que se conoce como pensamiento computacional. De hecho, existen cursos que directamente se denominan «Pensamiento computacional con Scratch».

## Los algoritmos en la educación matemática

La enseñanza de las matemáticas está llena de algoritmos. Así, ya en las primeras etapas nos encontramos con algoritmos \(tradicionales o no\) para las operaciones básicas, más adelante tenemos los que permiten calcular el mínimo común múltiplo y el máximo común divisor y... en bachillerato, por ejemplo, se aprende el método de Gauss para resolver sistemas de ecuaciones lineales. Al enseñar estos algoritmos, lo realmente interesante, es que los alumnos aprendan a asignarles un significado. Es decir,

Por otro lado, cuando diseñamos un algoritmo hemos de anticiparnos

### Un ejemplo de pseudocódigo

El siguiente ejemplo describe lo que vendría a ser un entrenamiento de natación. Es un algoritmo que devuelve los metros que se han hecho en total, a partir del número de series de 100 que se definen, los metros de calentamiento y los metros de vuelta a la calma.

```
ALGORITMO entrenamiento
DATOS
    calentamiento  
    calma
    numseries100
    metros
INICIO
    metros = 0
    calentamiento = 400
    calma = 600
    numseries100 = 10
    metros = calentamiento
REPETIR numseries100
    metros = metros + 100
FIN REPETIR
    metros = metros + calma
ESCRIBIR “Has hecho <metros> metros. Enhorabuena”
FIN
```

### Otro ejemplo de pseudocódigo: algoritmo de la suma tradicional

```
ALGORITMO suma
DATOS
    sumando1
    sumando2
INICIO
    escribir el primer número
    escribir debajo el segundo número, de forma que coincidan unidades con unidades, decenas con decenas, etc.
    trazar una línea horizontal
    llevada=0
    REPETIR veces=máximo(cifras de sumando1, cifras de sumando2)
        orden=0 //indica la posición que tomaremos. Orden 0 serán las unidades.
        parcial=sumando1(orden)+sumando2(orden)
        SI parcial<10 ENTONCES //no hay llevada
            ESCRIBIR parcial
            llevada=0
        EN CASO CONTRARIO //hay llevada
            ESCRIBIR parcial-10
            llevada=1 
```

## Empezando con Scratch

La tarea de iniciación a Scratch más habitual es la realización de un collage de presentación. 

## Diseño de una actividad con Scratch

A continuación, dejamos un ejemplo de diseño en detalle de una actividad en torno a la idea de mínimo común múltiplo.

![](/otros-recursos/assets/scratch_canvas.png)

