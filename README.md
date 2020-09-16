# Statistical bioinformatics, ex-1 

This is your README. READMEs are where you can communicate what your project is and how to use it.
Write your name on line 6, save it, and then head back to GitHub Desktop.
This markdown is for my study purpose

(one hash means big title)
**this is bold**
_this is italics_

 
## a little content (definition)
(two hases mean small title)

[] is name of link
() is actual address to the website
exclamation mark trasnforms a link into showing an image.
there shouldnt be a space between [] and ()

Repository: a folder containing history of changes
pull: update remote->local repository
push: update local->remote repository

## a little content (markdown+Rmarkdown+Git)

create repository

	1) create a remote repository
	2) establish credential of computer and register this key with remote repository.
	3) remote suppository is cloned locally (from remote to the local repository) 

add contents

	4) put file in the local repository/or remote repository.
	5) commit
	6) push/pull to synchronize

	push+6 means you have 6 commit that is not pushed to remote yet 

commit to master, branching

	1) change all files related with a single bug
	2) write a summary and description
	3) commit to master 
	(commit to master is like drawing a line saying until here is fixing a 1st bug. You froze sequence of changes in the local repository)

	if you have 6 bugs->you probably have 6 commits.
	If bug4 turned out not to be an error then you can do cherry pick (reverse change that is in the middle without affecting others)

	you can merge branches into a master.

	if you have 6 branches: you have 6 independent changes. you can merge branches together.

Rmarkdown
	Rknit creates 'html' file from R with markdown ->html

	markdown: formatting of parts of documents using symbols. (##makes a title etc)
	Rmarkdown: allows to format document and also to include R code and also output of execution. (just like jupiter notebook)

	r setup: means set up markdown file
	without any sign->means comment in R markdown
	'''this block is R code
	'''
	insert R: creates R code block

	'''
	{r samples}
	'''
	samples is the name of a particular cell. you can use 'samples' in other cells as well.

	`r ` this part is R code but can be used within text. 
## an example of link
[ETH Zurich](https://ethz.ch/en.html)

## an example  of images
![image of a science cat](https://octodex.github.com/images/bannekat.png)

