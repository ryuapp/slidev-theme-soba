---
theme: ./

---

# Slidevテーマ soba

開発者のためのプレゼンテーションスライド

<div class="pt-12">
  <span @click="next" class="px-2 p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10">
    スペースで次のページ <carbon:arrow-right class="inline"/>
  </span>
</div>

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

# ナビゲーション

左下にカーソルを合わせると、ナビゲーションのコントロールパネルが表示されます

### キーボードのショートカット

|     |     |
| --- | --- |
| <kbd>スペース</kbd> / <kbd>タブ</kbd> / <kbd>→</kbd> | 次のアニメーションかスライドへ |
| <kbd>←</kbd> / <kbd>シフト</kbd> <kbd>スペース</kbd> | 前のアニメーションかスライドへ |
| <kbd>↑</kbd> |	前のスライドへ |
| <kbd>↓</kbd> | 次のスライドへ |

---
layout: image-right
image: 'https://source.unsplash.com/collection/94734566/1920x1080'
---

# Code

コードスニペットを利用することで、ハイライトをダイレクトに行なえます

```ts
interface User {
  id: number
  firstName: string
  lastName: string
  role: string
}

function updateUser(id: number, update: Partial<User>) {
  const user = getUser(id)
  const newUser = { ...user, ...update }
  saveUser(id, newUser)
}
```

---
layout: center
class: "text-center"
---

# もっと知りたい人は

[ドキュメント](https://sli.dev) / [ドキュメント(日本語)](https://ja.sli.dev) / [GitHubレポジトリ](https://github.com/slidevjs/slidev)
