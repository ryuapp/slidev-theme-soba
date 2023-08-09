---
theme: ./
showPageCount: true
disablePageCount: [1,7,9,11]
themeConfig:
  primary: '#39b54a'
htmlAttrs:
  lang: 'ja'
---

# Slidevテーマ Soba

日本語向けのシンプルなテーマ

---
layout: profile
profileImage: https://img.ryu.app/logo/ryuapp.svg
---

# Ryu
フロントエンド開発者
- [Portfolio](https://www.ryu.app)
- [GitHub](https://github.com/ryuapp/)

---

# Sobaとは？
日本語向けのシンプルな[Slidev](https://github.com/slidevjs/slidev)のスライドテーマです

マークダウンでのスライド作成に集中出来るように  
「**見やすさ**」と「__手軽さ__」を重視した細かい調整を行なっています  
<br>
## 調整内容
1. 日本語フォントの使用
    - 日本語 ⇒ [Noto Sans JP](https://fonts.google.com/noto/specimen/Noto+Sans+JP)
    - アルファベットや記号 ⇒ [Poppins](https://fonts.google.com/specimen/Poppins)
2. 文字の大きさ、太さ、間隔


---

# Slidevとは？

Slidevはスライド作成ツールであり、開発者向けに設計されたプレゼンテーションツールです  
次のような機能を備えています

- 📝 **テキストベース** - マークダウンでコンテンツに集中し、スタイルを整えられる
- 🎨 **テーマの切り替え** - npm を通じてテーマを共有できる
- 🧑‍💻 **開発者フレンドリー** - コードハイライト、オートコンプリートによるライブコーディングができる
- 🤹 **インタラクティブ** - Vue コンポーネントを埋め込んで表現を強化できる
- 🎥 **録画・撮影** -  録画機能とカメラビューがあります
- 📤 **便利** - PDF、PNG、またはホスティング可能な SPA で出力できる
- 🛠 **カスタマイズ** - Webページで出来る事は何でもできる

<br>
<br>

もっと知りたい人は [なぜSlidev？](https://ja.sli.dev/guide/why.html)

---
layout: section
---

# Section
最初のセクション

---
layout: center
---

# Center
中央揃え

---
layout: quote
---

# Quote
<blockquote>
  <p>
  深淵を覗く時<br />
  深淵もまたこちらを覗いているのだ
  </p>
<footer>ニーチェ</footer>
</blockquote>

---
layout: image-right
image: /soba.jpg
---

# Image-right
右に画像
---
layout: image-left
image: /soba.jpg
---

# Image-left
左に画像

---
layout: image
image: /soba.jpg
---

# Image
全面に画像

---

# Code
コードスニペットを利用することで、ハイライトを簡単に実装出来ます
```ts {|4|6-8|}
// main.ts
import { Hono } from 'hono'

const app = new Hono()

app.get('/', (c) => {
  return c.text('Hello Hono!')
})

export default app
```

---
layout: end
---

# おわり
