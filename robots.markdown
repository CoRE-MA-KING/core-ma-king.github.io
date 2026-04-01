---
layout: page
title: ロボット紹介
permalink: /robots/
background: '/assets/images/pic3.png'
---
<link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">


ここではこれまで製作したロボットを紹介します。
## 2026年大会
### アタッカー
RPコンテナの回収機構、自動射出機能、自動回避機能などいろいろな機能を盛り込みました。実際に大会でも有効に機能させて、競技的にも有利に進めることができました。特にRPコンテナの回収機構は大会でも唯一4個並べて設置してVPの獲得を達成し、戦術の幅を広げることができました。
![](/img/2026/attacker2.jpg){:class="responsive-image"}
### ストライダー
MAQUADという名前のオリジナル4脚です。ボールねじを使った直動減速機を用いて膝を駆動しているところが特徴です。  
大会では4/7のゾーンを踏破することができました。
![](/img/2026/strider3.jpg){:class="responsive-image"}
## 2025年大会
### アタッカー
内部装填機構を搭載し最大132枚のディスクを搭載可能。本番でも安定感のあるロボットでたくさんの撃破をすることができました。  
本番では機材トラブルによって使えませんでしたが、相手のダメージパネルの認識をして自動照準をするための機能を実装しました。
![](/img/2025/attacker.jpg){:class="responsive-image"}

### ストライダー
MEVIUSは東大の河原塚先生が開発した[オープンソース](https://haraduka.github.io/mevius-hardware/)の4脚ロボットです。MA-KINGでも公開されている資料をもとに製作しています。
競技用にハードウェアもアレンジを加えています。また学習部分は自分たちで行いました。
![](/img/2025/MEVIUS.png){:class="responsive-image"}

## MFT, 柏の葉ミニ大会まで
MFTに向けて製作し、柏の葉ミニ大会にも出場した機体です。
射出機構が2つになり、サスペンション周辺もリンクを組みなおすなどの改修が行われています。

![](/img/2025/kashiwanoha_event3.JPG){:class="responsive-image"}

メインボードをロボマス開発ボードから自作の基板にアップデートされています。
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">去年はロボマス開発ボードを使っていましたが、今年は自作のメインボードを作っています!<a href="https://twitter.com/hashtag/CoREjp?src=hash&amp;ref_src=twsrc%5Etfw">#CoREjp</a><a href="https://twitter.com/hashtag/CoREjp_MAKING?src=hash&amp;ref_src=twsrc%5Etfw">#CoREjp_MAKING</a> <a href="https://t.co/OcWuw9PXuZ">pic.twitter.com/OcWuw9PXuZ</a></p>&mdash; MA-KING (@ma_king_core) <a href="https://twitter.com/ma_king_core/status/1830595782854230249?ref_src=twsrc%5Etfw">September 2, 2024</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## 2024年大会
基本的には最低限の移動と射出機構・調整機構のみを持たせたロボットです。  

![](/img/2024/machine2.JPG){:class="responsive-image"}
<iframe width="100%" src="https://www.youtube.com/embed/g99aZ9_2WnY?si=asZpj99N2D4BiKRR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


サスペンションによって段差によるダメージを受けないようにしていました。
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">サスペンションのバネは直前までラジコン用を検討してましたが間に合わなかったのでポリカ板でなんちゃって板バネでやり過ごしました。<br>ディスクとか段差は乗り越えられたものの衝撃消しきれなくて映像系の接触不良トラブルにもなってしまった反省箇所。<a href="https://twitter.com/hashtag/CoREjp?src=hash&amp;ref_src=twsrc%5Etfw">#CoREjp</a><a href="https://twitter.com/hashtag/CoREjp_MAKING?src=hash&amp;ref_src=twsrc%5Etfw">#CoREjp_MAKING</a> <a href="https://t.co/rDvONOwwxx">pic.twitter.com/rDvONOwwxx</a></p>&mdash; じょわじ (@Atimsys) <a href="https://twitter.com/Atimsys/status/1771863501729878236?ref_src=twsrc%5Etfw">March 24, 2024</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

ベルトを使った方式の射出機構で連射性能も高いです。
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">CoRE1で射出機構の設計を担当しました<br>平ベルト2本の速度差をつけることで回転をかけて射出します。<br>発射機構は往復せず一方向に回すだけで高速連射できるのがちょっとした工夫です。<br>（装填可能枚数が少ないため連射すると一瞬で弾切れになるのが反省…）<a href="https://twitter.com/hashtag/CoREjp?src=hash&amp;ref_src=twsrc%5Etfw">#CoREjp</a><a href="https://twitter.com/hashtag/CoREjp_MAKING?src=hash&amp;ref_src=twsrc%5Etfw">#CoREjp_MAKING</a> <a href="https://t.co/YWeO6orTsQ">pic.twitter.com/YWeO6orTsQ</a></p>&mdash; Loop (@Infinite_Loop_) <a href="https://twitter.com/Infinite_Loop_/status/1771882282548412797?ref_src=twsrc%5Etfw">March 24, 2024</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

電装系はロボマス開発ボードとロボマスモータを基本とした構成です。主に既製品を利用していますが、一部細かい自作基板があります。
![](/img//2024/MA-KINGシステム構成図2024.jpg){:class="responsive-image"}

ロボットの制御はロボマス開発ボードのSTM32マイコンで基本的に行われています。コードは公開されてるので参考までにリンクを貼っておきます。  
[https://github.com/CoRE-MA-KING/RoboMasterDevBoard](https://github.com/CoRE-MA-KING/RoboMasterDevBoard)

実はJetsonを搭載しており、マイコンからロボットの状態を送って操縦者に機体情報が分かるようなUIを付けていました。またRealSenseの録画を行っており、次回の大会で自動照準機能などを実装できるような準備もしていました。
