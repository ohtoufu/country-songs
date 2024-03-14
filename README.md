■サービス概要
このアプリケーションは、ユーザーの気分に合わせてカントリーソングを検索、楽曲を再生するプラットフォームです。  
選択した気分に基づいて、YouTube や他の音楽ストリーミング サービスのリンクが提供されます。
■このサービスへの思い・作りたい理由
都会で育ち、故郷がないという経験から、カントリーソングの故郷を思う歌詞とメロディーに心を打たれました。  
しかし、周りにカントリーミュージックを共有できる人が少ないことに気をつけて、多くの人にこのジャンルの楽曲を紹介したいと思い、このサービスを制作したいと思いました。
■ユーザー層について
30代〜40代の年齢層を主な目標としています。仕事や家庭でのプレッシャーやストレスを感じやすく、心を癒すための穏やかな音楽が求められると考えています。
■サービスの利用イメージ
1.気分や感情の選択  
・トップページにて「今の気分は」ボタンをクリック  
・表示された気分や感情の選択肢から自分の気分や感情にあった項目を選択。  
項目は「楽しい」「悲しい」「怒り」などの選択肢があります。（多くても5つまで）  
2.曲調の選択  
・気分や感情の選択後、「明るい曲調」か「静かな曲調」のいずれかの選択  
3.楽曲の再生  
・選択された選択肢から検索された楽曲を、ブラウザ上でyoutube動画の再生  
■ユーザーの獲得について
SNSを活用している時代がメインターゲット層のため主にX(旧Twitter)での宣伝が良いと考えています。
■サービスの差別化ポイント・推しポイント
このアプリケーションの特徴は、カントリーミュージックに特化している点です。他の楽曲検索サービスとは異なり、カントリーソングのみを検索・再生することができます。  
さらにユーザーの気分や感情に基づいた楽曲検索機能を提供し、特定の気分や感情に合った楽曲を手軽に見つけることができます。
従来の音楽ストリーミングサービスとは異なり、よりパーソナライズされた音楽体験を、手軽に提供することができます。
■機能候補
技術スタック  
- フロントエンド：HTML,CSS,JavaScript  
- バックエンド：Ruby on Rails  
- API：YouTube APi,Spotify API,Apple Music API  

MVPリリース時までに作っていたいもの：  
1.気分や感情に基づいた楽曲検索機能。  
・キーワードやタグの生成：  
ユーザーが選択した項目に基づいて特定のキーワードやタグを生成  
例、「楽しい」を選択した場合「嬉しい」「楽しい」などのキーワード 
2.カントリーソングを検索できる機能。  
・外部音楽データベースとAPIの実装  
生成されたキーワードやタグを使用して外部音楽データベースやAPIを検索する関連楽曲を取得  
SpotifyのAPIなど  
3.楽曲再生機能。  
・検索情報をもとに関連するYouTube動画をランダムで１曲検索、取得してブラウザ上で再生  
4.楽曲情報の表示機能。  
返された検索結果に基づいて関連する楽曲を取得  
Spotify APIを使用することでタイトル・アーティスト名などの情報を取得  
5.外部サービスへのリンク機能。  
Spotify・App musicへのリンクを表示(主要な音楽ストリーミングサービスのリンク2つ)  
各音楽ストリーミングサービスのAPIを使用して、取得した情報をもとに該当する楽曲に直接リンクするURLを生成。  

本リリースまでに作りたいもの：  
1.ユーザーの評価やフィードバック機能。  

追加機能案
・SNSでシェアできる楽曲の共有機能  
・
■機能の実現構想
1.楽曲検索機能。楽曲データベースや外部の音楽API(youtubeまたはspotify)を利用して楽曲情報を取得し検索機能に組み込みたい。  
2.ユーザーの感情分析機能。アプリケーション側で用意した選択肢から楽曲を選択したい。