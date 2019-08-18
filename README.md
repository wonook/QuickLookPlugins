# QuickLookPlugins
Some plugins for quick-look function for mac OS X

## Installations

We'll be using Homebrew Cask (https://github.com/caskroom/homebrew-cask)

With Homebrew installed, run:

    $ brew install caskroom/cask/brew-cask

to install brew-cask and run `$ brew cask` .. commands

----

## List of useful plugins

### QLColorCode

Preview source code files with syntax highlighting

    $ brew cask install qlcolorcode


### QuickLookJSON

Preview JSON files w/ highlighting

    $ brew cask install quicklook-json


### QLMarkdown

Preview Markdown files w/ styles

    $ brew cask install qlmarkdown


### QLStephen

Preview plain text files without a file extension. e.g. README, CHANGELOG, Gemfile etc.

    $brew cask install qlstephen


### BetterZipQL

Preview contents of archives

    $ brew cask install betterzipql


### Suspicious Package

Preview contents of a package file

    $ brew cask install suspicious-package


----

## Additional stuff

### To be able to select/copy text right from quicklook, run the following command in terminal:

    $ defaults write com.apple.finder QLEnableTextSelection -bool TRUE;killall Finder

to reset the settings:

    $ defaults delete com.apple.finder QLEnableTextSelection;killall Finder
