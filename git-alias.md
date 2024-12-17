
`git config --global --edit`で一括に、または`git config --global alias.xxx xxx`で別々に編集することが可能であるが、以下前者を例にあげよう。

```
[alias]
  co = checkout
  br = branch
  ci = commit
  st = status
  lo = log --oneline
  unstage = 'reset HEAD --'
```
