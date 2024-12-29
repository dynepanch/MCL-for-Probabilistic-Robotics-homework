# MCL-for-Probabilistic-Robotics-homework

# 左から右に行くモデル
![demo](https://github.com/dynepanch/MCL-for-Probabilistic-Robotics-homework/blob/main/gif/left_to_right.gif)
## 
初期姿勢

$$
u=
\begin{pmatrix}
0.5\\
0
\end{pmatrix}
$$

に対して制御入力

$$
u=
\begin{pmatrix}
0.5\\
0
\end{pmatrix}
$$

を与えた赤丸で示される基準のロボットに対し、
パーティクルで信念分布を近似する。
パーティクルの位置と角度に指数分布に応じて、
ガウス分布に基づいた雑音を与え、また制御入力にバイアスを加えることにより誤差とする。
配置された３つの点ランドマークは距離２、角度&plusmn;60度の地点で観測され、パーティクルの尤度に影響をあたえる。
尤度は二次元のガウス分布によって定義され、複数のランドマークに対して導出された値を平均、正規化することで重みに変換する。
重みを基に系統サンプリングでパーティクルの更新を行うことにより信念分布の近似とする。

# 右に行った後に旋回して左に戻るモデル
![demo](https://github.com/dynepanch/MCL-for-Probabilistic-Robotics-homework/blob/main/gif/left_to_right_to_left.gif)

# １次元的表現
![demo](https://github.com/dynepanch/MCL-for-Probabilistic-Robotics-homework/blob/main/gif/line.gif)