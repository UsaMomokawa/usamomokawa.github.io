---
title: "最初の投稿"
date: 2022-03-01T23:07:36+09:00
summary: "ブログを作成しました"
---

ブログを作成しました :rabbit:

## 構成

- Hugo
  - Theme は [PaperMod](https://git.io/hugopapermod)
- GitHub Pages
  - GitHub Actions で自動デプロイ

## 参考にしたもの

HugoのGetting Startedが便利でした!

- [Installing](https://gohugo.io/getting-started/installing)
- [Host on GitHub](https://gohugo.io/hosting-and-deployment/hosting-on-github/)

[hugoを使って爆速でブログを作成する](https://zenn.dev/harachan/articles/a043e9a756cae4) もおすすめです(同期の @harachan の記事です:smile:)

## Tips

`config.yml` で楽々カスタムできるんだな〜と学びました。便利。

- menu bar

```yml
menu:
  main:
    - identifier: archives
      name: archives
      url: /archives/
```

- emoji

```yml
enableEmoji: true
```

詳しくは [Configure Hugo](https://gohugo.io/getting-started/configuration/) や、使用しているテーマのDocsを参照してください。
