1. clone this repository

```
$ git clone https://github.com/razzius/robin-hood
```

2. switch to a branch with your name

```
$ git switch -c razzi
```

3. translate inscription.txt

```
$ vim inscription.txt
```

4. commit and push your changes

```
$ git add inscription.txt && git commit -m 'my translation'
$ git push origin razzi
```

5. fetch somebody else's version

```
$ git fetch robyn
```

6. merge their changes with yours

```
$ git merge origin/robyn
```

7. resolve the merge conflict!

```
$ git status
$ vim inscription.txt
$ git add inscription.txt
$ git commit
```

## See also

https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging
