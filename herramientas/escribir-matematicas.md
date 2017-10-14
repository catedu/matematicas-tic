# Escribir matemáticas

## LaTeX

LaTeX es algo que genera sentimientos encontrados. Hay gente que lo ama y gente que lo odia.

## LaTeX en MS Word

![](/herramientas/assets/latex-word.png)

Aproximadamente desde verano de 2017, ya se pueden escribir [ecuaciones en la sintaxis de LaTeX en documentos de MS Word](https://blogs.msdn.microsoft.com/murrays/2017/07/30/latex-math-in-office/). Para Powerpoint hay una triquiñuela, pero no hemos conseguido hacerla funcionar con el paquete de idioma español, así que lo dejaremos para otro momento y vamos a centrarnos ahora en lo que funciona desde la versión de Office 1707 \(Build 8326.2058\). Y esto es una novedad, a la que tampoco se le ha dado mucha publicidad, pero para la que existía una potencial comunidad de usuarios que la esperaban como agua de mayo. Facilita enormemente, por ejemplo, el copy-paste de fórmulas de otros sitios. Además, la sintaxis de LaTeX puede parecer extraña al principio, pero es bastante más eficaz para escribir ecuaciones y fórmulas que el seleccionado manual con el ratón a través de múltiples menús.

### Cómo funciona

1- Insertar ecuación y seleccionar modo {}LaTeX

![](/herramientas/assets/latexword01.png)

2- En el cuadro de la ecuación, escribir \(o pegar\) en sintaxis LaTeX la expresión que deseemos. Por ejemplo: \frac{a+b}{c+d}![](/herramientas/assets/latexword02.png)

3- Para ir alternando habrá que darle a "Convertir". Si convertimos a "Profesional", veremos el resultado:

![](/herramientas/assets/latexword03.png)

4- Mientras que si convertimos a "Lineal", volveremos a ver la expresión LaTeX que hay detrás de ese renderizado, pudiendo modificarla de nuevo.

### Cosas interesantes

Si copiamos una fórmula de estas y pegamos en otra aplicación \(editor de LaTeX o un simple notepad\), lo que aparecerá será la expresión LaTeX. Maravilloso. Aunque sería todavía mejor si Word permitiese entrar en el modo ecuación tecleando $$ o \\[. Todo llegará, supongo. Y otra cosa que tampoco está habilitada en el editor de ecuaciones en modo LaTeX es el empleo de tags como \begin o \end.

### Y limitaciones

A día de hoy \(octubre de 2017\), y con la última versión posible de Word, nos encontramos con situaciones un poco marcianas. Son situaciones que recuerdan a esos vídeos de YouTube en los que cogen una canción en inglés, la traducen con Google Translate a otros idiomas y luego de vuelta al inglés. Y el resultado, bueno, el resultado os lo podéis [imaginar](https://www.youtube.com/watch?v=6mqG5l-9wIE).

## El minimalismo al rescate

El minimalismo es bello. Y en lo que a escritura se refiere, tiene nombre propio: [markdown](https://es.wikipedia.org/wiki/Markdown). De hecho, este libro está hecho con Gitbook, que sigue ese sistema. En lo que a matemáticas se refiere, se puede escribir esto de aquí:

$$e=\lim_{n\to\infty}\left(1+\cfrac{1}{n}\right)^n$$

sin más que escribir esto otro:

Hay un buen puñado de editores de markdown. En el fondo, basta con un editor de texto plano, como el bloc de notas de toda la vida o el magnífico [Notepad++](#). Pero es que no hace falta. Los editores especializados en Markdown te permiten ver directamente el resultado de lo que escribes. Por ejemplo, esta es la barra de Gitbook Editor que veo arriba del todo mientras escribo estas líneas:

![](/herramientas/assets/barra-gitbook.png)

¿Para qué más? Lo simple es bello. Y si quieres cambiar el estilo, también hay plantillas y formas de hacerlo. A continuación, vamos a ver un poquito en profundidad un editor que, aunque se encuentra en versión beta todavía, es increíble. Por simple. Se trata de [Typora](#).

### Typora

![](/herramientas/assets/typoralogo.png)

#### Descarga e instalación

En la página web de [Typora ](https://typora.io/)podemos descargar el programita en cuestión. Si tenemos Windows o Mac se nos bajará un ejecutable, mientras que si tenemos Linux, en la página vienen las [instrucciones ](https://typora.io/#linux)para que se mantenga actualizado.

Para poder disfrutar de todas las capacidades de exportación, hay que instalar pandoc.

#### Aspecto del entorno

Puede parecer simple, porque lo es. Observemos que todas las opciones son accesibles desde los menús \(o con atajos de teclado\) y que tampoco hay que estar tecleando en markdown \(aunque acelera el asunto\).

![](/herramientas/assets/typora01.png)Como podemos ver, tenemos las opciones básicas de cualquier editor.

