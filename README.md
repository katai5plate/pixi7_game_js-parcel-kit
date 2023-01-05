# はじめかた

1. Node.js と VSCode と VSCode 拡張の Prettier を入れる
2. ターミナルを開く
3. `npm i` する
4. `npm run dev` すると `http://localhost:1234` にプレビューされる
5. src 内のファイルを編集しながらゲームを作る

## ゲームをデプロイする

1. ターミナルを開く
2. `npm run build` する
3. `dist` フォルダに出力されるので、それを公開する

## スマホでテストプレイする

1. ipconfig コマンド等で、現在接続しているルータからのローカル IP アドレスを調べる（ `192.168.X.X` など）
2. スマホで同じルータに Wifi 接続する
3. 1 で調べた IP アドレスのポート 1234 をスマホのブラウザで開く（ `192.168.0.5` なら `http://192.168.0.5:1234` を開く）

## 元プロジェクト

https://github.com/hothukurou/pixi_game_js
https://hothukurou.com/blog/post-2058
