---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
title: About
---

My name is Wolfgang Salazar, I work as a developer. I live in Maracaibo, Venezuela. I love making reliable and maintainable code, but overall making products that people love to use.

Here are some of my most recent projects:

 * **Neo-Trello** *(Status : "Work In Progress")*: A Trello clone made with Python+Django in the backend, and Vue.js in the frontend. I made this project because I really like Trello and making a clone of it would be a really good way of practice my frontend skills, you can take a look to the source code [Backend](https://gitlab.com/wolfgangsalazarmora/neo-trello-backend), [Frontend](https://gitlab.com/wolfgangsalazarmora/neo-trello-frontend), you can also signup and start using it right away [Here](https://neo-trello.wsalazar.com.ve).

 * **Todolisto** *(Status : "Complete")*: A todoapp made with Python+Flask. I made this project to test the Google App Engine platform, It serves its purpose as a toy project to get some experience in google app engine platform but nothing more than that so it isn't very developed, source code [Here](https://github.com/wolfgang000/todolisto).

 * **Wolfmusic** *(Status : "Abandoned")*: A Spotify clone made with Python+Django. In this project I had the ambitious goal of making a music streaming app but I quickly realize the immense scope of this goal and subsequently shut down the project, source code [Here](https://github.com/wolfgang000/wolfmusic).

#### Contact

<ul class="social-media-list">
    {% if site.email %}
        <li>{% include icon-email.html email=site.email %}</li>
    {% endif %}

    {% if site.linkedin_username %}
        <li>{% include icon-linkedin.html username=site.linkedin_username %}</li>
    {% endif %}

    {% if site.github_username %}
        <li>{% include icon-github.html username=site.github_username %} </li>
    {% endif %}

    {% if site.gitlab_username %}
        <li>{% include icon-gitlab.html username=site.gitlab_username %} </li>
    {% endif %}
</ul>
