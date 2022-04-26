# 概要

ranmd9a が作成・修正したプログラムの一覧です。

- このページや wiki が Google 検索にのらないので(Search Console に登録しようとしてもうまく読み込まないし) note にも記載しています。  
  [https://note.com/ranmd9a/n/n3d23a653cd9f](https://note.com/ranmd9a/n/n3d23a653cd9f)

| 名前 | 説明 |
|---|---|
| [beatlist](https://github.com/ranmd9a/beatlist/releases/latest) | **2022年時点のbeatlist最新版。**<br>Alaanor 氏の作成した、PC上で動作するカスタム譜面・プレイリスト管理用ソフト。<br>現時点では Alaanor 氏版 beatlist が使えないので、動くように修正したもの。 |
| [BSCustomKeyEvents](https://github.com/ranmd9a/BSCustomKeyEvents/releases/latest) | **CustomSaberやCustomAvatarでVR用コントローラーのボタン押下に応じてなんらかのアクションを起こさせるための BeatSaber 用プラグイン。**<br>PureDark 氏作成のものを修正したもの。 |
| [SongStatus](https://github.com/ranmd9a/BeatSaber-SongStatus/releases/latest) | **曲の開始時に譜面情報をテキストファイルに出力する BeatSaber 用プラグイン。**<br>[xyonico氏](https://github.com/xyonico)、[OshiHidra氏](https://github.com/OshiHidra)作成のものを修正したもの。<br>OBS Studio で  UserData\songStatus.txt を「テキスト(GDI+)」で読み込むことでオーバーレイ表示します。<br>出力できる項目は少ないですが、プレイ開始・終了時しか動かないので HttpStatus より軽量かも？ |
| [BSPlaylistMaker](https://github.com/ranmd9a/BSPlaylistMaker/releases/latest) | **beatsaver.com で検索した結果を playlist に保存する Chrome 拡張機能。**<br>現在表示されている曲だけが対象になるので、検索結果すべてを対象にしたい場合は画面を下までスクロールして全曲表示する必要があります。<br>※検索結果が何件になるか事前に知る方法がないので、下手すると何万曲も対象になってChrome がメモリ不足で落ちる可能性があるためそのようにしています。<br>インストール手順は[こちら](https://github.com/ranmd9a/BSPlaylistMaker)。 |
| [favoritesToPlaylist](https://github.com/ranmd9a/favoritesToPlaylist) | BeatSaber用。<br>BeatSaber のゲーム内でお気に入りに入れた曲をプレイリスト化するスクリプト。<br>ゲーム内MOD の PlaylistManager で同様のことができるらしい(?)のであまり使う必要はないと思います。 |

※そのほかの repository は省略。

※fork したものばっかりですな。
