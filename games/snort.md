---
layout: default
title: Snort
---
# Snort
グラフ上の節点を塗り分けるゲーム

- 手番時に塗ることができる節点がないプレイヤの負けとなる
- 塗ることができる節点
  - その節点が無色（塗られていない）
  - 隣接する節点は全て, 無色か自色
    - 一つでも自色以外で塗られている節点と隣接している場合塗ることが出来ない

- 2018年度MCTS輪講の実装題材
  - 1次元配列（path-graph）上での実装

## リンク
- [Wikipedia](https://en.wikipedia.org/wiki/Col_(game)) 
