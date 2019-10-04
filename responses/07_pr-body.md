## Paso 8: Añade una lista

En este pull request aprenderás sobre listas y emoticonos. También añadirás algunos detalles a tu currículum.

:point_down: _¡Esto son áreas expandibles! Haz clic para abrirlas y ver más información._

<details>
  <summary>Emoticonos</summary>

  ### Emoticonos

  Los emoticonos son divertidos :sparkles:, y pueden ser un poco tontos :stuck_out_tongue_winking_eye:, pero también pueden ser una herramienta de comunicación importante cuando se trabaja con equipos remotos ✅. El tono no se transmite tan claramente por escrito como cuando se habla cara a cara, y los emoticonos pueden ser de ayuda al aportar el contexto y las emociones. :heart:

  El uso más apropiado de los emoticonos es como añadidos extra, no como sustitutos del texto. Con las imágenes, el texto descriptivo las hace más comprensibles para lectores en pantalla, pero los lectores en pantalla no garantizan la transmisión de la intención tras los emoticonos. Asegúrate de que el sentido de lo que quieres decir está claro en el texto, de forma que los emoticonos ayuden a entenderlo mejor en lugar de generar más confusión.

  Aquí tienes algunos ejemplos de emoticonos populares en markdown.

  | Qué ves    | Qué escribes |
  | ---------- | ------------ |
  | :heart:    | `:heart:`    |
  | :+1:       | `:+1:`       |
  | :smile:    | `:smile:`    |
  | :sparkles: | `:sparkles:` |
  | :tada:     | `:tada:`     |

  Para más información sobre los emoticonos disponibles, [consulta esta práctica chuleta](https://gist.github.com/rxaviers/7360908). En la maýoría de los campos de texto en GitHub puedes teclear `:` y empezar a escribir el nombre de un emoticono. Una búsqueda aproximada te mostrará los cinco resultados más parecidos y te permitirá seleccionar uno.

  ![imagen de una búsqueda aproximada de emoticonos en GitHub](https://user-images.githubusercontent.com/9906718/34602228-47cab148-f1ff-11e7-91f1-56d0fed702f0.png)
  <hr>
</details>


<details>
  <summary>Listas ordenadas</summary>

  ### Listas ordenadas

  Las listas ordenadas tienen números. Puedes anidar listas ordenadas dentro de un elemento de lista con sangrías (añadiendo dos espacios al principio de la línea). Puedes leer más acerca de [formato y sintaxis](https://help.github.com/articles/basic-writing-and-formatting-syntax/) en la _Ayuda de GitHub_.

  ```
  1. Item 1
  2. Item 2
  3. Item 3
     1. Item 3a
     2. Item 3b
  ```

  1. Item 1
  2. Item 2
  3. Item 3
     1. Item 3a
     2. Item 3b

 <hr>
</details>

<details>
 <summary>Listas sin ordenar</summary>

  ### Listas sin ordenar

  Para crear una lista sin ordenar, utiliza los caracteres `-` o `*`. Como con las listas ordenadas, puedes anidar una lista dentro  de otra añadiendo dos espacios al principio de la línea.

  ```
  * Item 1
  * Item 2
    * Item 2a
    * Item 2b
  ```

  * Item 1
  * Item 2
    * Item 2a
    * Item 2b

  <hr>
</details>

### Añade una lista

Deja que la gente te conozca añadiendo una lista que contenga algunas de tus cosas favoritas. ¿No se te ocurre qué poner? Puedes empezar con una lista de tus libros o restaurantes favoritos.


### :keyboard: Actividad: Crea una lista

{% if preferences.gitTool == 'cli' %}
1. In your shell, checkout to the branch in this pull request:
      ```shell
      git checkout add-lists-emphasis
      ```
1. In your text editor of choice, open the file called `04-lists.md`, in the `_includes` directory. Create a markdown list in the file. It can be ordered or unordered.
1. Save your file.
1. Stage your new file:
      ```shell
      git add _includes/04-lists.md
      ```
1. Commit the change and add a commit message:
      ```shell
      git commit -m "<YOUR MESSAGE>"
      ```
1. Push your new commit to GitHub:
      ```shell
      git push
      ```
{% else %}
1. Edita `_includes/04-lists.md` en este pull request.
1. Crea una lista markdown en el archivo. Puede ser ordenada o sin ordenar.
1. Haz commit de tus cambios.
{% endif %}

<hr>
<h3 align="center">Mira mi respuesta más abajo.</h3>
