## ethnaの関連ファイル編集をサポートするためのプラグイン

### 1. 参考元
**ethna-backend**

https://github.com/akinama/vim-php-ethna-backend.vim

### 2. 使い方
#### 2.1 関連ファイルを開く
ethna backend ファイルを開いている時は backend の、frontend ファイルを開いている時は frontend の関連ファイルを QuickFixWindow に表示します
```vimrc
:call EthnaJump() 編集中ファイルの関連ファイルを開く

お好みでマッピングして下さい (例)
nnoremap <leader>ej :call EthnaJump()<CR>
```

#### 2.2 関連ファイルの定義
* backend - TdGateway, GenericDao, Module
* fronted - act, view, tpl
