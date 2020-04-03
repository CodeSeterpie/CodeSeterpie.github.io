---
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

## Kaggleスコア

<div align="center">

<img src="/assets/images/home/kaggle_score.jpg" width="800">

</div>

|日付|コンペ|スコア|順位|詳細|
|:---|:---|---:|---:|:---|
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

## Recent Posts

{% assign posts = site.posts %}

{% for post in posts limit:5 %}
  {% include archive-single.html %}
{% endfor %}


