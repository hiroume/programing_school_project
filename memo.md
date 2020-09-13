## メモを追記していきます

###  目標　bootstrapを利用して、イケてるウェブアプリを作成できる

習得手順
* rails new　して『yay on rails』の画面にまでたどりりついてもらう
  
  * 基本のビュー骨組みを提供（scaffoldで十分かも）
* webpackerを導入してもらう
  * webpackerとがどんなものか
  * 既存の何に置き換わっているのか？
  * railsとはどの様に進化していくのか？についても触れたい
* bootstrapテンプレートを導入してもらう
  * 最初はフルサポート？？
  * テキストベースで大丈夫そう？？
* bootstrapテンプレートの中身と、ブラウザ上での動作・要素を確認して勘所をつかんでもらう
* 自作でコンポーネントを作成できる様に教育する
  * [マテリアルデザイン for Bootstrapでサクサク作れる様に練習してもらう](https://fezvrasta.github.io/bootstrap-material-design/)
  * [[Rails6.0] Rails6 + yarn + webpacker でMaterial Design for Bootstrapを導入する](https://qiita.com/sasakura_870/items/38e17d95d9497cf81413)
  * JSのフレームワークを導入させる？？
  *
  
  
##  なんでもメモ
[こちらを参考にしました](https://www.sejuku.net/blog/68146)
[ディレクトリ構造・特定のファイルにのみ読み込ませる方法など](https://noknow.info/it/ruby/rails/how_to_use_webpacker?lang=ja#sec1)
* app/jacvascript配下に他のjsを管理するためのjavascriptsディレクトリを作成
  * その中に適用したいjsを定義する
  * さらに読み込むためのjsファイルを定義する
* app/javascript/stylesheets配下に読み込ませたいcssファイルを定義する
* app/javascript/packs/application.js内部で先ほどのcssファイルをimportする
* cssの呼び出しタグも忘れず定義する　<%= stylesheet_pack_tag 'application'%>



##  気づきメモ
* 全てのページに適用する場合は『packs/application.js』ないにて『import '../js/application'』とする様だ
* 逆にピンポイントなページに読み込ませたい場合には


##  疑問点メモ
* 個別のビューに個別のスタイルがあてたい場合、個別のscriptがあてたい場合どうすれば良いか
