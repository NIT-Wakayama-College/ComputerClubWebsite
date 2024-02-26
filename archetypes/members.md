+++
title = 'NAME' # NAMEにフルネームを記入
date = {{ .Date }}
categories = 'member'
members-tags = ['20XX年入学', 'XXXX学科', '第X回ゆめくじら', 'XX部門'] # 入学年、学科、所属等を入力
tags = [''] # 自分の得意分野などのキーワードを入力
author = ['20YYG-NAME'] # 2022B-KashiuchiSotaroのように入力
+++

## 基本情報
- 名前:NAME()
- ニックネーム: NICNAME
- 所属学科:{{< taxonomies_link "members-tags" "XXXX学科" >}}
- 入学年度:{{< taxonomies_link "members-tags" "20XX年入学" >}}
- 役職/所属:{{< taxonomies_link "members-tags" "第X回ゆめくじら" >}}, {{< taxonomies_link "members-tags" "XX部門" >}}
- keyword:{{< taxonomies_link "tags" "" >}}

## 活動内容

| 日付 | 活動内容 |
|---|---|
| YYYY/MM | 内容 |
