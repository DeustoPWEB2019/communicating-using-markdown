Algo no está bien con esa imagen. Asegúrate de que:

- Has eliminado el texto de relleno
- El formato de tu imagen es correcto (`![alt-text](image-url)`)
- La imagen tiene un texto alternativo

### :keyboard: Actividad: Añade una imagen

{% if preferences.gitTool == 'cli' %}
1. In your shell, checkout to the branch in this pull request:
      ```shell
      git checkout add-images-links
      ```
1. In your text editor of choice, open the file called `02-image.md`, in the `_includes` directory. In the file, replace the content with the correct Markdown for your image of choice. Don't forget to include alt-text!
1. Save your file.
1. Stage your new file:
      ```shell
      git add _includes/02-image.md
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
1. Haz scroll para buscar el archivo `_includes/02-image.md`.
1. Haz clic en el icono del lápiz :pencil:.
1. Añade una imagen usando la sintaxis `![Imagen del Yaktocat](https://octodex.github.com/images/yaktocat.png)`.
1. Haz scroll hasta la parte de abajo y haz commit de tus cambios a tu branch.
{% endif %}



<!-- If you would like assistance troubleshooting, create a post on the [GitHub Community]({{ communityBoard }}) board. You might also want to search for your issue to see if other people have resolved it in the past. -->

<hr>
<h3 align="center">Mira mi respuesta más abajo.</h3>
