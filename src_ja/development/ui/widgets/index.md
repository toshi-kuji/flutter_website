---
# title: Widget catalog
title: ウィジェットカタログ
# description: A catalog of some of Flutter's rich set of widgets.
description: Flutter の代表的なウィジェットをカテゴリー別に分けたカタログ。
# short-title: Widgets
short-title: ウィジェット
---

<!-- Create beautiful apps faster with Flutter's collection of visual, structural,
platform, and interactive widgets. In addition to browsing widgets by category,
you can also see all the widgets in the [widget index][]. -->
Flutter の多種多様なウィジェットを使って美しいアプリをスピーディに開発しましょう。
ビジュアル、構造、プラットフォーム、インタラクティブ性など、それぞれの目的に特化したウィジェットがそろっています。
こちらではカテゴリー別にウィジェットを閲覧することができます。
すべてを一覧で閲覧する場合は [ウィジェット目録][] をご利用ください。

<div class="card-deck card-deck--responsive">
{% assign categories = site.data.catalog.index | sort: 'name' -%}
{% for section in categories %}
    <div class="card">
        <div class="card-body">
            <a href="{{page.url}}{{section.id}}"><header class="card-title">{{section.name}}</header></a>
            <p class="card-text">{{section.description}}</p>
        </div>
        <div class="card-footer card-footer--transparent">
            <a href="{{page.url}}{{section.id}}">Visit</a>
        </div>
    </div>
{% endfor %}
</div>


[ウィジェット目録]: {{site.url}}/reference/widgets
