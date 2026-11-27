# ベンザイテンシステム オプション分析（参考・判定には使いません）

取得 日本時間 2026-11-27 19:36（米国 11/27 05:36）・銘柄 SMH SOXX SOXL SOXS QQQ TQQQ SQQQ

## 結論の一覧

<table>
<thead><tr><th nowrap>銘柄</th><th nowrap>建玉の偏り</th><th nowrap>σ（前日比）</th></tr></thead>
<tbody>
<tr><td nowrap>SMH＊<br>422.46</td><td nowrap>いつも並み</td><td nowrap>コール 0.4σ<br>前日→コール0.9σ</td></tr>
<tr><td nowrap>SOXX＊<br>127.98</td><td nowrap>ほぼ半々</td><td nowrap>記録待ち</td></tr>
<tr><td nowrap>SOXL＊<br>32.02</td><td nowrap>ほぼ半々</td><td nowrap>記録待ち</td></tr>
<tr><td nowrap>SOXS＊<br>62.13</td><td nowrap>コールが多い</td><td nowrap>記録待ち</td></tr>
<tr><td nowrap>QQQ＊<br>633.93</td><td nowrap>いつも並み</td><td nowrap>コール 0.8σ<br>前日 動きなし</td></tr>
<tr><td nowrap>TQQQ＊<br>45.28</td><td nowrap>コールが多い</td><td nowrap>記録待ち</td></tr>
<tr><td nowrap>SQQQ＊<br>49.60</td><td nowrap>コールが多い</td><td nowrap>記録待ち</td></tr>
</tbody>
</table>

＊ 今の板が崩れているため、同じ取引日の前回の有効な実行（日本時間 11/27 12:46）の結果。

## 大口の賭け（ヘッジファンドなどの大口の向き・推定）

<table>
<thead><tr><th nowrap>銘柄・向き・強さ</th><th nowrap>主な賭け</th></tr></thead>
<tbody>
<tr><td nowrap><b>SMH＊</b> 原指数<br>ベア 🐻 大</td><td nowrap>1/15 350P買 $24M<br>2/19 350P買 $24M</td></tr>
<tr><td nowrap><b>SOXX＊</b> 原指数<br>ベア 🐻 中</td><td nowrap>3/19 130P売 $9.0M<br>12/24 131C売 $8.8M</td></tr>
<tr><td nowrap><b>SOXL＊</b> レバ3倍<br>ブル 🐂 小<br>→原指数 ブル 🐂</td><td nowrap>12/4 30C買 $5.8M<br>12/11 30C売 $4.8M</td></tr>
<tr><td nowrap><b>SOXS＊</b> 逆レバ3倍<br>ベア 🐻 小<br>→原指数 ブル 🐂</td><td nowrap>12/18 125C売 $8.7M<br>12/18 120C買 $1.8M</td></tr>
<tr><td nowrap><b>QQQ＊</b> 原指数<br>はっきりせず</td><td nowrap>12/4 635P売 $53M<br>12/18 600P買 $39M</td></tr>
<tr><td nowrap><b>TQQQ＊</b> レバ3倍<br>はっきりせず</td><td nowrap>3/19 30P買 $1.6M<br>1/15 50C買 $1.5M</td></tr>
<tr><td nowrap><b>SQQQ＊</b> 逆レバ3倍<br>ブル 🐂 小<br>→原指数 ベア 🐻</td><td nowrap>12/31 42C買 $1.4M<br>12/18 55C売 $0.5M</td></tr>
</tbody>
</table>

向きは、大口（その日の代金の多い上位10契約。深い ITM を除く）ごとに買い・売りを推定し、コール買い・プット売り＝ブル（上げ）、コール売り・プット買い＝ベア（下げ）としてデルタ換算で足した差。強さは、その差がその ETF の1日の売買代金の何% か（1% 未満 小・3% 未満 中・10% 未満 大・それ以上 特大。記録が20回たまったら、過去の記録の中の順位）。主な賭けは代金の多い順（買＝買い、売＝売り）。深い ITM は向きの合計に入れていません。＊は、今の板が崩れているため、同じ取引日の前回の有効な実行の結果。

## レバ系 vs 原指数

<table>
<thead><tr><th nowrap>群</th><th nowrap>半導体</th><th nowrap>ナスダック100</th></tr></thead>
<tbody>
<tr><td nowrap>原指数</td><td nowrap>ベア 🐻 大<br>−4.6億ドル<br>SMH＋SOXX</td><td nowrap>はっきりせず<br>+1.1億ドル<br>QQQ</td></tr>
<tr><td nowrap>レバ系</td><td nowrap>ブル 🐂 小<br>+1.4億ドル<br>SOXL＋SOXS</td><td nowrap>ベア 🐻 小<br>−24.4百万ドル<br>TQQQ＋SQQQ</td></tr>
<tr><td nowrap>見立て</td><td nowrap>逆向き<br>（原指数はベア・<br>レバ系はブル）</td><td nowrap>はっきりせず</td></tr>
</tbody>
</table>

レバ系は原指数の向きに直した額（SOXL・TQQQ は ×3、SOXS・SQQQ は ×−3。SOXS のコール買い＝半導体へのベア）。強さは、原指数に直した1日の売買代金に対する割合。レバ系のオプションは個人の売買が多く、原指数（SMH・SOXX・QQQ）は機関の守り（ヘッジ）が多いとされる。 IV（30日）: SMH 65%・SOXX 73%・SOXL 207%・SOXS 227%・QQQ 34%・TQQQ 100%・SQQQ 105%。


**大きな建玉**（行使価格（株価からの距離）・平常比）

印の見方（★・☆）:

<table>
<thead><tr><th nowrap>印</th><th nowrap>意味</th></tr></thead>
<tbody>
<tr><td nowrap>★</td><td nowrap>いつもより、<br>はっきりこちら側に偏っている<br>（1σ 以上）。<br>この側の壁に注目</td></tr>
<tr><td nowrap>☆</td><td nowrap>偏りは小さい<br>（1σ 未満か、<br>記録が足りない）。<br>数の多い側に参考で付ける</td></tr>
<tr><td nowrap>印なし</td><td nowrap>反対側の大きな建玉</td></tr>
</tbody>
</table>

☆は『今の数が多い側』、σは『いつもと比べてどちらに寄ったか』なので、☆の側と σ の向きが逆になることがあります。

<table>
<thead><tr><th nowrap>銘柄・側</th><th nowrap>行使価格</th><th nowrap>枚数/金額</th></tr></thead>
<tbody>
<tr><td nowrap>SMH<br>プット☆</td><td nowrap>340 (−19.5%)<br>300 (−29.0%)<br>400 (−5.3%)</td><td nowrap>1.3/0.13<br>1.2/0.06▼<br>0.74▼/2.9</td></tr>
<tr><td nowrap>SMH<br>コール</td><td nowrap>500 (+18.4%)<br>520 (+23.1%)<br>490 (+16.0%)</td><td nowrap>0.91/2.1<br>0.93▼/0.57<br>0.96/0.50</td></tr>
<tr><td nowrap>SOXX<br>プット</td><td nowrap>125 (−2.3%)<br>120 (−6.2%)<br>130 (+1.6%)</td><td nowrap>—</td></tr>
<tr><td nowrap>SOXX<br>コール☆</td><td nowrap>155 (+21.1%)<br>145 (+13.3%)<br>161.67 (+26.3%)</td><td nowrap>—</td></tr>
<tr><td nowrap>SOXL<br>プット</td><td nowrap>25 (−21.9%)<br>30 (−6.3%)<br>40 (+24.9%)</td><td nowrap>—</td></tr>
<tr><td nowrap>SOXL<br>コール☆</td><td nowrap>40 (+24.9%)<br>38 (+18.7%)<br>35 (+9.3%)</td><td nowrap>—</td></tr>
<tr><td nowrap>SOXS<br>プット</td><td nowrap>50 (−19.5%)<br>55 (−11.5%)<br>45 (−27.6%)</td><td nowrap>—</td></tr>
<tr><td nowrap>SOXS<br>コール☆</td><td nowrap>80 (+28.8%)<br>60 (−3.4%)<br>78 (+25.5%)</td><td nowrap>—</td></tr>
<tr><td nowrap>QQQ<br>プット☆</td><td nowrap>550 (−13.2%)<br>600 (−5.4%)<br>580 (−8.5%)</td><td nowrap>0.73▼/0.21▼<br>0.82▼/0.62<br>0.81▼/0.36▼</td></tr>
<tr><td nowrap>QQQ<br>コール</td><td nowrap>700 (+10.4%)<br>680 (+7.3%)<br>720 (+13.6%)</td><td nowrap>1.2▲/1.7<br>1.1▲/3.7▲<br>1.1▲/0.52</td></tr>
<tr><td nowrap>TQQQ<br>プット</td><td nowrap>40 (−11.7%)<br>45 (−0.6%)<br>50 (+10.4%)</td><td nowrap>—</td></tr>
<tr><td nowrap>TQQQ<br>コール☆</td><td nowrap>50 (+10.4%)<br>55 (+21.5%)<br>58 (+28.1%)</td><td nowrap>—</td></tr>
<tr><td nowrap>SQQQ<br>プット</td><td nowrap>40 (−19.4%)<br>36 (−27.4%)<br>45 (−9.3%)</td><td nowrap>—</td></tr>
<tr><td nowrap>SQQQ<br>コール☆</td><td nowrap>55 (+10.9%)<br>60 (+21.0%)<br>50 (+0.8%)</td><td nowrap>—</td></tr>
</tbody>
</table>

σ は、いつも（①の毎日の記録）と比べた偏りの大きさと、偏っている側です（1σ 以上で偏り、2σ 以上で大きな偏り）。『前日から』は、前日の記録からどちら側へ何σ動いたか。行使価格の横は株価からの距離。『枚数/金額』は、その建玉の枚数と入っているお金（建玉 × 値段 × 100）が、過去30日の同じ側の平常の何倍か（▲▲ 30日で最多・▲ 多い・▼ 少ない・▼▼ 30日で最少）。図と詳しい表は各銘柄の【結論】、言葉の意味は最後の『見方』。

## SMH　422.46

米国 11/26 22:46（取引時間外）・直近の取引日 11/25・板 Yahoo

> 今の板が崩れているため（気配のある契約が 2%（取引時間外の崩れた板の可能性））、**前回の有効な実行（日本時間 2026-11-27 12:46・板 Yahoo）の結果**を載せています。同じ取引日（11/25）の約定・建玉なので、内容は今と同じです。

### 結論

<table>
<thead><tr><th nowrap>問い</th><th nowrap>答え</th></tr></thead>
<tbody>
<tr><td nowrap>建玉の偏り</td><td nowrap><b>いつも並み（偏りは小さい）</b><br>（プット 54%・コール 46%）</td></tr>
<tr><td nowrap>σ（側）</td><td nowrap><b>コール側に 0.4σ</b><br><b>（1σ 未満で、偏りは小さい）</b></td></tr>
<tr><td nowrap>前日から</td><td nowrap><b>コール側へ 0.9σ</b><br>（11/24 プット側に 0.5σ<br>（プット÷コール 1.47）<br>→ 今 コール側に 0.4σ<br>（1.19））</td></tr>
<tr><td nowrap>大きなプット☆</td><td nowrap>340 (−19.5%) 1.3/0.13<br>300 (−29.0%) 1.2/0.06▼<br>400 (−5.3%) 0.74▼/2.9</td></tr>
<tr><td nowrap>大きなコール</td><td nowrap>500 (+18.4%) 0.91/2.1<br>520 (+23.1%) 0.93▼/0.57<br>490 (+16.0%) 0.96/0.50</td></tr>
</tbody>
</table>

- σ: いつも（10/9〜11/24 の 25日）のプット÷コールは平均 1.31、今は 1.19。記録が60日たまるまでは目安。
- 大きなプット・コールの印: ★ 偏っている側、☆ 偏りは小さいが数の多い側。『○/○』は、枚数/金額（建玉 × 値段 × 100）が過去30日の平常の何倍か。
- 偏りの物差し: 満期まで 3〜75日の全ての建玉（①の毎日の記録と同じ）。建玉には買い手と売り手が同じ数だけいるので、偏りはコールとプットの数で見ています。

**プットの大きな建玉の枚数とお金**（数の多い側）（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>340</b> OTM</td><td nowrap>85,682 (<b>1.3</b>)</td><td nowrap>1.52M (<b>0.13</b>)</td></tr>
<tr><td nowrap><b>300</b> OTM</td><td nowrap>49,132 (<b>1.2</b>)</td><td nowrap>0.70M (<b>0.06▼</b>)</td></tr>
<tr><td nowrap><b>400</b> OTM</td><td nowrap>20,577 (<b>0.74▼</b>)</td><td nowrap>33.3M (<b>2.9</b>)</td></tr>
<tr><td nowrap><b>450</b> ITM</td><td nowrap>17,602 (<b>0.66▼</b>)</td><td nowrap>69.5M (<b>6.1▲</b>)</td></tr>
<tr><td nowrap><b>420</b> ATM</td><td nowrap>16,540 (<b>0.67▼</b>)</td><td nowrap>32.1M (<b>2.8</b>)</td></tr>
</tbody>
</table>

- 平常（11/6〜11/24 の 13日、うち 10日は値段を推定）の中央値: 枚数 1番目 66,681枚・2番目 40,816枚・3番目 27,766枚・4番目 26,780枚・5番目 24,591枚。金額 11.5Mドル（大きなプット 65本）。30日分の記録がたまるまでは目安。
- プットの建玉の合計（45日以内・株価の ±30%）: 429,009枚＝平常の0.78倍 ▼。

**コールの大きな建玉の枚数とお金**（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>500</b> OTM</td><td nowrap>23,466 (<b>0.91</b>)</td><td nowrap>6.52M (<b>2.1</b>)</td></tr>
<tr><td nowrap><b>520</b> OTM</td><td nowrap>18,391 (<b>0.93▼</b>)</td><td nowrap>1.76M (<b>0.57</b>)</td></tr>
<tr><td nowrap><b>490</b> OTM</td><td nowrap>14,584 (<b>0.96</b>)</td><td nowrap>1.56M (<b>0.50</b>)</td></tr>
<tr><td nowrap><b>510</b> OTM</td><td nowrap>8,824 (<b>0.74▼</b>)</td><td nowrap>1.77M (<b>0.57</b>)</td></tr>
<tr><td nowrap><b>525</b> OTM</td><td nowrap>7,818 (<b>0.71▼</b>)</td><td nowrap>1.20M (<b>0.39</b>)</td></tr>
</tbody>
</table>

- 平常（11/6〜11/24 の 13日、うち 10日は値段を推定）の中央値: 枚数 1番目 25,671枚・2番目 19,755枚・3番目 15,139枚・4番目 11,900枚・5番目 10,993枚。金額 3.10Mドル（大きなコール 65本）。30日分の記録がたまるまでは目安。
- コールの建玉の合計（45日以内・株価の ±30%）: 190,731枚＝平常の0.76倍 ▼。

