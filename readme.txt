mac c++開発環境構築


. VSCode 拡張機能のインストール
  C/C++
  Code Runner
  CodeLLDB

. macにインストール必要なもの
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
xcode-select --install
brew install gcc
brew install gdb
brew install ninja
```