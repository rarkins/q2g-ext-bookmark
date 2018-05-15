# Bookmark Extension
[![TravisCI](https://travis-ci.org/q2g/q2g-ext-bookmark.svg?branch=master)](https://travis-ci.org/q2g/q2g-ext-bookmark)
[![Downloads](https://m.sense2go.net/downloads.svg?q2g-ext-bookmark)](https://m.sense2go.net/extension-package)

This extension was developed, for blind users to handle bookmarks with full keyboard control and full JAWS support.

## Intro

![teaser](./docs/teaser.gif "Short teaser")

![bookmarkpublish](./docs/bookmark_publish.gif "Publush Bookmarks")

## Settings

### Options

In the accessibillity options you can switch the use of shortcuts from the default values to customise shortcuts. The recommendation ist to use the combination of "strg + alt + {any keycode}", so that you do not get in truble with screenreaders shortcuts.

![settings](./docs/screenshot_2.PNG?raw=true "Settings")

## Install

### binary

1. [Download the ZIP](https://m.sense2go.net/extension-package) and unzip
2. Qlik Sense Desktop
   Copy it to: %homeptah%\Documents\Qlik\Sense\Extensions and unzip
3. Qlik Sense Entripse
   Import in the QMC

### source

1. Clone the Github Repo into extension directory
2. Install [nodejs](https://nodejs.org/)
3. Open Node.js command prompt
4. npm install
5. npm run build