- 枚数の平常比は同じ側・同じ順位（過去の各日の、枚数が同じ順位の建玉）、金額の平常比は同じ側の過去の大きな建玉（各日の上位5本）と比べた倍率。▲▲ 30日で最多・▲ 多い（上位25%）・▼ 少ない（下位25%）・▼▼ 30日で最少。印が無ければ平常並み。建玉の合計も▲なら、満期（特に3・6・9・12月の第3金曜）に向けて全体が増えている分を差し引いて見てください。金額は建玉 × 値段 × 100（ITM は本質的な価値を含む。今の板）。

**プットの大きな建玉**（数の多い側）（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>340</b> (−19.5%)</td><td nowrap>85,682 (20%)</td><td nowrap>11/27 $0.05</td></tr>
<tr><td nowrap><b>300</b> (−29.0%)</td><td nowrap>49,132 (11%)</td><td nowrap>11/27 $0.02</td></tr>
<tr><td nowrap><b>400</b> (−5.3%)</td><td nowrap>20,577 (5%)</td><td nowrap>12/18 $19.10</td></tr>
<tr><td nowrap><b>450</b> (+6.5%)</td><td nowrap>17,602 (4%)</td><td nowrap>12/18 $43.03</td></tr>
<tr><td nowrap><b>420</b> (−0.6%)</td><td nowrap>16,540 (4%)</td><td nowrap>12/18 $27.15</td></tr>
</tbody>
</table>

**コールの大きな建玉**（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>500</b> (+18.4%)</td><td nowrap>23,466 (12%)</td><td nowrap>12/18 $4.10</td></tr>
<tr><td nowrap><b>520</b> (+23.1%)</td><td nowrap>18,391 (10%)</td><td nowrap>12/4 $0.19</td></tr>
<tr><td nowrap><b>490</b> (+16.0%)</td><td nowrap>14,584 (8%)</td><td nowrap>11/27 $0.04</td></tr>
<tr><td nowrap><b>510</b> (+20.7%)</td><td nowrap>8,824 (5%)</td><td nowrap>11/27 $0.02</td></tr>
<tr><td nowrap><b>525</b> (+24.3%)</td><td nowrap>7,818 (4%)</td><td nowrap>12/18 $1.81</td></tr>
</tbody>
</table>

### オプションの配置（図）

![SMH のオプションの配置](SMH_options_chart.svg)

- 今の株価でのガンマの合計は**マイナス**（−281百万ドル／1%）、ゼロガンマは **471.68**（+11.7%）。
- 上の段: 株価がその値になったときの、ディーラーのガンマの合計（赤い点線がゼロガンマ）。赤い背景（マイナス）の価格帯では、ディーラーが下げで売り・上げで買うので値動きが大きくなりやすく、緑の背景（プラス）では小さくなりやすい。
- 中の段: 行使価格ごとのガンマ（コールは上、プットは下）。下の段: 行使価格ごとの建玉（45日以内の満期）と、プットの壁・コールの壁（灰色の点線）。黒い線が今の株価。

### 大口の賭け（推定）

**ベア 🐻・強さ 大**（売買代金の 5.8%）

- 大口のデルタ換算（株を何ドル分買った・売ったのと同じ向きか）: 差 **−3.7億ドル**（ブル側 +20.6百万ドル・ベア側 −4.0億ドル）。代金はブル側 4.8百万ドル・ベア側 77.0百万ドル。1日の売買代金 64.7億ドル（20日の平均）
- 大口が見ている価格: 下げの的（プット買い） **350**（−17.2%）
- 深い ITM の大口（合計に入れない）: 3本・代金 1.8億ドル（12/18 585P買・12/18 645P（向き不明）・12/18 635P買）。株と組み合わせた取引（配当の裁定・乗り換えなど）のことが多い。そのまま賭けとみると −2.6億ドル 分

<table>
<thead><tr><th nowrap>契約</th><th nowrap>推定・意味</th><th nowrap>代金・枚数</th></tr></thead>
<tbody>
<tr><td nowrap>1/15 350P<br>−17.2%<br>建玉 35,964</td><td nowrap><b>買い</b><br>下げへの賭け・<br>守り</td><td nowrap>$24M<br>19,103枚<br>Δ −$155M<br>IV 68%</td></tr>
<tr><td nowrap>2/19 350P<br>−17.2%<br>建玉 13,277</td><td nowrap><b>買い</b><br>下げへの賭け・<br>守り</td><td nowrap>$24M<br>13,254枚<br>Δ −$121M<br>IV 61%</td></tr>
<tr><td nowrap>1/15 400P<br>−5.3%<br>建玉 43,854</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$19M<br>7,021枚<br>Δ —<br>IV 62%</td></tr>
<tr><td nowrap>12/18 420P<br>−0.6%<br>建玉 7,012</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$16M<br>5,739枚<br>Δ —<br>IV 69%</td></tr>
<tr><td nowrap>1/15 375P<br>−11.2%<br>建玉 10,110</td><td nowrap><b>買い寄り</b><br>下げへの賭け・<br>守り</td><td nowrap>$12M<br>6,512枚<br>Δ −$37M<br>IV 65%</td></tr>
<tr><td nowrap>12/18 400P<br>−5.3%<br>建玉 15,955</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$9.4M<br>4,926枚<br>Δ —<br>IV 72%</td></tr>
<tr><td nowrap>12/18 450P<br>+6.5%<br>建玉 12,609</td><td nowrap><b>買い</b><br>下げへの賭け・<br>守り（ITM）</td><td nowrap>$5.6M<br>1,305枚<br>Δ −$35M<br>IV 63%</td></tr>
<tr><td nowrap>3/19 495P<br>+17.2%<br>建玉 720</td><td nowrap><b>買い</b><br>下げへの賭け・<br>守り（ITM）</td><td nowrap>$5.5M<br>600枚<br>Δ −$18M<br>IV 46%</td></tr>
<tr><td nowrap>12/18 460P<br>+8.9%<br>建玉 4,742</td><td nowrap><b>買い</b><br>下げへの賭け・<br>守り（ITM）</td><td nowrap>$5.1M<br>1,031枚<br>Δ −$30M<br>IV 62%</td></tr>
<tr><td nowrap>12/4 400C<br>−5.3%<br>建玉 18</td><td nowrap><b>買い寄り</b><br>上げへの賭け<br>（ITM）</td><td nowrap>$4.8M<br>1,410枚<br>Δ +$21M<br>IV 85%</td></tr>
<tr><td nowrap>12/18 585P<br>+38.5%<br>建玉 1,538</td><td nowrap><b>買い</b><br>深い ITM の買い</td><td nowrap>$87M<br>5,350枚<br>Δ −$225M<br>IV 51%</td></tr>
<tr><td nowrap>12/18 645P<br>+52.7%<br>建玉 0</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$47M<br>2,125枚<br>Δ —<br>IV 102%</td></tr>
<tr><td nowrap>12/18 635P<br>+50.3%<br>建玉 526</td><td nowrap><b>買い寄り</b><br>深い ITM の買い</td><td nowrap>$42M<br>1,990枚<br>Δ −$39M<br>IV 99%</td></tr>
</tbody>
</table>

推定の向きは最後の約定の位置（売り気配で約定＝買い）と、前回の実行からの IV の上下（今回は前回の記録なし）から。買い・売りの分かる大口は代金の 65%。誰の取引かは分かりません。表の『代金・枚数』は、代金・その日の出来高・Δ（デルタ換算。株を何ドル分買った＋・売った−のと同じ向きか）・IV。

### 詳しく

**まとめ**: 下の支えの候補 **400**（−5.3%）・340（−19.5%）・300（−29.0%）。上の重さの候補 **490**（+16.0%）・500（+18.4%）・520（+23.1%）。次の満期（11/27・1日）の想定の幅 ±3.8%（406.31〜438.61）。ガンマはマイナス側（ゼロガンマ 471.14）→ 値動きが大きくなりやすい。

**下の支えの候補**（プットの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>420</td><td nowrap>−0.6%</td><td nowrap>16,540</td><td nowrap>4%</td></tr>
<tr><td nowrap>400</td><td nowrap>−5.3%</td><td nowrap>20,577</td><td nowrap>5%</td></tr>
<tr><td nowrap>350</td><td nowrap>−17.2%</td><td nowrap>11,820</td><td nowrap>3%</td></tr>
<tr><td nowrap>340</td><td nowrap>−19.5%</td><td nowrap>85,682</td><td nowrap>20%</td></tr>
<tr><td nowrap>300</td><td nowrap>−29.0%</td><td nowrap>49,132</td><td nowrap>11%</td></tr>
</tbody>
</table>

**上の重さの候補**（コールの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>490</td><td nowrap>+16.0%</td><td nowrap>14,584</td><td nowrap>8%</td></tr>
<tr><td nowrap>500</td><td nowrap>+18.4%</td><td nowrap>23,466</td><td nowrap>12%</td></tr>
<tr><td nowrap>510</td><td nowrap>+20.7%</td><td nowrap>8,824</td><td nowrap>5%</td></tr>
<tr><td nowrap>520</td><td nowrap>+23.1%</td><td nowrap>18,391</td><td nowrap>10%</td></tr>
<tr><td nowrap>525</td><td nowrap>+24.3%</td><td nowrap>7,818</td><td nowrap>4%</td></tr>
</tbody>
</table>

**次の満期 11/27（1日）**: プットの壁 340（−19.5%）・コールの壁 490（+16.0%）・最大の痛み 452.5（+7.1%）・想定の幅 ±3.8%

アウト・オブ・ザ・マネーに払われた代金: プット 142.4百万ドル・コール 39.0百万ドル（プットの割合 78%）

**建玉の増減**（①の日次の記録の 11/24 → 今の板。45日以内の満期）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>距離</th><th nowrap>増減</th><th nowrap>想定元本</th></tr></thead>
<tbody>
<tr><td nowrap>305P</td><td nowrap>−27.8%</td><td nowrap>+9,144</td><td nowrap>278.9百万ドル</td></tr>
<tr><td nowrap>350P</td><td nowrap>−17.2%</td><td nowrap>+5,105</td><td nowrap>178.7百万ドル</td></tr>
<tr><td nowrap>320P</td><td nowrap>−24.3%</td><td nowrap>+2,986</td><td nowrap>95.6百万ドル</td></tr>
<tr><td nowrap>340P</td><td nowrap>−19.5%</td><td nowrap>−12,696</td><td nowrap>−431.7百万ドル</td></tr>
<tr><td nowrap>500P</td><td nowrap>+18.4%</td><td nowrap>−1,046</td><td nowrap>−52.3百万ドル</td></tr>
</tbody>
</table>

合計: プット 468.1百万ドル・コール 730.4百万ドル（想定元本の増減）

**全体**: IV30 65%・7日 77%・期間構造 1.19（目先の不安が強い）・プットの割高さ +7.2pt・建玉のプット/コール 1.45

**過去の検証**: 未検証（第190回で、2008〜2025年の QQQ・SPY・NVDA・AVGO・AMD・QCOM・TXN の板で確かめ中）。それまでは、下の目安は過去の効きが確かめられていない参考の値です。

## SOXX　127.98

米国 11/26 22:46（取引時間外）・直近の取引日 11/25・板 Yahoo

> 今の板が崩れているため（気配のある契約が 4%（取引時間外の崩れた板の可能性））、**前回の有効な実行（日本時間 2026-11-27 12:46・板 Yahoo）の結果**を載せています。同じ取引日（11/25）の約定・建玉なので、内容は今と同じです。

### 結論

<table>
<thead><tr><th nowrap>問い</th><th nowrap>答え</th></tr></thead>
<tbody>
<tr><td nowrap>建玉の偏り</td><td nowrap><b>ほぼ半々</b><br><b>（いつもとの比較はまだできない）</b><br>（プット 50%・コール 50%）</td></tr>
<tr><td nowrap>σ（側）</td><td nowrap><b>—</b></td></tr>
<tr><td nowrap>前日から</td><td nowrap><b>—</b><br>（前日の記録と比べられません<br>（σ を出せない日））</td></tr>
<tr><td nowrap>大きなプット</td><td nowrap>125 (−2.3%)<br>120 (−6.2%)<br>130 (+1.6%)</td></tr>
<tr><td nowrap>大きなコール☆</td><td nowrap>155 (+21.1%)<br>145 (+13.3%)<br>161.67 (+26.3%)</td></tr>
</tbody>
</table>

- σ: ①の毎日の記録が 0日分しかなく、σ を出せません（10日たまると出ます）。
- 大きなプット・コールの印: ★ 偏っている側、☆ 偏りは小さいが数の多い側。『○/○』は、枚数/金額（建玉 × 値段 × 100）が過去30日の平常の何倍か。
- 偏りの物差し: 満期まで 3〜75日の全ての建玉（①の毎日の記録と同じ）。建玉には買い手と売り手が同じ数だけいるので、偏りはコールとプットの数で見ています。

**プットの大きな建玉の枚数とお金**（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>125</b> OTM</td><td nowrap>38,614 (<b>—</b>)</td><td nowrap>30.9M (<b>—</b>)</td></tr>
<tr><td nowrap><b>120</b> OTM</td><td nowrap>34,994 (<b>—</b>)</td><td nowrap>20.5M (<b>—</b>)</td></tr>
<tr><td nowrap><b>130</b> ITM</td><td nowrap>27,157 (<b>—</b>)</td><td nowrap>23.8M (<b>—</b>)</td></tr>
<tr><td nowrap><b>110</b> OTM</td><td nowrap>23,407 (<b>—</b>)</td><td nowrap>5.49M (<b>—</b>)</td></tr>
<tr><td nowrap><b>140</b> ITM</td><td nowrap>20,965 (<b>—</b>)</td><td nowrap>33.3M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

**コールの大きな建玉の枚数とお金**（数の多い側）（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>155</b> OTM</td><td nowrap>58,800 (<b>—</b>)</td><td nowrap>6.54M (<b>—</b>)</td></tr>
<tr><td nowrap><b>145</b> OTM</td><td nowrap>24,843 (<b>—</b>)</td><td nowrap>2.75M (<b>—</b>)</td></tr>
<tr><td nowrap><b>161.67</b> OTM</td><td nowrap>17,705 (<b>—</b>)</td><td nowrap>0.44M (<b>—</b>)</td></tr>
<tr><td nowrap><b>160</b> OTM</td><td nowrap>16,543 (<b>—</b>)</td><td nowrap>0.72M (<b>—</b>)</td></tr>
<tr><td nowrap><b>140</b> OTM</td><td nowrap>12,526 (<b>—</b>)</td><td nowrap>4.87M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

- 枚数の平常比は同じ側・同じ順位（過去の各日の、枚数が同じ順位の建玉）、金額の平常比は同じ側の過去の大きな建玉（各日の上位5本）と比べた倍率。▲▲ 30日で最多・▲ 多い（上位25%）・▼ 少ない（下位25%）・▼▼ 30日で最少。印が無ければ平常並み。建玉の合計も▲なら、満期（特に3・6・9・12月の第3金曜）に向けて全体が増えている分を差し引いて見てください。金額は建玉 × 値段 × 100（ITM は本質的な価値を含む。今の板）。

