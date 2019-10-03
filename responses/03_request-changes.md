Has hecho un cambio a este archivo, pero no veo un título todavía. Añade otro commit con algún título. Puedes continuar haciendo commits en un branch incluso después de haber creado el pull request.

### :keyboard: Actividad: Añade un título

{% if preferences.gitTool == 'cli' %}
1. Open your preferred command line interface, which we'll call your shell from now on.
1. Clone this repository:
      ```shell
      git clone {{ thePayload.repository.clone_url }}
      ```
1. Navigate to the repository in your shell:
      ```shell
      cd {{ thePayload.repository.name }}
      ```
1. Checkout to the branch in this pull request:
      ```shell
      git checkout add-headers
      ```
1. In your text editor of choice, open the file called `01-name.md`, in the `_includes` directory. On the first line, replace the text with your name, and add a `#` before the content to make it an H1 Header.
1. Save your file.
1. Stage your file:
      ```shell
      git add _includes/01-name.md
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
1. Haz clic en la pestaña "Files changed".
1. Haz scroll para buscar el archivo `_includes/01-name.md`.
1. Haz clic en el icono del lápiz :pencil:.
1. Añade un título incluyendo un `#` seguido por un espacio.
1. Haz scroll hasta la parte de abajo y haz commit de tus cambios a tu branch.
{% endif %}


<!-- If you would like assistance troubleshooting, create a post on the [GitHub Community]({{ communityBoard }}) board. You might also want to search for your issue to see if other people have resolved it in the past. -->

<hr>
<h3 align="center">Mira mi respuesta más abajo.</h3>
