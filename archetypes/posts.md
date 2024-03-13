+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
description = ''
categories = 'news or blog'
tags = ['']
author = ['']
+++

## 注釈
### フロントマターの書き方
- `title`には記事のタイトルを記述する
- `description`には記事の説明を記述する
- `categories`にはnewsかblogか記入する
- `author`には記事を書いた人を記述する
- `tags`には適切なタグを設定する

### 記事の注意事項
- 記事自体はMarkdown形式で記述する
- 見出しは`##`から始める
- 写真やその他のファイルは`index.md`と同じフォルダに格納する
