---
layout: splash
permalink: /
header:
  overlay_color: "#2b2b2b"
  overlay_image: /assets/images/icon/homeimage.jpeg
  actions:
    - label: "<i class='fab fa-fw fa-github'></i> GitHub"
      url: "https://github.com/CodeSeterpie/CodeSeterpie"
excerpt: >
  SEの技術力・コミュニケーション力の醸成を目的に活動しているグループです。今の具体的な活動は、Googleの子会社が運営するAIのコンペティションプラットフォーム『Kaggle（カグル）』に、素人ながらプライベートで参加しています。
---

<img src="/assets/images/home/kaggle_score.jpg" width="800">

|日付|コンペ|スコア|順位|詳細|
|:---|:---|---:|---:|:---|
|2020/04/04|-|-|-|-|
|2020/03/28|House Prices|**0.13149**|1554|[活動記録 2020/03/28](https://codeseterpie.github.io/blog/report_20200328/)|
|2020/03/21|House Prices|**0.13250**|1605|[活動記録 2020/03/21](https://codeseterpie.github.io/blog/report_20200321/)|
|2020/03/14|House Prices|0.13524|1986|[活動記録 2020/03/14](https://codeseterpie.github.io/blog/report_20200314/)|
|2020/03/07|House Prices|0.13524|1986|[活動記録 2020/03/07](https://codeseterpie.github.io/blog/report_20200307/)|
|2020/02/29|House Prices|**0.13524**|1986|[活動記録 2020/02/29](https://codeseterpie.github.io/blog/report_20200229/)|
|2020/02/22|House Prices|0.13573|2374|[活動記録 2020/02/22](https://codeseterpie.github.io/blog/report_20200222/)|
|2020/02/15|House Prices|**0.13573**|2374|[活動記録 2020/02/15](https://codeseterpie.github.io/blog/report_20200215/)|
|2020/02/08|House Prices|**0.13815**|2567|[活動記録 2020/02/08](https://codeseterpie.github.io/blog/report_20200208/)|
|2020/02/01|House Prices|**0.22697**|4336|[活動記録 2020/02/01](https://codeseterpie.github.io/blog/report_20200201/)|
|2020/01/25|House Prices|0.24105|-|[活動記録 2020/01/25](https://codeseterpie.github.io/blog/report_20200125/)|
|2020/01/18|House Prices|**0.23934**|4587|[活動記録 2020/01/18](https://codeseterpie.github.io/blog/report_20200118/)|
|2020/01/11|House Prices|0.25883|4760|[活動記録 2020/01/11](https://codeseterpie.github.io/blog/report_20200111/)|

※太字は前回より良くなったスコア

{{ content }}

<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% if paginator %}
  {% assign posts = paginator.posts %}
{% else %}
  {% assign posts = site.posts %}
{% endif %}

{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}

#### House Pricesのスコア
House Pricesのスコアは下の数式の通り、真の値と予測値のlogをとった値のRMSE(Root Mean Squared Error:平均平方二乗誤差)の評価指標で計算されます。

<img src="/assets/images/github/%E8%A9%95%E4%BE%A1%E6%8C%87%E6%A8%99_HousePrices.jpg" width="500">

