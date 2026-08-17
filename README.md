# recruit-site

S'UIMIN 採用HP。GitHub Pages で https://recruit.suimin.co.jp/ に公開。

## 構成

- `index.html` — エンジニア職の求人（本体。文章・スタイル・スクリプトを1ファイルに集約）
- `assets/img/` — 画像（index.html から相対パスで参照）
- `others/index.html` — エンジニア職以外の求人（準備中ページ）

## 更新の流れ

- main は保護されているため直接 push はできません。ブランチを作成し PR → マージで自動反映されます。
- メンバー紹介の原稿は index.html 末尾の `#pf-0`〜`#pf-2` ブロックが唯一の編集箇所です。モーダル表示はそこから内容を読み込みます。

## 公開前のTODO

- `<meta name="robots" content="noindex">` の削除（index.html 冒頭）
- Search Console への登録
