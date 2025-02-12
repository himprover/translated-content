---
title: 非同期 JavaScript
slug: Learn/JavaScript/Asynchronous
---

{{LearnSidebar}}

このモジュールでは、{{Glossary("asynchronous")}} {{Glossary("JavaScript")}} に触れ、なぜそれが重要なのか、そして、潜在的なブロッキング処理（例えばサーバからリソースを取得する）に効果的に対処するためにどうやって使うのかを見ていきます。

> **注目:**
>
> #### フロントエンド Web 開発者を目指す方へ
>
> 目標に向かって頑張るために必要な情報をまとめたコースをご用意しました。
>
> [**Get started**](/ja/docs/Learn/Front-end_web_developer)

## 前提条件

非同期 JavaScript はとても高度なトピックなので、事前に [JavaScript の第一歩](/ja/docs/Learn/JavaScript/First_steps)と [JavaScript の構成要素](/ja/docs/Learn/JavaScript/Building_blocks)のモジュールに取り組んでおくことをおすすめします。

> **メモ:** ファイルを作成する手段のないコンピューター・タブレット・その他の端末をお使いの場合、（ほとんどの）コード例は [JSBin](https://jsbin.com/) や [Glitch](https://glitch.com) などのオンラインエディターでも試すことができます。

## ガイド

- [非同期 JavaScript の導入](/ja/docs/Learn/JavaScript/Asynchronous/Introducing)
  - : この記事では**同期**プログラミングと**非同期**プログラミングとは何か、なぜ頻繁に非同期のテクニックを使う必要があるのか、歴史的に非同期関数は JavaScript でどのように実装されてきたのか、そしてその問題点が何だったのかを見ていきます。
- [Promise の使い方](/ja/docs/Learn/JavaScript/Asynchronous/Promises)
  - : ここでは Promise を紹介し、Promise ベースの API の使い方をお見せします。`async` と `await` キーワードの紹介もここで行います。
- [Promise ベースの API の実装](/ja/docs/Learn/JavaScript/Asynchronous/Implementing_a_promise-based_API)
  - : この記事では独自の Promise ベースの API を実装する方法を概説します。
- [Worker の導入](/ja/docs/Learn/JavaScript/Asynchronous/Introducing_workers)
  - : Worker を使用すると、特定のタスクを別のスレッドで実行し、メインコードの応答性を維持することができます。この記事では、長時間実行される同期的な関数を Worker を使用して書き直します。

## 学習の評価

- [アニメーションを順番に再生する](/ja/docs/Learn/JavaScript/Asynchronous/Sequencing_animations)
  - : この評価では Promise を使用して一連のアニメーションを特定の順序で再生してください。

## 関連情報

- [Asynchronous Programming](https://eloquentjavascript.net/11_async.html) (Marijn Haverbeke 氏の非常に優れたオンライン書籍 [Eloquent JavaScript](https://eloquentjavascript.net/) より)
