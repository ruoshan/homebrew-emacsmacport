# Homebrew-emacsmacport

use the https://github.com/emacs-tw/emacs-mac-mirror as source. the original one
is so hard to reach for me.

### Usage
##### Enable:
```
brew tap ruoshan/emacsmacport
```

##### Install:
```
brew install emacs-mac
```

Note: Prepending `{brew --prefix}/share/info` to your `INFOPATH` is suggested to access the info files. For example:

```
export INFOPATH='/usr/local/share/info:/usr/share/info'
```


##### Disable:
```
brew untap ruoshan/emacsmacport
```
