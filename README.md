## Purpose of this Repository:


## How to Use this Template:

This repository serves as a template, for information on making and using a repository go to https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template.

The overview of this process is:

1. Select the option to "Use this template," located next to the option to clone this repository.
2. Name the repository, and select "Create repository from template."
3. Clone your repository with SSH keys.
	* Open a command line or terminal on your device and enter the directory into which you want to clone your template based repository. 
	* Enter `git clone git@github.com:USERNAME/REPONAME`. Where USERNAME and REPONAME are replaced respectively by your github account's username and the name you chose to give this repository.
	* Enter `git remote add upstream git@github.com:USERNAME/REPONAME`
4. Now you can make edits and changes to the files on your device and push changes to your Github repository as with any other repository.

## How to Initialize this repository:
After you have cloned this repository, made your changes, and prepared 

Run the command
`make {insert type here}`

For pdf, insert `all-via-pdf` or `all`.

For dvi, insert `all-via-dvi`.

For epub, insert `epub`.

For zip, insert `zip`.

# To clean your local directory run:

`make clean` or `make realclean`

## Adding Citations:
To cite something you have to first add a citation to the bibliography.bib file in your local directory.

# Here is an example format for a citation in the bibliography file:

`@misc{ call_tag,`
	`address = {Example Place},`
	`title = {Example Title},`
	`abstract = {Details of article you are referencing},`
	`booktitle = {Example Title},`
	`publisher = {Example Publisher},`
	`author = {Example Author},`
	`month = {Dec},`
	`year = {2017},`
	`file = {Example File Extension, to something like Zotero},
}`

# To add a citation to elements in your local directory:

`This sentence is used as an example citation call ~\cite{call_tag}.`

## ARFC 
http://arfc.npre.illinois.edu/manual/guides/writing/report
