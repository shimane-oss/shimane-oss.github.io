# しまねOSS協議会ウェブサイト

## ローカル環境での確認方法

- 静的サイトジェネレーター[Jekyll](https://jekyllrb.com/)を使用します。
- Ruby 2.5.0以上

1. リポジトリをクローンする。  
`git clone https://github.com/shimane-oss/shimane-oss.github.io.git`  
2. フォルダを移動する。  
`cd shimane-oss.github.io`  
3. 必要なGemをインストールする。  
`bundle install --path 'vendor/bundle'`  
または  
`bundle config set path 'vendor/bundle'`  
`bundle install`  
4. Webサーバを起動する。  
`bundle exec jekyll serve`  
5. ブラウザに表示する。  
`open 'http://localhost:4000'`
