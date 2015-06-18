## My first git push
### Pushing a markdown file

### What I had to do:

* git add .			To link the markdown file from my workspace to the index, this tells git to keep control of this file.
* git commit -m		To commit the the markdown file to my local repository with a message.
* git push	 		To push the file markdown file to my remote repository on GitHub.

### When it failed I had to first pull the master branch, re-initialize and push again, i.e.:

* git pull https://github.com/scovia/myFirstRepo.git master
* git init 
* git add .
* git commit -m
* git push

Then it worked!!!
