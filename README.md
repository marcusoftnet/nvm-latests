# nvm-latests
[nvm](https://github.com/creationix/nvm) is an awesome tool to keep control over several instances of [iojs](http://iojs.org) and [Node](http://nodejs.org) on your computer.

The only problem I've found with nvm is that it doesn't update itself and it's hard to see if there's new version, or what the latests version is.

This simple (!) tool solves that.

You can got to http://nvm-latest.herokuapp.com and copy the current url, or you can just go:
´´´bash
	curl http://nvm-latest.herokuapp.com/script | bash
´´´

or using Wget:

´´´bash
wget -qO- http://nvm-latest.herokuapp.com/script | bash
´´´
# Principle
I will not store the script but rather get it from github.
I will cache the latests tag from github for 24 h.

# kanban
Here's what I'm doing right now

## Todo
- deploy to Heroku
- latests version is stored (where?) and only looked up once per day

## Doing
- /script returns the raw script for curl-ling scenarios

## Done
- Home page has copy-button for the script to get it on clipboard
- Home page has copy-button for the script to get it on clipboard with sudo-prefix
- Home page has link for the latests version
- add Makefile
- add config object
- set up inital structure of project
