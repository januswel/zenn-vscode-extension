---
title: "ローカル画像を表示するテスト"
emoji: "🪐"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: []
published: true
---

## 正しい指定

`![](/images/example-images/zenn-editor.png)`

![](/images/example-images/zenn-editor.png)

`![](/images/example-images/zenn-editor.webp)`

![](/images/example-images/zenn-editor.webp)

## 存在しないパス

`![](/images/example-images/not-exist.png)`

![](/images/example-images/not-exist.png)

## 誤った指定（相対パス）

`![](../images/example-images/zenn-editor.png)`

![](../images/example-images/zenn-editor.png)

## 対応していない拡張子

`![](/images/example-images/zenn-editor.svg)`

![](/images/example-images/zenn-editor.svg)

## URL を指定

`![](http://placehold.jp/54/e3f2ff/000000/720x480.png?text=zenn-editor.png)`

![](http://placehold.jp/54/e3f2ff/000000/720x480.png?text=zenn-editor.png)

## 同一画像の連続表示

```md
![1st](/images/example-images/zenn-editor.png)
![2nd](/images/example-images/zenn-editor.png)
```

![1st](/images/example-images/zenn-editor.png)

![2nd](/images/example-images/zenn-editor.png)

## 不同画像の連続表示

```md
![1st](/images/example-images/zenn-editor.png)
![2nd](/images/example-images/zenn-icon.png)
```

![1st](/images/example-images/zenn-editor.png)

![2nd](/images/example-images/zenn-icon.png)
