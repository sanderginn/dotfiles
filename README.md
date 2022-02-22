## Steps
1. Install brew:  
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

2. Install 1password-cli and login:  
```
brew install --cask 1password-cli
op signin my.1password.com <username>
```

3. Install and run chezmoi:  
`sh -c "$(curl -fsLS chezmoi.io/get)" -- init --apply sanderginn`