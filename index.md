---
layout: default
---

<style>
  #signUp {
    display: inline-block;
    border-style: solid;
    font-family: Overpass;
    font-size: 15pt;
    border-width: 1px;
    cursor: pointer;
    border-radius: 5px;
    box-shadow: 1px 2px #ccc;
    margin: 10px;
    padding: 9px;
    padding-bottom: -3px;
    color: black;
    text-decoration: none;
    background: #FCEDA3;

  }
</style>

Research Software Kent is a network of researchers at the University of Kent who routinely develop software as a key part of their research, e.g., for the purposes of numerical modelling, data analysis, or as a key output of their work.  The group exists to help promote best practises in software engineering to maximise the value of software for research, and to provide help and support to those engaging in software engineering for research purposes.

This group is managed by [Dominic Orchard](https://www.kent.ac.uk/computing/people/3074/orchard-dominic), School of Computing. Do [e-mail me](mailto:d.a.orchard@kent.ac.uk) if you have any questions, or read [this introduction post](https://research-software-kent.github.io/misc/2022/12/02/hello-world.html) for more details of the background and motivation.

<span id='signUp'>
[Sign-up to the mailing list](https://lists.kent.ac.uk/sympa/info/research-software-kent)
</span>


## Posts

<ul>
  {% for post in site.posts %}
    <li>
	    {{ post.date | date: "%-d %B %Y" }} - <i><a href="{{ post.url }}">{{ post.title }}</a></i>
    </li>
  {% endfor %}
</ul>

## Events

Coming in 2023: seminar series on key software engineering practises
