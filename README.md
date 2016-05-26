This is my own README. Please see also the original [README](README).

Recently I discovered that a clone of HP42S might surface from SwissMicros, and I contacted the [Free42S forum](https://groups.google.com/forum/#!forum/free42discuss) to see if there was any willingness to further open source this project (*).

One might wonder what the relation is between those two projects: it's all about **preservation**.

One recurring issue of many websites is that they come and go - there is no guarantee that a site will exist after X years. Currently web technology (heck, here is the proof) allows to easily create websites without much effort - which means those sites often disappear as quickly as they came.

Similarly, many hardware projects surface but will eventually die, leaving behind owners that have the hardware but not the software to keep that hardware running. Example include synthesisers (more specifically those that can be updated via USB), SwissMicros devices and the public part of their software (eg the DM-1x JavaScript permitting to program the devices, the documentation, etc), [JAERO](https://github.com/jontio/JAERO/issues/8), [DGS](http://www.dragongoserver.net/) and more.

What most of these projects have in common is

- open source software and/or hardware
- a web site crammed full of useful info and additional documentation, *but disjoint from the source code*. That website will disappear at some point in the future, leaving behind bare source code (which is more likely to survive because it will be collected by anyone understanding its primary value). A simple example of valuable information that should not live outside the project is [this page](http://thomasokken.com/free42/importexport.html) - imagine the website is gone, how would one get that info without reverse-engineering Free42s?

Some of these projects also make it difficult to contribute, by insisting on archaic contribution mechanisms. I can understand that a project that has been ongoing since 2004 is not likely to have caught up with recent evolutions (for example, it is still using Eclipse for the Android component).

I believe that such projects deserve to outlive their owners, but to guarantee that, a mechanism must be used that facilitates their survival: by replicating the entire project, and ensuring that it can easily be contributed to.

In order to "raise the concentration", websites should ideally be Markdown pages inside a project, rather than a (usually private) side project: this would allow to propagate and share news as well as sourcecode, rather than force users to visit a website to discover news. JAERO and Free42s are examples of this issue, as those pages carry a lot of extra information that contributes to the value of the project.

*:  But I got kicked out, being accused of "git/github sales pitching", and didn't get a chance to explain why exactly I saw it important to further open source the project. Also, my reaction was a reply to an existing post that read "Source Code on github", opened by someone else (unfortunately, I didn't note the name), and finally the entire thread was deleted - which is a disaster from an archival point of view. Plus, this attitude is nipping open source initiatives in the bud...

But the worst part? The sourcecode *is* available, see [build-src-doc](build-src-doc). Except that svn://mactv/free42/trunk is not reachable, and would already require to be edited in order to compile. See? This is exactly the problem - a truly open source project should not have this kind of issues (so this is a first action point to tackle). And at least the [history file](HISTORY) seems to be available and matches http://thomasokken.com/free42/history.html, so there is a kind of syncing in the project.