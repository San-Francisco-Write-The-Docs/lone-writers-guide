<-- https://docs.google.com/document/d/1UUQEpZB9kcQ4zJFQp_Ez33aMvgoCx_nwh5ZBvvFu0ug/edit -->

********************
Style Guides
********************

This page is about creating a style guide. It covers things to think about when creating a style guide and sources for style guides. It is not, however, a style guide. It is not prescriptive. (It also does not discuss tools.)

There is one basic premise: A STYLE GUIDE IS A GOOD THING TO HAVE.


Before you begin:
-----------------

Before you start writing that style guide, keep these ideas in mind:

* Get buy-in from management, other writers, engineers, PMs - anyone who will have to use the style guide - that it's time to make and start using one.
* You might not have to create your own style guide from scratch. Check around at work:

  * Your company, if it's big, might have other technical documentation teams that already have one. You might even end up being the "hero" that finds a few of them and starts a global style guide project. (That happened to me once.)
  * Your company might have a corporate communications guide, a marketing style guide, or other internal guides that you can build upon.
  * Someone else at your company might have started a style guide that languished but could be a place to start.

* Determine who your contributors will be. Good help and input can and should come from more than just official technical writers. Support Engineers, Product Engineering, Marketing and Sales are all places to look for collaborators. You will also likely need sign-off from your Legal department for some stuff.
* Decide where your style guide will live, how people can contribute to it, and stuff like that. In my experience putting it somewhere like a wiki is a good compromise between having it be easily viewed by anyone who wants to see it and worked on by anyone who wants to work on it.


Resources:
----------

To help you out if you do have to create a style guide from scratch:

* Standard style guides that are useful places to start:

  * Chicago Manual of Style (http://www.chicagomanualofstyle.org/home.html)
  * Microsoft Writing Style Guide (https://docs.microsoft.com/en-us/style-guide/welcome/) - supersedes the old Microsoft Manual of Style
  * Handbook of Technical Writing (http://www.powells.com/book/-9781250004413)
  * Wired Style Guide (if you can find an old copy)

* Publicly-available, comprehensive company style guides:

  * Apple (https://help.apple.com/applestyleguide/)
  * Tech Prose (http://www.techprose.com/assets/techwriting_guidelines.pdf)
  * Rackspace (https://rackerlabs.github.io/docs-rackspace/style-guide/index.html)
  * Google Developer Documentation (https://developers.google.com/style/)

* Ask in the Write the Docs Slack. I feel confident at least a few of us have style guides we're happy and able to share with you.


And now, the meat of it (or seitan or something for those who don't want meat):
-------------------------------------------------------------------------------

In the real world, we generally don't have time to make our style guide as detailed as we'd like it to be right off the bat. So, first tackle the more important stuff, then after that go for it all!

Always remember accessibility. A very easy example is that "above" and "below" mean nothing if users are using a screen reader because of a visual impairment. Use "previous" and "following". Basically, if it takes that little effort to make something more accessible, there's no good excuse not to do it.

Also remember gender neutrality. It's one thing to say "the user" and "he/she", but that doesn't cover it all. First of all, we now generally recognize that gender isn't binary. Also, it's awkward. You can avoid the whole thing by writing in the plural: "Users...". Or, use the second person and write directly to your users.

First pass
++++++++++

Elements you probably want to make decisions on as early in the process as possible:

* Company product names, including trademark attribution, capitalization, and any allowable short forms
* Legalese page (your Legal department might already have this for you):

  * Disclaimers
  * Proprietary and/or confidentiality statements
  * Copyrights
  * EULA
  * Anything else your company requires

* Who is your audience?
* Doc set architecture
* Doc directory structure
* Document naming convention

Style Elements
++++++++++++++

* Verb tense
* Active v. passive voice (c'mon, pick active!)
* Tone: conversational? didactic? something in between?
* Are contractions acceptable?
* Use of courtesies (Please, thank you, etc. Depending on your audience, they might be expected.)
* Title v. sentence case for headings, captions, titles, table column headings
* Graphics/screenshot guidelines: output format, callout style, naming convention
* Links: do they use something like "click here" or show the URL?
* SEO strategy (for online documentation)
* Obviously there are lots more. Please add to this list!
