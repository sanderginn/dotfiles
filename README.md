## Steps
1. Install brew:  
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

2. Install and run chezmoi:  
`sh -c "$(curl -fsLS chezmoi.io/get)" -- init --apply sanderginn`

3. Set SSH keys:  
```
op signin my.1password.com <username>
eval $(op signin my)
op get document ssh_private > ~/.ssh/id_rsa
op get document ssh_public > ~/.ssh/id_rsa.pub
```