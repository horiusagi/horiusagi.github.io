---
layout: page
title: blog
---

<ul class="post-list">
    {% for post in site.posts %}
      <li>
        <h2><a class="post-title" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2>
        <p class="post-meta">{{ post.date | date: '%B %-d, %Y — %H:%M' }}</p>
        <p>{{ post.description }}</p>
      </li>
    {% endfor %}
</ul>
<ul class="sidebar">
{% assign currentYear = site.time | date: "%Y" %}
{% assign currentMonth = site.time | date: "%B" %}
{% for post in site.posts %}

    {% assign postYear = post.date | date: "%Y" %}
    {% assign postMonth = post.date  | date: "%B" %}

    {% if forloop.first %}
    <li> {{ postYear}}
        <ul>
            <li> {{ postMonth }}
                <ul>
    {% endif %}

    {% if (postYear == currentYear and postMonth == currentMonth) or forloop.first %}
        <li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endif %}

    {% if postYear == currentYear and postMonth != currentMonth %}
        </ul></li>
        <li> {{ postMonth }}
            <ul>
                <li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endif %}

    {% if postYear != currentYear %}
        </ul></li></ul></li>
            <li> {{ postYear}}
                <ul>
                    <li> {{ postMonth }}
                        <ul>
                            <li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endif %}
    {% assign currentYear = postYear %}
    {% assign currentMonth = postMonth %}
{% endfor %}</ul>
