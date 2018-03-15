# インストール
環境: Mac
```bash
# もろもろやってない人向け。brew？？って人はこれやる

# install brew
brew &>/dev/null || /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew upgrade -y
brew install yarn

# elmのインストール(yarn向け)
yarn global add elm
```
参考: [プログラミング言語Elmの薄い本](https://giisyu.gitbooks.io/elm_usui_book/content/src/install/install.html)

# 最初のElmアプリケーション
`01_basic/Hello.elm`
```elm
module Hello exposing (..)

import Html exposing (text)

main =
  text "Hello"
```

`01_basic/`
```bash
open http://localhost:8000
elm reactor
```
Hello.elmをクリックするとこんにちは世界

# 基本