**プットの大きな建玉**（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>125</b> (−2.3%)</td><td nowrap>38,614 (13%)</td><td nowrap>12/18 $8.35</td></tr>
<tr><td nowrap><b>120</b> (−6.2%)</td><td nowrap>34,994 (12%)</td><td nowrap>12/18 $6.50</td></tr>
<tr><td nowrap><b>130</b> (+1.6%)</td><td nowrap>27,157 (9%)</td><td nowrap>12/18 $10.95</td></tr>
<tr><td nowrap><b>110</b> (−14.0%)</td><td nowrap>23,407 (8%)</td><td nowrap>12/4 $1.60</td></tr>
<tr><td nowrap><b>140</b> (+9.4%)</td><td nowrap>20,965 (7%)</td><td nowrap>12/18 $16.65</td></tr>
</tbody>
</table>

**コールの大きな建玉**（数の多い側）（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>155</b> (+21.1%)</td><td nowrap>58,800 (30%)</td><td nowrap>12/18 $1.15</td></tr>
<tr><td nowrap><b>145</b> (+13.3%)</td><td nowrap>24,843 (12%)</td><td nowrap>11/27 $0.03</td></tr>
<tr><td nowrap><b>161.67</b> (+26.3%)</td><td nowrap>17,705 (9%)</td><td nowrap>11/27 $0.02</td></tr>
<tr><td nowrap><b>160</b> (+25.0%)</td><td nowrap>16,543 (8%)</td><td nowrap>11/27 $0.01</td></tr>
<tr><td nowrap><b>140</b> (+9.4%)</td><td nowrap>12,526 (6%)</td><td nowrap>12/18 $4.55</td></tr>
</tbody>
</table>

### オプションの配置（図）

![SOXX のオプションの配置](SOXX_options_chart.svg)

- 今の株価でのガンマの合計は**マイナス**（−59百万ドル／1%）、ゼロガンマは **144.67**（+13.0%）。
- 上の段: 株価がその値になったときの、ディーラーのガンマの合計（赤い点線がゼロガンマ）。赤い背景（マイナス）の価格帯では、ディーラーが下げで売り・上げで買うので値動きが大きくなりやすく、緑の背景（プラス）では小さくなりやすい。
- 中の段: 行使価格ごとのガンマ（コールは上、プットは下）。下の段: 行使価格ごとの建玉（45日以内の満期）と、プットの壁・コールの壁（灰色の点線）。黒い線が今の株価。

### 大口の賭け（推定）

**ベア 🐻・強さ 中**（売買代金の 1.3%）

- 大口のデルタ換算（株を何ドル分買った・売ったのと同じ向きか）: 差 **−87.4百万ドル**（ブル側 +26.5百万ドル・ベア側 −1.1億ドル）。代金はブル側 13.1百万ドル・ベア側 16.1百万ドル。1日の売買代金 69.4億ドル（20日の平均）
- 大口が見ている価格: 上値の重し（コール売り） **131**（+2.4%）
- 深い ITM の大口（合計に入れない）: 3本・代金 33.7百万ドル（12/18 450P（向き不明）・2/19 240P（向き不明）・3/19 300P（向き不明））。株と組み合わせた取引（配当の裁定・乗り換えなど）のことが多い。向きは分からない

<table>
<thead><tr><th nowrap>契約</th><th nowrap>推定・意味</th><th nowrap>代金・枚数</th></tr></thead>
<tbody>
<tr><td nowrap>12/18 125P<br>−2.3%<br>建玉 34,208</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$10M<br>12,070枚<br>Δ —<br>IV 79%</td></tr>
<tr><td nowrap>3/19 130P<br>+1.6%<br>建玉 6,648</td><td nowrap><b>売り寄り</b><br>下値の防御線<br>（ITM）</td><td nowrap>$9.0M<br>5,070枚<br>Δ +$15M<br>IV 59%</td></tr>
<tr><td nowrap>12/24 131C<br>+2.4%<br>建玉 4</td><td nowrap><b>売り</b><br>上値の重し</td><td nowrap>$8.8M<br>10,379枚<br>Δ −$65M<br>IV 69%</td></tr>
<tr><td nowrap>12/4 140P<br>+9.4%<br>建玉 5,649</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$6.7M<br>4,478枚<br>Δ —<br>IV 93%</td></tr>
<tr><td nowrap>1/15 130C<br>+1.6%<br>建玉 4,691</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$6.0M<br>5,148枚<br>Δ —<br>IV 67%</td></tr>
<tr><td nowrap>12/18 140P<br>+9.4%<br>建玉 11,822</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$4.3M<br>2,562枚<br>Δ —<br>IV 72%</td></tr>
<tr><td nowrap>12/18 130P<br>+1.6%<br>建玉 12,234</td><td nowrap><b>売り寄り</b><br>下値の防御線<br>（ITM）</td><td nowrap>$4.1M<br>3,711枚<br>Δ +$12M<br>IV 79%</td></tr>
<tr><td nowrap>1/15 150C<br>+17.2%<br>建玉 13,875</td><td nowrap><b>売り寄り</b><br>上値の重し</td><td nowrap>$3.9M<br>9,003枚<br>Δ −$16M<br>IV 60%</td></tr>
<tr><td nowrap>12/18 145C<br>+13.3%<br>建玉 5,103</td><td nowrap><b>売り</b><br>上値の重し</td><td nowrap>$3.4M<br>9,280枚<br>Δ −$33M<br>IV 75%</td></tr>
<tr><td nowrap>12/18 110P<br>−14.0%<br>建玉 8,557</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$3.2M<br>8,907枚<br>Δ —<br>IV 87%</td></tr>
<tr><td nowrap>12/18 450P<br>+251.6%<br>建玉 8,438</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$16M<br>5,655枚<br>Δ —<br>IV —</td></tr>
<tr><td nowrap>2/19 240P<br>+87.5%<br>建玉 0</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$10M<br>1,000枚<br>Δ —<br>IV —</td></tr>
<tr><td nowrap>3/19 300P<br>+134.4%<br>建玉 0</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$7.8M<br>611枚<br>Δ —<br>IV —</td></tr>
</tbody>
</table>

推定の向きは最後の約定の位置（売り気配で約定＝買い）と、前回の実行からの IV の上下（今回は前回の記録なし）から。買い・売りの分かる大口は代金の 49%。誰の取引かは分かりません。表の『代金・枚数』は、代金・その日の出来高・Δ（デルタ換算。株を何ドル分買った＋・売った−のと同じ向きか）・IV。

### 詳しく

**まとめ**: 下の支えの候補 **125**（−2.3%）・120（−6.2%）・110（−14.0%）。上の重さの候補 **145**（+13.3%）・155（+21.1%）・161.67（+26.3%）。既に割れたプットの壁 130（+1.6%）。次の満期（11/27・1日）の想定の幅 ±4.4%（122.41〜133.56）。ガンマはマイナス側（ゼロガンマ 144.37）→ 値動きが大きくなりやすい。

**下の支えの候補**（プットの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>125</td><td nowrap>−2.3%</td><td nowrap>38,614</td><td nowrap>13%</td></tr>
<tr><td nowrap>122</td><td nowrap>−4.7%</td><td nowrap>6,221</td><td nowrap>2%</td></tr>
<tr><td nowrap>120</td><td nowrap>−6.2%</td><td nowrap>34,994</td><td nowrap>12%</td></tr>
<tr><td nowrap>115</td><td nowrap>−10.1%</td><td nowrap>9,339</td><td nowrap>3%</td></tr>
<tr><td nowrap>110</td><td nowrap>−14.0%</td><td nowrap>23,407</td><td nowrap>8%</td></tr>
</tbody>
</table>

**上の重さの候補**（コールの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>140</td><td nowrap>+9.4%</td><td nowrap>12,526</td><td nowrap>6%</td></tr>
<tr><td nowrap>145</td><td nowrap>+13.3%</td><td nowrap>24,843</td><td nowrap>12%</td></tr>
<tr><td nowrap>155</td><td nowrap>+21.1%</td><td nowrap>58,800</td><td nowrap>30%</td></tr>
<tr><td nowrap>160</td><td nowrap>+25.0%</td><td nowrap>16,543</td><td nowrap>8%</td></tr>
<tr><td nowrap>161.67</td><td nowrap>+26.3%</td><td nowrap>17,705</td><td nowrap>9%</td></tr>
</tbody>
</table>

**次の満期 11/27（1日）**: プットの壁 100（−21.9%）・コールの壁 145（+13.3%）・最大の痛み 145（+13.3%）・想定の幅 ±4.4%

アウト・オブ・ザ・マネーに払われた代金: プット 33.5百万ドル・コール 32.9百万ドル（プットの割合 50%）

**建玉の増減**: 前回の記録（前回のオプション分析 11/25）と建玉が同じため、出せません（建玉の公表がまだ更新されていない可能性）

**全体**: IV30 73%・7日 89%・期間構造 1.22（目先の不安が強い）・プットの割高さ +4.3pt・建玉のプット/コール 1.06

**過去の検証**: 未検証（第190回で、2008〜2025年の QQQ・SPY・NVDA・AVGO・AMD・QCOM・TXN の板で確かめ中）。それまでは、下の目安は過去の効きが確かめられていない参考の値です。

## SOXL　32.02

米国 11/26 22:46（取引時間外）・直近の取引日 11/25・板 Yahoo

> 今の板が崩れているため（気配のある契約が 2%（取引時間外の崩れた板の可能性））、**前回の有効な実行（日本時間 2026-11-27 12:46・板 Yahoo）の結果**を載せています。同じ取引日（11/25）の約定・建玉なので、内容は今と同じです。

### 結論

<table>
<thead><tr><th nowrap>問い</th><th nowrap>答え</th></tr></thead>
<tbody>
<tr><td nowrap>建玉の偏り</td><td nowrap><b>ほぼ半々</b><br><b>（いつもとの比較はまだできない）</b><br>（プット 49%・コール 51%）</td></tr>
<tr><td nowrap>σ（側）</td><td nowrap><b>—</b></td></tr>
<tr><td nowrap>前日から</td><td nowrap><b>—</b><br>（前日の記録と比べられません<br>（σ を出せない日））</td></tr>
<tr><td nowrap>大きなプット</td><td nowrap>25 (−21.9%)<br>30 (−6.3%)<br>40 (+24.9%)</td></tr>
<tr><td nowrap>大きなコール☆</td><td nowrap>40 (+24.9%)<br>38 (+18.7%)<br>35 (+9.3%)</td></tr>
</tbody>
</table>

- σ: ①の毎日の記録が 0日分しかなく、σ を出せません（10日たまると出ます）。
- 大きなプット・コールの印: ★ 偏っている側、☆ 偏りは小さいが数の多い側。『○/○』は、枚数/金額（建玉 × 値段 × 100）が過去30日の平常の何倍か。
- 偏りの物差し: 満期まで 3〜75日の全ての建玉（①の毎日の記録と同じ）。建玉には買い手と売り手が同じ数だけいるので、偏りはコールとプットの数で見ています。

**プットの大きな建玉の枚数とお金**（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>25</b> OTM</td><td nowrap>54,068 (<b>—</b>)</td><td nowrap>12.1M (<b>—</b>)</td></tr>
<tr><td nowrap><b>30</b> OTM</td><td nowrap>29,356 (<b>—</b>)</td><td nowrap>10.1M (<b>—</b>)</td></tr>
<tr><td nowrap><b>40</b> 超ITM</td><td nowrap>24,384 (<b>—</b>)</td><td nowrap>24.9M (<b>—</b>)</td></tr>
<tr><td nowrap><b>35</b> ITM</td><td nowrap>21,131 (<b>—</b>)</td><td nowrap>15.0M (<b>—</b>)</td></tr>
<tr><td nowrap><b>33</b> ITM</td><td nowrap>7,859 (<b>—</b>)</td><td nowrap>3.78M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

**コールの大きな建玉の枚数とお金**（数の多い側）（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> OTM</td><td nowrap>61,490 (<b>—</b>)</td><td nowrap>19.0M (<b>—</b>)</td></tr>
<tr><td nowrap><b>38</b> OTM</td><td nowrap>20,966 (<b>—</b>)</td><td nowrap>3.53M (<b>—</b>)</td></tr>
<tr><td nowrap><b>35</b> OTM</td><td nowrap>20,029 (<b>—</b>)</td><td nowrap>4.78M (<b>—</b>)</td></tr>
<tr><td nowrap><b>37</b> OTM</td><td nowrap>19,353 (<b>—</b>)</td><td nowrap>2.90M (<b>—</b>)</td></tr>
<tr><td nowrap><b>36</b> OTM</td><td nowrap>14,651 (<b>—</b>)</td><td nowrap>3.17M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

- 枚数の平常比は同じ側・同じ順位（過去の各日の、枚数が同じ順位の建玉）、金額の平常比は同じ側の過去の大きな建玉（各日の上位5本）と比べた倍率。▲▲ 30日で最多・▲ 多い（上位25%）・▼ 少ない（下位25%）・▼▼ 30日で最少。印が無ければ平常並み。建玉の合計も▲なら、満期（特に3・6・9・12月の第3金曜）に向けて全体が増えている分を差し引いて見てください。金額は建玉 × 値段 × 100（ITM は本質的な価値を含む。今の板）。

**プットの大きな建玉**（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>25</b> (−21.9%)</td><td nowrap>54,068 (25%)</td><td nowrap>11/27 $0.28</td></tr>
<tr><td nowrap><b>30</b> (−6.3%)</td><td nowrap>29,356 (13%)</td><td nowrap>11/27 $1.29</td></tr>
<tr><td nowrap><b>40</b> (+24.9%)</td><td nowrap>24,384 (11%)</td><td nowrap>11/27 $8.15</td></tr>
<tr><td nowrap><b>35</b> (+9.3%)</td><td nowrap>21,131 (10%)</td><td nowrap>12/18 $9.10</td></tr>
<tr><td nowrap><b>33</b> (+3.1%)</td><td nowrap>7,859 (4%)</td><td nowrap>11/27 $2.55</td></tr>
</tbody>
</table>

**コールの大きな建玉**（数の多い側）（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> (+24.9%)</td><td nowrap>61,490 (34%)</td><td nowrap>12/31 $4.72</td></tr>
<tr><td nowrap><b>38</b> (+18.7%)</td><td nowrap>20,966 (11%)</td><td nowrap>11/27 $0.27</td></tr>
<tr><td nowrap><b>35</b> (+9.3%)</td><td nowrap>20,029 (11%)</td><td nowrap>11/27 $0.83</td></tr>
<tr><td nowrap><b>37</b> (+15.6%)</td><td nowrap>19,353 (11%)</td><td nowrap>11/27 $0.43</td></tr>
<tr><td nowrap><b>36</b> (+12.4%)</td><td nowrap>14,651 (8%)</td><td nowrap>11/27 $0.58</td></tr>
</tbody>
</table>

