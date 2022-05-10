---
layout: default
title: "List"

---

Here is all my content. Enjoy.
- 2022
    - CTF's
        - [test writeup]({{ site.url }}/writeup/2022/04/27/first-writeup/)
            - EZCTF2022
                {% for post in site.writeups %}
                <li>
                    <a href="{{ post.url }}">{{ post.title }}</a></li>
                {% endfor %}
    - Other stuff
        - [test link to google](https://google.com/)
