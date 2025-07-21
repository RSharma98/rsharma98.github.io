---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
---
Hi, I'm Rahul! I'm a Software Engineer based in London, United Kingdom. I specialise in backend development with languages such as Ruby on Rails, TypeScript, Java, Python, and more. On this website you'll find some of the apps and videogames I have developed in my spare time.

# Applications

<div id="project-showcase">
    {% for app in site.apps %}
        <a href="{{ app.url }}">
            <div class="project" style="background-image: url({{ app.images[0] }})">
                <div class="project-overlay">
                    {% for language in app.languages %}
                        <p class="project-language">{{ app.languages[forloop.index0] }}</p>
                    {% endfor %}
                </div>
            </div>
        </a>
    {% endfor %}
</div>

# Games

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