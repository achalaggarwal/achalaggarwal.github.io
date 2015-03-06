---
title: Sublime Text 2
date: 2012-06-28
layout: post
permalink: /post/sublime-text-2
---

I have been playing around with the Sublime Text 2 betas for a while now. I started using it mainly when I started working on [Kinesis](http://kinesis.io "Kinesis"). I had to constantly switch between Windows and Mac, I needed to an editor which would well in both worlds. I tried doing a combination of [TextMate](http://macromates.com/) on OS X and [e](http://www.e-texteditor.com/) on Windows.

It just didn't work right. And then I found Sublime Text 2. \**heaven*\*

Yesterday, Sublime Text 2 went out of beta and released to the public with a huge update. Another cool thing you should know about Sublime is that the trial mode is not really a trial. It is a timeless trial mode which shows you a pop-up to buy a license after you save files a few times. This pop-up can be easily dismissed. There are no limitations on using the software what so ever.

That said, I would highly recommend buying a license for it as these guys have done an awesome job. :)

Now let me tell you what all customizations I have done in my install -

### Command Line Support

When using TextMate, I had multiple alias set to open it from the command line. I wanted something same or similar when I moved to Sublime. Luckily, searching through the docs, I saw that it does include a [command line tool called subl](http://www.sublimetext.com/docs/2/osx_command_line.html)

### Package Control

This is a full featured package manager which can be used to install and update all the latest plugins all around the web. The [Package Control](http://wbond.net/sublime_packages/package_control) plugin makes it dead simple to do all those things.

After the installation is complete, all you need to do is

*On Mac OS X*

    Press Command + Shift + P (on OS X)

*On Windows*

    Press Control + Shift + P (on Windows)

*then*

    Type "install"

This opens the list of available packages to customize your install of Sublime.

### Bracket Highlighter

This is a really simple but nifty little plugin. It does exactly what the name says. Highlights the corresponding bracket in the code. It also allows for code folding.

It is available on the Package Control and also on [Github](https://github.com/facelessuser/BracketHighlighter)

### Sidebar

The default sidebar in Sublime, does not give me any options at all. Yes, it allows me to browse through files and view the whole tree, but thats about it. If I want to say rename a file - Nope, can't be done.

The *SideBarEnhancements* plugin fixes all of this and more. The features range from basic to advanced. I sure this will definitely help you out.
It can be downloaded via the Package control or via [Github](https://github.com/titoBouzout/SideBarEnhancements/)

### SublimeCodeIntel

This is a plugin which has been ported from the Open Komodo Editor. Provides full-featured code completion for the following languages:

- PHP
- Python
- RHTML
- JavaScript
- Smarty
- Mason
- Node.js
- XBL
- Tcl
- HTML
- HTML5
- TemplateToolkit
- XUL
- Django
- Perl
- Ruby
- Python3

It is available on the Package Control and also on [Github](https://github.com/Kronuz/SublimeCodeIntel)

### SublimeLinter

This brings the power of "linters" directly inside Sublime. It basically highlights the line of code which it thinks has errors. It makes it really easy to spot errors in the following languages:

- CoffeeScript
- CSS
- Java
- Javascript
- Objective-J
- Perl
- PHP
- Python
- Ruby

It is available on the Package Control and also on [Github](https://github.com/SublimeLinter/SublimeLinter)

### WordCount

This plugin is completely optional. If you want to use Sublime as your primary text editor as well, then you would want to know the word count :)
