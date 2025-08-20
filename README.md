# macOS useful settings

## Git global settings
`git config --global --list`

```bash
user.name=
user.email=
user.signingkey=
pull.rebase=true
commit.gpgsign=true
tag.gpgsign=true
push.autosetupremote=true
```

`git config --global push.autoSetupRemote true`

## JAVA_HOME and conditional $PATH modification
`cat .zshrc`


## Other things

### pwd with escaped spaces
`printf "%q" "$(pwd)" | pbcopy`
