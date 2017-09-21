---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
title: About
---

My name is Wolfgang Salazar, I work as a developer and I love making reliable and maintainable code, but overall making products that people love to use, I mainly use Python + Django for the backend and (JavaScript + Vue) or (TypeScript + Angular) for the frontend.

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
