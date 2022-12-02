---
layout: default
---

<style>
  #signUp {
    border-style: outline;
    font-family: Overpass;
    border-width: 1px;
  }
</style>

Research Software Kent is a network of researchers at the University of Kent who routinely develop software as a key part of their research, e.g., for the purposes of numerical modelling, data analysis, or as a key output of their work.  The group exists to help promote best practises in software engineering to maximise the value of software for research, and to provide help and support to those engaging in software engineering for research purposes.

This group is managed by [Dr Dominic Orchard](mailto:d.a.orchard@kent.ac.uk)

<a href="https://lists.kent.ac.uk/sympa/info/research-software-kent"><div id='signUp'>Sign-up to the mailing list</div></a>

## Upcoming events

__Coming in 2023: seminar series on key software engineering practises__

## News

<ul>
  {% for post in site.posts %}
    <li>
	    {{ post.date | date: "%-d %B %Y" }} - <i><a href="{{ post.url }}">{{ post.title }}</a></i>
    </li>
  {% endfor %}
</ul>