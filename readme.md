# Require
* xcode 8.x
* [homebrew](http://mxcl.github.com/homebrew/)
* node 5+
* npm
* php 7+

# Install
1. git clone --recursive https://github.com/foodbank/.dotfiles.git
2. cd ~/.dotfiles
3. make build

# osx user
1. xcode-select --install
2. brew install bash-completion git node tmux byobu yarn
3. npm -g install gulp instant-markdown-d

# Laravel developer
1. brew install homebrew/php/php71
2. brew install nginx --with-http2
3. brew install homebrew/php/composer
4. composer global require [laravel/installer](https://github.com/laravel/installer)
5. composer global require [laravel/valet](https://github.com/laravel/valet)
6. composer global require [hirak/prestissimo](https://github.com/hirak/prestissimo)
7. valet install
8. valet restart

# Bug for valet 2.0.3
```
sudo chown root:wheel /usr/local/Cellar/nginx/1.10.3/homebrew.mxcl.nginx.plist
sudo chown root:wheel /usr/local/Cellar/php71/7.1.2_13/homebrew.mxcl.php71.plist
sudo chown root:wheel /usr/local/Cellar/dnsmasq/2.76/homebrew.mxcl.dnsmasq.plist

```
And this
```
sudo brew services restart nginx
sudo brew services restart php71
sudo brew services restart dnsmasq
```
And this
```
sudo killall mDNSResponder
```

# linux user
* apt-get install git make

# root (manual)
* ln -s ~User/.vim .
* ln -s ~User/.vim/.vimrc .vimrc
* ln -s ~User/.vim/.gitconfig ~/.gitconfig
* ln -s ~User/.vim/.sqliterc ~/.sqliterc
* ln -s ~User/.vim/.bash_profile .profile

# Update config
1. Update github config ~/.gitconfig
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
