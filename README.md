# install

## Mac

- [`homebrew`](https://brew.sh/)
- [`iterm2`](https://www.iterm2.com/downloads.html)
- [`'zsh`](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH#macos`
- [`ohmyzsh`](https://github.com/ohmyzsh/ohmyzsh#basic-installation)


## nvm
```
git clone https://github.com/creationix/nvm.git .nvm

```

add to ~/.bashrc
```
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion
```

## Java 8
https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-get-on-ubuntu-16-04
```
sudo apt-get update
sudo apt-get install default-jre
sudo apt-get install default-jdk
sudo add-apt-repository ppa:webupd8team/java
sudo apt-get update
sudo apt-get install oracle-java8-installer
```
