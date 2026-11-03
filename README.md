# games

自作ゲームの公開場所(GitHub Pages)。ゲームごとにフォルダを分ける。一覧は https://40kuro.github.io/games/

| フォルダ | ゲーム | URL |
|---|---|---|
| `hairo/` | 灰狼(SRPG・全18章の試作、PWA) | https://40kuro.github.io/games/hairo/ |

ここに置くのは組み立て結果だけ。元のファイルは非公開のリポジトリにあり、`engine/build.py` → `engine/build_pwa.py` で作った `dist/pwa/` の中身を各フォルダに置いている。
ブラウザで開いて「ホーム画面に追加」するとアプリとして起動でき、一度開けば電波がなくても遊べる。セーブは端末のブラウザ内のみ(同じ 40kuro.github.io の中なので、フォルダを移しても引き継がれる)。
