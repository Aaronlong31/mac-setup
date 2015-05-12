# Using Homebrew

To install a package (or **Formula** in Homebrew vocabulary) simply type:

    $ brew install <formula>

To update Homebrew's directory of formulae, run:

    $ brew update

**Note**: I've seen that command fail sometimes because of a bug. If that ever happens, run the following (when you have Git installed):

    $ cd /usr/local
    $ git fetch origin
    $ git reset --hard origin/master

To see if any of your packages need to be updated:

    $ brew outdated

To update a package:

    $ brew upgrade <formula>

Homebrew keeps older versions of packages installed, in case you want to roll back. That rarely is necessary, so you can do some cleanup to get rid of those old versions:

    $ brew cleanup

To see what you have installed (with their version numbers):

    $ brew list --versions

My brew list:
```shell
brew install the_silver_searcher
brew install php56
brew install php56-mcrypt
brew install autojump
brew install byobu
brew install maven
brew install mysql
brew install thrift
brew install tree
brew install wget
brew install opensll
brew install pcre
brew install imagemagick
brew install composer
brew install brew-cask
brew install node
brew install redis
brew install tomcat
brew install mosquitto
```
