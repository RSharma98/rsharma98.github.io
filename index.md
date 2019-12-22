---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
---
Hello! My name is Rahul and I'm a games developer/student based in London, United Kingdom. I am deeply passionate about game development and love the process of making games, especially programming them! I've worked on many games in the past using various engines and languages, and on this website you'll find some of the games I am most proud of. Please do get in touch via the email address in the footer if you'd like more information or to discuss a potential opportunity.

<div id="project-showcase">
    {% for game in site.games %}
        <a href="{{ game.url }}">
            <div class="project" style="background-image: url({{ game.images[0] }})">
                <div class="project-overlay"></div>
            </div>
        </a>
    {% endfor %}
</div>