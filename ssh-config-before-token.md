##

- go to home dir:
  `cd ~`

- `cd .ssh`

- `mkdir .ssh`

- `cd .ssh`
- `pwd`

- generate ssh key
  `ssh-keygen -t rsa -C "email@email.com"`

- paste public ssh key in github

  - `code id_rsa.pub`

- test connection
  `ssh -T git@github.com`

- add key to repository

  - `` eval `ssh-agent -s`  ``
  - `ssh-add ~/.ssh/name`
    - or
  - `ssh-add`

### `git push`

- remember to finish ssh configuration:
  - `git branch --set-upstream-to git@github.com:User/your-repo.git`

`-u` = `--set-upstream-to`