### オプションの配置（図）

![SOXL のオプションの配置](SOXL_options_chart.svg)

- 今の株価でのガンマの合計は**プラス**（+0百万ドル／1%）、ゼロガンマは **31.77**（−0.8%）。
- 上の段: 株価がその値になったときの、ディーラーのガンマの合計（赤い点線がゼロガンマ）。赤い背景（マイナス）の価格帯では、ディーラーが下げで売り・上げで買うので値動きが大きくなりやすく、緑の背景（プラス）では小さくなりやすい。
- 中の段: 行使価格ごとのガンマ（コールは上、プットは下）。下の段: 行使価格ごとの建玉（45日以内の満期）と、プットの壁・コールの壁（灰色の点線）。黒い線が今の株価。

### 大口の賭け（推定）

**ブル 🐂・強さ 小**（売買代金の 0.3%） — SOXL はレバ3倍。半導体に直すと **ブル 🐂**

- 大口のデルタ換算（株を何ドル分買った・売ったのと同じ向きか）: 差 **+35.7百万ドル**（ブル側 +53.5百万ドル・ベア側 −17.8百万ドル）。代金はブル側 19.4百万ドル・ベア側 7.1百万ドル。1日の売買代金 139.2億ドル（20日の平均）
- 大口が見ている価格: 上げの的（コール買い） **40**（+24.9%）・下げの的（プット買い） **20**（−37.5%）
- 深い ITM の大口（合計に入れない）: 3本・代金 22.8百万ドル（12/18 140P買・12/18 165P（向き不明）・1/15 250P（向き不明））。株と組み合わせた取引（配当の裁定・乗り換えなど）のことが多い。そのまま賭けとみると −2.5百万ドル 分

<table>
<thead><tr><th nowrap>契約</th><th nowrap>推定・意味</th><th nowrap>代金・枚数</th></tr></thead>
<tbody>
<tr><td nowrap>12/4 30C<br>−6.3%<br>建玉 751</td><td nowrap><b>買い</b><br>上げへの賭け<br>（ITM）</td><td nowrap>$5.8M<br>10,305枚<br>Δ +$21M<br>IV 251%</td></tr>
<tr><td nowrap>12/11 30C<br>−6.3%<br>建玉 94</td><td nowrap><b>売り</b><br>上値の重し<br>（ITM）</td><td nowrap>$4.8M<br>6,813枚<br>Δ −$14M<br>IV 241%</td></tr>
<tr><td nowrap>2/19 30C<br>−6.3%<br>建玉 361</td><td nowrap><b>買い</b><br>上げへの賭け<br>（ITM）</td><td nowrap>$4.6M<br>4,073枚<br>Δ +$9.0M<br>IV 176%</td></tr>
<tr><td nowrap>2/19 40C<br>+24.9%<br>建玉 840</td><td nowrap><b>買い</b><br>上げへの賭け</td><td nowrap>$4.2M<br>5,611枚<br>Δ +$9.8M<br>IV 163%</td></tr>
<tr><td nowrap>12/4 27C<br>−15.7%<br>建玉 4</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$2.6M<br>3,516枚<br>Δ —<br>IV 264%</td></tr>
<tr><td nowrap>12/4 25C<br>−21.9%<br>建玉 213</td><td nowrap><b>買い寄り</b><br>上げへの賭け<br>（ITM）</td><td nowrap>$2.6M<br>2,864枚<br>Δ +$3.6M<br>IV 283%</td></tr>
<tr><td nowrap>1/15 25C<br>−21.9%<br>建玉 8,336</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$2.5M<br>2,037枚<br>Δ —<br>IV 201%</td></tr>
<tr><td nowrap>1/15 20P<br>−37.5%<br>建玉 31,143</td><td nowrap><b>買い</b><br>下げへの賭け・<br>守り</td><td nowrap>$2.3M<br>7,150枚<br>Δ −$3.7M<br>IV 212%</td></tr>
<tr><td nowrap>1/15 25P<br>−21.9%<br>建玉 28,321</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$2.3M<br>4,088枚<br>Δ —<br>IV 210%</td></tr>
<tr><td nowrap>12/4 35C<br>+9.3%<br>建玉 1,880</td><td nowrap><b>買い</b><br>上げへの賭け</td><td nowrap>$2.3M<br>6,528枚<br>Δ +$9.9M<br>IV 244%</td></tr>
<tr><td nowrap>12/18 140P<br>+337.2%<br>建玉 738</td><td nowrap><b>買い寄り</b><br>深い ITM の買い</td><td nowrap>$17M<br>1,552枚<br>Δ −$2.5M<br>IV 209%</td></tr>
<tr><td nowrap>12/18 165P<br>+415.3%<br>建玉 0</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$3.1M<br>236枚<br>Δ —<br>IV 229%</td></tr>
<tr><td nowrap>1/15 250P<br>+680.8%<br>建玉 0</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$2.9M<br>135枚<br>Δ —<br>IV 183%</td></tr>
</tbody>
</table>

推定の向きは最後の約定の位置（売り気配で約定＝買い）と、前回の実行からの IV の上下（今回は前回の記録なし）から。買い・売りの分かる大口は代金の 78%。誰の取引かは分かりません。表の『代金・枚数』は、代金・その日の出来高・Δ（デルタ換算。株を何ドル分買った＋・売った−のと同じ向きか）・IV。

### 詳しく

**まとめ**: 下の支えの候補 **30**（−6.3%）・28（−12.6%）・25（−21.9%）。上の重さの候補 **35**（+9.3%）・38（+18.7%）・40（+24.9%）。既に割れたプットの壁 40（+24.9%）。次の満期（11/27・1日）の想定の幅 ±13.0%（27.86〜36.19）。ガンマはプラス側（ゼロガンマ 31.77）→ 値動きが小さくなりやすい。

**下の支えの候補**（プットの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>32</td><td nowrap>−0.1%</td><td nowrap>6,205</td><td nowrap>3%</td></tr>
<tr><td nowrap>30</td><td nowrap>−6.3%</td><td nowrap>29,356</td><td nowrap>13%</td></tr>
<tr><td nowrap>28</td><td nowrap>−12.6%</td><td nowrap>7,822</td><td nowrap>4%</td></tr>
<tr><td nowrap>26</td><td nowrap>−18.8%</td><td nowrap>6,505</td><td nowrap>3%</td></tr>
<tr><td nowrap>25</td><td nowrap>−21.9%</td><td nowrap>54,068</td><td nowrap>25%</td></tr>
</tbody>
</table>

**上の重さの候補**（コールの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>35</td><td nowrap>+9.3%</td><td nowrap>20,029</td><td nowrap>11%</td></tr>
<tr><td nowrap>36</td><td nowrap>+12.4%</td><td nowrap>14,651</td><td nowrap>8%</td></tr>
<tr><td nowrap>37</td><td nowrap>+15.6%</td><td nowrap>19,353</td><td nowrap>11%</td></tr>
<tr><td nowrap>38</td><td nowrap>+18.7%</td><td nowrap>20,966</td><td nowrap>11%</td></tr>
<tr><td nowrap>40</td><td nowrap>+24.9%</td><td nowrap>61,490</td><td nowrap>34%</td></tr>
</tbody>
</table>

**次の満期 11/27（1日）**: プットの壁 25（−21.9%）・コールの壁 40（+24.9%）・最大の痛み 36（+12.4%）・想定の幅 ±13.0%

アウト・オブ・ザ・マネーに払われた代金: プット 30.5百万ドル・コール 45.8百万ドル（プットの割合 40%）

**建玉の増減**: 前回の記録（前回のオプション分析 11/25）と建玉が同じため、出せません（建玉の公表がまだ更新されていない可能性）

**全体**: IV30 207%・7日 251%・期間構造 1.22（目先の不安が強い）・プットの割高さ +15.0pt・建玉のプット/コール 0.81

**過去の検証**: 未検証（第190回で、2008〜2025年の QQQ・SPY・NVDA・AVGO・AMD・QCOM・TXN の板で確かめ中）。それまでは、下の目安は過去の効きが確かめられていない参考の値です。

## SOXS　62.13

米国 11/26 22:46（取引時間外）・直近の取引日 11/25・板 Yahoo

> 今の板が崩れているため（気配のある契約が 0%（取引時間外の崩れた板の可能性））、**前回の有効な実行（日本時間 2026-11-27 12:46・板 Yahoo）の結果**を載せています。同じ取引日（11/25）の約定・建玉なので、内容は今と同じです。

### 結論

<table>
<thead><tr><th nowrap>問い</th><th nowrap>答え</th></tr></thead>
<tbody>
<tr><td nowrap>建玉の偏り</td><td nowrap><b>コール（買う権利）</b><br><b>のほうが多い</b><br><b>（いつもとの比較はまだできない）</b><br>（プット 33%・コール 67%）</td></tr>
<tr><td nowrap>σ（側）</td><td nowrap><b>—</b></td></tr>
<tr><td nowrap>前日から</td><td nowrap><b>—</b><br>（前日の記録と比べられません<br>（σ を出せない日））</td></tr>
<tr><td nowrap>大きなプット</td><td nowrap>50 (−19.5%)<br>55 (−11.5%)<br>45 (−27.6%)</td></tr>
<tr><td nowrap>大きなコール☆</td><td nowrap>80 (+28.8%)<br>60 (−3.4%)<br>78 (+25.5%)</td></tr>
</tbody>
</table>

- σ: ①の毎日の記録が 0日分しかなく、σ を出せません（10日たまると出ます）。
- 大きなプット・コールの印: ★ 偏っている側、☆ 偏りは小さいが数の多い側。『○/○』は、枚数/金額（建玉 × 値段 × 100）が過去30日の平常の何倍か。
- 偏りの物差し: 満期まで 3〜75日の全ての建玉（①の毎日の記録と同じ）。建玉には買い手と売り手が同じ数だけいるので、偏りはコールとプットの数で見ています。

**プットの大きな建玉の枚数とお金**（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>50</b> OTM</td><td nowrap>5,177 (<b>—</b>)</td><td nowrap>1.95M (<b>—</b>)</td></tr>
<tr><td nowrap><b>55</b> OTM</td><td nowrap>2,089 (<b>—</b>)</td><td nowrap>0.74M (<b>—</b>)</td></tr>
<tr><td nowrap><b>45</b> OTM</td><td nowrap>1,956 (<b>—</b>)</td><td nowrap>0.35M (<b>—</b>)</td></tr>
<tr><td nowrap><b>52</b> OTM</td><td nowrap>1,766 (<b>—</b>)</td><td nowrap>0.44M (<b>—</b>)</td></tr>
<tr><td nowrap><b>60</b> OTM</td><td nowrap>1,732 (<b>—</b>)</td><td nowrap>1.09M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

**コールの大きな建玉の枚数とお金**（数の多い側）（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>80</b> OTM</td><td nowrap>10,217 (<b>—</b>)</td><td nowrap>5.01M (<b>—</b>)</td></tr>
<tr><td nowrap><b>60</b> ITM</td><td nowrap>5,155 (<b>—</b>)</td><td nowrap>5.47M (<b>—</b>)</td></tr>
<tr><td nowrap><b>78</b> OTM</td><td nowrap>3,190 (<b>—</b>)</td><td nowrap>3.16M (<b>—</b>)</td></tr>
<tr><td nowrap><b>55</b> 超ITM</td><td nowrap>3,129 (<b>—</b>)</td><td nowrap>4.37M (<b>—</b>)</td></tr>
<tr><td nowrap><b>65</b> OTM</td><td nowrap>2,676 (<b>—</b>)</td><td nowrap>2.42M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

- 枚数の平常比は同じ側・同じ順位（過去の各日の、枚数が同じ順位の建玉）、金額の平常比は同じ側の過去の大きな建玉（各日の上位5本）と比べた倍率。▲▲ 30日で最多・▲ 多い（上位25%）・▼ 少ない（下位25%）・▼▼ 30日で最少。印が無ければ平常並み。建玉の合計も▲なら、満期（特に3・6・9・12月の第3金曜）に向けて全体が増えている分を差し引いて見てください。金額は建玉 × 値段 × 100（ITM は本質的な価値を含む。今の板）。

**プットの大きな建玉**（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>50</b> (−19.5%)</td><td nowrap>5,177 (20%)</td><td nowrap>11/27 $0.29</td></tr>
<tr><td nowrap><b>55</b> (−11.5%)</td><td nowrap>2,089 (8%)</td><td nowrap>11/27 $1.09</td></tr>
<tr><td nowrap><b>45</b> (−27.6%)</td><td nowrap>1,956 (8%)</td><td nowrap>11/27 $0.20</td></tr>
<tr><td nowrap><b>52</b> (−16.3%)</td><td nowrap>1,766 (7%)</td><td nowrap>11/27 $0.46</td></tr>
<tr><td nowrap><b>60</b> (−3.4%)</td><td nowrap>1,732 (7%)</td><td nowrap>11/27 $2.73</td></tr>
</tbody>
</table>

**コールの大きな建玉**（数の多い側）（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>80</b> (+28.8%)</td><td nowrap>10,217 (21%)</td><td nowrap>12/4 $5.12</td></tr>
<tr><td nowrap><b>60</b> (−3.4%)</td><td nowrap>5,155 (11%)</td><td nowrap>11/27 $4.97</td></tr>
<tr><td nowrap><b>78</b> (+25.5%)</td><td nowrap>3,190 (7%)</td><td nowrap>12/24 $12.40</td></tr>
<tr><td nowrap><b>55</b> (−11.5%)</td><td nowrap>3,129 (6%)</td><td nowrap>11/27 $8.65</td></tr>
<tr><td nowrap><b>65</b> (+4.6%)</td><td nowrap>2,676 (6%)</td><td nowrap>11/27 $2.91</td></tr>
</tbody>
</table>

### オプションの配置（図）

![SOXS のオプションの配置](SOXS_options_chart.svg)

- 今の株価でのガンマの合計は**プラス**（+3百万ドル／1%）。
- 上の段: 株価がその値になったときの、ディーラーのガンマの合計（赤い点線がゼロガンマ）。赤い背景（マイナス）の価格帯では、ディーラーが下げで売り・上げで買うので値動きが大きくなりやすく、緑の背景（プラス）では小さくなりやすい。
- 中の段: 行使価格ごとのガンマ（コールは上、プットは下）。下の段: 行使価格ごとの建玉（45日以内の満期）と、プットの壁・コールの壁（灰色の点線）。黒い線が今の株価。

### 大口の賭け（推定）

**ベア 🐻・強さ 小**（売買代金の 0.2%） — SOXS は逆レバ3倍。半導体に直すと **ブル 🐂**

