# MCL-for-Probabilistic-Robotics-homework

# 左から右に行くモデル
![demo](https://github.com/dynepanch/MCL-for-Probabilistic-Robotics-homework/blob/main/gif/left_to_right.gif)
## 
初期姿勢
$$
x0=
\begin{pmatrix}
-3.5\\
0 \\
0
\end{pmatrix}
$$
に対し制御指令
$$
u=
\begin{pmatrix}
0.5\\
0
\end{pmatrix}
$$
を与えられた赤丸で示されたロボットに対し、100個のパーティクルで信念分布を近似する。
\\
点ランドマークは距離2、角度$&plusmn\frac{\pi}{3}$で観測し、尤度関数に反映する。

# 右に行った後に旋回して左に戻るモデル
![demo](https://github.com/dynepanch/MCL-for-Probabilistic-Robotics-homework/blob/main/gif/left_to_right_to_left.gif)

# １次元的表現
![demo](https://github.com/dynepanch/MCL-for-Probabilistic-Robotics-homework/blob/main/gif/line.gif)