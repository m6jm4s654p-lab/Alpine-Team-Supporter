# v1.0.2

- Manager v0.13.57の .txt データ更新ファイル取り込みに対応。従来の .atsdata / .json も引き続き取り込み可能。

# Alpine Team Supporter v1.0.0

閲覧専用PWAです。

## 閲覧機能
1. 予定表
2. 選手一覧
3. チームランキング
4. 会場情報
5. 天気・積雪
6. レース速報

## データ更新
Alpine Team Manager v0.13.56以降で作成した `.atsdata` ファイルを取り込みます。データはSupporter利用者の端末内（localStorage）へ保存されます。サーバーには保存しません。

対応ブラウザではPWAの file_handlers により .atsdata タップからSupporter起動を試行できます。非対応端末では画面上の「データ更新ファイルを取り込む」を使用してください。
