# Require
* xcode 8.x
* [homebrew](http://mxcl.github.com/homebrew/)
* node 5+
* npm
* php 7+

# osx
1. xcode-select --install
2. brew install bash-completion git node tmux byobu
3. npm -g install gulp instant-markdown-d

# Laravel developer
1. brew install php70 --with-fpm
2. brew install composer
3. composer global require [laravel/installer](https://github.com/laravel/installer)
4. composer global require [laravel/valet](https://github.com/laravel/valet)
5. composer global require [hirak/prestissimo](https://github.com/hirak/prestissimo)
6. valet install
7. valet restart

# Linux user
* apt-get install git make

# Installation
* git clone --recursive https://github.com/foodbank/.dotfiles.git
* cd ~/.dotfiles
* make build

# root (manual)
* ln -s ~User/.vim .
* ln -s ~User/.vim/.vimrc .vimrc
* ln -s ~User/.vim/.gitconfig ~/.gitconfig
* ln -s ~User/.vim/.sqliterc ~/.sqliterc
* ln -s ~User/.vim/.bash_profile .profile

# Update personal config
1. Git config ~/.gitconfig
2. Create github access [tokens](https://github.com/settings/tokens) open ~/.bash_profile file found HOMEBREW_GITHUB_API_TOKEN pasted it!

# Chrome extension
* [inbox-by-gmail](https://chrome.google.com/webstore/detail/inbox-by-gmail/gkljgfmjocfalijkgoogmfffkhmkbgol)
* [instant-markdown](https://chrome.google.com/webstore/detail/markdown-preview/jmchmkecamhbiokiopfpnfgbidieafmd?hl=zh-TW)
* [pretty-js](https://chrome.google.com/webstore/detail/pretty-beautiful-javascri/piekbefgpgdecckjcpffhnacjflfoddg)
* [full-page-screen-capture](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl)
* [json-formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?hl=zh-TW)
* [hangouts](https://chrome.google.com/webstore/detail/google-hangouts/nckgahadagoaajjgafhacjanaoiihapd?hl=zh-TW)
* [Momentum](https://chrome.google.com/webstore/detail/momentum/laookkfknpbbblfpciffpaejjkokdgca?hl=en)

# Referances
* [vimcasts](http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/) -- vimcasts.org
* [vim-instant-markdown](https://github.com/suan/vim-instant-markdown.git) -- vim-instant-markdown

# Uninstall
* make clean
