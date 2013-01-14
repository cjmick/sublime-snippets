Sublime Text 2 Snippets
====================

A collection of [Sublime Text](http://www.sublimetext.com/) snippets useful for writing various programming code

##Installation

These snippets can now be installed via [Sublime Package Control](http://wbond.net/sublime_packages/package_control).


To create a new snippet, select Tools | New Snippet…. Sublime Text will present you with an skeleton for a new snippet.

Snippets can be stored under any package’s folder, but to keep it simple while you’re learning, you can save them to your Packages/User folder.

Snippets File Format

Snippets typically live in a Sublime Text package. They are simplified XML files with the extension sublime-snippet. For instance, you could have a greeting.sublime-snippet inside an Email package.

The structure of a typical snippet is as follows (including the default hints Sublime Text inserts for your convenience):

<snippet>
    <content><![CDATA[Type your snippet here]]></content>
    <!-- Optional: Tab trigger to activate the snippet -->
    <tabTrigger>xyzzy</tabTrigger>
    <!-- Optional: Scope the tab trigger will be active in -->
    <scope>source.python</scope>
    <!-- Optional: Description to show in the menu -->
    <description>My Fancy Snippet</description>
</snippet>
