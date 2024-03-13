### setup vscode as default editor of git:

So you don't have to deal with VI editor anymore

- `git config --global core.editor code`

### Open `.gitconfig` file:

- `git config --global -e`

### add:

```
# [core]
#  editor = code --wait
[diff]
  tool = default-difftool
[difftool "default-difftool"]
  cmd = code --wait --diff $LOCAL $REMOTE
[merge]
	tool = default-difftool
[mergetool "default-difftool"]
	cmd = code --wait $MERGED
[difftool]
	prompt = false
```

### compare HEAD with the last commit

`git difftool HEAD`
git commit -m
