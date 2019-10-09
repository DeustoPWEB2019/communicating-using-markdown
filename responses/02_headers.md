## Paso 3: Añade títulos

Como has visto en tu sitio web, tu portafolio no tiene demasiado contenido todavía. Vamos a aprender cómo editar el archivo en este pull request para incorporar algunos títulos con Markdown.

Puedes ver un ejemplo de título en la parte superior de esta página. Exactamente igual que en HTML, un título es una porción de texto más grande al principio de cada sección. Hay seis tamaños.

#### Ejemplo

```
# Esto es un título <h1>, que es el más grande
## Esto es un título <h2> 
###### Esto es un título <h6>, que es el más pequeño
```

#### Cómo se ve

# Esto es un título &lt;h1&gt;, que es el más grande
## Esto es un título &lt;h2&gt; 
###### Esto es un título &lt;h6&gt;, que es el más pequeño

En issues, pull requests y comentarios, puedes usar la barra de formateo de texto.

La barra no está disponible en todas partes. Cuando editas un archivo, tienes que teclear los símbolos `#` manualmente.

### :keyboard: Actividad: Edita tu archivo con títulos

{% if preferences.gitTool == 'cli' %}
1. Abre tu interfaz de línea de comandos, al que a partir de ahora llamaremos tu terminal.
1. Clona este repositorio:
      ```shell
      git clone {{ thePayload.repository.clone_url }}
      ```
1. Navega hasta el repositorio en tu terminal:
      ```shell
      cd {{ thePayload.repository.name }}
      ```
1. Cámbiate al branch de este pull request:
      ```shell
      git checkout add-headers
      ```
1. En tu editor de textos, abre el archivo llamado `01-name.md`, en el directorio `_includes`. En la primera línea, reemplaza el texto con tu nombre, y añade un `#` antes del contenido para convertirlo en un título H1.
1. Guarda tu archivo. Cada vez que hagas cambios, es una buena idea teclear `git status`. Deberías teclear esto después de añadir los archivos, y también después de hacer commit. ¡Siempre es una buena idea!
1. Añade tus archivos:
      ```shell
      git add _includes/01-name.md
      ```
1. Haz commit de los cambios y añade un mensaje de commit:
      ```shell
      git commit -m "<TU MENSAJE>"
      ```
1. Haz push de tu nuevo commit a GitHub:
      ```shell
      git push
      ```
{% else %}
1. En este pull request, haz clic en la pestaña **Files changed**.
1. En la esquina superior derecha de la vista del archivo, haz clic en el icono del **pequeño lápiz** ✏️ del archivo llamado `_includes/01-name.md`.
1. En la pestaña **Edit file**, añade un `#` antes del contenido para convertirlo en un título h1. Puedes añadir más títulos, utilizando entre uno y seis caracteres `#`.
1. Encima del nuevo contenido, haz clic en **Preview changes**.
1. En la parte inferior de la página, escribe un mensaje de commit corto y significativo que describa el cambio que has realizado en el archivo.
1. Haz clic en **Commit changes**.
{% endif %}

<hr>
<h3 align="center">Busca mi respuesta más abajo.</h3>
