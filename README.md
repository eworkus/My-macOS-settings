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

```Bash
__JAVA_HOME="/Users/USER/Developer/JDK/jdk-24.0.2.jdk/Contents/Home"
[[ -d $__JAVA_HOME ]] && export JAVA_HOME="$__JAVA_HOME"
[[ -d $__JAVA_HOME/bin ]] && export PATH="$__JAVA_HOME/bin:$PATH"
unset __JAVA_HOME
```

## Other things

### pwd with escaped spaces
`printf "%q" "$(pwd)" | pbcopy`
