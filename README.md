## BIN PATH APPENDER

Addends passed argument to PATH in ~/.zshrc.

**Maintainer:** [@gad0lin](https://github.com/gad0lin) 


### Installation

1. Enable the plugin by adding it to your `plugins` definition in `~/.zshrc`.

  ```
  plugins=(papp)
  ```

2. [Install asdf](https://github.com/asdf-vm/asdf#setup) by running the following:
  
  ```
  cd ~/.oh-my-zsh/plugins/
  git clone git@github.com:gad0lin/papp.git
  ```




### Usage
Calling:
```
papp ~/bin/ 
```
will append following entry to ~/.zshrc file:
```
export PATH="$PATH:~/bin"
```
