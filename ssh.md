##

- go to home dir:
  `cd ~`

- `cd .ssh`

- `mkdir .ssh`

- `cd .ssh`
- `pwd`

- generate ssh key
  `ssh-keygen -t rsa -C "email@email.com"`

- `code id_rsa.pub`

- test connection
  `ssh -T git@github.com`

- add key to repository
  - `` eval `ssh-agent -s`  ``
  - `ssh-add`
