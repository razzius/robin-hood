1. switch to a branch with your name

$ git switch -c razzi

2. translate inscription.txt

$ vim inscription.txt

3. commit and push your changes

$ git add inscription.txt && git commit -m 'my translation'
$ git push origin razzi

4. fetch somebody else's version

$ git fetch robyn

5. merge their changes with yours

$ git merge origin/robyn

6. resolve the merge conflict!

$ git status
$ vim inscription.txt
$ git add inscription.txt
$ git commit