- 大口のデルタ換算（株を何ドル分買った・売ったのと同じ向きか）: 差 **−11.1百万ドル**（ブル側 +16.0百万ドル・ベア側 −27.1百万ドル）。代金はブル側 6.3百万ドル・ベア側 8.7百万ドル。1日の売買代金 63.9億ドル（20日の平均）
- 大口が見ている価格: 上値の重し（コール売り） **125**（+101.2%）・上げの的（コール買い） **120**（+93.1%）
- 深い ITM の大口（合計に入れない）: 3本・代金 1.9百万ドル（12/18 40C買・2/19 41C（向き不明）・2/19 40C買）。株と組み合わせた取引（配当の裁定・乗り換えなど）のことが多い。そのまま賭けとみると +2.3百万ドル 分

<table>
<thead><tr><th nowrap>契約</th><th nowrap>推定・意味</th><th nowrap>代金・枚数</th></tr></thead>
<tbody>
<tr><td nowrap>12/18 125C<br>+101.2%<br>建玉 528</td><td nowrap><b>売り</b><br>上値の重し<br>（原指数には逆）</td><td nowrap>$8.7M<br>15,966枚<br>Δ −$27M<br>IV 295%</td></tr>
<tr><td nowrap>12/18 120C<br>+93.1%<br>建玉 6,423</td><td nowrap><b>買い</b><br>上げへの賭け<br>（原指数には逆）</td><td nowrap>$1.8M<br>3,121枚<br>Δ +$5.6M<br>IV 292%</td></tr>
<tr><td nowrap>12/18 100C<br>+61.0%<br>建玉 3,457</td><td nowrap><b>買い</b><br>上げへの賭け<br>（原指数には逆）</td><td nowrap>$0.9M<br>1,185枚<br>Δ +$2.7M<br>IV 280%</td></tr>
<tr><td nowrap>12/4 120C<br>+93.1%<br>建玉 2,528</td><td nowrap><b>買い寄り</b><br>上げへの賭け<br>（原指数には逆）</td><td nowrap>$0.8M<br>5,699枚<br>Δ +$2.1M<br>IV 315%</td></tr>
<tr><td nowrap>12/31 75C<br>+20.7%<br>建玉 39</td><td nowrap><b>買い寄り</b><br>上げへの賭け<br>（原指数には逆）</td><td nowrap>$0.6M<br>411枚<br>Δ +$0.7M<br>IV 239%</td></tr>
<tr><td nowrap>12/31 47C<br>−24.4%<br>建玉 64</td><td nowrap><b>買い</b><br>上げへの賭け<br>（ITM）<br>（原指数には逆）</td><td nowrap>$0.5M<br>204枚<br>Δ +$1.0M<br>IV 214%</td></tr>
<tr><td nowrap>12/31 95C<br>+52.9%<br>建玉 21</td><td nowrap><b>買い</b><br>上げへの賭け<br>（原指数には逆）</td><td nowrap>$0.4M<br>420枚<br>Δ +$1.1M<br>IV 252%</td></tr>
<tr><td nowrap>12/11 75P<br>+20.7%<br>建玉 6</td><td nowrap><b>売り</b><br>下値の防御線<br>（ITM）<br>（原指数には逆）</td><td nowrap>$0.4M<br>204枚<br>Δ +$0.7M<br>IV 244%</td></tr>
<tr><td nowrap>12/18 95C<br>+52.9%<br>建玉 1,243</td><td nowrap><b>買い</b><br>上げへの賭け<br>（原指数には逆）</td><td nowrap>$0.4M<br>505枚<br>Δ +$1.2M<br>IV 279%</td></tr>
<tr><td nowrap>1/15 75C<br>+20.7%<br>建玉 320</td><td nowrap><b>買い</b><br>上げへの賭け<br>（原指数には逆）</td><td nowrap>$0.4M<br>252枚<br>Δ +$0.9M<br>IV 230%</td></tr>
<tr><td nowrap>12/18 40C<br>−35.6%<br>建玉 470</td><td nowrap><b>買い</b><br>深い ITM の買い</td><td nowrap>$0.9M<br>367枚<br>Δ +$1.9M<br>IV 234%</td></tr>
<tr><td nowrap>2/19 41C<br>−34.0%<br>建玉 109</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$0.5M<br>160枚<br>Δ —<br>IV 191%</td></tr>
<tr><td nowrap>2/19 40C<br>−35.6%<br>建玉 232</td><td nowrap><b>買い寄り</b><br>深い ITM の買い</td><td nowrap>$0.5M<br>151枚<br>Δ +$0.4M<br>IV 190%</td></tr>
</tbody>
</table>

推定の向きは最後の約定の位置（売り気配で約定＝買い）と、前回の実行からの IV の上下（今回は前回の記録なし）から。買い・売りの分かる大口は代金の 100%。誰の取引かは分かりません。表の『代金・枚数』は、代金・その日の出来高・Δ（デルタ換算。株を何ドル分買った＋・売った−のと同じ向きか）・IV。

### 詳しく

**まとめ**: 下の支えの候補 **55**（−11.5%）・50（−19.5%）・45（−27.6%）。上の重さの候補 **65**（+4.6%）・78（+25.5%）・80（+28.8%）。次の満期（11/27・1日）の想定の幅 ±11.9%（54.75〜69.51）。ガンマはプラス側（ゼロガンマ —）→ 値動きが小さくなりやすい。

**下の支えの候補**（プットの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>60</td><td nowrap>−3.4%</td><td nowrap>1,732</td><td nowrap>7%</td></tr>
<tr><td nowrap>55</td><td nowrap>−11.5%</td><td nowrap>2,089</td><td nowrap>8%</td></tr>
<tr><td nowrap>52</td><td nowrap>−16.3%</td><td nowrap>1,766</td><td nowrap>7%</td></tr>
<tr><td nowrap>50</td><td nowrap>−19.5%</td><td nowrap>5,177</td><td nowrap>20%</td></tr>
<tr><td nowrap>45</td><td nowrap>−27.6%</td><td nowrap>1,956</td><td nowrap>8%</td></tr>
</tbody>
</table>

**上の重さの候補**（コールの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>65</td><td nowrap>+4.6%</td><td nowrap>2,676</td><td nowrap>6%</td></tr>
<tr><td nowrap>70</td><td nowrap>+12.7%</td><td nowrap>2,644</td><td nowrap>5%</td></tr>
<tr><td nowrap>75</td><td nowrap>+20.7%</td><td nowrap>1,283</td><td nowrap>3%</td></tr>
<tr><td nowrap>78</td><td nowrap>+25.5%</td><td nowrap>3,190</td><td nowrap>7%</td></tr>
<tr><td nowrap>80</td><td nowrap>+28.8%</td><td nowrap>10,217</td><td nowrap>21%</td></tr>
</tbody>
</table>

**次の満期 11/27（1日）**: プットの壁 50（−19.5%）・コールの壁 80（+28.8%）・最大の痛み 55（−11.5%）・想定の幅 ±11.9%

アウト・オブ・ザ・マネーに払われた代金: プット 5.3百万ドル・コール 22.5百万ドル（プットの割合 19%）

**建玉の増減**: 前回の記録（前回のオプション分析 11/25）と建玉が同じため、出せません（建玉の公表がまだ更新されていない可能性）

**全体**: IV30 227%・7日 269%・期間構造 1.19（目先の不安が強い）・プットの割高さ −9.3pt・建玉のプット/コール 0.57

**過去の検証**: 未検証（第190回で、2008〜2025年の QQQ・SPY・NVDA・AVGO・AMD・QCOM・TXN の板で確かめ中）。それまでは、下の目安は過去の効きが確かめられていない参考の値です。

## QQQ　633.93

米国 11/26 22:46（取引時間外）・直近の取引日 11/25・板 Yahoo

> 今の板が崩れているため（気配のある契約が 3%（取引時間外の崩れた板の可能性））、**前回の有効な実行（日本時間 2026-11-27 12:46・板 Yahoo）の結果**を載せています。同じ取引日（11/25）の約定・建玉なので、内容は今と同じです。

### 結論

<table>
<thead><tr><th nowrap>問い</th><th nowrap>答え</th></tr></thead>
<tbody>
<tr><td nowrap>建玉の偏り</td><td nowrap><b>いつも並み（偏りは小さい）</b><br>（プット 50%・コール 50%）</td></tr>
<tr><td nowrap>σ（側）</td><td nowrap><b>コール側に 0.8σ</b><br><b>（1σ 未満で、偏りは小さい）</b></td></tr>
<tr><td nowrap>前日から</td><td nowrap><b>ほとんど動いていない</b><br><b>（0.0σ）</b><br>（11/24 コール側に 0.8σ<br>（プット÷コール 1.00）<br>→ 今 コール側に 0.8σ<br>（1.00））</td></tr>
<tr><td nowrap>大きなプット☆</td><td nowrap>550 (−13.2%) 0.73▼/0.21▼<br>600 (−5.4%) 0.82▼/0.62<br>580 (−8.5%) 0.81▼/0.36▼</td></tr>
<tr><td nowrap>大きなコール</td><td nowrap>700 (+10.4%) 1.2▲/1.7<br>680 (+7.3%) 1.1▲/3.7▲<br>720 (+13.6%) 1.1▲/0.52</td></tr>
</tbody>
</table>

- σ: いつも（10/9〜11/24 の 25日）のプット÷コールは平均 1.19、今は 1.00。記録が60日たまるまでは目安。
- 大きなプット・コールの印: ★ 偏っている側、☆ 偏りは小さいが数の多い側。『○/○』は、枚数/金額（建玉 × 値段 × 100）が過去30日の平常の何倍か。
- 偏りの物差し: 満期まで 3〜75日の全ての建玉（①の毎日の記録と同じ）。建玉には買い手と売り手が同じ数だけいるので、偏りはコールとプットの数で見ています。

**プットの大きな建玉の枚数とお金**（数の多い側）（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>550</b> OTM</td><td nowrap>134,658<br>(<b>0.73▼</b>)</td><td nowrap>38.9M (<b>0.21▼</b>)</td></tr>
<tr><td nowrap><b>600</b> OTM</td><td nowrap>129,457<br>(<b>0.82▼</b>)</td><td nowrap>114M (<b>0.62</b>)</td></tr>
<tr><td nowrap><b>580</b> OTM</td><td nowrap>118,993<br>(<b>0.81▼</b>)</td><td nowrap>66.9M (<b>0.36▼</b>)</td></tr>
<tr><td nowrap><b>650</b> ITM</td><td nowrap>115,517<br>(<b>0.88▼</b>)</td><td nowrap>320M (<b>1.7▲</b>)</td></tr>
<tr><td nowrap><b>640</b> ATM</td><td nowrap>112,279 (<b>1.0</b>)</td><td nowrap>241M (<b>1.3</b>)</td></tr>
</tbody>
</table>

- 平常（11/6〜11/24 の 13日、うち 10日は値段を推定）の中央値: 枚数 1番目 183,492枚・2番目 157,873枚・3番目 147,429枚・4番目 130,953枚・5番目 111,618枚。金額 184Mドル（大きなプット 65本）。30日分の記録がたまるまでは目安。
- プットの建玉の合計（45日以内・株価の ±30%）: 3,086,671枚＝平常の0.97倍。

**コールの大きな建玉の枚数とお金**（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>700</b> OTM</td><td nowrap>211,523 (<b>1.2▲</b>)</td><td nowrap>26.5M (<b>1.7</b>)</td></tr>
<tr><td nowrap><b>680</b> OTM</td><td nowrap>153,527 (<b>1.1▲</b>)</td><td nowrap>58.2M (<b>3.7▲</b>)</td></tr>
<tr><td nowrap><b>720</b> OTM</td><td nowrap>130,531 (<b>1.1▲</b>)</td><td nowrap>8.16M (<b>0.52</b>)</td></tr>
<tr><td nowrap><b>715</b> OTM</td><td nowrap>106,604 (<b>1.0</b>)</td><td nowrap>12.1M (<b>0.77</b>)</td></tr>
<tr><td nowrap><b>690</b> OTM</td><td nowrap>103,369 (<b>1.0</b>)</td><td nowrap>23.2M (<b>1.5</b>)</td></tr>
</tbody>
</table>

- 平常（11/6〜11/24 の 13日、うち 10日は値段を推定）の中央値: 枚数 1番目 181,157枚・2番目 141,667枚・3番目 122,745枚・4番目 106,992枚・5番目 101,539枚。金額 15.7Mドル（大きなコール 65本）。30日分の記録がたまるまでは目安。
- コールの建玉の合計（45日以内・株価の ±30%）: 2,952,903枚＝平常の1.0倍。

- 枚数の平常比は同じ側・同じ順位（過去の各日の、枚数が同じ順位の建玉）、金額の平常比は同じ側の過去の大きな建玉（各日の上位5本）と比べた倍率。▲▲ 30日で最多・▲ 多い（上位25%）・▼ 少ない（下位25%）・▼▼ 30日で最少。印が無ければ平常並み。建玉の合計も▲なら、満期（特に3・6・9・12月の第3金曜）に向けて全体が増えている分を差し引いて見てください。金額は建玉 × 値段 × 100（ITM は本質的な価値を含む。今の板）。

**プットの大きな建玉**（数の多い側）（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>550</b> (−13.2%)</td><td nowrap>134,658 (4%)</td><td nowrap>12/18 $4.40</td></tr>
<tr><td nowrap><b>600</b> (−5.4%)</td><td nowrap>129,457 (4%)</td><td nowrap>12/18 $11.61</td></tr>
<tr><td nowrap><b>580</b> (−8.5%)</td><td nowrap>118,993 (4%)</td><td nowrap>12/18 $7.87</td></tr>
<tr><td nowrap><b>650</b> (+2.5%)</td><td nowrap>115,517 (4%)</td><td nowrap>12/18 $29.86</td></tr>
<tr><td nowrap><b>640</b> (+1.0%)</td><td nowrap>112,279 (4%)</td><td nowrap>12/18 $24.91</td></tr>
</tbody>
</table>

**コールの大きな建玉**（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>700</b> (+10.4%)</td><td nowrap>211,523 (7%)</td><td nowrap>12/18 $1.85</td></tr>
<tr><td nowrap><b>680</b> (+7.3%)</td><td nowrap>153,527 (5%)</td><td nowrap>12/18 $4.84</td></tr>
<tr><td nowrap><b>720</b> (+13.6%)</td><td nowrap>130,531 (4%)</td><td nowrap>12/18 $0.68</td></tr>
<tr><td nowrap><b>715</b> (+12.8%)</td><td nowrap>106,604 (4%)</td><td nowrap>12/18 $0.87</td></tr>
<tr><td nowrap><b>690</b> (+8.8%)</td><td nowrap>103,369 (4%)</td><td nowrap>12/18 $3.06</td></tr>
</tbody>
</table>

### オプションの配置（図）

![QQQ のオプションの配置](QQQ_options_chart.svg)

- 今の株価でのガンマの合計は**マイナス**（−3,822百万ドル／1%）、ゼロガンマは **659.80**（+4.1%）。
- 上の段: 株価がその値になったときの、ディーラーのガンマの合計（赤い点線がゼロガンマ）。赤い背景（マイナス）の価格帯では、ディーラーが下げで売り・上げで買うので値動きが大きくなりやすく、緑の背景（プラス）では小さくなりやすい。
- 中の段: 行使価格ごとのガンマ（コールは上、プットは下）。下の段: 行使価格ごとの建玉（45日以内の満期）と、プットの壁・コールの壁（灰色の点線）。黒い線が今の株価。

