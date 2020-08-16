# YoutubeLiveをめっちゃ便利にするツール ver 0.2

このツールはYoutubeLiveを楽にするための機能を詰め込んだサポートツールです。

主に以下の機能があります。

- 以前開いていた配信にすぐ戻れる機能
- スーパーチャット一覧表示機能
- スーパーチャットに既読確認マークが付けられる機能

また、以下の機能を予定しています。

- YoutubeLiveのチャット欄を固定のURLで表示できる機能
- コメント読み上げ機能
- 配信の予定時間が近づいたら通知する機能
- プラグイン機能

## インストール方法
1. [リリースページ](https://github.com/happou31/YoutubeLiveApp/releases)から最新版の zip をダウンロードして解凍する
2. 終わり

## 使い方
1. Youtubeにログインする  
ブラウザ上と同じようにログインしてください。  
2段階認証を使っている場合は「Google認証アプリ」を使う方法を選んでください。  
スマホの通知をタップする方法は現在動きません…(原因調査中)
2. ダッシュボードが開くので、そこから配信を作ったり、既に立っている配信管理ページを開く　
3. *スパチャ一覧表示は、現在配信管理画面に飛ぶと自動的に開くウインドウの「ツール」から開くことが出来ます。どう考えても不便なので、配信管理画面のウインドウからも飛べるようにしたいと思っています*

##### *詳しい解説は現在準備中…*

## アンインストール方法
1. フォルダを丸ごと削除する
2. Win+R を押して %appdata% と入力する
3. youtube_live というフォルダを削除する
4. (なんか他にあったら教えて)

## for Developers

### Require

- Node.js >= 12.13.1
- yarn(recommended)

## Develop

1. Package install
```
$ yarn
```

2. Develop build start
```bash
$ yarn dev
```

3. Start debug
```
$ yarn start
```

## Build

### for Windows x86 or x86_64
```powershell
> yarn build:win
```

### for Others

_Work in progress_

Maybe will implement soon...
Or You can pull request me 😀
