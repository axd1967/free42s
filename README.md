This is my own README for the [Free42 project](http://thomasokken.com/free42). Please see also the original [README](README).

Recently I discovered that an HP42S clone might surface from SwissMicros, and I contacted the [Free42S forum](https://groups.google.com/forum/#!forum/free42discuss) to see if there was any willingness to further open source this project.

One might wonder what the relation is between those two projects: it's all about **preservation**.

One recurring issue of many websites is that they come and go - there is no guarantee that a site will exist after X years. Currently web technology (heck, here is the proof) allows to easily create websites without much effort - which means those sites often disappear as quickly as they came, because there is no deeper motivation to keep a site going. But web sites also disappear for other - more mundane - reasons. The end result is often users that are left behind.

Similarly, many hardware projects surface but will eventually die, leaving behind owners that have the hardware but not the software to keep that hardware running. Example include synthesisers (more specifically those that can be updated via USB, think of e.g. [Tetra](http://dsiforum.com/viewtopic.php?f=19&t=2154)), [SwissMicros](https://www.swissmicros.com/) devices and the public part of their software (eg the [DM-1x Javascript decoding utility](https://www.swissmicros.com/nut_decoder.html), the documentation, etc), [JAERO](https://github.com/jontio/JAERO/issues/8), [DGS](http://www.dragongoserver.net/) and more. Often, those websites are difficult to archive (for example, I can't easily save a webpage from SwissMicros - this might not be on purpose, and it very much likely the result of choice of tools, but the end result is that one has to resort to web scrapers etc...).

What most of these projects have in common is

- open source software and/or hardware
- a web site crammed full of useful info and additional documentation, *but disjoint from the source code*. That website will disappear at some point in the future, leaving behind bare source code (which is more likely to survive because it will be collected by anyone understanding its primary value). A simple example of valuable information that should not live outside the Free42 project is [this page](http://thomasokken.com/free42/importexport.html) - imagine the website is gone, how would one get that info without reverse-engineering Free42s?

Some of these projects also make it difficult to contribute, by insisting on archaic contribution mechanisms. I can understand that a project that has been ongoing since 2004 is not likely to have caught up with recent evolutions (for example, it is still using Eclipse for the Android component), nor that there is a need to overhaul tools that work fine.

But the point is that I believe that such projects deserve to outlive their owners, but to guarantee that, a mechanism must be used that facilitates their survival: by replicating the entire project, and ensuring that it can easily be contributed to. It is a pity that such sites have to be scooped up in some museum or internet archive site.

Web pages could be e.g. Markdown pages inside a project (which gives a nice rendering on GitHub and is easy to update), rather than separate (usually private) websites project: this would also allow to propagate and share news as well as sourcecode, rather than force users to visit a website to discover news. JAERO and Free42s are examples of this issue, as those sites carry a lot of extra information that contributes to the value of the project. One will admit that Markdown allows for far less nice layouts than custom HTML, but the priority here is ease of access, distribution, survival, ... above nice (but sometimes difficult and sometimes even unavalaible) tools: KISS.

Don't believe me? Try http://www.hp42s.com/ (it's referenced in the [WP article](https://en.wikipedia.org/wiki/HP-42S)).

# What is missing in this project
There is more important stuff scattered around that belongs in the repository (or maybe better in subprojects, but they should remain together under a "master HP42 umbrella project"):

* the Alternative HP-42S/Free42 Manual, written by José Lauro Strapasson and Russ Jones, in source form
* documentation of the extensions
    * (GPS, time) as explained in http://thomasokken.com/free42/extensions.html
    * import/export feature http://thomasokken.com/free42/importexport.html
* example 42S programs (http://thomasokken.com/free42/42progs/index.html)
* the HP42S Code Editor of Andreas Granberg (http://thomasokken.com/free42/code-editor/)
* install instructions such as http://thomasokken.com/free42/42progs/InstallationinstructionsforFree42.htm
* (sourcecode of) the tools needed to run Free42S images on the forthcoming DM-42

(the list is probably not finished)