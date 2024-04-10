```bash
$ git clone https://github.com/rarycoringa/DIM0517_20241_Q3.git
$ cd DIM0517_20241_Q3/
$ git config user.name "Rary Coringa"
$ git config user.email "rary.goncalves.123@ufrn.edu.br"
```

```bash
$ git checkout main
$ git rebase b1
$ git branch -d b1
$ git branch -m main b1
```

```bash
$ git checkout -b main HEAD~4
$ git cherry-pick bce9b66
$ git push -f
```

```bash
$ git checkout b1
$ git reset HARD~1
$ git push -f
```

```bash
$ git checkout main
$ git add commands.md
$ git commit -m "add commands at an .md file"
$ git push
```
