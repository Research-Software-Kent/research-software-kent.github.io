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

Research Software Kent is a 'Community of Practice' and network of researchers at the University of Kent who routinely develop software as a key part of their research, e.g., for the purposes of numerical modelling, data analysis, or as a key output of their work.  The group exists to help promote best practises in software engineering to maximise the value of software for research, and to provide help and support to those engaging in software engineering for research purposes.

This group is managed by [Dominic Orchard](https://www.kent.ac.uk/computing/people/3074/orchard-dominic), School of Computing. Do [e-mail me](mailto:d.a.orchard@kent.ac.uk) if you have any questions, or read [this introduction post](https://research-software-kent.github.io/misc/2023/06/01/hello-world.html) for more details of the background and motivation.

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

* __Wednesday 6th December 2023, 3pm__ - _TBD

* __Wednesday 22nd November 2023, 3pm__ - 'Training session: Using Git and GitHub together, effectively' -
This will be our first "training" focussed session. Dominic will give a bit of an whistle stop tour of some core Git ideas and then using this in concert with GitHub. A cursory knowledge of using Git will be helpful, so looking at some introductory resources first (e.g., [the gittutorial](https://git-scm.com/docs/gittutorial)) will be helpful.
  
* __Wednesday 8th November 2023, 3pm__ - _'Why is research software important?'_ - Kennedy Seminar Room 2 - Please sign up to the mailing list for an invite link. For this initial session I would like to collect some examples of good practice already going on, so if you have something you are proud of and wouldn't mind sharing, then please let me know.
