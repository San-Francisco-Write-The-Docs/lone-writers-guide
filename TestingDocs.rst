
*******************
Getting docs tested
*******************

=================================================================
How to swim in the deep water - A lone writer’s guide to survival
=================================================================


Why Test Docs?
==============

Docs need QA testing, just like software. If the documentation doesn't work, then customers will assume the product doesn't work. Suppose a customer reads that a line of sample code in your docs will make the software do something magical; then when that bit of code gets pasted in the terminal -- nothing happens, or worse the customer gets an error. Customers will quickly conclude that the product does not work or is too difficult to use, although the problem might be a code sample that is outdated or incorrect.

Accurate documentation matters, because it affects the customer's perception of how reliable and easy to use the product is. A documentation bug can be as damaging to the company's reputation as a software bug.

What You'll Find When You Test
==============================

* Inaccurate instructions, that were based on internal documentation or your notes from interviewing engineers (Engineers are smart, but that doesn't mean that everything they tell you is correct.)
* Missing steps that are necessary but not documented, because they seemed implicit when the instructions were written. Any documented procedure for using a product is useless if one key step or multiple steps are missing.
* Software bugs. Find out how to file a bug in your development environment.
* Outdated information that was true several versions ago, but wasn't updated at some point when the product changed.

How to Test
===========

The best method for testing documentation is to follow the procedural part of the docs, step by step, including installation and all the various functions of the product. This is more robust and reliable than a doc review (in which engineers read your docs and sign off), but it takes a lot more time. The most practical approach is to ask engineers to review everything, and test as much as you reasonably can.

When testing, consider these guidelines:
* Be very careful to assume that the product's eventual user does not know even the most basic things that you already know about the product. If the doc does not say, "Do X", then don't do it during the testing.
* Plan your testing ahead of time. Unless your documentation is short, a systematic approach will be necessary to test the entire contents.
* Document every error or bug that you find, because you'll have data to show your managers that testing the docs is a valuable use of your time, and that you are making big improvements.

Decide how formal the documentation of your testing should be. One approach is to check off each line in the documentation on a printed page as its accuracy is verified. A more systematic approach is to create a table or spreadsheet, with each line of documentation inserted into a cell of the first column. (The approach you choose might have to depend on who does the testing, and how much time they want to spend.)

The spreadsheet approach gives the following benefits:
* You can add columns to enter the pass/fail status of the passage of text, the platform it was tested on, who did the test, what the pass/fail criteria were, links to any JIRA tickets that resulted, and any additional comments.
* You can use formulas in a table to produce statistics about your testing, like what percentage of the information was correct.
* You have proof that you tested individual lines of text in the docs, and when you tested them.

Who should test the docs?
========================
* Writers should test the entire doc set to verify that everything in it is accurate -- even though this is not enough testing. The writer, developers and quality assurance people might know the product well enough that they automatically fill in missing steps or gloss over areas that aren't explained well enough for a customer. For that reason, writer and engineers cannot be the only testers.
* A new employee who needs to learn the company's products is an ideal tester, if you approach them at the right time. Sales engineers are strongly motivated to understand the product and to give you feedback when it doesn't work. And they might consider it a favor if you make sure they get the latest copy of the software and all the documentation. Newly hired support engineers might also be good prospects, if your company expects them to know the product deeply.
* Any intelligent person who is outside of the engineering part of the company and willing to test the docs is a good potential tester.
