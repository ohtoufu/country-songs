■サービス概要
このアプリケーションはユーザーが設定した「布団に入りたい時間」から逆算し
お風呂、またはシャワーを浴びるのに適した時間を通知するアプリです。
■このサービスへの思い・作りたい理由
入院した時シャワーやお風呂は予約制で、術後は介助がなければシャワーを浴びることもできませんでした。
その体験から好きな時にシャワーを浴びれるというのは幸せなことなんだと感じました。
退院後、友人と話していた時に「帰ってから家事やゲームをしていて気づいたら寝る時間になって朝シャワーを浴びてる」
という話を聞き入院時の話をしたところ、分かるが時間を忘れてしまうという話を聞きこのアプリの制作を考えました。

私自身、作業をして気がついたら寝ようと思っていた時間が過ぎていたという体験は何度もしているので
このサービスを通じて多くの人の生活を少しだけ豊かにできたらと思っています。

■ユーザー層について
このサービスは、帰宅後も家事や作業、趣味を行う時間をとりたいと思っている20代〜40代を主な対象としています。

入浴は眠る約２時間前、シャワーのみなら約90分前が適切な時間と言われていますが
忙しい日々の中、時間を気にして作業をするのはストレスを感じるでしょう。

このサービスでは、時計を気にして作業しなくとも良質な睡眠を少しだけサポートしたいと考えています。

■サービスの利用イメージ
1.布団に入りたい時間の選択
・トップページにて布団に入りたい時間を設定
・設定する時間は曜日ごとに設定するか一律で設定するか選択可能
2.入浴かシャワーかの選択
・時間を設定後、「お風呂」か「シャワー」どちらかの項目を選択
3.適切な入浴時間の表示
・設定した条件から適切な入力時間がブラウザ上に表示
・LINEを連携させると表示された時間に通知を送信

■ユーザーの獲得について
SNSを活用している年代がメインターゲット層のため主にX(旧Twitter)での宣伝が良いと考えています。

■サービスの差別化ポイント・推しポイント
ユーザーが自身で時間を設定するのではなく、睡眠の質が良くなると言われている
時間を「寝たい時間」から逆算して通知するというのがポイントです。

■機能候補
技術スタック

フロントエンド：HTML,CSS,JavaScript
バックエンド：Ruby on Rails
API：LINE Messaging API
MVPリリース時までに作っていたいもの：
1.ユーザーが布団に入りたい時間の登録機能。
・ユーザーが指定した時間をDBに保存
2.お風呂かシャワーか選択できる機能
・お風呂かシャワーの項目をアプリ側で用意し選択された情報をDBに保存
3.時間の計算機能
・ユーザーが設定した条件に基づき適切な時間を計算し、ブラウザ上に時間を表示
4.ユーザー管理機能
・LINE Messaging APIを使用してユーザー登録・ログイン
・登録した時間等の編集・削除
5.時間の通知機能
・ユーザー登録したユーザーにはLINEを使用して逆算された時間に入浴を促す通知を送信

本リリースまでに作りたいもの：
1.ユーザーの評価やフィードバック機能。

追加機能案
・パーソナライズドなアドバイス
　ユーザーが普段の入浴時間帯をアプリに登録して、それに基づいて推奨時間を調整する

■機能の実現構想
1.時間の逆算機能: ユーザーが登録した布団に入りたい時間から、お風呂やシャワーを浴びる適切な時間を計算したい。
2.ユーザー登録とログイン: ユーザーがアプリに登録し、ログインすることで予定を管理できるようにしたい。