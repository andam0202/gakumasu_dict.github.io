# Github pagesでページを作成・公開する

https://qiita.com/madoreenu/items/b47833bf785562c77819

## Jekyllのインストール

1. Rubyをインストールする
2. Bundlerをインストールする
3. Jekyllをインストールする
4. テーマを適用する
5. ローカルで確認する

<!-- [Rubyをインストールする。](https://qiita.com/kerupani129/items/77dd1e3390b53f4e97b2) -->

```bash
sudo apt-get install ruby-full
gem install jekyll bundler
```

他の人が作ったテーマをダウンロード

```bash
cd alembic-main
bundle install


# ローカルで確認する
bundle exec jekyll serve

# 後はconfig.ymlを編集していく
```
