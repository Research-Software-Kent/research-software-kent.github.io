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


## Blog posts

<ul>
  {% for post in site.posts %}
    <li>
	    {{ post.date | date: "%-d %B %Y" }} - <i><a href="{{ post.url }}">{{ post.title }}</a></i>
    </li>
  {% endfor %}
</ul>

## Events and News

* __Friday 13th June 2025, 2pm__ - 'Workshop on Testing' (Kennedy SR2) - In this short workshop we'll look at concepts around software correctness and testing, with practical examples using Python and the pytest framework for unit testing.

* __Thursday 29th May 2025, 3pm__ - 'Software Citation - How to be citable and how to cite' (Dominic Orchard) - In this talk, I'll look at how to make research software citable, how to cite others, and how to encourage software citation within your own discipline.

* __Wednesday 3rd April at 3pm__ (KenSR6) Last meeting of term, informal discussion and cakes!

* __Wednesday 6th March 2024__ - Second __code clinic__ of the term. Come by if you want to talk through any problems your are having with your code and get some support!

* __Wednesday 21st February 2024__ - 'Pair Programming' (Dominic Orchard) - Pair programming is a technique for working with another person which can aid problem solving and provide live code review. This can be particularly helpful for on-boarding new team members and students or to work through difficult problems together. There are a few 'paradigms' that I will talk through (and I can point to some further resources).

* __Wednesday 6th February 2024__ - Our first __Code clinic__ session. Drop by to discuss any problems and get help!

* __Wednesday 24th January 2024__ - 'Continuous integration and GitHub actions' (Stefan Marr) 

* __Wednesday 6th December 2023, 3pm__ - 'Errors and where to find them' (Gary Thompson) An introduction to bugs and errors in the field:  how to find them, how to understand them, how to fix them and how to avoid them. The talk will be centred round python and will cover stack traces, Exceptions, throwing Exceptions and a brief introduction to why testing is a good idea…

* __Wednesday 22nd November 2023, 3pm__ - 'Training session: Using Git and GitHub together, effectively' -
This will be our first "training" focussed session. Dominic will give a bit of an whistle stop tour of some core Git ideas and then using this in concert with GitHub. A cursory knowledge of using Git will be helpful, so looking at some introductory resources first (e.g., [the gittutorial](https://git-scm.com/docs/gittutorial)) will be helpful.
  
* __Wednesday 8th November 2023, 3pm__ - _'Why is research software important?'_ - Kennedy Seminar Room 2 - Please sign up to the mailing list for an invite link. For this initial session I would like to collect some examples of good practice already going on, so if you have something you are proud of and wouldn't mind sharing, then please let me know.
