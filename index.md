---
layout: home
title: Home
filters:
    - Hi
---
# Hi, I'm Rahul!
<div id="intro">
    <div id="left"> <img src="images/Rahul.jpg" alt="Picture of me"> </div>
    <div id="right">
        I am a Game Designer and Programmer and student based in London, United Kingdom. I have a bachelors degree in Computer Science and am currently working towards a Master's in Digital Games Theory and Design.
        <br><br>
        My main interest lies in the field of programming (especially games) and I have many examples of my work available on this website.
        <br><br>
        If you require any further information or would like to discuss a potential opportunity please get in touch through rahul@rahulsharma.uk.
    </div>
</div>
<div class="social-icons">
    <a href="https://twitter.com/Rahulio2D" target="_blank"><img alt="Twitter" src="/images/social/Twitter.png"></a>
    <a href="https://github.com/RSharma98" target="_blank"><img alt="Github" src="/images/social/Github.png"></a>
</div>
<div class="project-showcase">
    {% for game in site.games %}
        <a href="{{ game.url }}">
            <div class="project">
                <div class="project-image" style="background-image: url({{ game.images[0] }})">
                    {% for filter in game.filters %}
                        <h4 class="filter"> {{filter}} </h4>
                    {% endfor %}
                    <div class="project-overlay"></div>
                </div>
                <h3 class="project-name"> {{ game.title }} </h3>
            </div>
        </a>
    {% endfor %}
</div>