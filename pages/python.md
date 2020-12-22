---
layout: page
title: Pythonプログラミング
permalink: /python/
---

## 環境設定など

* [環境設定]({% link _contents/python/devenv-setup.md %})

## 数独ソルバーを作る

ここでは数独の本を写真で撮影して、それを画像認識することで、自動的に数独を解くソルバーを作る。

<table class="images">
<tr>
  <td style="text-align: center; width: 50%;">{{ '**入力画像**' | markdownify }}</td>
  <td style="text-align: center; width: 50%;">{{ '**出力画像**' | markdownify }}</td>
</tr>
<tr>
  <td>{% include lightbox.html src="/public/images/sudoku/level_3_small.jpg" style="width: 100%;" %}</td>
  <td>{% include lightbox.html src="/public/images/sudoku/level_3_ans_small.jpg" style="width: 100%;" %}</td>
</tr>
</table>

* [バイナリデータの読み込み]({% link _contents/python/read-binary.md %})
* [ロジスティック回帰 -その1-]({% link _contents/python/logistic-regression-01.md %})
* [ロジスティック回帰 -その2-]({% link _contents/python/logistic-regression-02.md %})
* [画像中の図形検出]({% link _contents/python/figure-detection.md %})
* [数独を解く]({% link _contents/python/solve-sudoku.md %})
* [課題: 画像中の数独問題を解こう]({% link _contents/python/assignment-sudoku.md %})

## 深層学習による画像生成の基礎

ここでは敵対的生成ネットワーク (GAN) を利用して、Oxford flower datasetから、自然な花の画像を生成することを目指す。

<table class="images">
<tr>
  <td style="text-align: center; width: 50%;">{{ '**教師画像**' | markdownify }}</td>
  <td style="text-align: center; width: 50%;">{{ '**出力画像**' | markdownify }}</td>
</tr>
<tr>
  <td>{% include lightbox.html src="/public/images/gan/x_real_150.jpg" style="width: 100%;" %}</td>
  <td>{% include lightbox.html src="/public/images/gan/x_fake_150.jpg" style="width: 100%;" %}</td>
</tr>
</table>

* [畳み込みニューラルネット]({% link _contents/python/convolutional-network.md %})
* [敵対的生成ネットワーク(GAN)]({% link _contents/python/gan.md %})
* [条件付き画像生成 (CGAN)]({% link _contents/python/conditional-gan.md %})
* [GANの学習安定化テクニック]({% link _contents/python/stabilize-gan-training.md %})
* [課題: GANによる高品質画像生成コンテスト]({% link _contents/python/assignment-gan.md %})
