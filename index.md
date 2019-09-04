---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
---
Hello! My name is Rahul and I like to make games. On this website you'll find some of the games I've worked on in the past that I am most proud of, as well as some of my current projects. Click on an image for more details about a game and feel free to get in touch if you'd like more information or to talk about a potential opportunity. 

<div id="project-showcase">
    {% for game in site.games %}
        <a href="{{ game.url }}">
            <div class="project" style="background-image: url({{ game.images[0] }})">
                <div class="project-overlay"></div>
            </div>
        </a>
    {% endfor %}
</div>