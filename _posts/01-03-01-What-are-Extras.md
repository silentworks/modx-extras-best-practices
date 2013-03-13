---
title: What are Extras
isChild: true
---

## What are Extras {#what_are_extras}

This might be a question you probably ask yourself when you first look at [MODX][modx]. Other CMSes
have _Plugins_, _Extensions_ and _Modules_. In [MODX][modx] term this is called an Extra, anything
that provides additional functionality to the CMS and is Modular in its codebase can be seen as a
Extra.

An Extra can contain many different elements like [Snippets][modx-snippets], [Chunks][modx-chunks], 
[Plugins][modx-plugins], [Namespaces][modx-namespaces], [Settings][modx-settings] and 
[Custom Dashboard Widgets][modx-dashboard] to name a few. I will give a brief breakdown of 
what some of these are, but will not go into details since the 
[MODX Official Documentation][modxdocs] does this already.

* [__Snippets__][modx-snippets] - PHP code that you can call in your Templates and Chunks in a MODX project, you
can use Snippets to process Chunks also.
* [__Chunks__][modx-chunks] - Chunks are HTML code that can be processed by Snippets or called Standalone in a MODX 
project.
* [__Plugins__][modx-plugins] - Plugins give you access to System hooks which allows you to alter the System without 
hacking the core.

Extras can be developed to be used on both frontend and backend of your [MODX][modx] project. Some 
Extras that allow backend functionality with a GUI is also sometimes referred to as a 
Custom Manager Page (CMP).

Extras that are CMPs are normally split into two sets of subdirectories (assets and core). This is 
done for security purposes and to allow you to move your entire MODX core outside of your webroot.
Majority of the Extras developed as CMPs will make use of ExtJS to create the User Interface (UI) 
even though this is not the only way of creating backend UI in [MODX][modx].

[modx]: http://www.modx.com/
[modxdocs]: http://docs.modx.com/display/revolution20/Home
[modx-chunks]: http://docs.modx.com/display/revolution20/Chunks
[modx-snippets]: http://docs.modx.com/display/revolution20/Snippets
[modx-plugins]: http://docs.modx.com/display/revolution20/Plugins
[modx-namespaces]: http://docs.modx.com/display/revolution20/Namespaces
[modx-settings]: http://docs.modx.com/display/revolution20/Settings
[modx-dashboard]: http://docs.modx.com/display/revolution20/Dashboards
