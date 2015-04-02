# Fresh Linux Setup

**Disclaimer:** this is mainly for my own personal use but figured i'd share.

This repo contains a list of software/programs I will typically install
on a fresh linux image.  Many of the programs are related to development
and programming and can be obtained via the Debian package manager (aptitude)
however others may be "extra-curricular" :)

I will probably also include other steps/activities in here to get a
fresh Linux install off the ground and ready for development.

## List of aptitude packages

* zsh
* terminator
* python-pip
* fabric
* mongodb
* git
* git-gui
* gnome-do
* ubuntu-gnome-desktop
* npm
* tftpd

## Other programs

* Google Chrome (duh)
* Pycharm
* clion
* rubymine
* webstorm
* thunderbird
* spotify

## Other stuff

### zsh configuration

Get ohmyzsh:

```
curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
```

Setup zsh as default shell:

```
sudo chsh -s /usr/bin/zsh <user>
```

### Git config

```
git config --global user.name "Stephen Stack"
git config --global user.email "ss@stephenstack.com"
git config --global core.editor emacs
git config -- global diff.tool meld
```

### Trivial stuff

* Generate SSH key and copy to GitHub
