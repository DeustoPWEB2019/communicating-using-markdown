## Paso 10: Combina listas y énfasis

¡Bonita lista, @{{ user.username }}! Puedes combinar este pull request cuando hayas terminadp.

### :keyboard: Actividad: Combina el pull request

{% if preferences.gitTool == 'cli' %}
1. Check out to the `master` branch:
    ```shell
    git checkout master
    ```
2. Merge your branch:
    ```shell
    git merge add-lists-emphasis
    ```
3. Push the merged history to GitHub:
    ```shell
    git push
    ```
4. Delete your the branch locally:
    ```shell
    git branch -d add-lists-emphasis
    ```
{% else %}
1. Haz clic en **Merge pull request** más abajo.
{% endif %}

<hr>
<h3 align="center">Mira mi respuesta más abajo.</h3>

<!-- delete from here after successful config of course -->
<hr>
<h3 align="center">:warning: Este último paso no carga automáticamente :warning: </h3>

Una vez hayas combinado (merge) tu pull request, bórralo (**Delete branch**), y habrás terminado con el curso, aunque en [el seguimiento de progreso](https://lab.github.com/DeustoPWEB2019/comunicar-usando-markdown) veas que te falta el último paso. Hay algún problema con la configuración del tutorial que estoy intentando resolver.

Mientras tanto, aquí puedes ver tu trabajo: {{ url }}

Esta es la URL que tienes que entregar a través de la actividad correspondiente en la plataforma ALUD.

Le he dado un nuevo look a tu portafolio añadiendo un tema de Jekyll. Para seleccionar otro, consulta “[Adding a Jekyll theme to your GitHub Pages site with the Jekyll Theme Chooser](https://help.github.com/articles/adding-a-jekyll-theme-to-your-github-pages-site-with-the-jekyll-theme-chooser/) en la *Ayuda de GitHub*.

<hr>
<h3 align="center"><a href="{{ issueUrl }}">Ve al último paso.</a></h3>




