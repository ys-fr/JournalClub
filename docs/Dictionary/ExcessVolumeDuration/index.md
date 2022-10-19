# Excess Volume duration

Excess Volume durationとは、取引量 (約定量) をベースに決定する時間のことを指す。この指標は、Volume durationとは異なり、signed volumeを用いて定義される; この指標を定量的に定義するために、ある市場における取引単位 (lot size) を$\mathcal{\kappa}$, 任意の定数 $n$, volume durationで定義される時刻$i$に対応する実時刻 (physical time)を$t_i$, $V_b(t)$ を時刻 $t$ までに取引された買い注文量、$V_a(t)$ を時刻 $t$ までに取引された売り注文量と定義しよう。price durationによって定義される時刻は、下記のように定式化される:

$$
A:=\left\{ t \big|\left|\left\{ V_a\left(t\right) - V_b\left(t\right)\right\} -\left\{  V_a\left(t_{i}\right) - V_b\left(t_{i}\right) \right\}\right| \geq n\mathcal{\kappa}, t>t_i\right\}\\
t_{i+1} := \min A.
$$

このVolume durationはsigned volumeの捉えることができる。

## 個人的なコメント
そもそもorder signは長期記憶過程なので、excess volume duration で定義される時刻は非独立では?