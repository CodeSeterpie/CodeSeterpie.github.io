---
permalink: /about/
title: "CodeSeterpie(コードセタピー)とは"
---

![SocialPreview](/assets/images/SocialPreview/SocialPreview.jpeg)

このグループはSEの技術力・コミュニケーション力の醸成を目的に活動しています。  
今の具体的な活動は、Googleの子会社が運営するAIのコンペティションプラットフォーム『Kaggle（カグル）』に、素人ながらプライベートで参加しています。Kaggleへの参加は「データサイエンティストの技術力（知識と経験）の向上」と「新たな仲間づくり」を目的としています。

素人集団なので

* みんなで１つの目標に向かって

* みんなで勉強して

* みんなで解決します

## Menu
* [活動記録](https://codeseterpie.github.io/)  
  これまでに開催した会ごとのKaggleスコア、考察、課題等をまとめています。
* [環境構築](https://github.com/CodeSeterpie/CodeSeterpie/wiki/%E7%92%B0%E5%A2%83%E6%A7%8B%E7%AF%89)  
  実際にデータ分析を行うために必要なDocker、JupyterLabなどの実行環境の構築手順をまとめています。
* [Issues](https://github.com/CodeSeterpie/CodeSeterpie/issues)  
  課題、質問、やってみたい事はここから挙げてください。
* [Projects](https://github.com/CodeSeterpie/CodeSeterpie/projects)  
  現在の目標とそれに対する課題を管理しています。
* [Insights](https://github.com/CodeSeterpie/CodeSeterpie/pulse)  
  このGithubページの動き(commits、pull requests、issuesの更新状況のサマリー)を見ることができます。

## Docker(ドッカー)とは

Docker（ドッカー）とは、Docker, Inc.によって開発された非常に軽量なコンテナ型の仮想アプリケーション実行環境です。CUIで操作を行い、JupyterLabが動作する環境をDockerのコンテナ上に構築します。

下の利点からこのグループではDockerを使っています。
  * OSの種類(Windows、Mac、Linux)によらず、各自の端末に同じ実行環境を簡単に作ることができる。
  * 環境の切り替え・変更(ライブラリの追加等）が簡単にできる。
  * Dockerは仮想化の技術だが、Hypervisorを使った仮想化よりも、容量も軽量で動作も軽い。
  * IT業界で広く使われる技術であるため、知識が流用できる。

![docker_image](/assets/images/github/docker_image.jpg)

## JupyterLab(ジュピターラボ)とは

JupyterLab(ジュピターラボ)とはブラウザで動作するプログラムの対話型実行環境です。 ノートブックと呼ばれるドキュメントを作成し、プログラムの記述と実行、メモの作成、またそれらの保存などをブラウザ上で行うことができます。  

プログラムを編集して実行ボタンを押すだけで、数値やグラフを含んだ処理結果が表示されるので、データ分析処理を何度もすぐに試すことができます。また、保存したノートブックをGithubに上げることで、プログラムと処理結果を合わせて共有することができます。

![jupyter_image](/assets/images/github/jupyter_image.jpg)
