# Price duration

Price durationとは、価格変動をベースに決定する時間のことを指す。例えば、一単位の価格変動をサンプリングバンドとする tick time はその代表例である。ここで、price duration を定量的に定義するために、ある市場における価格幅 (tick size) を$\mathcal{\theta}$, $n$ を任意の定数, $t_i$ をprice durationで定義される時刻$i$に対応する実時刻 (physical time), $p(t)$ を時刻 $t$ における価格と定義しよう。price durationによって定義される時刻は、下記のように定式化される:

$$
A:=\left\{ t \big|\left|p\left(t\right)-p\left(t_{i}\right)\right| \geq n\mathcal{\theta}, t>t_i\right\}\\
t_{i+1} := \min A.
$$

特に$n=1$の場合、tick time (ティック時間) と呼ばれる。