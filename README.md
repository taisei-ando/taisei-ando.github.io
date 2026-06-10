# Taisei Ando Personal Website

安藤大生の個人ページ用リポジトリです。Hugo Blox をベースにした、日英対応のアカデミックサイトです。

- Site: <https://taisei-ando.github.io/>
- Languages: English / Japanese
- Main sections: About, Publications, CV, News, Projects

## Stack

- Hugo `0.156.0`
- Hugo Blox
- Node.js `22`
- pnpm `10`
- Go `1.21+` (Hugo Modules 用)
- Netlify build configuration

## Local Development

前提:

- Hugo Extended
- Node.js
- pnpm
- Go

起動:

```bash
pnpm install
pnpm dev
```

ビルド:

```bash
pnpm build
```

ローカルサーバーは通常 `http://localhost:1313` で立ち上がります。

## Project Structure

```text
config/_default/         Hugo / Hugo Blox の設定
content/en/              英語コンテンツ
content/ja/              日本語コンテンツ
data/authors/            プロフィール情報
assets/media/            プロフィール画像やアイコン
layouts/                 テーマ上書き用のカスタムレイアウト
netlify.toml             Netlify のビルド設定
```

## Where To Edit

主に編集する場所:

- `data/authors/me.yaml`: 英語プロフィール
- `data/authors/me-ja.yaml`: 日本語プロフィール
- `content/en/_index.md`: 英語トップ
- `content/ja/_index.md`: 日本語トップ
- `content/en/publications/`, `content/ja/publications/`: 論文一覧
- `content/en/news/`, `content/ja/news/`: お知らせ
- `content/en/projects/`, `content/ja/projects/`: プロジェクト
- `content/en/cv.md`, `content/ja/cv.md`: CV
- `config/_default/menus.yaml`, `config/_default/menus.ja.yaml`: ナビゲーション

## Customization Notes

このリポジトリは Hugo Blox の素のテンプレートではなく、以下を個別調整しています。

- 日英 2 言語構成
- プロフィール情報の独自更新
- `layouts/` 配下でのブロック/パーシャル上書き
- Netlify 用ビルド設定

テンプレート更新時は、`layouts/` と `hugo-blox/` 配下の差分影響を先に確認した方が安全です。

## Deployment

Netlify でのビルド設定は [`netlify.toml`](/mnt/c/Users/taab7/workspace/taisei-ando.github.io/netlify.toml) にあります。公開 URL の既定値は [`config/_default/hugo.yaml`](/mnt/c/Users/taab7/workspace/taisei-ando.github.io/config/_default/hugo.yaml) で `https://taisei-ando.github.io/` に設定しています。

## License

サイト本文・業績情報・画像などの扱いは著作権者の意図を優先してください。コードベースのライセンスは [`LICENSE.md`](/mnt/c/Users/taab7/workspace/taisei-ando.github.io/LICENSE.md) を参照してください。
