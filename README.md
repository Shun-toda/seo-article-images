# seo-article-images

SEO記事生成システム共通の画像CDNリポジトリ。

`raw.githubusercontent.com` 経由で画像を配信し、Shopify / WordPress などの外部CMSにそのまま貼り付けられる形式に変換するために使用される。

## 使い方

`/md-to-html` スキル（`.claude/skills/md-to-html/`）が自動でアップロード・URL置換を行う。手動操作不要。

## ディレクトリ構成

```
article_<番号>/
├── h2/      H2見出し用インフォグラフィック
├── logo/    業者ロゴ
├── ss/      業者スクリーンショット
└── misc/    その他
```

商材ごとに分かれていないため、`article_<番号>` の番号は商材間で衝突する可能性がある。
スキル側で記事ファイル名と商材スラッグを組み合わせて衝突を回避している。
