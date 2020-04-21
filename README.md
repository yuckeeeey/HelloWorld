# vim
vim設定の覚書
## ヤンクでクリップボードにコピー
デフォルトのvim.tinyではクリップボードが使えないので以下をインストール．

```
sudo apt install vim-gnome
```
vimrcに以下を追加．

```Shell
clipboard=unamedplus
```
