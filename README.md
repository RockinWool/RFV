# このプログラムはTar_nullaの部屋というサイトで使っているものです
HugoおよびGithubpagesの技術に感謝します

## hugoのインストール
2021.11.06: 何故かhugoがWindowsに入っていないという問題が発生したため、再度セットアップ作業を行った。hugoのインストールに関しては[このサイト](https://qiita.com/utibori1/items/46fde79958ec9202d6c4)を参考にした。なお、PATH設定後はVSCodeを再起動しないとターミナルに反映されない。

## theme
config.tomlに以下を明記してbalck-and-lightテーマを使用できるようにしています。
```toml
theme = "black-and-light"
```
なお、詳細な説明は[ここ](https://qiita.com/higebobo/items/e371ba0edaddd943e706)を参考に作ればよいと思います。昔どう設定したのかはもう思い出せないのですが。

## 新しい記事の投稿

```bash
hugo new posts/hogehoge.md
```
