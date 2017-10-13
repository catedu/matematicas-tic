# Escribir matemáticas

## LaTeX

LaTeX es algo que genera sentimientos encontrados. Hay gente que lo ama y gente que lo odia.

## LaTeX en MS Word

![](/herramientas/assets/latex-word.png)

Aproximadamente desde verano de 2017, ya se pueden escribir [ecuaciones en la sintaxis de LaTeX en documentos de MS Word](https://blogs.msdn.microsoft.com/murrays/2017/07/30/latex-math-in-office/). Para Powerpoint hay una triquiñuela, pero no hemos conseguido hacerla funcionar con el paquete de idioma español, así que lo dejaremos para otro momento y vamos a centrarnos ahora en lo que funciona desde la versión de Office 1707 \(Build 8326.2058\). Y esto es una novedad, a la que tampoco se le ha dado mucha publicidad, pero para la que existía una potencial comunidad de usuarios que la esperaban como agua de mayo. Facilita enormemente, por ejemplo, el copy-paste de fórmulas de otros sitios. Además, la sintaxis de LaTeX puede parecer extraña al principio, pero es bastante más eficaz para escribir ecuaciones y fórmulas que el seleccionado manual con el ratón a través de múltiples menús.

### Cómo funciona

1- Insertar ecuación y seleccionar modo {}LaTeX

[![](https://3.bp.blogspot.com/--1Y6LYgFEyc/Wb581DFkHlI/AAAAAAAAEZQ/sFbWA_N97YoYEMd5OZWCbCiO9ueDjKbVwCEwYBhgL/s1600/word01.jpg)](https://3.bp.blogspot.com/--1Y6LYgFEyc/Wb581DFkHlI/AAAAAAAAEZQ/sFbWA_N97YoYEMd5OZWCbCiO9ueDjKbVwCEwYBhgL/s1600/word01.jpg)

2- En el cuadro de la ecuación, escribir \(o pegar\) en sintaxis LaTeX la expresión que deseemos. Por ejemplo: \frac{a+b}{c+d}[![](https://4.bp.blogspot.com/-88omupwe07Q/Wb581My8ZzI/AAAAAAAAEZY/j9-Yft7EQ9AIjDeG4MYRKwZ_qwlyARAcACEwYBhgL/s1600/word02.jpg)](https://4.bp.blogspot.com/-88omupwe07Q/Wb581My8ZzI/AAAAAAAAEZY/j9-Yft7EQ9AIjDeG4MYRKwZ_qwlyARAcACEwYBhgL/s1600/word02.jpg)

3- Para ir alternando habrá que darle a "Convertir". Si convertimos a "Profesional", veremos el resultado:

[![](https://3.bp.blogspot.com/-bTZkagvVTSo/Wb581fq-jHI/AAAAAAAAEZY/9BAqXSmvb_kq3o6lq-A-LyN1biErDqb1QCEwYBhgL/s1600/word03.jpg)](https://3.bp.blogspot.com/-bTZkagvVTSo/Wb581fq-jHI/AAAAAAAAEZY/9BAqXSmvb_kq3o6lq-A-LyN1biErDqb1QCEwYBhgL/s1600/word03.jpg)

4- Mientras que si convertimos a "Lineal", volveremos a ver la expresión LaTeX que hay detrás de ese renderizado, pudiendo modificarla de nuevo.

### Cosas interesantes

Si copiamos una fórmula de estas y pegamos en otra aplicación \(editor de LaTeX o un simple notepad\), lo que aparecerá será la expresión LaTeX. Maravilloso. Aunque sería todavía mejor si Word permitiese entrar en el modo ecuación tecleando $$ o \\[. Todo llegará, supongo. Y otra cosa que tampoco está habilitada en el editor de ecuaciones en modo LaTeX es el empleo de tags como \begin o \end.

### Y limitaciones

A día de hoy \(octubre de 2017\), y con la última versión posible de Word, nos encontramos con situaciones un poco marcianas. Son situaciones que recuerdan a esos vídeos de YouTube en los que cogen una canción en inglés, la traducen con Google Translate a otros idiomas y luego de vuelta al inglés. Y el resultado, bueno, el resultado os lo podéis [imaginar](https://www.youtube.com/watch?v=6mqG5l-9wIE).

## El minimalismo al rescate

El minimalismo es bello. Y en lo que a escritura se refiere, tiene nombre propio: [Markdown](https://es.wikipedia.org/wiki/Markdown). De hecho, este libro está hecho con Gitbook, que sigue ese sistema. En lo que a matemáticas se refiere, se puede escribir esto de aquí:


$$
e=\lim_{n\to\infty} \left(1 +\cfrac{1}{n}\right)^n
$$


sin más que escribir esto otro:

```
$$e=\lim_{n\to\infty} \left(1+\cfrac{1}{n}\right)^n$$
```

Si es la primera vez que ves la sintaxis de LaTeX para expresiones matemáticas, te puede sonar raro. Pero enseguida te habitúas. Y respecto a la sintaxis de Markdown, resulta tan simple que pronto te ves escribiendo palabras entre dos asteriscos para activar la **negrita**.

```
**negrita**
```

Hay un buen puñado de editores de Markdown. En el fondo, basta con un editor de texto plano, como el bloc de notas de toda la vida o el magnífico [Notepad++](https://notepad-plus-plus.org). Pero es que no hace falta. Los editores especializados en Markdown te permiten ver directamente el resultado de lo que escribes. Por ejemplo, esta es la barra de Gitbook Editor que veo arriba del todo mientras escribo estas líneas:

![](/herramientas/assets/barra-gitbook.png)

¿Para qué más? Lo simple es bello. Y si quieres cambiar el estilo, también hay plantillas y formas de hacerlo. A continuación, vamos a ver un poquito en profundidad un editor que, aunque se encuentra en versión beta todavía, es increíble. Por simple. Se trata de [Typora](https://typora.io/). 

### Typora

En la página web de [Typora ](https://typora.io/)podemos descargar el programita en cuestión. Si tenemos Windows o Mac se nos bajará un ejecutable, mientras que si tenemos Linux, en la página vienen las [instrucciones ](https://typora.io/#linux)para que se mantenga actualizado.