### 大口の賭け（推定）

**はっきりしない**（ブルとベアが拮抗（差は合計の 3%））

- 大口のデルタ換算（株を何ドル分買った・売ったのと同じ向きか）: 差 **+1.1億ドル**（ブル側 +16.4億ドル・ベア側 −15.3億ドル）。代金はブル側 1.4億ドル・ベア側 1.5億ドル。1日の売買代金 419.8億ドル（20日の平均）
- 大口が見ている価格: 下値の防御線（プット売り） **635**（+0.2%）・上値の重し（コール売り） **680**（+7.3%）・下げの的（プット買い） **600**（−5.4%）
- 深い ITM の大口（合計に入れない）: 3本・代金 3.5億ドル（12/18 725P買・12/18 735P買・11/30 700P売）。株と組み合わせた取引（配当の裁定・乗り換えなど）のことが多い。そのまま賭けとみると −6.7億ドル 分

<table>
<thead><tr><th nowrap>契約</th><th nowrap>推定・意味</th><th nowrap>代金・枚数</th></tr></thead>
<tbody>
<tr><td nowrap>12/4 635P<br>+0.2%<br>建玉 42,672</td><td nowrap><b>売り</b><br>下値の防御線</td><td nowrap>$53M<br>33,122枚<br>Δ +$1.0B<br>IV 42%</td></tr>
<tr><td nowrap>12/18 600P<br>−5.4%<br>建玉 68,681</td><td nowrap><b>買い</b><br>下げへの賭け・<br>守り<br>組の片側かも</td><td nowrap>$39M<br>33,591枚<br>Δ −$590M<br>IV 41%</td></tr>
<tr><td nowrap>12/18 610P<br>−3.8%<br>建玉 56,295</td><td nowrap><b>売り寄り</b><br>下値の防御線<br>組の片側かも</td><td nowrap>$38M<br>26,963枚<br>Δ +$281M<br>IV 40%</td></tr>
<tr><td nowrap>1/15 680C<br>+7.3%<br>建玉 19,376</td><td nowrap><b>売り寄り</b><br>上値の重し</td><td nowrap>$33M<br>31,147枚<br>Δ −$268M<br>IV 29%</td></tr>
<tr><td nowrap>1/15 600P<br>−5.4%<br>建玉 37,752</td><td nowrap><b>買い</b><br>下げへの賭け・<br>守り</td><td nowrap>$32M<br>18,194枚<br>Δ −$360M<br>IV 35%</td></tr>
<tr><td nowrap>3/19 650P<br>+2.5%<br>建玉 45,616</td><td nowrap><b>売り</b><br>下値の防御線<br>（ITM）</td><td nowrap>$28M<br>6,143枚<br>Δ +$210M<br>IV 26%</td></tr>
<tr><td nowrap>12/18 650C<br>+2.5%<br>建玉 24,243</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$26M<br>17,190枚<br>Δ —<br>IV 35%</td></tr>
<tr><td nowrap>1/15 610P<br>−3.8%<br>建玉 32,247</td><td nowrap><b>買い寄り</b><br>下げへの賭け・<br>守り</td><td nowrap>$25M<br>12,083枚<br>Δ −$136M<br>IV 34%</td></tr>
<tr><td nowrap>1/15 610C<br>−3.8%<br>建玉 2,334</td><td nowrap><b>買い寄り</b><br>上げへの賭け<br>（ITM）</td><td nowrap>$23M<br>5,022枚<br>Δ +$102M<br>IV 36%</td></tr>
<tr><td nowrap>12/18 580P<br>−8.5%<br>建玉 67,327</td><td nowrap><b>買い寄り</b><br>下げへの賭け・<br>守り<br>組の片側かも</td><td nowrap>$23M<br>28,733枚<br>Δ −$176M<br>IV 45%</td></tr>
<tr><td nowrap>12/18 725P<br>+14.4%<br>建玉 5,315</td><td nowrap><b>買い</b><br>深い ITM の買い</td><td nowrap>$126M<br>13,708枚<br>Δ −$842M<br>IV 29%</td></tr>
<tr><td nowrap>12/18 735P<br>+15.9%<br>建玉 3,119</td><td nowrap><b>買い寄り</b><br>深い ITM の買い</td><td nowrap>$116M<br>11,369枚<br>Δ −$350M<br>IV 31%</td></tr>
<tr><td nowrap>11/30 700P<br>+10.4%<br>建玉 3,026</td><td nowrap><b>売り寄り</b><br>深い ITM の売り</td><td nowrap>$114M<br>17,060枚<br>Δ +$520M<br>IV 53%</td></tr>
</tbody>
</table>

推定の向きは最後の約定の位置（売り気配で約定＝買い）と、前回の実行からの IV の上下から。買い・売りの分かる大口は代金の 92%。誰の取引かは分かりません。表の『代金・枚数』は、代金・その日の出来高・Δ（デルタ換算。株を何ドル分買った＋・売った−のと同じ向きか）・IV。

### 詳しく

**まとめ**: 下の支えの候補 **600**（−5.4%）・580（−8.5%）・550（−13.2%）。上の重さの候補 **680**（+7.3%）・700（+10.4%）・720（+13.6%）。次の満期（11/27・1日）の想定の幅 ±2.1%（620.60〜647.25）。ガンマはマイナス側（ゼロガンマ 659.80）→ 値動きが大きくなりやすい。

**下の支えの候補**（プットの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>610</td><td nowrap>−3.8%</td><td nowrap>103,301</td><td nowrap>3%</td></tr>
<tr><td nowrap>600</td><td nowrap>−5.4%</td><td nowrap>129,457</td><td nowrap>4%</td></tr>
<tr><td nowrap>590</td><td nowrap>−6.9%</td><td nowrap>89,102</td><td nowrap>3%</td></tr>
<tr><td nowrap>580</td><td nowrap>−8.5%</td><td nowrap>118,993</td><td nowrap>4%</td></tr>
<tr><td nowrap>550</td><td nowrap>−13.2%</td><td nowrap>134,658</td><td nowrap>4%</td></tr>
</tbody>
</table>

**上の重さの候補**（コールの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>680</td><td nowrap>+7.3%</td><td nowrap>153,527</td><td nowrap>5%</td></tr>
<tr><td nowrap>690</td><td nowrap>+8.8%</td><td nowrap>103,369</td><td nowrap>4%</td></tr>
<tr><td nowrap>700</td><td nowrap>+10.4%</td><td nowrap>211,523</td><td nowrap>7%</td></tr>
<tr><td nowrap>715</td><td nowrap>+12.8%</td><td nowrap>106,604</td><td nowrap>4%</td></tr>
<tr><td nowrap>720</td><td nowrap>+13.6%</td><td nowrap>130,531</td><td nowrap>4%</td></tr>
</tbody>
</table>

**次の満期 11/27（1日）**: プットの壁 550（−13.2%）・コールの壁 700（+10.4%）・最大の痛み 644（+1.6%）・想定の幅 ±2.1%

アウト・オブ・ザ・マネーに払われた代金: プット 632.0百万ドル・コール 295.8百万ドル（プットの割合 68%）

**建玉の増減**（①の日次の記録の 11/24 → 今の板。45日以内の満期）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>距離</th><th nowrap>増減</th><th nowrap>想定元本</th></tr></thead>
<tbody>
<tr><td nowrap>510P</td><td nowrap>−19.5%</td><td nowrap>+34,494</td><td nowrap>1,759.2百万ドル</td></tr>
<tr><td nowrap>690C</td><td nowrap>+8.8%</td><td nowrap>+34,215</td><td nowrap>2,360.8百万ドル</td></tr>
<tr><td nowrap>605P</td><td nowrap>−4.6%</td><td nowrap>+25,225</td><td nowrap>1,526.1百万ドル</td></tr>
<tr><td nowrap>690P</td><td nowrap>+8.8%</td><td nowrap>−16,579</td><td nowrap>−1,144.0百万ドル</td></tr>
<tr><td nowrap>725P</td><td nowrap>+14.4%</td><td nowrap>−12,881</td><td nowrap>−933.9百万ドル</td></tr>
</tbody>
</table>

合計: プット 6,052.4百万ドル・コール 9,998.0百万ドル（想定元本の増減）

**全体**: IV30 34%・7日 42%・期間構造 1.22（目先の不安が強い）・プットの割高さ +9.0pt・建玉のプット/コール 1.06

**過去の検証**: 未検証（第190回で、2008〜2025年の QQQ・SPY・NVDA・AVGO・AMD・QCOM・TXN の板で確かめ中）。それまでは、下の目安は過去の効きが確かめられていない参考の値です。

## TQQQ　45.28

米国 11/26 22:46（取引時間外）・直近の取引日 11/25・板 Yahoo

> 今の板が崩れているため（気配のある契約が 0%（取引時間外の崩れた板の可能性））、**前回の有効な実行（日本時間 2026-11-27 12:46・板 Yahoo）の結果**を載せています。同じ取引日（11/25）の約定・建玉なので、内容は今と同じです。

### 結論

<table>
<thead><tr><th nowrap>問い</th><th nowrap>答え</th></tr></thead>
<tbody>
<tr><td nowrap>建玉の偏り</td><td nowrap><b>コール（買う権利）</b><br><b>のほうが多い</b><br><b>（いつもとの比較はまだできない）</b><br>（プット 37%・コール 63%）</td></tr>
<tr><td nowrap>σ（側）</td><td nowrap><b>—</b></td></tr>
<tr><td nowrap>前日から</td><td nowrap><b>—</b><br>（前日の記録と比べられません<br>（σ を出せない日））</td></tr>
<tr><td nowrap>大きなプット</td><td nowrap>40 (−11.7%)<br>45 (−0.6%)<br>50 (+10.4%)</td></tr>
<tr><td nowrap>大きなコール☆</td><td nowrap>50 (+10.4%)<br>55 (+21.5%)<br>58 (+28.1%)</td></tr>
</tbody>
</table>

- σ: ①の毎日の記録が 0日分しかなく、σ を出せません（10日たまると出ます）。
- 大きなプット・コールの印: ★ 偏っている側、☆ 偏りは小さいが数の多い側。『○/○』は、枚数/金額（建玉 × 値段 × 100）が過去30日の平常の何倍か。
- 偏りの物差し: 満期まで 3〜75日の全ての建玉（①の毎日の記録と同じ）。建玉には買い手と売り手が同じ数だけいるので、偏りはコールとプットの数で見ています。

**プットの大きな建玉の枚数とお金**（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> OTM</td><td nowrap>37,848 (<b>—</b>)</td><td nowrap>6.95M (<b>—</b>)</td></tr>
<tr><td nowrap><b>45</b> ATM</td><td nowrap>28,255 (<b>—</b>)</td><td nowrap>9.27M (<b>—</b>)</td></tr>
<tr><td nowrap><b>50</b> 超ITM</td><td nowrap>25,938 (<b>—</b>)</td><td nowrap>16.9M (<b>—</b>)</td></tr>
<tr><td nowrap><b>35</b> OTM</td><td nowrap>24,257 (<b>—</b>)</td><td nowrap>2.43M (<b>—</b>)</td></tr>
<tr><td nowrap><b>55</b> 超ITM</td><td nowrap>21,443 (<b>—</b>)</td><td nowrap>22.9M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

**コールの大きな建玉の枚数とお金**（数の多い側）（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>50</b> OTM</td><td nowrap>23,309 (<b>—</b>)</td><td nowrap>3.80M (<b>—</b>)</td></tr>
<tr><td nowrap><b>55</b> OTM</td><td nowrap>20,484 (<b>—</b>)</td><td nowrap>1.19M (<b>—</b>)</td></tr>
<tr><td nowrap><b>58</b> OTM</td><td nowrap>12,212 (<b>—</b>)</td><td nowrap>0.47M (<b>—</b>)</td></tr>
<tr><td nowrap><b>57</b> OTM</td><td nowrap>12,094 (<b>—</b>)</td><td nowrap>0.57M (<b>—</b>)</td></tr>
<tr><td nowrap><b>54</b> OTM</td><td nowrap>11,051 (<b>—</b>)</td><td nowrap>0.58M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

- 枚数の平常比は同じ側・同じ順位（過去の各日の、枚数が同じ順位の建玉）、金額の平常比は同じ側の過去の大きな建玉（各日の上位5本）と比べた倍率。▲▲ 30日で最多・▲ 多い（上位25%）・▼ 少ない（下位25%）・▼▼ 30日で最少。印が無ければ平常並み。建玉の合計も▲なら、満期（特に3・6・9・12月の第3金曜）に向けて全体が増えている分を差し引いて見てください。金額は建玉 × 値段 × 100（ITM は本質的な価値を含む。今の板）。

**プットの大きな建玉**（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> (−11.7%)</td><td nowrap>37,848 (14%)</td><td nowrap>12/18 $2.78</td></tr>
<tr><td nowrap><b>45</b> (−0.6%)</td><td nowrap>28,255 (11%)</td><td nowrap>12/18 $4.60</td></tr>
<tr><td nowrap><b>50</b> (+10.4%)</td><td nowrap>25,938 (10%)</td><td nowrap>12/18 $7.40</td></tr>
<tr><td nowrap><b>35</b> (−22.7%)</td><td nowrap>24,257 (9%)</td><td nowrap>12/18 $1.54</td></tr>
<tr><td nowrap><b>55</b> (+21.5%)</td><td nowrap>21,443 (8%)</td><td nowrap>12/18 $11.03</td></tr>
</tbody>
</table>

**コールの大きな建玉**（数の多い側）（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>50</b> (+10.4%)</td><td nowrap>23,309 (15%)</td><td nowrap>12/11 $2.04</td></tr>
<tr><td nowrap><b>55</b> (+21.5%)</td><td nowrap>20,484 (13%)</td><td nowrap>11/27 $0.01</td></tr>
<tr><td nowrap><b>58</b> (+28.1%)</td><td nowrap>12,212 (8%)</td><td nowrap>11/27 $0.01</td></tr>
<tr><td nowrap><b>57</b> (+25.9%)</td><td nowrap>12,094 (8%)</td><td nowrap>12/18 $0.68</td></tr>
<tr><td nowrap><b>54</b> (+19.3%)</td><td nowrap>11,051 (7%)</td><td nowrap>11/27 $0.03</td></tr>
</tbody>
</table>

### オプションの配置（図）

![TQQQ のオプションの配置](TQQQ_options_chart.svg)

- 今の株価でのガンマの合計は**プラス**（+1百万ドル／1%）、ゼロガンマは **44.86**（−0.9%）。
- 上の段: 株価がその値になったときの、ディーラーのガンマの合計（赤い点線がゼロガンマ）。赤い背景（マイナス）の価格帯では、ディーラーが下げで売り・上げで買うので値動きが大きくなりやすく、緑の背景（プラス）では小さくなりやすい。
- 中の段: 行使価格ごとのガンマ（コールは上、プットは下）。下の段: 行使価格ごとの建玉（45日以内の満期）と、プットの壁・コールの壁（灰色の点線）。黒い線が今の株価。

