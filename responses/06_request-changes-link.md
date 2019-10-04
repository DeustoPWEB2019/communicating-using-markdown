Algo no está bien con ese enlace. Asegúrate de que:

- Has eliminado el texto de relleno
- El formato de tu enlace es correcto (`[texto](url)`)

### :keyboard: Actividad: Add a link

{% if preferences.gitTool == 'cli' %}
1. In your shell, verify that you are currently checked out to the branch `add-images-links`:
      ```shell
      git status
      ```
1. If you are _not_, then checkout to that branch:
      ```shell
      git checkout add-images-links
      ```
1. In your text editor of choice, open the file called `03-links.md`, in the `_includes` directory. Add a link using the syntax `[text](https://example.com)`.
1. Save your file.
1. Stage your new file:
      ```shell
      git add _includes/03-links.md
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
1. Haz scroll para buscar el archivo `_includes/03-link.md`.
1. Haz clic en el icono del lápiz :pencil:.
1. Añade un enlace usando la sintaxis `[texto](https://ejemplo.com)`.
1. Haz scroll hasta la parte de abajo y haz commit de tus cambios a tu branch.
{% endif %}



<!-- If you would like assistance troubleshooting, create a post on the [GitHub Community]({{ communityBoard }}) board. You might also want to search for your issue to see if other people have resolved it in the past. -->

<hr>
<h3 align="center">Mira mi respuesta más abajo.</h3>
