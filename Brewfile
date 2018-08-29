brew update
brew upgrade
# homebrew-cask設定、インストール
brew tap homebrew/boneyard
brew tap caskroom/cask
brew tap caskroom/homebrew-versions
# for ricty
brew tap sanemat/font
# 各種インストール
brew install rbenv ruby-build
brew install pyenv
brew install pyenv-virtualenv
brew install zsh
brew install ack
brew install git git-flow-avh tig gibo git-lfs
brew install mercurial
brew install mysql@5.7 postgresql mongodb memcached redis
brew install datomic rethinkdb
brew install spark
brew install tmux
brew install openssl
brew install --powerline --vim-powerline ricty
brew install wget curl
brew install gcc
brew install ivy sbt scala giter8 typesafe-activator
brew install groovy grails gradle griffon
brew install node php56
brew install yarn
brew install jetty tomcat nginx
brew install libxml2 libxslt
brew install homebrew/dupes/libiconv
#brew install imagemagick
brew install imagemagick@6
brew link imagemagick@6 --force
brew install heroku-toolbelt
brew install terminal-notifier
brew install elixir
brew install ghostscript
brew install graphviz
brew install jq
brew install yuicompressor
brew install fabric
brew install clamav
brew install diff-so-fancy
brew install namebench
brew install unison unox rsync
brew install mecab mecab-ipadic 
brew install neovim
brew install kompose
brew install amazon-ecs-cli
# 必須アプリ
brew cask install java java8
brew cask install sourcetree
brew cask install tower
brew cask install versions
brew cask install intellij-idea
brew cask install eclipse-java
brew cask install android-studio
brew cask install appcode
brew cask install rubymine
brew cask install pycharm
brew cask install webstorm
brew cask install datagrip
brew cask install xamarin-studio
brew cask install visual-studio
brew cask install visual-studio-code
brew cask install iterm2
brew cask install google-chrome
brew cask install google-drive
brew cask install google-japanese-ime
brew cask install google-hangouts
brew cask install firefox
brew cask install opera-neon
brew cask install thunderbird
brew cask install virtualbox
brew cask install vagrant
brew cask install caffeine
brew cask install alfred
brew cask install dropbox
brew cask install evernote
brew cask install path-finder
brew cask install omnifocus
brew cask install karabiner
brew cask install karabiner-elements
brew cask install skitch
brew cask install sequel-pro psequel
# brew cask install lastpass-universal
brew cask install sublime-text
brew cask install atom
brew cask install textmate
brew cask install limechat
brew cask install clipy
# brew cask install synergy
brew cask install amazon-drive
brew cask install amazon-music
brew cask install accessmenubarapps
brew cask install robomongo
brew cask install 1password
brew cask install slack
brew cask install qsync-client
brew cask install filezilla
brew cask install duet
brew cask install screenhero
brew cask install gimp
brew cask install chrome-remote-desktop-host
brew cask install charles
brew cask install sketch
brew cask install skype
brew cask install hipchat jira-client
brew cask install adobe-reader
brew cask install mysqlworkbench
brew cask install xquartz
brew cask install wireshark
brew cask install insync
brew cask install docker
brew cask install docker-toolbox
brew cask install the-unarchiver
brew cask install kindle
brew cask install balsamiq-mockups
brew cask install macwinzipper
brew cask install ngrok
brew cask install linear
brew cask install near-lock
brew cask install synergy
brew cask install soundflower
brew cask install fastlane
brew cask install vlc
brew cask install gitkraken
brew cask install td-agent
brew cask install dash
brew cask install parallels-desktop
brew cask install discord
brew cask install soapui
brew cask install franz
if [ -n "$(brew cask outdated --quiet)" ]; then
  brew cask reinstall $(brew cask outdated --quiet)
fi
brew cleanup
brew prune
