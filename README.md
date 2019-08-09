# all-package-managers-async
All your package managers run all at once.

## Requirements
1. Python

Python 3.5 is likely the minimum version, but I've only run it on Python
3.7+

## Installation
Clone to somewhere in your path, and that should be it

## Command Reference
| Command | Description |
|---|---|
| up-all | Updates all available packages in package managers |
| up-git | Updates all git repositories in a given directory (default = `~`) |
| up-pip | Updates all python 3 global pip packages |

### Supported Package Managers
| Manager | URL |
|---|---|
| composer | https://getcomposer.org/ |
| homebrew | https://brew.sh/ |
| oh-my-zsh | https://ohmyz.sh/ |
| oh-my-zsh custom plugins | https://github.com/robbyrussell/oh-my-zsh/wiki/Customization#overriding-and-adding-plugins |
| pip | https://pypi.org/project/pip/ |
| vim-plug | https://github.com/junegunn/vim-plug |
| yarn | https://yarnpkg.com/ |

### Helper Files
| File | Description |
|---|---|
| up-vim.vim | Updates all Vim Plug packages |


## Future
- [ ] More package managers
- [ ] Better project structure
- [ ] Installer
- [ ] Homebrew

## Why?
Most package managers claim to be the only one you need. And maybe
there's one that is! (I'm looking at you [Homebrew][1]) But it can be
frustrating when you have six different mangers, all with more security
updates than you can handle.

Adding to that headache, many truly stellar tools only come as git
repositories.

Until we have one Package Manager to rule them all, One Package Manager
to find them, here's a tool to bring them all and bind them.
Asynchronously.

[1]:https://brew.sh 
