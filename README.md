# レコログ — 製品LP

iPhone アプリ「レコログ」（内部名 RecipeLog）の製品紹介ページ。GitHub Pages で公開する想定。

- 公開URL: https://shoheicraftdev-design.github.io/recipe-log-lp/ **公開済**（2026-08-24）
- App Store: **公開中**。`https://apps.apple.com/jp/app/レコログ/id6803313611`
- サポート / プライバシーポリシー / 利用規約: https://shoheicraftdev-design.github.io/recipe-log-support/

## 位置づけ

Sodato LP（`sodato-lp`）・GearDeban LP（`geardeban-lp`）・えも日LP（`emo-diary-lp`）と同じく、**匿名ライン（note・Xで製品名を出さない）を維持したまま
アプリ名とストアURLを出せるチャネル**。ASC のマーケティングURLに設定する想定。
サポート・法務ページは別リポジトリ `recipe-log-support` が持つ（ここには置かない）。

## 内容の版

**v1.0（2026-08-24 App Store 公開・build 2）に合わせて作成。** 参照: `recipe-log/docs/appstore/v1-store-listing.md`

## 素材

`images/` のスクリーンショットは、アプリ側リポジトリ `recipe-log` の
`docs/appstore/screenshots/6.5-inch/`（提出用・1284×2778）を長辺640pxへ縮小したもの。
差し替える場合は元の 1284×2778 から作り直すこと。`appicon.png` は
`RecipeLog/Assets.xcassets/AppIcon.appiconset/AppIcon-1024.png` の縮小（256px）。

| ファイル | 元 |
| :--- | :--- |
| `shot-timeline.png` | `01-timeline.png`（タイムライン） |
| `shot-rating.png` | `02-rating.png`（作った記録の採点・5軸＋総合★） |
| `shot-detail.png` | `03-detail.png`（レシピ詳細） |
| `shot-recipes.png` | `04-recipes.png`（マイレシピ一覧・カテゴリ単位） |

## 文言のルール（アプリ側 `docs/appstore/v1-store-listing.md` を継承）

- 総合★は「5軸の平均」ではなく「また作るかという独立した結論」——ここを曖昧にしない。
- 良し悪しが付くのは「料理名」ではなく「そのレシピ（参照先）」——同じ料理名でも別レシピとして扱われる点を混同しない。
- 本文・材料は書き写さない設計（参照はURLか写真のどちらか1つ＋自分のメモ）——「レシピを丸ごと保存できる」というような誤読を招く表現はしない。
- 解析・広告SDK・トラッキングは無い（申告は「データを収集しない」）。iCloud同期は開発者を含む第三者がアクセスできない旨も継承。
