# line-bot-trial-1
HEROKUとつないでFIXIEからproxieを持ってくる。

LINEの各ユーザー情報とFIXIE_URLは各自環境変数で設定

# 送られてきた文章をオウム返しするBOT
#今後の予定(多分やらない)
* しりとり管理(ひらがなオンリー)

* json使ってユーザー情報やテキストデータを保存してオウム返しではなくメッセージを送ったユーザー以外の他のユーザーにメッセージを送信

* 誰がどんな発言をしたかについてのDBも作成

* 上記のDBを用いてしりとりの順番の管理や,言葉の重複チェック,もちろんしりとりが成立しているかのチェックなどを実装
