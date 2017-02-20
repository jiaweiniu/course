## 画像信号処理１５回目　レポート２:
西田研究室
学籍番号
——————————————————————————————————————————————

画像の周波数領域に、低周波数部分はデータ変化緩やかの部分で、高周波数部分はデータ変化激しい部分です.
従って、低周波数のカットによるエッジ抽出が可能です.

——————————————————————————————————————————————

#### 実行結果:

> **元画像:**

![](git_avatar.png)

> **50％の低周波数カット結果:**

![](git_avatar_edge.png)

> **比べとして: 3x3 laplacianフィルターの結果:**

![](git_avatar_edge_2.png)

——————————————————————————————————————————————

#### 考察：
低周波数カットによるエッジ抽出はもっと細部を保留できますか、ノイズも酷い.
ノイズ除去フィルターと組み合わせて使えば、もっといい効果を得れるかもしれません.