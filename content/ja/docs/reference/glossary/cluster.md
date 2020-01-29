---
title: クラスター
id: cluster
date: 2019-06-15
full_link: 
short_description: >

   Kubernetesが管理するコンテナ化されたアプリケーションを実行する、ノードと呼ばれるマシンの集合です。クラスターには、少なくとも1つのワーカーノードと少なくとも1つのマスターノードがあります。

aka: 
tags:
- fundamental
- operation
---
Kubernetesが管理するコンテナ化されたアプリケーションを実行する、ノードと呼ばれるマシンの集合です。クラスターには、少なくとも1つのワーカーノードと少なくとも1つのマスターノードがあります。

<!--more-->
ワーカーノードは、アプリケーションのコンポーネントであるPodをホストします。マスターノードは、クラスター内のワーカーノードとPodを管理します。複数のマスターノードを使用して、クラスターにフェイルオーバーと高可用性を提供します。