### 大口の賭け（推定）

**はっきりしない**（ブルとベアが拮抗（差は合計の 2%）） — TQQQ はレバ3倍。ナスダック100に直すと **はっきりしない**

- 大口のデルタ換算（株を何ドル分買った・売ったのと同じ向きか）: 差 **+0.4百万ドル**（ブル側 +10.5百万ドル・ベア側 −10.1百万ドル）。代金はブル側 4.4百万ドル・ベア側 3.7百万ドル。1日の売買代金 62.5億ドル（20日の平均）
- 大口が見ている価格: 下値の防御線（プット売り） **40**（−11.7%）・上げの的（コール買い） **50**（+10.4%）・下げの的（プット買い） **30**（−33.7%）
- 深い ITM の大口（合計に入れない）: 3本・代金 12.1百万ドル（1/15 77P（向き不明）・1/15 76P買・1/15 70P（向き不明））。株と組み合わせた取引（配当の裁定・乗り換えなど）のことが多い。そのまま賭けとみると −3.6百万ドル 分

<table>
<thead><tr><th nowrap>契約</th><th nowrap>推定・意味</th><th nowrap>代金・枚数</th></tr></thead>
<tbody>
<tr><td nowrap>12/18 51C<br>+12.6%<br>建玉 1,049</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$3.6M<br>16,147枚<br>Δ —<br>IV 97%</td></tr>
<tr><td nowrap>3/19 50C<br>+10.4%<br>建玉 6,108</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$1.8M<br>2,848枚<br>Δ —<br>IV 81%</td></tr>
<tr><td nowrap>3/19 30P<br>−33.7%<br>建玉 8,827</td><td nowrap><b>買い</b><br>下げへの賭け・<br>守り</td><td nowrap>$1.6M<br>5,745枚<br>Δ −$4.1M<br>IV 102%</td></tr>
<tr><td nowrap>1/15 50C<br>+10.4%<br>建玉 16,935</td><td nowrap><b>買い寄り</b><br>上げへの賭け</td><td nowrap>$1.5M<br>3,753枚<br>Δ +$3.7M<br>IV 87%</td></tr>
<tr><td nowrap>12/4 42C<br>−7.2%<br>建玉 73</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$1.1M<br>2,135枚<br>Δ —<br>IV 135%</td></tr>
<tr><td nowrap>12/11 51P<br>+12.6%<br>建玉 787</td><td nowrap><b>買い寄り</b><br>下げへの賭け・<br>守り（ITM）</td><td nowrap>$1.1M<br>1,483枚<br>Δ −$2.3M<br>IV 103%</td></tr>
<tr><td nowrap>3/19 40C<br>−11.7%<br>建玉 881</td><td nowrap><b>買い寄り</b><br>上げへの賭け<br>（ITM）</td><td nowrap>$1.1M<br>970枚<br>Δ +$1.5M<br>IV 88%</td></tr>
<tr><td nowrap>12/31 40C<br>−11.7%<br>建玉 205</td><td nowrap><b>売り</b><br>上値の重し<br>（ITM）</td><td nowrap>$1.0M<br>1,183枚<br>Δ −$3.8M<br>IV 105%</td></tr>
<tr><td nowrap>12/18 40P<br>−11.7%<br>建玉 12,923</td><td nowrap><b>売り寄り</b><br>下値の防御線</td><td nowrap>$0.9M<br>3,328枚<br>Δ +$2.1M<br>IV 120%</td></tr>
<tr><td nowrap>1/15 40C<br>−11.7%<br>建玉 9,445</td><td nowrap><b>買い</b><br>上げへの賭け<br>（ITM）</td><td nowrap>$0.9M<br>975枚<br>Δ +$3.1M<br>IV 101%</td></tr>
<tr><td nowrap>1/15 77P<br>+70.1%<br>建玉 344</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$7.7M<br>2,398枚<br>Δ —<br>IV 87%</td></tr>
<tr><td nowrap>1/15 76P<br>+67.8%<br>建玉 129</td><td nowrap><b>買い</b><br>深い ITM の買い</td><td nowrap>$2.7M<br>879枚<br>Δ −$3.6M<br>IV 92%</td></tr>
<tr><td nowrap>1/15 70P<br>+54.6%<br>建玉 3,833</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$1.6M<br>658枚<br>Δ —<br>IV 71%</td></tr>
</tbody>
</table>

推定の向きは最後の約定の位置（売り気配で約定＝買い）と、前回の実行からの IV の上下（今回は前回の記録なし）から。買い・売りの分かる大口は代金の 55%。誰の取引かは分かりません。表の『代金・枚数』は、代金・その日の出来高・Δ（デルタ換算。株を何ドル分買った＋・売った−のと同じ向きか）・IV。

### 詳しく

**まとめ**: 下の支えの候補 **45**（−0.6%）・40（−11.7%）・35（−22.7%）。上の重さの候補 **50**（+10.4%）・55（+21.5%）・58（+28.1%）。既に割れたプットの壁 50（+10.4%）。次の満期（11/27・1日）の想定の幅 ±6.4%（42.37〜48.19）。ガンマはプラス側（ゼロガンマ 44.86）→ 値動きが小さくなりやすい。

**下の支えの候補**（プットの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>45</td><td nowrap>−0.6%</td><td nowrap>28,255</td><td nowrap>11%</td></tr>
<tr><td nowrap>43</td><td nowrap>−5.0%</td><td nowrap>7,328</td><td nowrap>3%</td></tr>
<tr><td nowrap>42</td><td nowrap>−7.2%</td><td nowrap>7,566</td><td nowrap>3%</td></tr>
<tr><td nowrap>40</td><td nowrap>−11.7%</td><td nowrap>37,848</td><td nowrap>14%</td></tr>
<tr><td nowrap>35</td><td nowrap>−22.7%</td><td nowrap>24,257</td><td nowrap>9%</td></tr>
</tbody>
</table>

**上の重さの候補**（コールの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>50</td><td nowrap>+10.4%</td><td nowrap>23,309</td><td nowrap>15%</td></tr>
<tr><td nowrap>54</td><td nowrap>+19.3%</td><td nowrap>11,051</td><td nowrap>7%</td></tr>
<tr><td nowrap>55</td><td nowrap>+21.5%</td><td nowrap>20,484</td><td nowrap>13%</td></tr>
<tr><td nowrap>57</td><td nowrap>+25.9%</td><td nowrap>12,094</td><td nowrap>8%</td></tr>
<tr><td nowrap>58</td><td nowrap>+28.1%</td><td nowrap>12,212</td><td nowrap>8%</td></tr>
</tbody>
</table>

**次の満期 11/27（1日）**: プットの壁 40（−11.7%）・コールの壁 55（+21.5%）・最大の痛み 50（+10.4%）・想定の幅 ±6.4%

アウト・オブ・ザ・マネーに払われた代金: プット 12.2百万ドル・コール 22.4百万ドル（プットの割合 35%）

**建玉の増減**: 前回の記録（前回のオプション分析 11/25）と建玉が同じため、出せません（建玉の公表がまだ更新されていない可能性）

**全体**: IV30 100%・7日 123%・期間構造 1.24（目先の不安が強い）・プットの割高さ +9.9pt・建玉のプット/コール 0.58

**過去の検証**: 未検証（第190回で、2008〜2025年の QQQ・SPY・NVDA・AVGO・AMD・QCOM・TXN の板で確かめ中）。それまでは、下の目安は過去の効きが確かめられていない参考の値です。

## SQQQ　49.60

米国 11/26 22:46（取引時間外）・直近の取引日 11/25・板 Yahoo

> 今の板が崩れているため（気配のある契約が 3%（取引時間外の崩れた板の可能性））、**前回の有効な実行（日本時間 2026-11-27 12:46・板 Yahoo）の結果**を載せています。同じ取引日（11/25）の約定・建玉なので、内容は今と同じです。

### 結論

<table>
<thead><tr><th nowrap>問い</th><th nowrap>答え</th></tr></thead>
<tbody>
<tr><td nowrap>建玉の偏り</td><td nowrap><b>コール（買う権利）</b><br><b>のほうが多い</b><br><b>（いつもとの比較はまだできない）</b><br>（プット 40%・コール 60%）</td></tr>
<tr><td nowrap>σ（側）</td><td nowrap><b>—</b></td></tr>
<tr><td nowrap>前日から</td><td nowrap><b>—</b><br>（前日の記録と比べられません<br>（σ を出せない日））</td></tr>
<tr><td nowrap>大きなプット</td><td nowrap>40 (−19.4%)<br>36 (−27.4%)<br>45 (−9.3%)</td></tr>
<tr><td nowrap>大きなコール☆</td><td nowrap>55 (+10.9%)<br>60 (+21.0%)<br>50 (+0.8%)</td></tr>
</tbody>
</table>

- σ: ①の毎日の記録が 0日分しかなく、σ を出せません（10日たまると出ます）。
- 大きなプット・コールの印: ★ 偏っている側、☆ 偏りは小さいが数の多い側。『○/○』は、枚数/金額（建玉 × 値段 × 100）が過去30日の平常の何倍か。
- 偏りの物差し: 満期まで 3〜75日の全ての建玉（①の毎日の記録と同じ）。建玉には買い手と売り手が同じ数だけいるので、偏りはコールとプットの数で見ています。

**プットの大きな建玉の枚数とお金**（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> OTM</td><td nowrap>3,646 (<b>—</b>)</td><td nowrap>0.22M (<b>—</b>)</td></tr>
<tr><td nowrap><b>36</b> OTM</td><td nowrap>2,933 (<b>—</b>)</td><td nowrap>0.03M (<b>—</b>)</td></tr>
<tr><td nowrap><b>45</b> OTM</td><td nowrap>2,626 (<b>—</b>)</td><td nowrap>0.33M (<b>—</b>)</td></tr>
<tr><td nowrap><b>41</b> OTM</td><td nowrap>2,571 (<b>—</b>)</td><td nowrap>0.07M (<b>—</b>)</td></tr>
<tr><td nowrap><b>42</b> OTM</td><td nowrap>2,563 (<b>—</b>)</td><td nowrap>0.23M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

**コールの大きな建玉の枚数とお金**（数の多い側）（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>55</b> OTM</td><td nowrap>16,262 (<b>—</b>)</td><td nowrap>3.34M (<b>—</b>)</td></tr>
<tr><td nowrap><b>60</b> OTM</td><td nowrap>14,978 (<b>—</b>)</td><td nowrap>1.12M (<b>—</b>)</td></tr>
<tr><td nowrap><b>50</b> ATM</td><td nowrap>12,048 (<b>—</b>)</td><td nowrap>4.57M (<b>—</b>)</td></tr>
<tr><td nowrap><b>35</b> 超ITM</td><td nowrap>11,738 (<b>—</b>)</td><td nowrap>17.4M (<b>—</b>)</td></tr>
<tr><td nowrap><b>48</b> ITM</td><td nowrap>10,206 (<b>—</b>)</td><td nowrap>5.04M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

- 枚数の平常比は同じ側・同じ順位（過去の各日の、枚数が同じ順位の建玉）、金額の平常比は同じ側の過去の大きな建玉（各日の上位5本）と比べた倍率。▲▲ 30日で最多・▲ 多い（上位25%）・▼ 少ない（下位25%）・▼▼ 30日で最少。印が無ければ平常並み。建玉の合計も▲なら、満期（特に3・6・9・12月の第3金曜）に向けて全体が増えている分を差し引いて見てください。金額は建玉 × 値段 × 100（ITM は本質的な価値を含む。今の板）。

**プットの大きな建玉**（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> (−19.4%)</td><td nowrap>3,646 (9%)</td><td nowrap>12/18 $0.86</td></tr>
<tr><td nowrap><b>36</b> (−27.4%)</td><td nowrap>2,933 (7%)</td><td nowrap>12/4 $0.05</td></tr>
<tr><td nowrap><b>45</b> (−9.3%)</td><td nowrap>2,626 (6%)</td><td nowrap>11/27 $0.15</td></tr>
<tr><td nowrap><b>41</b> (−17.3%)</td><td nowrap>2,571 (6%)</td><td nowrap>11/27 $0.06</td></tr>
<tr><td nowrap><b>42</b> (−15.3%)</td><td nowrap>2,563 (6%)</td><td nowrap>12/11 $1.06</td></tr>
</tbody>
</table>

**コールの大きな建玉**（数の多い側）（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>55</b> (+10.9%)</td><td nowrap>16,262 (12%)</td><td nowrap>11/27 $0.35</td></tr>
<tr><td nowrap><b>60</b> (+21.0%)</td><td nowrap>14,978 (11%)</td><td nowrap>11/27 $0.06</td></tr>
<tr><td nowrap><b>50</b> (+0.8%)</td><td nowrap>12,048 (9%)</td><td nowrap>12/18 $5.35</td></tr>
<tr><td nowrap><b>35</b> (−29.4%)</td><td nowrap>11,738 (9%)</td><td nowrap>12/18 $14.88</td></tr>
<tr><td nowrap><b>48</b> (−3.2%)</td><td nowrap>10,206 (8%)</td><td nowrap>12/18 $6.33</td></tr>
</tbody>
</table>

### オプションの配置（図）

![SQQQ のオプションの配置](SQQQ_options_chart.svg)

- 今の株価でのガンマの合計は**プラス**（+11百万ドル／1%）。
- 上の段: 株価がその値になったときの、ディーラーのガンマの合計（赤い点線がゼロガンマ）。赤い背景（マイナス）の価格帯では、ディーラーが下げで売り・上げで買うので値動きが大きくなりやすく、緑の背景（プラス）では小さくなりやすい。
- 中の段: 行使価格ごとのガンマ（コールは上、プットは下）。下の段: 行使価格ごとの建玉（45日以内の満期）と、プットの壁・コールの壁（灰色の点線）。黒い線が今の株価。

### 大口の賭け（推定）

**ブル 🐂・強さ 小**（売買代金の 0.3%） — SQQQ は逆レバ3倍。ナスダック100に直すと **ベア 🐻**

- 大口のデルタ換算（株を何ドル分買った・売ったのと同じ向きか）: 差 **+8.5百万ドル**（ブル側 +9.8百万ドル・ベア側 −1.3百万ドル）。代金はブル側 2.5百万ドル・ベア側 0.5百万ドル。1日の売買代金 32.3億ドル（20日の平均）
- 大口が見ている価格: 上値の重し（コール売り） **55**（+10.9%）
- 深い ITM の大口（合計に入れない）: 3本・代金 1.8百万ドル（12/18 37C買・12/18 40C売・1/15 27C（向き不明））。株と組み合わせた取引（配当の裁定・乗り換えなど）のことが多い。そのまま賭けとみると +3.6百万ドル 分

