---
title: Home
layout: home
---

I am in the process of migrating and consolidating my content on this site.

### Some Selected Projects

* [Physics Math](/physics-math/) Worng toward some educational physics tools.
* [Altoid MIDI Box](https://github.com/BobKerns/Altoid-Box-MIDI/) DIY open-source hardware MIDI controller with display in an Altoids tin.
* [Bass Flute Patch](https://github.com/BobKerns/BassFlute/) Bass Flute patch for Native Instruments' Kontakt
* [GenUtils](https://github.com/BobKerns/genutils/) Generator Utilities bring array-like operations to sync and async generators.

### My Old Blog

I'm in the process of migrating away from Typepad. My [old blog is here](https://bobkerns.typepad.com/).

### Public GitHub Repositories

<!-- markdownlint-disable MD033 -->
<dl>
{% for repository in site.github.public_repositories %}
    {% if repository.fork == false and site.data.hidden_repos[repository.name] != true %}
        <dt><b>
            <a href="{{ repository.html_url }}">{{ repository.name }}</a>
        </b></dt>
        <dd>{{repository.description | default: "[No description]" }}<br>
            <i>Last updated: {{ repository.updated_at }}</i><br>
            Topics: <i>{{ repository.topics | join: ", " }}</i>
        </dd>
    {% endif %}
{% endfor %}
</dl>
<!-- markdownlint-enable MD033 -->
