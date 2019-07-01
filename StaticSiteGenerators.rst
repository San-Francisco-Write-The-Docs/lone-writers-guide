
**********************
Audit existing content
**********************

How to swim in the deep water - A lone writer’s guide to survival
=================================================================

Starting notes:
---------------

* What are static site generators?
* From the June WTD Newsletter:

WHAT IS A STATIC SITE GENERATOR?
================================

A static site generator (SSG) is a tool that can convert a collection of markup files into web pages. Most SSGs include programs that host the resulting web site, but because the output doesn't depend on a specific hosting server, you have many options for deploying the content. Popular static site generators include Sphinx, Jekyll, and Asciidoctor.

Advantages of SSGs:
-------------------

* You can leverage developer tools like Github.
* You author content for SSGs in markup languages, which are non-proprietary, straightforward to read and learn, and easier to use than raw HTML. rST, Markdown, and AsciiDoc are examples of markup languages.
* It's relatively easy to migrate from one static site generator to another.
* There are lots of free, open source SSG tools.
* SSGs use a workflow that developers are familiar with.

One important advantage is that you can keep the documentation close to the code, sometimes even in the same repository as the code, and you can use the same workflow as for code. This encourages developers to keep documentation synchronized with the code.

You should use a static site generator if:
------------------------------------------

* You need to collaborate with developers.
* You need something that's easy to set up and to maintain.
* Your budget for infrastructure and tooling is low.

Disadvantages:
--------------

* SSGs have no content management system to manage things like:

  * Permissions - Access control isn’t built into most static site generators. If you don’t want your docs publicly accessible, access control is an additional expense on your time.
  * Versioning - Not all SSGs support deploying different versions of the same content at once. However, with some SSGs, you can name source control branches in a specific way to handle deploying different versions simultaneously. For example, you might name a branch "3.5" for the docs for version 3.5 of your content. Then, you can create a branch named 3.6 for the next version, and the SSG publishes both versions based on the content of the respective branches. 

* SSGs don't provide an editing tool or many of the editing features of other documentation authoring tools.

WHICH ONE SHOULD I USE?
=======================

You may want to choose a static site generator based on what markup language you work in and what programming language you or your colleagues have experience in. For example, you can write in rST to publish with Sphinx, which is written in Python. Or, you can write in Markdown to publish in Jekyll, which is written in Ruby.

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

All static site generators generate output in HTML, along with some that can also generate PDF, ePub, HTML inside JSON, and other formats.

David Walsh wrote a `a great primer on static site generators <https://davidwalsh.name/introduction-static-site-generators>`_ , especially if you’re interested in the plusses and minuses. The `Docs as Code book <http://docslikecode.com/>`_ and articles have a lot of great content around this as well.
