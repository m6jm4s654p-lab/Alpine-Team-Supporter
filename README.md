# Alpine Team Supporter v1.1.0

閲覧専用PWAです。

## 閲覧機能
1. 年間スケジュール（4〜9月／10〜3月）
2. 大会一覧
3. 選手一覧（全国ランク SL・GS・SG表示）
4. レース速報

## データ更新
Alpine Team Manager v0.13.56以降で作成した `.atsdata` ファイルを取り込みます。データはSupporter利用者の端末内（localStorage）へ保存されます。サーバーには保存しません。

対応ブラウザではPWAの file_handlers により .atsdata タップからSupporter起動を試行できます。非対応端末では画面上の「データ更新ファイルを取り込む」を使用してください。

## v1.0.1
- Alpine Team Supporter表記へ統一
- Supporter専用のグリーン系カラーへ変更
- Supporter専用アイコン・ロゴへ変更
- 画面構成と機能はv1.0.0から変更なし

## v1.1.0
- 閲覧画面を4機能へ再構成
- 年間スケジュールを6か月単位で表示
- 選手氏名行に全国ランク SL・GS・SGを表示
