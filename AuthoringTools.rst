
***************************
Authoring tools - selecting
***************************

=================================================================
How to swim in the deep water - A lone writer’s guide to survival
=================================================================


When choosing an authoring tool, think about both your audience and your content creators. For the purposes of this discussion, let's think first about the differences in writing for end users versus software developers.


=================================
Choosing an End User Content Tool
=================================

Ask yourself these questions about your audience before choosing a tool for delivering end-user content:
   * Is my audience very visually oriented, or otherwise doesn't feel comfortable with reading long passages of text? If so, you may need to consider using graphics and videos in your documentation.
   * Does the user content need to interact with the application? For example, would it help if a user could click a button in the documentation and have it open up the window the documentation is describing?
   * Will users read the documentation offline, or in situations where they may not have access to a computer?
   * Will users be reading this documentation on a mobile device? If so, which platform?

You also need to understand your content creators:
   * Are they comfortable with version control systems like git?
   * Are they comfortable working in a markup language, or do they require a WYSIWYG (What You See Is What You Get, describes a graphical interface much like MS Word) interface for editing?
   * Are they professional technical writers, software developers, or a variety of people with different job descriptions?
   * Do they have the skills and tools to create video or graphical content?
   * Do they understand how to design and write clear, concise, and helpful content?
   * Is creating content a rewarding experience for them, or a chore?

Some of the same tools recommended for Software Developer documentation make work for you if your content creator community has a high level of familiarity with technology and is comfortable working in a markup language.

Non-Technical-Writer Content Tools
------------------------------------

If your content creator community is made up of non-technical writers, and is more comfortable in a word-processing (WYSIWYG) type of editing environment, you may find these tools useful:
   * Atlassian Confluence (a wiki with a word-processor-style editing interface)
   * Google Docs (an online word-processor with simple editing tools and commenting features)

Technical Writer Content Tools
------------------------------

If your content creators are mainly technical writers, and need the power of more complex authoring tools, there are many options. A few of these are:
   * Madcap Flare and other online help authoring tools (provides level of application integration)
   * Oxygen for DITA (single-source authoring in XML, publish to many formats)
   * FrameMaker (traditional word processor, can publish to HTML, DITA, or PDF, among other formats)
   * MS Word (publish to PDF)
   * Atlassian Confluence (wiki can be made to look like a traditional web site, many plugins to support authoring needs)
   * MediaWiki (great user community to support customization, wiki-style authoring)

Visual Documentation Tools
--------------------------

If your community requires visual documentation, look into video and graphics authoring tools:
   * Flowcharts (OmniGraffle, Gliffy, Visio)
   * Screen capture (SnagIt, platform-specific tools)
   * Video capture (QuickTime, SnagIt, platform-specific tools)

No matter who your content creators are, it will help to have a way to create templates for specific kinds of documentation so that they have a starting place that conforms to your style guide.


==========================================
Choosing a Software Developer Content Tool
==========================================

If your content creators are software developers, they may be more likely to keep the documentation up-to-date if the documentation lives with the code. This usually involves writing in a markup language, such as:
   * Markdown
   * reStructuredText
   * doxygen

How you deliver documentation written in a markup language depends on your audience. Ask yourself a few questions:
   * Is my audience internal or external to the company? This will affect whether you have to get external web site hosting for your generated static web pages.
   * Is my audience going to be working with code from GitHub? This may bias you toward using a solution that involves publishing from GitHub, such as ReadTheDocs.
   * Does my documentation need to be interactive -- for example, do I want to let users try out a JavaScript API in the browser, or see the real-time effects of code samples?

Publishing Developer Documentation
----------------------------------

Markup languages require some mechanism for publishing the content to a web site -- otherwise, the content can only be read by those who visit the source code repository. Some popular opensource publishing tools include:
   * Sphinx (builds static web pages from Markdown or reStructuredText)
   * doxygen (builds static web pages doxygen markup or Markdown markup in the code)
   * MkDocs (builds static web pages from Markdown)
   * ReadTheDocs (builds static web pages from Markdown or reStructuredText from GitHub repos)

API Documentation Generators
----------------------------

API documentation has very specific needs that may require more interactivity. If you're documenting an API, ask yourself:
   * Is this a JavaScript (REST) API?
   * How will you support docs for each version of the API?
   * How will you create API usage examples and keep them up-to-date?
   * How much interactivity does the audience require? Should they be able to "try out" the API in the documentation?
   * Will the author manually create the documentation, or do you need to generate as much as possible from the code structure itself?

Several tools exist to help with creating automatic API documentation for a variety of languages. This is only a few:
   * pydoctor (Python)
   * doxygen (C++, C, and several other languages)
   * javadoc (Java)
   * Swagger/swagger-codegen (REST/Javascript -- interactive API exploration)

Note that auto-generation tools are not that useful if the developers do not write descriptions for the API in the code. Creating templates for common IDE tools or editors (like emacs) can help encourage the creation of content for each API function.

API documentation also does not replace the need for examples and tutorials.


====================================
Related Topics
====================================

See also AuthoringToolsChanging.rst.
