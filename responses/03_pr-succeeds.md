## Paso 4: Combina tus títulos

Veo que has añadido por lo menos un título, @{{ user.username }}. Puedes seguir trabajando si quieres, o si no simplemente combina <sup>[:book:](https://help.github.com/articles/github-glossary/#merge)</sup> este pull request y continúa con el resto del curso.

### :keyboard: Actividad: Combina el pull request

{% if preferences.gitTool == 'cli' %}
1. Check out to the `master` branch:
    ```shell
    git checkout master
    ```
2. Merge your branch:
    ```shell
    git merge add-headers
    ```
3. Push the merged history to GitHub:
    ```shell
    git push
    ```
4. Delete your the branch locally:
    ```shell
    git branch -d add-headers
    ```
{% else %}
1. Haz clic en **Merge pull request** más abajo.
{% endif %}

<hr>
<h3 align="center">Mira mi respuesta más abajo.</h3>
