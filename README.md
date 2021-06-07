# リポジトリ名
Yahoo Shopping Scraping

## Dependency
requirements

## Usage
1.   スクレイピングする際は#で囲まれた部分をチェック
  *   キーワード(KEYWD)の変更
  *抽出するページ数(PAGE)の変更
  *   抽出する要素(ELE)の変更
  *   ELEのタグ(ELE_TAG)の変更 -> 商品ページのHTMLをチェック
  *   商品情報ページのタグ(DESC_LIST)の変更 ->リンク先のHTMLをチェック
  *   get_elements関数の変更 -> 商品ページのHTMLをチェック
2.   ランタイム→全てのセルを実行
3.   ドライブのマウント(URLに飛んでパスワードを入力)


## Attention
* 商品情報を手に入れるにはその商品のリンクに飛ぶ必要があるが商品によって遷移先が異なるため，適宜DESC_LISTを更新すること．



##References
* CSSセレクタ : https://gammasoft.jp/support/css-selector-for-python-web-scraping/


