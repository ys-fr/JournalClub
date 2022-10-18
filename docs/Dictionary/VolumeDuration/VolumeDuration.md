# Volume duration

Volume durationとは、取引量 (約定量) をベースに決定する時間のことを指す。この指標を定量的に定義するために、ある市場における取引単位 (lot size) を$\mathcal{\kappa}$, 任意の定数 $n$, volume durationで定義される時刻$i$に対応する実時刻 (physical time)を$t_i$, $V(t)$ を時刻 $t$ までに取引された注文量と定義しよう。price durationによって定義される時刻は、下記のように定式化される:

$$
A:=\left\{ t \big|\left|V\left(t\right)-V\left(t_{i}\right)\right| \geq n\mathcal{\kappa}, t>t_i\right\}\\
t_{i+1} := \min A.
$$

このVolume durationは注文量のintensityとして捉えることができる。