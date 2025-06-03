# 2章 オームの法則とキルヒホッフの法則

## 例題2-6 並列接続の場合の合成抵抗値

`example2-06-b.asc` は例題2-6の(b)をシミュレートするためのschematicです．実行結果は以下のようになります．

![/results/02/example2-06-b.png](/results/02/example2-06-b.png)
<p align="center"> Fig.2-1. example2-06-b.asc の実行結果 </p>

電圧が 6V で合計電流が 6A なので，合成抵抗値は 1Ω であることがわかります．

## 例題2-8 並列接続の場合の枝路電流値

`example2-08.asc` は例題2-8をシミュレートするためのschematicです．実行結果は以下のようになります．

![/results/02/example2-08.png](/results/02/example2-08.png)
<p align="center"> Fig.2-2. example2-08.asc の実行結果 </p>

分流の公式を使って求めた $I_{2}$ の値はこのシミュレーション結果（I(R2)）に一致していることがわかります．

## 例題2-10 直並列接続の場合の合成抵抗値

`example2-10-a.asc` は例題2-10(a)をシミュレートするためのschematicです．実行結果は以下のようになります．

![/results/02/example2-10-a.png](/results/02/example2-10-a.png)
<p align="center"> Fig.2-3. example2-10-a.asc の実行結果</p>

a点とb点の間の電圧が 3.2V で，a点からb点に流れる電流（I(R1)）が 1A なので，合成抵抗値は 3.2Ωであることがわかります．

同様に `example2-10-b.asc` は例題2-10(b)をシミュレートするためのschematicです．実行結果は以下のようになります．

![/results/02/example2-10-b.png](/results/02/example2-10-b.png)
<p align="center"> Fig.2-4. example2-10-b.asc の実行結果</p>

a点とb点の間の電圧が 5V で，a点からb点に流れる電流（I(R1) + I(R3)）が合計 2A なので，合成抵抗値は 2.5Ωであることがわかります．
