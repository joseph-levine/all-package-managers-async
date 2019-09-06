# all-package-managers-async
All your package managers run all at once.

## Requirements
1. Python

Python 3.5 is likely the minimum version, but I've only run it on Python
3.7+

## Installation
Clone to somewhere in your path, and that should be it

## Running
```
up-all
```

## Supported Package Managers
| Manager | URL |
|---|---|
| composer | https://getcomposer.org/ |
| Homebrew | https://brew.sh/ |
| oh-my-zsh | https://ohmyz.sh/ |
| oh-my-zsh custom plugins | https://github.com/robbyrussell/oh-my-zsh/wiki/Customization#overriding-and-adding-plugins |
| npm | https://www.npmjs.com/ |
| pathogen | https://github.com/tpope/vim-pathogen |
| pecl | https://pecl.php.net/ |
| pip | https://pypi.org/project/pip/ |
| Ruby Gems | https://rubygems.org/ |
| Vagrant Boxes | https://www.vagrantup.com/ |
| ~~vim 8~~ (broken) | :help packages |
| vim-plug | https://github.com/junegunn/vim-plug |
| vundle | https://github.com/VundleVim/Vundle.vim |
| yarn | https://yarnpkg.com/ |

## Future
- [x] Single file (easier to install for now)
- [ ] More package managers
- [ ] Mercurial/SVN support
- [ ] Better project structure
- [ ] Installer
- [ ] Homebrew
- [ ] Cache list of installed package managers

## Contributing
Yes! Make a pull request, I'll try to get it in.

Especially welcome are more package manager update lines. The goal is
to be as comprehensive as possible.

## Why?
Many package managers claim to be the only one you need. And maybe
there's one that is! (I'm looking at you [Homebrew][1]) But it can be
frustrating when you have six different mangers, all with more security
updates than you can handle.

Adding to that headache, many truly stellar tools only come as version
controlled repositories.

Until we have one Package Manager to rule them all, One Package Manager
to find them, here's a tool to bring them all and bind them.
Asynchronously.

[1]:https://brew.sh
