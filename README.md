# docker-machine plugin for oh my zsh

A copy of the completion script from the [docker-machine](https://github.com/docker/machine/blob/master/contrib/completion/zsh/_docker-machine) git repo with added functionality:

* `docker-machine use mymachine` - alias for `eval $(docker-machine env mymachine)`
* default timeout for `docker-machine ls` is now 3 seconds
* adds `log-opt="max-size=10m"` and `log-opt="max-file=10"` to all `docker-machine create ...` commands 

# Installation

```
cd ~/.oh-my-zsh/custom/plugins
git clone https://github.com/poma/zsh-docker-machine
# edit ~/.zshrc and add `zsh-docker-machine` to plugin list
```
