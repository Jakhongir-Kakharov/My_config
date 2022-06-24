# Install & Customizing The Fish Shell

# Update Repo's
sudo apt update

# Install Fish
sudo apt install fish

# Run Fish Shell
fish

# Optional Below Here:

#Remove Greeting New Method
set --universal fish_greeting

# Install curl
sudo apt install curl

# Install git
sudo apt install git

# Install powerline fonts
sudo apt install fonts-powerline

# Install plank
sudo apt install plank

# Install omf
curl -L https://get.oh-my.fish | fish

# Set Fish Shell
chsh -s /usr/bin/fish

# Install Fisher
curl -sL https://git.io/fisher | source && fisher install jorgebucaran/fisher

# Install z
fisher install jethrokuan/z

# Theme shellder
fisher install simnalamburt/shellder

# Install exa
sudo apt install exa

wget -c http://old-releases.ubuntu.com/ubuntu/pool/universe/r/rust-exa/exa_0.9.0-4_amd64.deb
sudo apt-get install ./exa_0.9.0-4_amd64.deb

# Install peco
sudo apt install peco

# Install Tilda terminal
sudo apt install tilda

# Git clone
git clone 

# Neovim
sudo add-apt-repository ppa:neovim-ppa/stable
sudo apt-get update
sudo apt-get install neovim

#tweaks
sudo apt-add-repository universe
sudo apt install gnome-shell=3.36.4-1ubuntu1~20.04.2 gnome-shell-common=3.36.4-1ubuntu1~20.04.2 gnome-shell-extension-prefs=3.36.4-1ubuntu1~20.04.2
sudo apt install gnome-tweak-tool

# Node.js (LTS), Gulp, Ruby va Jekyllni Windows 10/Ubuntu/Mint da o'rnatish:
sudo apt-add-repository ppa:brightbox/ruby-ng
sudo apt-get update
sudo apt-get install curl ruby2.5 ruby2.5-dev gcc make g++ libffi-dev

# Using Ubuntu ikkita buyruqni birga berish kk
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash - 
sudo apt-get install -y nodejs

sudo gem i jekyll
sudo gem i jekyll-paginate-v2
sudo npm i -g gulp rimraf npm-check-updates
sudo apt update
sudo apt -y install ruby2.5 ruby2.5-dev gcc make g++ curl 

# npm 8.11 bo'lishi kk
/*
npm cache clean -f
npm install -g npm@8.11.0
npm config set package-lock false
sudo gem i bundler jekyll jekyll-paginate-v2
*/

npm uninstall gulp --save-dev
npm uninstall gulp -g

npm install gulp-cli -g
npm install gulp@3.9.1

#shell
https://extensions.gnome.org/extension/3210/compiz-windows-effect/

https://extensions.gnome.org/extension/19/user-themes/


#NEOVIM

sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'

sudo apt install code-insiders --classic


# .local 
chmod -R 777 .local


nvim
fisher list
omf list

:PlugInstall
:PlugUpdate
:TSUpdate
:TSInstall all

# install telegram
sudo snap install telegram-desktop --edge


# install tmux
sudo snap install tmux












