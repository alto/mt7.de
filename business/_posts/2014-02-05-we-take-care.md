---
title: We take care
layout: post
---

We write idiomatic code
-----------------------
When we write Ruby code, we do it the Ruby-way. Same goes with Javascript
or Perl or Go. We read code a lot and know how to use language-specific benefits
and avoid the drawbacks. Our code is not different from any other code.

We follow Rails conventions
---------------------------
Ruby on Rails comes with its own set of assumptions and conventions (which
is why it is called *opinionated*). We are not only aware of these, but we
follow them in our everyday work. Recommended reading
[The Rails 3 Way, Obie Fernandez](http://www.amazon.de/The-Rails-Addison-Wesley-Professional-Ruby/dp/0321601661/ref=sr_1_1?ie=UTF8&qid=1391266175&sr=8-1&keywords=the+rails+way).

We follow common styleguides
----------------------------
There are a couple of good styleguides around on GitHub and others. We
know them, we use them and we highly recommend them. Even to the point to
force ourselves by setting up these guides in our editors. For example
[Styleguide for Ruby](https://github.com/styleguide/ruby).

We use best practices
---------------------
We visit conferences and read books to know how the good guys write code.
We listen to people telling us about not the better ways, but the best
ways to achieve our goals. Every day.

We read all the commits
-----------------------
It's our codebase. We love it and we don't want anyone destroying it.
This is why we read any commit coming in. I mean literally, **every commit**.

We do pair programming
----------------------
If the issue to tackle is complicated, or we just want to talk to someone
while writing code, we simple ask anyone to join us in doing the work. Call
it 4-eye-principle, Wackeldackel or Rubberduck, it's on our toolbelt, ready
to be used when needed.

We have a refactoring board, from which we pick regularly
--------------------------------------------------------
Technical debt is everywhere. Our means to tackle this pile of guilt is
our refactoring board, which grows and shrinks, visible for each and everyone.
No process needed. There is always time to change existing and running
code. No broken windows allowed.

We use pull-requests to review code
-----------------------------------
We have a number of ways to push our code to the repository. Sending pull
requests is one of them. We ask others to take a look (or even ask ourselves
one day later), before we let it go into the wild. Simple and effective, if
needed.

We talk about our code
----------------------
There's a plethora of chances to talk about our codebase. Stand-ups,
coffee-times, ad-hoc discussions, lunchtime, and so on. Non-coders
disrespectfully shake their heads on us talking so much about our work.
We always talk about major code changes long before we implement them.

We know what everybody is working on
------------------------------------
In order to avoid conflicts we tell others what we are working on. No
surprises, and no major merge conflicts. And even if we are working
in the same code area, we are able to handle any conflict showing up.

We know our co-workers
----------------------
By working together every day, we know each others leanings, our strengths
and weaknesses. So we know when we have to support each other on tackling
complex problems and writing code. Even when someone tries something new
and experiments around, we trust what they are doing, because we know
they are doing right.

We seek code smells
-------------------
Whenever we write code, we take a look around, identifying and marking
code smells. We utilize TODO, FIXME and QUESTION a lot, and find the time
to decover these spots and remove them.

We modularize our code
----------------------
Even with all conventions, the codebase grows to a point where it is no
longer maintainable. We sport modules, mixins, concerns, gems, plugins,
packages. We know when to use inheritance and STI or composition. We do
this to remain focused on our given business case.

We test
-------
A lot. All kinds of tests. Sometimes first and sometimes after we write
the actual code. No bug without adding a test. No refactoring without a test.
To write a test it to write code. We utilize test coverage, but 100% is
not our goal. That'd be insane. There's a kind of test for each usecase.
We use the one most appropriate.

We struggle for fast tests
--------------------------
While writing tests is important, having a fast test suite is equally important.
Slow tests won't be run, it's simple as that. That's why we observe the
trend on Jenkins (or Travis CI).

We check the performance
------------------------
Every code change might have an impact. This is why we do *log-jammin'*.
We do it regularly and a lot. Logjam is a great tool for that.

We update
---------
We not only keep our tools up-to-date, we keep the tiny bits of libraries
and packages up-to-date as well. We not only update gems mentioned in
the *check-gem-versions* build, we check for rarely used or development-only
gems as well.

We give back
------------
Monkey-patching is easy. And dangerous. This is why we have a natural tendency
to return our code changes back to the original developers, in order to
improve their code and let ours grow smoothly and independently. We pullup
a lot.

We organize our codebase
------------------------
Rails provides good means to organize the code. But that's not sufficient.
There are authorizers, utilities, external APIs, decorators and so on.
And there's a neat little place for all of them.
