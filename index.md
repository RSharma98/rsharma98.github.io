---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
---
Hello! My name is Rahul and I'm a software developer based in London, United Kingdom. I am deeply passionate about game development and love the process of making games, with a keen interest in programming and game design! I primarily work with the Unity Engine, but I'm currently working on expanding my knowledge by learning some C++ with SDL and OpenGL. On this website you'll find some of the games I'm most proud of, with each containing a short gameplay video, images, a download link and/or source control, and more information about my contributions! :)

<div id="project-showcase">
    {% for game in site.games %}
        <a href="{{ game.url }}">
            <div class="project" style="background-image: url({{ game.images[0] }})">
                <div class="project-overlay">
                    <p class="project-language">{{ game.game_engine }}</p>
                </div>
            </div>
        </a>
    {% endfor %}
</div>