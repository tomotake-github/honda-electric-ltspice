# 3章 直流の電力と電力量

## 例題3-4 電源の固有電力

`example3-04.asc` は例題3-4をシミュレートするためのschematicです．負荷抵抗 RL の抵抗値を 1Ω から 500Ω まで変化させる設定になっています．実行すると，負荷抵抗で消費される電力 (V(a)*I(Rl))は `/results/03/example3-04.txt` のようになります．以下は実行結果のグラフです．

![results/03/example3-04.png](/results/03/example3-04.png)
<p align="center"> Fig.3-1. example3-04.asc の実行結果 </p>

負荷で消費される電力は抵抗値が $R_{L} = 100\Omega (= R_{s})$ で最大値 25W を取っています．
