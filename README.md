# freemind_parser
A Python parser of Freemind mindmap file .mm

Introduction
============
I'm a heavy addict to mindmap. I use it everyday for project management and log. And I apply GTD (getting things done) concept on the mindmap. Freemind is the perfect tool, which I've been using since 2003. It has perfect simpler the better GUI, well defined keyboard shortcut, cross-platform. And it's free. One downside is it's written in Java and consumes lots of memory, which was critical in 200x. Now this doesn't seem to be a problem to me.

I need to complain about its sibling Freeplane, which is very advance in 2009 comparing to Freemind. However its new versions are becoming more and more drifted from the "simpler is the better". So I switched back to Freemind again after 5 years.

And I have written my resume in Freemind, mostly the content. Mindmap is very good for this kind of hierarchical text, and also it enables TODO/DONE marks to track your progress. I use LaTeX to generate PDF. At the meantime, I also have a personal website with static pages generated by Pelican, which also contains my resume and project introduction. So my idea is to keep one unified content in Freemind and convert it to .md and .tex files. Another good idea is when I came into a situation that need different resume for different situations. You have to focus on different aspects for the same project, or delete some projects and emphasize some others. So I use "drop" icon in the mindmap and make it disappear from the final product. Thanks to Freemind, this can be done with only one keystroke. Or bring it back with another keystroke.

Usage
=====

freemind_parser.py
------------------
It parse the Freemind .mm file and create a data structure of python classes. For details, you have to look into the python file.

update_resume.py
----------------
It get data from freemind_parser.py and create .tex and .md file. This is highly 
