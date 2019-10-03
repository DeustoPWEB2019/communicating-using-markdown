## Paso 7: Combina tu imagen y enlace

This looks great, @{{ user.username }}! You've created a link to show off your portfolio, and now you can share it with the world.

### :keyboard: Actividad: Merge the Pull Request

{% if preferences.gitTool == 'cli' %}
1. Check out to the `master` branch:
    ```shell
    git checkout master
    ```
2. Merge your branch:
    ```shell
    git merge add-images-links
    ```
3. Push the merged history to GitHub:
    ```shell
    git push
    ```
4. Delete your the branch locally:
    ```shell
    git branch -d add-images-links
    ```
{% else %}
1. Haz clic en **Merge pull request** below.
{% endif %}

<hr>
<h3 align="center">Mira mi respuesta más abajo.</h3>
