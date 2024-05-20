# 🥰 Futurealize with Tech
略称は【FwT】

## 🤩 概要
卒業メンターにメッセージを共有できるサービス！！
<br/>
ライフイズテックの卒業メンバーの[のぞみ](https://twitter.com/lit_n59)・[さっきー](https://twitter.com/am2525nyan)・[うしょう](https://twitter.com/usyou081)・[いのれん](https://twitter.com/inoren_lit)が作成してます。

## ⚒️ 使用した技術

- `Next.js` 14.0.4
- `TypeScript`
- `SCSS` (スタイリング)
- `Supabase` (バックエンド)
- `Prisma` (ORM)
- `framer-motion` （アニメーション）

## 🌐 デプロイ
`Vercel`

## 📁 リポジトリ
FwTのリポジトリを紹介します

- [fwt](https://github.com/Futurealize-with-Tech/fwt)：メッセージを集めるサイトのコード
- [fwt-mentor](https://github.com/Futurealize-with-Tech/fwt-mentor)：卒業メンターさんがメッセージを集めるためのサイトのコード
- [fwt-api](https://github.com/Futurealize-with-Tech/fwt-api)：FwTのデータを操作するAPIのコード
- [route-page](https://github.com/Futurealize-with-Tech/route-page)：卒業メンターさんにバレないようにサイトを広めるためのサイトのコード
- [.github](https://github.com/Futurealize-with-Tech/.github)：GitHubのリポジトリテンプレートやコーディングにおけるルールなどを記述

## ⚙️ 環境変数
使っている環境変数は`Supabase`で使う以下の二つです。
<br/>
デプロイする際には、環境変数に以下のものを指定しないとプロジェクトが機能しません。

- NEXT_PUBLIC_SUPABASE_URL
- NEXT_PUBLIC_SUPABASE_ANON_KEY
