## Buen trabajo

Enhorabuena @{{ user.username }}, ¡has completado este curso!

![enhorabuena](https://octodex.github.com/images/welcometocat.png)

## Lo que ha ido bien

Durante este curso has conseguido:

- Añadir una lista de comprobación a un comentario en un issue
- Activar GitHub Pages en tu repositorio
- Hacer commit de los cambios a tu sitio web:
  + Añadir títulos al archivo `01-name.md`
  + Incluir una imagen en el archivo `02-image.md`
  + Crear enlaces a otros sitios web en el archivo `03-links.md`
  + Añadir tus logros al archivo `04-lists.md`
  + Utilizar énfasis como **negritas** y _cursivas_ en el archivo `05-emphasis.md`

## ¿Y ahora qué?

Ahora que ya dominas los elementos básicos de Markdown, @{{ user.username }}, aquí tienes información sobre algunas de las funciones molonas que no hemos visto.

### Más enlaces en Markdown

<details>
<summary>@Menciones de usuarios y grupos</summary>

  ### @Menciones de usuarios y grupos

  Escribir el símbolo `@` seguido de un nombre de usuario de GitHub enviará una notificación a ese usuario sobre el comentario publicado. Esto se llama una "@mención", porque estás mencionando a una persona. También puedes `@mencionar` grupos dentro de una organización. Para más información, consulta “[Receiving notifications about activity on GitHub](https://help.github.com/categories/receiving-notifications-about-activity-on-github/) en la *Ayuda de GitHub*.

  ```
  @githubteacher
  ```

  @githubteacher

  <hr>
</details>

<details>
  <summary>Enlaces cruzados</summary>

  ### Enlaces cruzados

  Para obtener una lista de issues y pull requests sugeridos en un repositorio, escribe `#`. Escribe el número o el título del issue o pull request para filtrar la lista, y después presiona el Tabulador o Enter para completar el resultado resaltado.

  Además, las referencias a issues y pull requests se convierten automáticamente en enlaces acortados al issue o pull request. Por ejemplo,


  | Tipo de referencia  | Referencia en bruto | Enlace corto |
  | ------------------- | ------------------- | ------------ |
  | URL de issue o pull request | `https://github.com/desktop/desktop/pull/3602` | [#3602](https://github.com/desktop/desktop/pull/3602) |
  | `#` con número de issue o pull request | #3602 | [#3602](https://github.com/desktop/desktop/pull/3602) |
  | `GH-` con número de issue o pull request | GH-3602 | [GH-3602](https://github.com/desktop/desktop/pull/3602) |
  | `Usuario/Repositorio#` con número de issue o pull request | desktop/desktop#3602 | [desktop/desktop#3602](https://github.com/desktop/desktop/pull/3602) |

  Para más información, consulta “[Autolinked references and URLs](https://help.github.com/articles/autolinked-references-and-urls/)” en la *Ayuda de GitHub*.

  <hr>
</details>

<details>
  <summary>Enlazando a commits específicos</summary>

  ### Enlazando a commits específicos

  Las referencias a los IDs de los commits (a las que normalmente se llama SHA o _hash_) se convierte automáticamente en enlaces cortos al commit en GitHub. Por ejemplo,

  | Tipo de referencia  | Referencia en bruto | Enlace corto |
  | ------------------- | ------------------- | ------------ |
  | URL de un commit | https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87 | [8304e9c](https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87) |
  | SHA | 8304e9c271a5e5ab4fda797304cd7bcca7158c87 | [8304e9c](https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87) |
  | Usuario@SHA | desktop@8304e9c271a5e5ab4fda797304cd7bcca7158c87 | [desktop@8304e9c](https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87) |
  | Usuario/Repositorio@SHA | Usuario/Repositorio@SHA: desktop/desktop@8304e9c271a5e5ab4fda797304cd7bcca7158c87 | [desktop/desktop@8304e9c](https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87)|


  <hr>
</details>

### Formato Markdown

<details>
  <summary>Citas</summary>

  ### Citas

  Puedes añadir un texto citado usando `>`.

  ```
  En palabras de Abraham Lincoln:

  > Pardon my French
  ```

  En palabras de Abraham Lincoln:

  > Pardon my French

  <hr>
</details>

<details>
  <summary>Tablas</summary>

  ### Tablas

  Puedes crear tablas reuniendo una serie de palabras divididas mediante `-` (para la primera fila), y separando cada columna con una barra vertical `|`:

    ```
    Primer encabezado | Segundo encabezado
    ----------------- | ------------------
    Contenido de la celda 1 | Contenido de la celda 2
    Contenido de la 1ra columna | Contenido de la 2nda columna
    ```

  Primer encabezado | Segundo encabezado
  ----------------- | ------------------
  Contenido de la celda 1 | Contenido de la celda 2
  Contenido de la 1ra columna | Contenido de la 2nda columna

  Para más información sobre el formateo de tablas, consulta "Organizing information with tables" en la _Ayuda de GitHub_.

<hr>
</details>

<details>
  <summary>Código en línea</summary>

  ### Código en línea

  Algunas palabras y frases necesitan formatearse en fuentes monoespaciadas, especialmente cuando escribimos acerca de código. Como has visto a lo largo de este curso, las palabras pueden distinguirse en markdown como `código en línea`.

  El código en línea se señala con un único caráter ``` a cada lado del texto, y puede usarse dentro de párrafos, títulos u otros elementos de Markdown.

  ```
  `el código en línea utiliza solo una tilde invertida`
  ```

  `el código en línea utiliza solo una tilde invertida`

  <hr>
</details>

<details>
  <summary>Bloques de código</summary>

  ### Bloques de código

  Para separar un bloque de texto más largo, utiliza tres caracteres ``` en lugar de uno, y coloca el texto aparte en su propio párrafo.

  Lo que escribimos:
  
    ```
    Cualquier cosa que escribamos en este **párrafo** no se _formateará_ incluso aunque normalmente sería reconocido en este contexto. :taco:
    ```
    
  Lo que vemos:
  
  ```
  Cualquier cosa que escribamos en este **párrafo** no se _formateará_ incluso aunque normalmente sería reconocido en este contexto. :taco:
  ```
<hr>
</details>

<details>
  <summary>Resaltado de sintaxis</summary>

  ### Resaltado de sintaxis

  Además de indicar el código en bloques, algunos bloques de código deberían colorearse diferente según el lenguaje de programación, como Javacsript o textos para la línea de comandos.

  Lo que escribimos:

      ```sh
      github-learning-lab ~/Proyectos/repositorio-de-recetas
      $ git init
      Initialized empty Git repository in /Users/github-learning-lab/Proyectos/repositorio-de-recetas/.git/
      ```

  Lo que vemos:

  ```sh
  github-learning-lab ~/Proyectos/repositorio-de-recetas
  $ git init
  Initialized empty Git repository in /Users/github-learning-lab/Proyectos/repositorio-de-recetas/.git/
  ```
  <hr>
</details>

<details>
  <summary>Desplegables de resumen</summary>

  ### Desplegables de resumen

  La mayoría del texto en este issue está formateado en bloques expandibles. Así es como se hacen con Markdown:

  ```
  <details>
    <summary>Título</summary>

    Aquí el contenido

  </details>
  ```

  <hr>
</details>

¿Quieres aprender más? No dejes de [consultar otros cursos]({{ host }}/courses).

<hr>
<h3 align="center">No responderé a este issue, simplemente ciérralo cuando hayas acabado.</h3>
