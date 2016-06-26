But I got kicked out, being accused of "git/github sales pitching", and actually missed my opportunity to explain why exactly I saw it important to further open source the project. Also, my reaction was a reply to an existing post that read "Source Code on github", opened on 11/10/2013 by William Bell, and finally the entire thread was deleted - which is a disaster from an archival point of view. Plus, this attitude is nipping open source initiatives in the bud...

Following is a thread started by William Bell, to which I added my 2c - after which the whole thread was deleted.

> Source Code on github
Showing 1-2 of 2 messages

>Source Code on github 	William Bell 	11/10/13 10:41 AM
Hi
I would suggest putting the source code on github so as to make collaboration easier.
Thanks

> Re: Source Code on github 	Thomas Okken 	11/14/13 7:13 AM
The current arrangement is more efficient. If someone wants to hack Free42, they can use the source code tarball from my web site, and if they want to contribute their code to the project, they can send me the code (or a diff) and I'll merge it into my source database. This is a bit more work than if others would be able to commit their work directly, but it saves me the overhead of maintaining yet another site... Besides, as long as I'm running this project, I want to be able to veto any code changes I don't like, and by having everything go through my hands before it is merged into my source database, code reviews are a natural part of the process.
Now, if someone wanted to start a community project, say, to transform Free42 into something more sophisticated, with multiple developers actively contributing, then using a public source database would make sense, but I have never gotten the impression that there is a lot of interest in that. (Of course there is also the issue that *I* am not interested in making major modifications or functionality extensions to Free42, so any such project would pretty much have to be a fork.)

The mistake is assuming that "others would be able to commit their work directly", and only demonstrates a lack of Git knowledge.

Notice also the remark on forking.

Know what? The sourcecode *is* available, see [build-src-doc](build-src-doc). Except that (e.g.) `svn://mactv/free42/trunk` is not reachable, and would already require to be edited in order to compile (also, it's odd that code that is already inside a repo requires a checkout). See? This is exactly the problem - a truly open source project should not have this kind of issues (so this is a first action point to tackle). And at least the [history file](HISTORY) seems to be available and matches http://thomasokken.com/free42/history.html, so there is a kind of syncing in the project.