<table>
<thead><tr><th nowrap>契約</th><th nowrap>推定・意味</th><th nowrap>代金・枚数</th></tr></thead>
<tbody>
<tr><td nowrap>1/15 75C<br>+51.2%<br>建玉 1,956</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$1.8M<br>6,688枚<br>Δ —<br>IV 123%</td></tr>
<tr><td nowrap>12/31 42C<br>−15.3%<br>建玉 502</td><td nowrap><b>買い</b><br>上げへの賭け<br>（ITM）<br>（原指数には逆）</td><td nowrap>$1.4M<br>1,511枚<br>Δ +$5.8M<br>IV 85%</td></tr>
<tr><td nowrap>1/15 68P<br>+37.1%<br>建玉 412</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$0.5M<br>240枚<br>Δ —<br>IV 126%</td></tr>
<tr><td nowrap>12/18 55C<br>+10.9%<br>建玉 5,909</td><td nowrap><b>売り寄り</b><br>上値の重し<br>組の片側かも<br>（原指数には逆）</td><td nowrap>$0.5M<br>1,191枚<br>Δ −$1.3M<br>IV 124%</td></tr>
<tr><td nowrap>1/15 65C<br>+31.0%<br>建玉 10,669</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$0.4M<br>1,108枚<br>Δ —<br>IV 116%</td></tr>
<tr><td nowrap>12/18 60P<br>+21.0%<br>建玉 523</td><td nowrap><b>売り</b><br>下値の防御線<br>（ITM）<br>（原指数には逆）</td><td nowrap>$0.4M<br>305枚<br>Δ +$1.0M<br>IV 126%</td></tr>
<tr><td nowrap>3/19 50C<br>+0.8%<br>建玉 1,746</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$0.4M<br>364枚<br>Δ —<br>IV 92%</td></tr>
<tr><td nowrap>12/18 48C<br>−3.2%<br>建玉 5,662</td><td nowrap><b>買い</b><br>上げへの賭け<br>（ITM）<br>（原指数には逆）</td><td nowrap>$0.3M<br>514枚<br>Δ +$1.5M<br>IV 115%</td></tr>
<tr><td nowrap>12/18 45C<br>−9.3%<br>建玉 3,389</td><td nowrap><b>買い</b><br>上げへの賭け<br>（ITM）<br>（原指数には逆）</td><td nowrap>$0.3M<br>399枚<br>Δ +$1.4M<br>IV 110%</td></tr>
<tr><td nowrap>12/18 57C<br>+14.9%<br>建玉 315</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$0.3M<br>850枚<br>Δ —<br>IV 125%</td></tr>
<tr><td nowrap>12/18 37C<br>−25.4%<br>建玉 2,557</td><td nowrap><b>買い</b><br>深い ITM の買い</td><td nowrap>$1.3M<br>1,003枚<br>Δ +$4.7M<br>IV 83%</td></tr>
<tr><td nowrap>12/18 40C<br>−19.4%<br>建玉 4,909</td><td nowrap><b>売り</b><br>深い ITM の売り</td><td nowrap>$0.3M<br>263枚<br>Δ −$1.1M<br>IV 95%</td></tr>
<tr><td nowrap>1/15 27C<br>−45.6%<br>建玉 3</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$0.2M<br>100枚<br>Δ —<br>IV —</td></tr>
</tbody>
</table>

推定の向きは最後の約定の位置（売り気配で約定＝買い）と、前回の実行からの IV の上下（今回は前回の記録なし）から。買い・売りの分かる大口は代金の 46%。誰の取引かは分かりません。表の『代金・枚数』は、代金・その日の出来高・Δ（デルタ換算。株を何ドル分買った＋・売った−のと同じ向きか）・IV。

### 詳しく

**まとめ**: 下の支えの候補 **45**（−9.3%）・40（−19.4%）・36（−27.4%）。上の重さの候補 **50**（+0.8%）・55（+10.9%）・60（+21.0%）。既に割れたプットの壁 50（+0.8%）。次の満期（11/27・1日）の想定の幅 ±6.4%（46.41〜52.79）。ガンマはプラス側（ゼロガンマ —）→ 値動きが小さくなりやすい。

**下の支えの候補**（プットの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>45</td><td nowrap>−9.3%</td><td nowrap>2,626</td><td nowrap>6%</td></tr>
<tr><td nowrap>42</td><td nowrap>−15.3%</td><td nowrap>2,563</td><td nowrap>6%</td></tr>
<tr><td nowrap>41</td><td nowrap>−17.3%</td><td nowrap>2,571</td><td nowrap>6%</td></tr>
<tr><td nowrap>40</td><td nowrap>−19.4%</td><td nowrap>3,646</td><td nowrap>9%</td></tr>
<tr><td nowrap>36</td><td nowrap>−27.4%</td><td nowrap>2,933</td><td nowrap>7%</td></tr>
</tbody>
</table>

**上の重さの候補**（コールの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>50</td><td nowrap>+0.8%</td><td nowrap>12,048</td><td nowrap>9%</td></tr>
<tr><td nowrap>51</td><td nowrap>+2.8%</td><td nowrap>5,538</td><td nowrap>4%</td></tr>
<tr><td nowrap>52</td><td nowrap>+4.8%</td><td nowrap>2,738</td><td nowrap>2%</td></tr>
<tr><td nowrap>55</td><td nowrap>+10.9%</td><td nowrap>16,262</td><td nowrap>12%</td></tr>
<tr><td nowrap>60</td><td nowrap>+21.0%</td><td nowrap>14,978</td><td nowrap>11%</td></tr>
</tbody>
</table>

**次の満期 11/27（1日）**: プットの壁 41（−17.3%）・コールの壁 60（+21.0%）・最大の痛み 44.5（−10.3%）・想定の幅 ±6.4%

アウト・オブ・ザ・マネーに払われた代金: プット 1.1百万ドル・コール 8.7百万ドル（プットの割合 11%）

**建玉の増減**: 前回の記録（前回のオプション分析 11/25）と建玉が同じため、出せません（建玉の公表がまだ更新されていない可能性）

**全体**: IV30 105%・7日 124%・期間構造 1.18（目先の不安が強い）・プットの割高さ −6.7pt・建玉のプット/コール 0.59

**過去の検証**: 未検証（第190回で、2008〜2025年の QQQ・SPY・NVDA・AVGO・AMD・QCOM・TXN の板で確かめ中）。それまでは、下の目安は過去の効きが確かめられていない参考の値です。

### 見方

- 結論の『偏り』: 満期まで3〜75日の全ての建玉の、プット（売る権利）とコール（買う権利）の数。建玉には買い手と売り手が同じ数だけいるので、『買いと売り』の偏りは、コールとプットの数で見る（誰が買い手かは無料の板では分からない）。
- 結論の『σ』: 今の log（プット÷コール）が、①の毎日の記録（崩れた板の日を除く）の平均から、標準偏差の何倍ずれているか。1σ 以上で『偏っている』、2σ 以上で『大きく偏っている』。『プット側に 1.2σ』は、いつもよりプットが多いこと。記録は 2026-10 から貯めているので、60日たまるまでは目安。
- 結論の『前日からの動き』: 前日（判定日より前の、いちばん新しい記録の日）の偏りを同じ物差し（同じ平均と標準偏差）で測り、今との差。『コール側へ 0.8σ』は、前日よりコールが増えた（プットが減った）向きに 0.8σ 動いたこと。前の記録が7日より前なら、その旨を書く。
- 結論の『大きな建玉の価格』: プット・コールそれぞれの、建玉の多い行使価格（v5 から両方。偏っている側、偏りが1σ 未満の日は数の多い側に印）。45日以内の満期・株価の ±30%（壁と同じ範囲）。『その値段』は、その行使価格で建玉が最も多い満期の契約の、今の値段（買い・売りの気配の中値。無ければ最後の約定値）。
- 結論の『大きな建玉のお金』: 建玉（枚）× 今の値段 × 100（1枚は100株）。行使価格ごとに45日以内の満期を合計（opt_money.py）。X などに流れる大口の投稿と同じ数え方で、ITM（イン・ザ・マネー）の建玉は本質的な価値（株価が動いて増えた分）を含む。超ITM は10% 以上 ITM、ATM は株価の ±1% 以内。建玉には買い手と売り手が同じ数だけいるので、買いか売りかは分からない。
- 結論の『平常比』: 判定日より前の30日（暦日）の、同じ側（コール／プット）の大きな建玉（各日の、枚数の多い上位5本。①の毎日の記録）と比べた倍率。枚数は同じ順位と比べる（1番目は、過去の各日の1番目の中央値と。1番目はいつも大きいため）。金額は、過去の大きな建玉の金額（30日 × 5本）の中央値と比べる（順位で比べると ITM と OTM が入れ替わって値がぶれるため）。▲▲ は平常の最大を超える、▲ は上位25%、▼ は下位25%、▼▼ は平常の最小を下回る。記録は 2026-11-20 から。それより前（11/6〜11/19）は、①の建玉の記録と IV から値段を推定して埋めた。
- 建玉の壁: 45日以内の満期の、行使価格ごとの建玉の合計（opt_levels.py。過去の検証と同じ定義）。
- 想定の幅: 次の満期の、今の株価に最も近い行使価格のコール＋プットの値段 ÷ 株価。市場がその満期までに見込む動きの目安。
- ガンマ: コールの建玉はディーラーの買い持ち、プットの建玉は売り持ちと仮定。マイナス側は「下げで売り・上げで買う」になり、値動きが大きくなりやすい（第105回: 動きの大きさは分かるが、向きは分からない）。
- 図（オプションの配置）: ガンマは opt_features.py の GEX と同じ定義（コールの建玉はディーラーの買い持ち、プットは売り持ちと仮定。1契約のガンマ × 建玉 × 100株 × 株価² × 1%。株価が1%動いたときにディーラーが売り買いする額、百万ドル。満期は1〜120日）。上の段は、株価がその値になったときの合計（IV と建玉は今のまま）。ゼロガンマより下の価格帯はマイナスで、値動きが大きくなりやすい（向きは分からない）。板が崩れている日は、①の毎日の記録の IV（7日・30日・90% の行使価格の割高さ）から IV を近似するので、形の目安として見る。
- 板の出どころ: Yahoo。日本時間の昼〜夕方（米国の深夜〜朝）は気配が0になって崩れるため、同じ取引日の前回の有効な実行の結果を載せる（一覧の＊。④は毎朝 6:40・11:40 に自動で実行）。
- 大口の賭け（v6、opt_flow.py）: 直近の取引日の、代金（出来高 × 値段 × 100）の多い上位10契約（深い ITM を除く。代金5万ドル以上）と、深い ITM の上位3契約。満期まで2日以上（0〜1日の満期は、その日のうちの短い売買が多いので除く）。買い・売りは、最後の約定の値段が売り気配に近い（買い）か買い気配に近い（売り）かで推定する（0.8 以上・0.2 以下。0.65〜0.8・0.2〜0.35 は『寄り』で重み半分）。中間・気配なしのときは、前回の実行からの IV の上下（その銘柄の全体の上下を引いた分）が ±1.5pt 以上なら『寄り』とする。無料の板には約定ごとの記録が無く、最後の1回で代表させているので、その日全体の向きとずれることがある。誰の取引か（ヘッジファンドか）は分からない。
- 大口の『デルタ換算』: デルタ × 枚数 × 100株 × 株価。株を何ドル分買った（＋）・売った（−）のと同じ向きかの目安。深い ITM（デルタ 0.80 以上の ITM）は、株と組み合わせた取引（配当の裁定・乗り換え）が多いので、向きの合計に入れずに別に示す。同じ満期・同じ種類で、買いと売りの枚数がほぼ同じ組は『組（スプレッド）の片側かも』と書く。
- 大口の『意味』: コール買い＝上げへの賭け、コール売り＝上値の重し（その価格を超えないとみる）、プット買い＝下げへの賭け・守り、プット売り＝下値の防御線（その価格を割らないとみる）。逆レバ ETF（SOXS・SQQQ）は、その ETF の上げ＝原指数の下げ。
- 建玉の増減: 建玉は1日1回（前の営業日の引け時点）しか更新されない。場中に実行すると、前の営業日に積まれた分が出る。
- 道筋（v6.6、opt_path.py）: 今の株価から上・下へ、ゼロガンマ・建玉の壁（上位3本）・次の壁（最大の壁の先で、最大の壁の建玉の3割以上ある行使価格）・ガンマ最大の行使価格・ガンマの山（株価より上で合計が最大）・平らになる価格（ガンマの合計の傾きが、最も急な所の4分の1以下になる所。これより上は、上げてもディーラーのガンマがほとんど増えず、ニュートラルに近い）・ガンマの谷（株価より下で最も深い）を価格の順に並べる。次の壁を探す範囲は株価の ±30〜60%（45日の 2σ）。1% 以内の関門はまとめる。
- ゼロガンマの推定の幅: IV を 0.85倍・1.15倍にしたときのゼロガンマの範囲（最小でも ±1%）。今の株価がその中なら『境目』。ゼロガンマは IV の取り方や満期の範囲で数% ずれる（他のサイトの図と違うことがある）ので、境目の中ではプラス・マイナスを決めつけない。
- 満期の内訳: 壁の建玉（45日以内の満期）のうち、次の満期（満期まで1日以上の最も近い満期）で消える割合。6割以上は『消える玉』、3〜6割は『半分ほど消える』、3割未満は『残る玉』。満期の後は、その壁が薄くなる（壁の支え・重しが弱まる）。主な満期は、次の満期を除いて、ガンマが最大の契約の満期。
- 壁の動き: 建玉の増減（前回の記録から）と、直近の取引日の大口（買い・売りの推定）を、同じ行使価格で並べる。コール売り＋建玉の増加＝上の壁の建設・増強、プット売り＋建玉の増加＝下の防御線の建設・増強、コール買い＝上げの的、プット買い＝下げの的・守り。その日の取引が建玉に出るのは次の営業日。誰の取引かは分からない。
- 2つの筋書き: 壁の配置とガンマ・想定の幅からの読みで、確率ではない。ガンマは値動きの大きさの目安で、向きは分からない。
- 価格の換算: レバ ETF の壁を原指数の動きに直して、原指数・他のレバ ETF の価格に換算する。日々の倍率の調整による目減りを入れる（log(レバの価格の比) ＝ 倍率 × log(1 + 原指数の動き) − (倍率² − 倍率)/2 × σ² × 年数。σ はレバの IV30 ÷ |倍率|、年数はその壁の主な満期まで）。例: 3倍のレバ ETF の IV が 200% ほどのとき、5週間で +56% になるには、原指数は単純な3分の1（+19%）より大きい約 +22% の上げが要る。SOXL・SOXS の原指数は SOXX と同じ半導体の指数。SMH は別の指数だが、動きは近いので 1倍とみる。
- 板は米国の取引時間外（日本時間の昼〜夕方）に崩れることがある。日本時間 23:30〜翌12時ごろの実行が確実。
- 参考の情報で、ベンザイテンシステムの判定には使っていません。

私は投資助言者ではありません。数値は今の板と過去データから計算した目安で、将来を保証しません。
