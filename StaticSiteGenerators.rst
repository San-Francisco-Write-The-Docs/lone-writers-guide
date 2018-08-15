
**********************
Audit existing content
**********************

How to swim in the deep water - A lone writer’s guide to survival
=================================================================

Starting notes:
---------------

* What are static site generators?
* From the June WTD Newsletter:

WHAT IS A STATIC SITE GENERATOR
===============================

A static site generator is a tool that can publish a collection of markup files to a site. Popular static site generators include Sphinx, Jekyll, and Asciidoctor.

Advantages:
-----------

* You can leverage developer tools like GitHub.
* Markup is straightforward to read and learn. easier to use than HTML. rST, Markdown, and AsciiDoc are examples of markup files.
* Easy migrate from one static site generator to another.
* There are lots of free, open source tools.
* Uses a workflow that developer are familiar with.

One important advantage is that you can keep the documentation really close to the code and you can use the same workflow as for code. This encourages developers to keep documentation synchronized with the code.

You should use a static site generator if:
------------------------------------------

* You need to collaborate with developers.
* Relatively easy to set up.
* Can be free.

Disadvantages:
--------------

* No content management system to manage:
* Permissions - Access control isn’t built into most static site generators. If you don’t want your docs publicly accessible, access control is an additional expense on your time.
* Versioning - If you’re using a certain kind of markup, you can use readthedocs has versioning built into the theme. Different branches represent different versions. If you name the branch a certain way (for example 3.5). Whenever you’re ready to release a different version of your product, you create a different branch, it creates the version for you.
* No one has developed this function for Markdown yet. Or it’s not popular yet.
* How do you go from version to version and how easy is it for your end users to find different versions of your docs.

WHICH ONE SHOULD I USE?
=======================

You may want to choose a static site generator based on what language you work in. For example, you can write in rST to publish with Sphinx, which is written in Python. Or, you can write in Markdown to publish in Jekyll, which is written in Ruby.

TABLE OF FEATURES
=================

+----------------+-----------------------+---------+------------------------+-----------------+
| Tool           | Programming Languages | Markup  | Outputs                | Notes           |
+================+=======================+=========+========================+=================+
| Sphinx         | Python                | rST     | HTML, LaTeX, PDF, epub |                 |
+----------------+-----------------------+---------+------------------------+-----------------+
| Jekyll         |                       |         |                        |                 |
+----------------+-----------------------+---------+------------------------+-----------------+
| AsciiDoctor    |                       |         |                        |                 |
+----------------+-----------------------+---------+------------------------+-----------------+
| Mkdocs         |                       |         |                        |                 |
+----------------+-----------------------+---------+------------------------+-----------------+
| Hexo.io        |                       |         |                        |                 |
+----------------+-----------------------+---------+------------------------+-----------------+

POPULAR TOOLS
=============

Sphinx
------

Jekyll
------

AsciiDoctor
-----------

Mkdocs
------

Mkdocs is a generator that does the same thing as readthedocs but with markdown.

Hexo.io
-------

Getting a Grip on Static Site Generators
========================================

In general, Sphinx parses rST, and Jekyll parses Markdown.

There are also plugins out there to make Markdown work with Sphinx (like `recommonmark <http://recommonmark.readthedocs.io/en/latest/>`_, or to make rST work with GitBook.

All static site generators generate output in HTML, along with some that generate PDF, ePub, HTML inside JSON, and other formats.

David Walsh wrote a `a great primer on static site generators <https://davidwalsh.name/introduction-static-site-generators>`_ , especially if you’re interested in the plusses and minuses. The `Docs as Code book <http://docslikecode.com/>`_ and articles have a lot of great content around this as well.
