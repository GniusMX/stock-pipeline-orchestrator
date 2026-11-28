# ベンザイテンシステム オプション分析（参考・判定には使いません）

取得 日本時間 2026-11-28 11:23（米国 11/27 21:23）・銘柄 SMH SOXX SOXL SOXS QQQ TQQQ SQQQ

## 結論の一覧

<table>
<thead><tr><th nowrap>銘柄</th><th nowrap>建玉の偏り</th><th nowrap>σ（前日比）</th></tr></thead>
<tbody>
<tr><td nowrap>SMH<br>440.06</td><td nowrap>いつも並み</td><td nowrap>コール 0.4σ<br>前日 動きなし</td></tr>
<tr><td nowrap>SOXX<br>134.07</td><td nowrap>ほぼ半々</td><td nowrap>記録待ち</td></tr>
<tr><td nowrap>SOXL<br>36.57</td><td nowrap>コールが多い</td><td nowrap>記録待ち</td></tr>
<tr><td nowrap>SOXS<br>52.94</td><td nowrap>コールが多い</td><td nowrap>記録待ち</td></tr>
<tr><td nowrap>QQQ<br>650.99</td><td nowrap>いつも並み</td><td nowrap>コール 0.7σ<br>前日→プット0.1σ</td></tr>
<tr><td nowrap>TQQQ<br>48.85</td><td nowrap>コールが多い</td><td nowrap>記録待ち</td></tr>
<tr><td nowrap>SQQQ<br>45.76</td><td nowrap>コールが多い</td><td nowrap>記録待ち</td></tr>
</tbody>
</table>

## 道筋の要約（上と下の関門）

<table>
<thead><tr><th nowrap>銘柄・ガンマ</th><th nowrap>上の関門</th><th nowrap>下の関門</th></tr></thead>
<tbody>
<tr><td nowrap><b>SMH</b> 440.06<br>ガンマ マイナス<br>（ゼロ 465）</td><td nowrap>465◇→520▲→550▲</td><td nowrap>400▼→295▼(100%消)</td></tr>
<tr><td nowrap><b>SOXX</b> 134.07<br>ガンマ マイナス<br>（ゼロ 159）</td><td nowrap>145▲→160▲</td><td nowrap>120▼→100▼</td></tr>
<tr><td nowrap><b>SOXL</b> 36.57<br>ガンマ プラス</td><td nowrap>40▲</td><td nowrap>30▼→25▼</td></tr>
<tr><td nowrap><b>SOXS</b> 52.94<br>ガンマ プラス</td><td nowrap>65▲(35%消)→78▲</td><td nowrap>40▼→30▼(40%消)</td></tr>
<tr><td nowrap><b>QQQ</b> 650.99<br>ガンマ マイナス<br>（ゼロ 669）</td><td nowrap>669◇→680▲→715▲</td><td nowrap>600▼→550▼</td></tr>
<tr><td nowrap><b>TQQQ</b> 48.85<br>ガンマ プラス<br>（ゼロ 43.6）</td><td nowrap>60▲→70▲</td><td nowrap>43.6◇→40▼</td></tr>
<tr><td nowrap><b>SQQQ</b> 45.76<br>ガンマ プラス</td><td nowrap>55▲→65▲(58%消)</td><td nowrap>40▼(35%消)→36▼(97%消)</td></tr>
</tbody>
</table>

◇ ゼロガンマ（超える・割るとガンマの符号が変わる）・▲ コールの壁（最大と次の壁）・▼ プットの壁（最大と次の支え）。（○%消）は、その壁の建玉のうち次の満期で消える割合（3割以上のとき）。境目は、ゼロガンマの推定の幅の中にいること。各銘柄の『道筋』に詳しい表。


## 大口の賭け（ヘッジファンドなどの大口の向き・推定）

<table>
<thead><tr><th nowrap>銘柄・向き・強さ</th><th nowrap>主な賭け</th></tr></thead>
<tbody>
<tr><td nowrap><b>SMH</b> 原指数<br>ベア 🐻 中</td><td nowrap>12/18 397.5C売 $4.4M<br>12/18 400P買 $3.1M</td></tr>
<tr><td nowrap><b>SOXX</b> 原指数<br>ベア 🐻 小</td><td nowrap>12/4 130C売 $3.9M<br>12/31 140C買 $1.6M</td></tr>
<tr><td nowrap><b>SOXL</b> レバ3倍<br>ベア 🐻 小<br>→原指数 ベア 🐻</td><td nowrap>12/4 35C売 $3.2M<br>12/4 40C売 $2.3M</td></tr>
<tr><td nowrap><b>SOXS</b> 逆レバ3倍<br>ブル 🐂 小<br>→原指数 ベア 🐻</td><td nowrap>12/4 60C売 $0.9M<br>12/4 60P売 $0.5M</td></tr>
<tr><td nowrap><b>QQQ</b> 原指数<br>ブル 🐂 大</td><td nowrap>11/30 645C買 $17M<br>11/30 650C買 $17M</td></tr>
<tr><td nowrap><b>TQQQ</b> レバ3倍<br>ベア 🐻 小<br>→原指数 ベア 🐻</td><td nowrap>12/4 48C売 $0.8M<br>1/15 50C買 $0.8M</td></tr>
<tr><td nowrap><b>SQQQ</b> 逆レバ3倍<br>ブル 🐂 小<br>→原指数 ベア 🐻</td><td nowrap>12/31 42C買 $1.1M<br>1/15 68P売 $0.6M</td></tr>
</tbody>
</table>

向きは、大口（その日の代金の多い上位10契約。深い ITM を除く）ごとに買い・売りを推定し、コール買い・プット売り＝ブル（上げ）、コール売り・プット買い＝ベア（下げ）としてデルタ換算で足した差。強さは、その差がその ETF の1日の売買代金の何% か（1% 未満 小・3% 未満 中・10% 未満 大・それ以上 特大。記録が20回たまったら、過去の記録の中の順位）。主な賭けは代金の多い順（買＝買い、売＝売り）。深い ITM は向きの合計に入れていません。

## レバ系 vs 原指数

<table>
<thead><tr><th nowrap>群</th><th nowrap>半導体</th><th nowrap>ナスダック100</th></tr></thead>
<tbody>
<tr><td nowrap>原指数</td><td nowrap>ベア 🐻 小<br>−1.3億ドル<br>SMH＋SOXX</td><td nowrap>ブル 🐂 大<br>+28.3億ドル<br>QQQ</td></tr>
<tr><td nowrap>レバ系</td><td nowrap>ベア 🐻 小<br>−98.5百万ドル<br>SOXL＋SOXS</td><td nowrap>ベア 🐻 小<br>−38.2百万ドル<br>TQQQ＋SQQQ</td></tr>
<tr><td nowrap>見立て</td><td nowrap>同じ向き（ベア）</td><td nowrap>逆向き<br>（原指数はブル・<br>レバ系はベア）</td></tr>
</tbody>
</table>

レバ系は原指数の向きに直した額（SOXL・TQQQ は ×3、SOXS・SQQQ は ×−3。SOXS のコール買い＝半導体へのベア）。強さは、原指数に直した1日の売買代金に対する割合。レバ系のオプションは個人の売買が多く、原指数（SMH・SOXX・QQQ）は機関の守り（ヘッジ）が多いとされる。 IV（30日）: SMH 58%・SOXX 64%・SOXL 203%・SOXS 197%・QQQ 29%・TQQQ 89%・SQQQ 91%。


## 価格の換算（レバ系と原指数の壁を、原指数の動きにそろえる）

**半導体**（原指数の動きにそろえた価格。太字がその銘柄の壁）

<table>
<thead><tr><th nowrap>原指数</th><th nowrap>SMH</th><th nowrap>SOXX</th><th nowrap>SOXL</th><th nowrap>SOXS</th></tr></thead>
<tbody>
<tr><td nowrap>+25.0%<br>12/18</td><td nowrap><b>550▲</b></td><td nowrap>168</td><td nowrap>66.0</td><td nowrap>23.4</td></tr>
<tr><td nowrap>◎+16.9%</td><td nowrap><b>500▲</b></td><td nowrap><b>160▲◇</b></td><td nowrap>56.0</td><td nowrap><b>30▼</b></td></tr>
<tr><td nowrap>+11.9%<br>12/18</td><td nowrap>492</td><td nowrap><b>150▲</b></td><td nowrap>47.3</td><td nowrap>32.6</td></tr>
<tr><td nowrap>◎+6.5%</td><td nowrap><b>465◇</b></td><td nowrap><b>145▲</b></td><td nowrap><b>40▲</b></td><td nowrap><b>40▼</b></td></tr>
<tr><td nowrap>−3.9%<br>12/18</td><td nowrap>423</td><td nowrap>129</td><td nowrap><b>30▼</b></td><td nowrap>51.4</td></tr>
<tr><td nowrap>−6.8%<br>12/18</td><td nowrap>410</td><td nowrap><b>125▼</b></td><td nowrap>27.4</td><td nowrap>56.3</td></tr>
<tr><td nowrap>◎−10.4%</td><td nowrap><b>400▼</b></td><td nowrap><b>120▼</b></td><td nowrap><b>25▼</b></td><td nowrap><b>65▲</b></td></tr>
<tr><td nowrap>◎−18.3%</td><td nowrap><b>350▼</b></td><td nowrap>109</td><td nowrap>18.3</td><td nowrap><b>78▲</b></td></tr>
</tbody>
</table>

**ナスダック100**（原指数の動きにそろえた価格。太字がその銘柄の壁）

<table>
<thead><tr><th nowrap>原指数</th><th nowrap>QQQ</th><th nowrap>TQQQ</th><th nowrap>SQQQ</th></tr></thead>
<tbody>
<tr><td nowrap>+13.3%<br>12/18</td><td nowrap>738</td><td nowrap><b>70▲</b></td><td nowrap>30.5</td></tr>
<tr><td nowrap>+9.8%<br>12/18</td><td nowrap><b>715▲</b></td><td nowrap>63.7</td><td nowrap>33.5</td></tr>
<tr><td nowrap>◎+4.9%</td><td nowrap><b>680▲◇</b></td><td nowrap><b>60▲</b></td><td nowrap><b>40▼</b></td></tr>
<tr><td nowrap>◎+0.5%</td><td nowrap><b>650▼</b></td><td nowrap><b>50▲</b></td><td nowrap>43.9</td></tr>
<tr><td nowrap>◎−3.8%<br>12/18</td><td nowrap>626</td><td nowrap><b>43.6◇</b></td><td nowrap><b>50▲</b></td></tr>
<tr><td nowrap>◎−6.9%<br>12/18</td><td nowrap><b>600▼</b></td><td nowrap><b>40▼</b></td><td nowrap><b>55▲</b></td></tr>
<tr><td nowrap>−11.7%<br>12/11</td><td nowrap>575</td><td nowrap>33.3</td><td nowrap><b>65▲</b></td></tr>
<tr><td nowrap>◎−15.0%<br>12/18</td><td nowrap><b>550▼</b></td><td nowrap><b>30▼</b></td><td nowrap>72.3</td></tr>
</tbody>
</table>

換算: レバ ETF の価格 ＝ 原指数の動きの倍率乗 × 日々の倍率の調整による目減り（SOXL・TQQQ は 3倍、SOXS・SQQQ は −3倍。SMH と SOXX は 1倍とみる）。目減りは、レバの IV30 ÷ 倍率を原指数の変動の大きさとし、その壁の主な満期（原指数の欄の日付）までの日数で計算（変動が IV より小さければ、目減りも小さい）。途中の値動きの道筋で実際の値はずれる。▲ コールの壁・▼ プットの壁・◇ ゼロガンマ（その銘柄の。SOXS・SQQQ のコールの壁は、原指数では下げの側）。◎ は、2つ以上の銘柄の壁が原指数の動きで ±1.5% 以内（レバ ETF の壁は、目減りの見積もりのぶれの半分だけ広げる）に重なる価格。


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
<tr><td nowrap>SMH<br>プット☆</td><td nowrap>400 (−9.1%)<br>500 (+13.6%)<br>350 (−20.5%)</td><td nowrap>0.26▼▼/1.7<br>0.34▼▼/7.1▲<br>0.32▼▼/0.26</td></tr>
<tr><td nowrap>SMH<br>コール</td><td nowrap>520 (+18.2%)<br>550 (+25.0%)<br>465 (+5.7%)</td><td nowrap>0.72▼▼/0.79<br>0.53▼▼/0.26▼<br>0.58▼/1.6</td></tr>
<tr><td nowrap>SOXX<br>プット☆</td><td nowrap>120 (−10.5%)<br>125 (−6.8%)<br>150 (+11.9%)</td><td nowrap>—</td></tr>
<tr><td nowrap>SOXX<br>コール</td><td nowrap>145 (+8.2%)<br>140 (+4.4%)<br>160 (+19.3%)</td><td nowrap>—</td></tr>
<tr><td nowrap>SOXL<br>プット</td><td nowrap>40 (+9.4%)<br>30 (−18.0%)<br>35 (−4.3%)</td><td nowrap>—</td></tr>
<tr><td nowrap>SOXL<br>コール☆</td><td nowrap>40 (+9.4%)<br>30 (−18.0%)<br>38 (+3.9%)</td><td nowrap>—</td></tr>
<tr><td nowrap>SOXS<br>プット</td><td nowrap>40 (−24.4%)<br>50 (−5.6%)<br>38 (−28.2%)</td><td nowrap>—</td></tr>
<tr><td nowrap>SOXS<br>コール☆</td><td nowrap>65 (+22.8%)<br>50 (−5.6%)<br>55 (+3.9%)</td><td nowrap>—</td></tr>
<tr><td nowrap>QQQ<br>プット☆</td><td nowrap>600 (−7.8%)<br>550 (−15.5%)<br>540 (−17.0%)</td><td nowrap>0.65▼/0.31▼<br>0.68▼▼/0.10▼<br>0.59▼▼/0.07▼▼</td></tr>
<tr><td nowrap>QQQ<br>コール</td><td nowrap>680 (+4.5%)<br>715 (+9.8%)<br>725 (+11.4%)</td><td nowrap>0.78▼/4.6▲<br>0.69▼▼/0.91<br>0.64▼▼/0.24</td></tr>
<tr><td nowrap>TQQQ<br>プット</td><td nowrap>40 (−18.1%)<br>50 (+2.4%)<br>45 (−7.9%)</td><td nowrap>—</td></tr>
<tr><td nowrap>TQQQ<br>コール☆</td><td nowrap>60 (+22.8%)<br>51 (+4.4%)<br>50 (+2.4%)</td><td nowrap>—</td></tr>
<tr><td nowrap>SQQQ<br>プット</td><td nowrap>40 (−12.6%)<br>42 (−8.2%)<br>36 (−21.3%)</td><td nowrap>—</td></tr>
<tr><td nowrap>SQQQ<br>コール☆</td><td nowrap>35 (−23.5%)<br>55 (+20.2%)<br>50 (+9.3%)</td><td nowrap>—</td></tr>
</tbody>
</table>

σ は、いつも（①の毎日の記録）と比べた偏りの大きさと、偏っている側です（1σ 以上で偏り、2σ 以上で大きな偏り）。『前日から』は、前日の記録からどちら側へ何σ動いたか。行使価格の横は株価からの距離。『枚数/金額』は、その建玉の枚数と入っているお金（建玉 × 値段 × 100）が、過去30日の同じ側の平常の何倍か（▲▲ 30日で最多・▲ 多い・▼ 少ない・▼▼ 30日で最少）。図と詳しい表は各銘柄の【結論】、言葉の意味は最後の『見方』。

## SMH　440.06

米国 11/27 21:23（取引時間外）・直近の取引日 11/27・板 Yahoo

### 結論

<table>
<thead><tr><th nowrap>問い</th><th nowrap>答え</th></tr></thead>
<tbody>
<tr><td nowrap>建玉の偏り</td><td nowrap><b>いつも並み（偏りは小さい）</b><br>（プット 54%・コール 46%）</td></tr>
<tr><td nowrap>σ（側）</td><td nowrap><b>コール側に 0.4σ</b><br><b>（1σ 未満で、偏りは小さい）</b></td></tr>
<tr><td nowrap>前日から</td><td nowrap><b>ほとんど動いていない</b><br><b>（0.0σ）</b><br>（11/25 コール側に 0.4σ<br>（プット÷コール 1.19）<br>→ 今 コール側に 0.4σ<br>（1.19））</td></tr>
<tr><td nowrap>大きなプット☆</td><td nowrap>400 (−9.1%) 0.26▼▼/1.7<br>500 (+13.6%)<br>0.34▼▼/7.1▲<br>350 (−20.5%) 0.32▼▼/0.26</td></tr>
<tr><td nowrap>大きなコール</td><td nowrap>520 (+18.2%) 0.72▼▼/0.79<br>550 (+25.0%)<br>0.53▼▼/0.26▼<br>465 (+5.7%) 0.58▼/1.6</td></tr>
</tbody>
</table>

- σ: いつも（10/9〜11/25 の 26日）のプット÷コールは平均 1.30、今は 1.19。記録が60日たまるまでは目安。
- 大きなプット・コールの印: ★ 偏っている側、☆ 偏りは小さいが数の多い側。『○/○』は、枚数/金額（建玉 × 値段 × 100）が過去30日の平常の何倍か。
- 偏りの物差し: 満期まで 3〜75日の全ての建玉（①の毎日の記録と同じ）。建玉には買い手と売り手が同じ数だけいるので、偏りはコールとプットの数で見ています。

**プットの大きな建玉の枚数とお金**（数の多い側）（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>400</b> OTM</td><td nowrap>17,906<br>(<b>0.26▼▼</b>)</td><td nowrap>21.2M (<b>1.7</b>)</td></tr>
<tr><td nowrap><b>500</b> 超ITM</td><td nowrap>13,991<br>(<b>0.34▼▼</b>)</td><td nowrap>91.2M (<b>7.1▲</b>)</td></tr>
<tr><td nowrap><b>350</b> OTM</td><td nowrap>8,736<br>(<b>0.32▼▼</b>)</td><td nowrap>3.29M (<b>0.26</b>)</td></tr>
<tr><td nowrap><b>410</b> OTM</td><td nowrap>8,419 (<b>0.33▼</b>)</td><td nowrap>8.89M (<b>0.69</b>)</td></tr>
<tr><td nowrap><b>425</b> OTM</td><td nowrap>7,306<br>(<b>0.30▼▼</b>)</td><td nowrap>12.9M (<b>1.0</b>)</td></tr>
</tbody>
</table>

- 平常（11/6〜11/25 の 14日、うち 10日は値段を推定）の中央値: 枚数 1番目 68,185枚・2番目 40,971枚・3番目 27,562枚・4番目 25,844枚・5番目 24,276枚。金額 12.8Mドル（大きなプット 70本）。30日分の記録がたまるまでは目安。
- プットの建玉の合計（45日以内・株価の ±30%）: 168,597枚＝平常の0.31倍 ▼▼。

**コールの大きな建玉の枚数とお金**（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>520</b> OTM</td><td nowrap>17,710<br>(<b>0.72▼▼</b>)</td><td nowrap>2.22M (<b>0.79</b>)</td></tr>
<tr><td nowrap><b>550</b> OTM</td><td nowrap>10,406<br>(<b>0.53▼▼</b>)</td><td nowrap>0.74M (<b>0.26▼</b>)</td></tr>
<tr><td nowrap><b>465</b> OTM</td><td nowrap>8,709 (<b>0.58▼</b>)</td><td nowrap>4.60M (<b>1.6</b>)</td></tr>
<tr><td nowrap><b>540</b> OTM</td><td nowrap>7,218 (<b>0.61▼</b>)</td><td nowrap>0.76M (<b>0.27▼</b>)</td></tr>
<tr><td nowrap><b>500</b> OTM</td><td nowrap>7,125 (<b>0.66▼</b>)</td><td nowrap>1.25M (<b>0.45</b>)</td></tr>
</tbody>
</table>

- 平常（11/6〜11/25 の 14日、うち 10日は値段を推定）の中央値: 枚数 1番目 24,568枚・2番目 19,687枚・3番目 14,930枚・4番目 11,772枚・5番目 10,736枚。金額 2.79Mドル（大きなコール 70本）。30日分の記録がたまるまでは目安。
- コールの建玉の合計（45日以内・株価の ±30%）: 145,942枚＝平常の0.58倍 ▼。

- 枚数の平常比は同じ側・同じ順位（過去の各日の、枚数が同じ順位の建玉）、金額の平常比は同じ側の過去の大きな建玉（各日の上位5本）と比べた倍率。▲▲ 30日で最多・▲ 多い（上位25%）・▼ 少ない（下位25%）・▼▼ 30日で最少。印が無ければ平常並み。建玉の合計も▲なら、満期（特に3・6・9・12月の第3金曜）に向けて全体が増えている分を差し引いて見てください。金額は建玉 × 値段 × 100（ITM は本質的な価値を含む。今の板）。

**プットの大きな建玉**（数の多い側）（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>400</b> (−9.1%)</td><td nowrap>17,906 (11%)</td><td nowrap>12/18 $12.00</td></tr>
<tr><td nowrap><b>500</b> (+13.6%)</td><td nowrap>13,991 (8%)</td><td nowrap>12/18 $65.22</td></tr>
<tr><td nowrap><b>350</b> (−20.5%)</td><td nowrap>8,736 (5%)</td><td nowrap>12/18 $3.92</td></tr>
<tr><td nowrap><b>410</b> (−6.8%)</td><td nowrap>8,419 (5%)</td><td nowrap>12/4 $6.53</td></tr>
<tr><td nowrap><b>425</b> (−3.4%)</td><td nowrap>7,306 (4%)</td><td nowrap>12/18 $19.85</td></tr>
</tbody>
</table>

**コールの大きな建玉**（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>520</b> (+18.2%)</td><td nowrap>17,710 (12%)</td><td nowrap>12/4 $0.28</td></tr>
<tr><td nowrap><b>550</b> (+25.0%)</td><td nowrap>10,406 (7%)</td><td nowrap>12/18 $0.73</td></tr>
<tr><td nowrap><b>465</b> (+5.7%)</td><td nowrap>8,709 (6%)</td><td nowrap>11/30 $0.67</td></tr>
<tr><td nowrap><b>540</b> (+22.7%)</td><td nowrap>7,218 (5%)</td><td nowrap>12/18 $1.21</td></tr>
<tr><td nowrap><b>500</b> (+13.6%)</td><td nowrap>7,125 (5%)</td><td nowrap>12/4 $0.71</td></tr>
</tbody>
</table>

### オプションの配置（図）

![SMH のオプションの配置](SMH_options_chart.svg)

- 今の株価でのガンマの合計は**マイナス**（−85百万ドル／1%）、ゼロガンマは **465.02**（+5.7%）。推定の幅 460.37〜469.67。
- 上の段: 株価がその値になったときの、ディーラーのガンマの合計（赤い点線がゼロガンマ）。赤い背景（マイナス）の価格帯では、ディーラーが下げで売り・上げで買うので値動きが大きくなりやすく、緑の背景（プラス）では小さくなりやすい。
- 中の段: 行使価格ごとのガンマ（コールは上、プットは下）。下の段: 行使価格ごとの建玉（45日以内の満期）と、プットの壁・コールの壁（灰色の点線）。黒い線が今の株価。
- 薄い色は 11/30 の満期で消える分（濃い色が残る分）。点線は 11/30 の満期の後のガンマの合計（IV・株価は今のまま）。4段目は、主な満期 1/15 だけのガンマ。

### 道筋（上と下の関門）

- 今の株価 440.06 は、ゼロガンマ 465（推定の幅 460〜470）の**下（マイナス）**。値動きが大きくなりやすい。11/30 の満期の後のゼロガンマは 480（+9.2%）。

<table>
<thead><tr><th nowrap>関門</th><th nowrap>価格（距離）</th><th nowrap>中身</th></tr></thead>
<tbody>
<tr><td nowrap>平らになる</td><td nowrap><b>577</b> (+31.1%)</td><td nowrap>ここより上は、<br>上げてもディーラーのガンマがほとんど増えない。<br>壁の力が弱まり、<br>ニュートラルに近い</td></tr>
<tr><td nowrap>コールの壁・次の壁</td><td nowrap><b>550</b> (+25.0%)</td><td nowrap>建玉 10,406・<br>11/30 の満期には無い・<br>12/18 に 94%</td></tr>
<tr><td nowrap>コールの壁（最大）</td><td nowrap><b>520</b> (+18.2%)</td><td nowrap>建玉 17,710・<br>11/30 の満期には無い・<br>12/4 に 61%</td></tr>
<tr><td nowrap>ガンマ最大（コール）</td><td nowrap><b>500</b> (+13.6%)</td><td nowrap>—</td></tr>
<tr><td nowrap>コールの壁・ゼロガンマ</td><td nowrap><b>465</b> (+5.7%)</td><td nowrap>建玉 8,709・<br>11/30 で 58% 消える・<br>12/18 に 28%。<br>超えるとガンマはプラス<br>（値動きが小さくなりやすい）。<br>推定の幅 460〜470</td></tr>
<tr><td nowrap><b>今</b></td><td nowrap><b>440.06</b></td><td nowrap>ガンマ マイナス</td></tr>
<tr><td nowrap>プットの壁</td><td nowrap><b>410</b> (−6.8%)</td><td nowrap>建玉 8,419・<br>11/30 で 4% 消える・<br>12/4 に 42%</td></tr>
<tr><td nowrap>プットの壁（最大）</td><td nowrap><b>400</b> (−9.1%)</td><td nowrap>建玉 17,906・<br>11/30 で 1% 消える・<br>12/18 に 95%</td></tr>
<tr><td nowrap>ガンマの谷</td><td nowrap><b>388</b> (−11.9%)</td><td nowrap>マイナスが最も深い。<br>下げが加速しやすい中心</td></tr>
<tr><td nowrap>プットの壁・ガンマ最大（プット）</td><td nowrap><b>350</b> (−20.5%)</td><td nowrap>建玉 8,736・<br>11/30 で 12% 消える・<br>12/18 に 71%</td></tr>
<tr><td nowrap>次の支え</td><td nowrap><b>295</b> (−33.0%)</td><td nowrap>建玉 36,819・<br>11/30 で 100% 消える</td></tr>
</tbody>
</table>

**2つの筋書き**（壁の配置からの読み。確率ではありません）

- 上に抜けた場合: ゼロガンマ 465（+5.7%）を上に超えると、ガンマはプラスになり、値動きが小さくなりやすい。最大のコールの壁 **520**（+18.2%。11/30 の満期には無い・12/4 に 61%）で止まりやすい。超えれば次の壁 **550**（+25.0%）。577（+31.1%）より上はガンマがほぼ平らで、壁の力が弱まる（ニュートラルに近い）。
- はね返された場合: ゼロガンマ 465 の手前で止まって下げると、ガンマはマイナスのままで、値動きが大きくなりやすい（ガンマの谷は 388）。下の支えは **410**→**400**→**350**。
- 次の満期（11/30）までの想定の幅は ±3.5%（425〜455）。最大のコールの壁 520 は幅の外・最大のプットの壁 400 は幅の外。
- ガンマは値動きの大きさの目安で、上げ・下げの向きは分かりません（第105回）。

**満期の内訳**（壁の建玉のうち、次の満期 11/30 で消える分。45日以内の満期）

<table>
<thead><tr><th nowrap>壁</th><th nowrap>建玉</th><th nowrap>消える分・<br>残る主な満期</th></tr></thead>
<tbody>
<tr><td nowrap><b>550C</b> (+25.0%)</td><td nowrap>10,406</td><td nowrap><b>0%</b>（残る玉）<br>12/18 に 94%</td></tr>
<tr><td nowrap><b>520C</b> (+18.2%)</td><td nowrap>17,710</td><td nowrap><b>0%</b>（残る玉）<br>12/4 に 61%</td></tr>
<tr><td nowrap><b>465C</b> (+5.7%)</td><td nowrap>8,709</td><td nowrap><b>58%</b><br>（半分ほど消える）<br>12/18 に 28%</td></tr>
<tr><td nowrap><b>410P</b> (−6.8%)</td><td nowrap>8,419</td><td nowrap><b>4%</b>（残る玉）<br>12/4 に 42%</td></tr>
<tr><td nowrap><b>400P</b> (−9.1%)</td><td nowrap>17,906</td><td nowrap><b>1%</b>（残る玉）<br>12/18 に 95%</td></tr>
<tr><td nowrap><b>350P</b> (−20.5%)</td><td nowrap>8,736</td><td nowrap><b>12%</b>（残る玉）<br>12/18 に 71%</td></tr>
<tr><td nowrap><b>295P</b> (−33.0%)</td><td nowrap>36,819</td><td nowrap><b>100%</b>（消える玉）<br>12/18 に 0%</td></tr>
</tbody>
</table>

- 11/30 の満期の後に残る最大の壁: プットの壁 400（今と同じ）・コールの壁 520（今と同じ）。
- 主な満期（11/30 を除いて、ガンマが最大の契約 1/15 350P の満期）: 1/15。図の4段目に、この満期だけのガンマを出しています。

**壁の動き**（建玉の増減と、今日の大口）

<table>
<thead><tr><th nowrap>契約</th><th nowrap>建玉の増減・大口</th><th nowrap>見立て</th></tr></thead>
<tbody>
<tr><td nowrap><b>397.5C</b> (−9.7%)</td><td nowrap>建玉 —<br>（今 1,055）<br>12/18 売 1,<br>050枚 $4.4M</td><td nowrap>上値の重し（コール売り）</td></tr>
<tr><td nowrap><b>420P</b> (−4.6%)</td><td nowrap>建玉 —<br>（今 2,981）<br>12/18 向き不明 1,<br>947枚 $3.5M</td><td nowrap>向きは不明</td></tr>
<tr><td nowrap><b>440C</b> (−0.0%)</td><td nowrap>建玉 —<br>（今 911）<br>1/15 向き不明 948枚 $3.3M</td><td nowrap>向きは不明</td></tr>
<tr><td nowrap><b>400P</b>★ (−9.1%)</td><td nowrap>建玉 —<br>（今 17,906）<br>12/18 買 2,<br>591枚 $3.1M</td><td nowrap>下げの的・守り（プット買い）</td></tr>
<tr><td nowrap><b>445C</b> (+1.1%)</td><td nowrap>建玉 —<br>（今 184）<br>12/11 売 1,<br>611枚 $2.9M</td><td nowrap>上値の重し（コール売り）</td></tr>
</tbody>
</table>

- 建玉の増減は前回の記録（11/27）から今の板まで（建玉は前の営業日の引けの数）。大口は直近の取引日（11/27）の、代金の多い契約（opt_flow の推定）。その日の取引が建玉に出るのは次の営業日なので、2つを続けて見ます。★は建玉の壁（上位3本）。コール売りなら、ディーラーはそのコールを買い持ちになり、その価格の近くで値動きを抑える向きに売り買いする（壁が厚くなる）とみます。

### 大口の賭け（推定）

**ベア 🐻・強さ 中**（売買代金の 1.6%）

- 大口のデルタ換算（株を何ドル分買った・売ったのと同じ向きか）: 差 **−1.0億ドル**（ブル側 +9.3百万ドル・ベア側 −1.1億ドル）。代金はブル側 1.6百万ドル・ベア側 16.7百万ドル。1日の売買代金 64.7億ドル（20日の平均）
- 大口が見ている価格: 上値の重し（コール売り） **445**（+1.1%）・上げの的（コール買い） **460**（+4.5%）・下げの的（プット買い） **400**（−9.1%）
- 深い ITM の大口（合計に入れない）: 3本・代金 89.4百万ドル（12/18 645P売・12/18 620P売・1/15 670P売）。株と組み合わせた取引（配当の裁定・乗り換えなど）のことが多い。そのまま賭けとみると +94.0百万ドル 分

<table>
<thead><tr><th nowrap>契約</th><th nowrap>推定・意味</th><th nowrap>代金・枚数</th></tr></thead>
<tbody>
<tr><td nowrap>12/18 397.5C<br>−9.7%<br>建玉 1,039</td><td nowrap><b>売り寄り</b><br><b>（IV −9.5pt）</b><br>上値の重し<br>組の片側かも</td><td nowrap>$4.4M<br>1,050枚<br>Δ −$18M<br>IV 61%</td></tr>
<tr><td nowrap>12/18 420P<br>−4.6%<br>建玉 0</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$3.5M<br>1,947枚<br>Δ —<br>IV 65%</td></tr>
<tr><td nowrap>1/15 440C<br>−0.0%<br>建玉 608</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$3.3M<br>948枚<br>Δ —<br>IV 55%</td></tr>
<tr><td nowrap>12/18 400P<br>−9.1%<br>建玉 16,959</td><td nowrap><b>買い寄り</b><br><b>（IV +1.6pt）</b><br>下げへの賭け・<br>守り<br>組の片側かも</td><td nowrap>$3.1M<br>2,591枚<br>Δ −$14M<br>IV 69%</td></tr>
<tr><td nowrap>12/11 445C<br>+1.1%<br>建玉 169</td><td nowrap><b>売り</b><br>上値の重し</td><td nowrap>$2.9M<br>1,611枚<br>Δ −$34M<br>IV 59%</td></tr>
<tr><td nowrap>1/15 450P<br>+2.3%<br>建玉 8,928</td><td nowrap><b>買い寄り</b><br><b>（IV +2.8pt）</b><br>下げへの賭け・<br>守り（ITM）</td><td nowrap>$2.2M<br>551枚<br>Δ −$6.1M<br>IV 54%</td></tr>
<tr><td nowrap>12/18 450C<br>+2.3%<br>建玉 2,989</td><td nowrap><b>売り寄り</b><br><b>（IV −1.8pt）</b><br>上値の重し<br>組の片側かも</td><td nowrap>$2.1M<br>1,023枚<br>Δ −$10M<br>IV 59%</td></tr>
<tr><td nowrap>12/4 445C<br>+1.1%<br>建玉 0</td><td nowrap><b>売り</b><br>上値の重し</td><td nowrap>$1.9M<br>1,463枚<br>Δ −$30M<br>IV 63%</td></tr>
<tr><td nowrap>12/18 460C<br>+4.5%<br>建玉 0</td><td nowrap><b>買い寄り</b><br>上げへの賭け<br>組の片側かも</td><td nowrap>$1.6M<br>1,088枚<br>Δ +$9.3M<br>IV 53%</td></tr>
<tr><td nowrap>12/2 430C<br>−2.3%<br>建玉 0</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$1.4M<br>801枚<br>Δ —<br>IV 61%</td></tr>
<tr><td nowrap>12/18 645P<br>+46.6%<br>建玉 0</td><td nowrap><b>売り寄り</b><br><b>（IV −11.8pt）</b><br>深い ITM の売り</td><td nowrap>$44M<br>2,125枚<br>Δ +$45M<br>IV 85%</td></tr>
<tr><td nowrap>12/18 620P<br>+40.9%<br>建玉 0</td><td nowrap><b>売り寄り</b><br><b>（IV −24.1pt）</b><br>深い ITM の売り</td><td nowrap>$25M<br>1,371枚<br>Δ +$30M<br>IV 66%</td></tr>
<tr><td nowrap>1/15 670P<br>+52.3%<br>建玉 0</td><td nowrap><b>売り寄り</b><br><b>（IV −11.6pt）</b><br>深い ITM の売り</td><td nowrap>$21M<br>905枚<br>Δ +$19M<br>IV 56%</td></tr>
</tbody>
</table>

推定の向きは最後の約定の位置（売り気配で約定＝買い）と、前回の実行からの IV の上下から。買い・売りの分かる大口は代金の 69%。誰の取引かは分かりません。表の『代金・枚数』は、代金・その日の出来高・Δ（デルタ換算。株を何ドル分買った＋・売った−のと同じ向きか）・IV。

### 詳しく

**まとめ**: 下の支えの候補 **410**（−6.8%）・400（−9.1%）・350（−20.5%）。上の重さの候補 **465**（+5.7%）・520（+18.2%）・550（+25.0%）。既に割れたプットの壁 500（+13.6%）。次の満期（11/30・3日）の想定の幅 ±3.5%（424.76〜455.36）。ガンマはマイナス側（ゼロガンマ 464.23）→ 値動きが大きくなりやすい。

**下の支えの候補**（プットの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>425</td><td nowrap>−3.4%</td><td nowrap>7,306</td><td nowrap>4%</td></tr>
<tr><td nowrap>410</td><td nowrap>−6.8%</td><td nowrap>8,419</td><td nowrap>5%</td></tr>
<tr><td nowrap>400</td><td nowrap>−9.1%</td><td nowrap>17,906</td><td nowrap>11%</td></tr>
<tr><td nowrap>380</td><td nowrap>−13.6%</td><td nowrap>6,898</td><td nowrap>4%</td></tr>
<tr><td nowrap>350</td><td nowrap>−20.5%</td><td nowrap>8,736</td><td nowrap>5%</td></tr>
</tbody>
</table>

**上の重さの候補**（コールの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>465</td><td nowrap>+5.7%</td><td nowrap>8,709</td><td nowrap>6%</td></tr>
<tr><td nowrap>500</td><td nowrap>+13.6%</td><td nowrap>7,125</td><td nowrap>5%</td></tr>
<tr><td nowrap>520</td><td nowrap>+18.2%</td><td nowrap>17,710</td><td nowrap>12%</td></tr>
<tr><td nowrap>540</td><td nowrap>+22.7%</td><td nowrap>7,218</td><td nowrap>5%</td></tr>
<tr><td nowrap>550</td><td nowrap>+25.0%</td><td nowrap>10,406</td><td nowrap>7%</td></tr>
</tbody>
</table>

**次の満期 11/30（3日）**: プットの壁 350（−20.5%）・コールの壁 465（+5.7%）・最大の痛み 425（−3.4%）・想定の幅 ±3.5%

アウト・オブ・ザ・マネーに払われた代金: プット 30.6百万ドル・コール 14.8百万ドル（プットの割合 67%）

**建玉の増減**（①の日次の記録の 11/27 → 今の板。45日以内の満期）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>距離</th><th nowrap>増減</th><th nowrap>想定元本</th></tr></thead>
<tbody>
</tbody>
</table>

合計: プット 0・コール 0（想定元本の増減）

**全体**: IV30 58%・7日 72%・期間構造 1.23（目先の不安が強い）・プットの割高さ +5.3pt・建玉のプット/コール 1.22

**過去の検証**: 未検証（第190回で、2008〜2025年の QQQ・SPY・NVDA・AVGO・AMD・QCOM・TXN の板で確かめ中）。それまでは、下の目安は過去の効きが確かめられていない参考の値です。

## SOXX　134.07

米国 11/27 21:23（取引時間外）・直近の取引日 11/27・板 Yahoo

### 結論

<table>
<thead><tr><th nowrap>問い</th><th nowrap>答え</th></tr></thead>
<tbody>
<tr><td nowrap>建玉の偏り</td><td nowrap><b>ほぼ半々</b><br><b>（いつもとの比較はまだできない）</b><br>（プット 53%・コール 47%）</td></tr>
<tr><td nowrap>σ（側）</td><td nowrap><b>—</b></td></tr>
<tr><td nowrap>前日から</td><td nowrap><b>—</b><br>（前日の記録と比べられません<br>（σ を出せない日））</td></tr>
<tr><td nowrap>大きなプット☆</td><td nowrap>120 (−10.5%)<br>125 (−6.8%)<br>150 (+11.9%)</td></tr>
<tr><td nowrap>大きなコール</td><td nowrap>145 (+8.2%)<br>140 (+4.4%)<br>160 (+19.3%)</td></tr>
</tbody>
</table>

- σ: ①の毎日の記録が 1日分しかなく、σ を出せません（10日たまると出ます）。
- 大きなプット・コールの印: ★ 偏っている側、☆ 偏りは小さいが数の多い側。『○/○』は、枚数/金額（建玉 × 値段 × 100）が過去30日の平常の何倍か。
- 偏りの物差し: 満期まで 3〜75日の全ての建玉（①の毎日の記録と同じ）。建玉には買い手と売り手が同じ数だけいるので、偏りはコールとプットの数で見ています。

**プットの大きな建玉の枚数とお金**（数の多い側）（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>120</b> OTM</td><td nowrap>28,461 (<b>—</b>)</td><td nowrap>10.8M (<b>—</b>)</td></tr>
<tr><td nowrap><b>125</b> OTM</td><td nowrap>27,317 (<b>—</b>)</td><td nowrap>15.3M (<b>—</b>)</td></tr>
<tr><td nowrap><b>150</b> 超ITM</td><td nowrap>15,870 (<b>—</b>)</td><td nowrap>30.8M (<b>—</b>)</td></tr>
<tr><td nowrap><b>100</b> OTM</td><td nowrap>13,340 (<b>—</b>)</td><td nowrap>1.68M (<b>—</b>)</td></tr>
<tr><td nowrap><b>115</b> OTM</td><td nowrap>10,252 (<b>—</b>)</td><td nowrap>2.44M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

**コールの大きな建玉の枚数とお金**（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>145</b> OTM</td><td nowrap>12,789 (<b>—</b>)</td><td nowrap>5.10M (<b>—</b>)</td></tr>
<tr><td nowrap><b>140</b> OTM</td><td nowrap>11,130 (<b>—</b>)</td><td nowrap>6.39M (<b>—</b>)</td></tr>
<tr><td nowrap><b>160</b> OTM</td><td nowrap>8,336 (<b>—</b>)</td><td nowrap>0.71M (<b>—</b>)</td></tr>
<tr><td nowrap><b>150</b> OTM</td><td nowrap>6,670 (<b>—</b>)</td><td nowrap>1.90M (<b>—</b>)</td></tr>
<tr><td nowrap><b>135</b> ATM</td><td nowrap>4,936 (<b>—</b>)</td><td nowrap>3.93M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

- 枚数の平常比は同じ側・同じ順位（過去の各日の、枚数が同じ順位の建玉）、金額の平常比は同じ側の過去の大きな建玉（各日の上位5本）と比べた倍率。▲▲ 30日で最多・▲ 多い（上位25%）・▼ 少ない（下位25%）・▼▼ 30日で最少。印が無ければ平常並み。建玉の合計も▲なら、満期（特に3・6・9・12月の第3金曜）に向けて全体が増えている分を差し引いて見てください。金額は建玉 × 値段 × 100（ITM は本質的な価値を含む。今の板）。

**プットの大きな建玉**（数の多い側）（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>120</b> (−10.5%)</td><td nowrap>28,461 (18%)</td><td nowrap>12/18 $3.85</td></tr>
<tr><td nowrap><b>125</b> (−6.8%)</td><td nowrap>27,317 (18%)</td><td nowrap>12/18 $5.60</td></tr>
<tr><td nowrap><b>150</b> (+11.9%)</td><td nowrap>15,870 (10%)</td><td nowrap>12/18 $19.65</td></tr>
<tr><td nowrap><b>100</b> (−25.4%)</td><td nowrap>13,340 (9%)</td><td nowrap>12/24 $1.32</td></tr>
<tr><td nowrap><b>115</b> (−14.2%)</td><td nowrap>10,252 (7%)</td><td nowrap>12/18 $2.80</td></tr>
</tbody>
</table>

**コールの大きな建玉**（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>145</b> (+8.2%)</td><td nowrap>12,789 (17%)</td><td nowrap>12/18 $3.85</td></tr>
<tr><td nowrap><b>140</b> (+4.4%)</td><td nowrap>11,130 (15%)</td><td nowrap>12/18 $5.75</td></tr>
<tr><td nowrap><b>160</b> (+19.3%)</td><td nowrap>8,336 (11%)</td><td nowrap>12/18 $1.10</td></tr>
<tr><td nowrap><b>150</b> (+11.9%)</td><td nowrap>6,670 (9%)</td><td nowrap>12/18 $2.77</td></tr>
<tr><td nowrap><b>135</b> (+0.7%)</td><td nowrap>4,936 (7%)</td><td nowrap>12/18 $8.30</td></tr>
</tbody>
</table>

### オプションの配置（図）

![SOXX のオプションの配置](SOXX_options_chart.svg)

- 今の株価でのガンマの合計は**マイナス**（−39百万ドル／1%）、ゼロガンマは **158.61**（+18.3%）。推定の幅 157.02〜160.19。
- 上の段: 株価がその値になったときの、ディーラーのガンマの合計（赤い点線がゼロガンマ）。赤い背景（マイナス）の価格帯では、ディーラーが下げで売り・上げで買うので値動きが大きくなりやすく、緑の背景（プラス）では小さくなりやすい。
- 中の段: 行使価格ごとのガンマ（コールは上、プットは下）。下の段: 行使価格ごとの建玉（45日以内の満期）と、プットの壁・コールの壁（灰色の点線）。黒い線が今の株価。
- 薄い色は 12/4 の満期で消える分（濃い色が残る分）。点線は 12/4 の満期の後のガンマの合計（IV・株価は今のまま）。4段目は、主な満期 12/18 だけのガンマ。

### 道筋（上と下の関門）

- 今の株価 134.07 は、ゼロガンマ 159（推定の幅 157〜160）の**下（マイナス）**。値動きが大きくなりやすい。12/4 の満期の後のゼロガンマは 159（+18.8%）。

<table>
<thead><tr><th nowrap>関門</th><th nowrap>価格（距離）</th><th nowrap>中身</th></tr></thead>
<tbody>
<tr><td nowrap>平らになる</td><td nowrap><b>193</b> (+44.0%)</td><td nowrap>ここより上は、<br>上げてもディーラーのガンマがほとんど増えない。<br>壁の力が弱まり、<br>ニュートラルに近い</td></tr>
<tr><td nowrap>ゼロガンマ・コールの壁・次の壁</td><td nowrap><b>160</b> (+19.3%)</td><td nowrap>超えるとガンマはプラス<br>（値動きが小さくなりやすい）。<br>推定の幅 157〜160。<br>建玉 8,336・<br>12/4 で 25% 消える・<br>12/18 に 74%</td></tr>
<tr><td nowrap>ガンマ最大（コール）</td><td nowrap><b>150</b> (+11.9%)</td><td nowrap>—</td></tr>
<tr><td nowrap>コールの壁（最大）</td><td nowrap><b>145</b> (+8.2%)</td><td nowrap>建玉 12,789・<br>12/4 の満期には無い・<br>12/18 に 87%</td></tr>
<tr><td nowrap>コールの壁</td><td nowrap><b>140</b> (+4.4%)</td><td nowrap>建玉 11,130・<br>12/4 の満期には無い・<br>12/18 に 90%</td></tr>
<tr><td nowrap><b>今</b></td><td nowrap><b>134.07</b></td><td nowrap>ガンマ マイナス</td></tr>
<tr><td nowrap>プットの壁・ガンマ最大（プット）</td><td nowrap><b>125</b> (−6.8%)</td><td nowrap>建玉 27,317・<br>12/4 の満期には無い・<br>12/18 に 97%</td></tr>
<tr><td nowrap>ガンマの谷</td><td nowrap><b>122</b> (−9.0%)</td><td nowrap>マイナスが最も深い。<br>下げが加速しやすい中心</td></tr>
<tr><td nowrap>プットの壁（最大）</td><td nowrap><b>120</b> (−10.5%)</td><td nowrap>建玉 28,461・<br>12/4 の満期には無い・<br>12/18 に 71%</td></tr>
<tr><td nowrap>プットの壁・次の支え</td><td nowrap><b>100</b> (−25.4%)</td><td nowrap>建玉 13,340・<br>12/4 の満期には無い・<br>12/24 に 81%</td></tr>
</tbody>
</table>

**2つの筋書き**（壁の配置からの読み。確率ではありません）

- 上に抜けた場合: ゼロガンマ 159（+18.3%）を上に超えると、ガンマはプラスになり、値動きが小さくなりやすい。最大のコールの壁 **145**（+8.2%。12/4 の満期には無い・12/18 に 87%）で止まりやすい。超えれば次の壁 **160**（+19.3%）。193（+44.0%）より上はガンマがほぼ平らで、壁の力が弱まる（ニュートラルに近い）。
- はね返された場合: ゼロガンマ 159 の手前で止まって下げると、ガンマはマイナスのままで、値動きが大きくなりやすい（ガンマの谷は 122）。下の支えは **125**→**120**→**100**。
- 次の満期（12/4）までの想定の幅は ±9.8%（121〜147）。最大のコールの壁 145 は幅の中・最大のプットの壁 120 は幅の外。
- ガンマは値動きの大きさの目安で、上げ・下げの向きは分かりません（第105回）。

**満期の内訳**（壁の建玉のうち、次の満期 12/4 で消える分。45日以内の満期）

<table>
<thead><tr><th nowrap>壁</th><th nowrap>建玉</th><th nowrap>消える分・<br>残る主な満期</th></tr></thead>
<tbody>
<tr><td nowrap><b>160C</b> (+19.3%)</td><td nowrap>8,336</td><td nowrap><b>25%</b>（残る玉）<br>12/18 に 74%</td></tr>
<tr><td nowrap><b>145C</b> (+8.2%)</td><td nowrap>12,789</td><td nowrap><b>0%</b>（残る玉）<br>12/18 に 87%</td></tr>
<tr><td nowrap><b>140C</b> (+4.4%)</td><td nowrap>11,130</td><td nowrap><b>0%</b>（残る玉）<br>12/18 に 90%</td></tr>
<tr><td nowrap><b>125P</b> (−6.8%)</td><td nowrap>27,317</td><td nowrap><b>0%</b>（残る玉）<br>12/18 に 97%</td></tr>
<tr><td nowrap><b>120P</b> (−10.5%)</td><td nowrap>28,461</td><td nowrap><b>0%</b>（残る玉）<br>12/18 に 71%</td></tr>
<tr><td nowrap><b>100P</b> (−25.4%)</td><td nowrap>13,340</td><td nowrap><b>0%</b>（残る玉）<br>12/24 に 81%</td></tr>
</tbody>
</table>

- 12/4 の満期の後に残る最大の壁: プットの壁 120（今と同じ）・コールの壁 145（今と同じ）。
- 主な満期（12/4 を除いて、ガンマが最大の契約 12/18 125P の満期）: 12/18。図の4段目に、この満期だけのガンマを出しています。

**壁の動き**（建玉の増減と、今日の大口）

<table>
<thead><tr><th nowrap>契約</th><th nowrap>建玉の増減・大口</th><th nowrap>見立て</th></tr></thead>
<tbody>
<tr><td nowrap><b>130P</b> (−3.0%)</td><td nowrap>建玉 −23,897（今 468）<br>12/18 売 1,793枚 $1.2M</td><td nowrap>下値の防御線<br>（プット売り）</td></tr>
<tr><td nowrap><b>130C</b> (−3.0%)</td><td nowrap>建玉 −3,208（今 405）<br>12/4 売 4,898枚 $3.9M</td><td nowrap>上値の重し<br>（コール売り）</td></tr>
<tr><td nowrap><b>140C</b>★ (+4.4%)</td><td nowrap>建玉 +81（今 11,130）<br>12/31 買 2,518枚 $1.6M<br>12/18 売 1,972枚 $1.1M</td><td nowrap>上げの的<br>（コール買い）</td></tr>
<tr><td nowrap><b>155C</b> (+15.6%)</td><td nowrap>建玉 −56,837（今 550）</td><td nowrap>コールの建玉の減少</td></tr>
<tr><td nowrap><b>100P</b>★ (−25.4%)</td><td nowrap>建玉 +11,602（今 13,340）</td><td nowrap>プットの建玉の増加<br>（売り買いは不明）</td></tr>
<tr><td nowrap><b>145C</b>★ (+8.2%)</td><td nowrap>建玉 +4,735（今 12,789）</td><td nowrap>コールの建玉の増加<br>（売り買いは不明）</td></tr>
</tbody>
</table>

- 建玉の増減は前回の記録（11/25）から今の板まで（建玉は前の営業日の引けの数）。大口は直近の取引日（11/27）の、代金の多い契約（opt_flow の推定）。その日の取引が建玉に出るのは次の営業日なので、2つを続けて見ます。★は建玉の壁（上位3本）。コール売りなら、ディーラーはそのコールを買い持ちになり、その価格の近くで値動きを抑える向きに売り買いする（壁が厚くなる）とみます。

### 大口の賭け（推定）

**ベア 🐻・強さ 小**（売買代金の 0.4%）

- 大口のデルタ換算（株を何ドル分買った・売ったのと同じ向きか）: 差 **−25.0百万ドル**（ブル側 +29.3百万ドル・ベア側 −54.4百万ドル）。代金はブル側 6.9百万ドル・ベア側 6.0百万ドル。1日の売買代金 69.4億ドル（20日の平均）
- 大口が見ている価格: 下値の防御線（プット売り） **130**（−3.0%）・上値の重し（コール売り） **140**（+4.4%）・上げの的（コール買い） **140**（+4.4%）。大口は **130〜140** の幅とみている
- 深い ITM の大口（合計に入れない）: 3本・代金 33.7百万ドル（12/18 450P（向き不明）・2/19 240P（向き不明）・3/19 300P（向き不明））。株と組み合わせた取引（配当の裁定・乗り換えなど）のことが多い。向きは分からない

<table>
<thead><tr><th nowrap>契約</th><th nowrap>推定・意味</th><th nowrap>代金・枚数</th></tr></thead>
<tbody>
<tr><td nowrap>12/4 130C<br>−3.0%<br>建玉 0</td><td nowrap><b>売り</b><br>上値の重し<br>（ITM）</td><td nowrap>$3.9M<br>4,898枚<br>Δ −$42M<br>IV 77%</td></tr>
<tr><td nowrap>12/31 140C<br>+4.4%<br>建玉 0</td><td nowrap><b>買い</b><br>上げへの賭け</td><td nowrap>$1.6M<br>2,518枚<br>Δ +$15M<br>IV 55%</td></tr>
<tr><td nowrap>12/18 130P<br>−3.0%<br>建玉 0</td><td nowrap><b>売り寄り</b><br><b>（IV −4.0pt）</b><br>下値の防御線</td><td nowrap>$1.2M<br>1,793枚<br>Δ +$4.7M<br>IV 70%</td></tr>
<tr><td nowrap>1/15 370C<br>+176.0%<br>建玉 203</td><td nowrap><b>買い寄り</b><br><b>（IV +4.5pt）</b><br>上げへの賭け</td><td nowrap>$1.2M<br>85枚<br>Δ +$0.0M<br>IV 50%</td></tr>
<tr><td nowrap>12/18 140C<br>+4.4%<br>建玉 9,975</td><td nowrap><b>売り寄り</b><br><b>（IV −3.0pt）</b><br>上値の重し</td><td nowrap>$1.1M<br>1,972枚<br>Δ −$5.5M<br>IV 64%</td></tr>
<tr><td nowrap>12/18 116.67P<br>−13.0%<br>建玉 0</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$1.1M<br>3,160枚<br>Δ —<br>IV 81%</td></tr>
<tr><td nowrap>12/18 120P<br>−10.5%<br>建玉 20,126</td><td nowrap><b>売り寄り</b><br><b>（IV −1.8pt）</b><br>下値の防御線</td><td nowrap>$1.0M<br>2,637枚<br>Δ +$4.3M<br>IV 76%</td></tr>
<tr><td nowrap>12/18 130C<br>−3.0%<br>建玉 0</td><td nowrap><b>売り</b><br>上値の重し<br>（ITM）</td><td nowrap>$1.0M<br>889枚<br>Δ −$7.2M<br>IV 71%</td></tr>
<tr><td nowrap>3/19 140C<br>+4.4%<br>建玉 0</td><td nowrap><b>買い寄り</b><br><b>（IV +4.1pt）</b><br>上げへの賭け</td><td nowrap>$1.0M<br>673枚<br>Δ +$2.3M<br>IV 57%</td></tr>
<tr><td nowrap>12/4 140P<br>+4.4%<br>建玉 0</td><td nowrap><b>売り寄り</b><br><b>（IV −1.5pt）</b><br>下値の防御線<br>（ITM）</td><td nowrap>$0.8M<br>842枚<br>Δ +$3.5M<br>IV 87%</td></tr>
<tr><td nowrap>12/18 450P<br>+235.6%<br>建玉 8,438</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$16M<br>5,655枚<br>Δ —<br>IV —</td></tr>
<tr><td nowrap>2/19 240P<br>+79.0%<br>建玉 0</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$10M<br>1,000枚<br>Δ —<br>IV 81%</td></tr>
<tr><td nowrap>3/19 300P<br>+123.8%<br>建玉 0</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$7.8M<br>611枚<br>Δ —<br>IV —</td></tr>
</tbody>
</table>

推定の向きは最後の約定の位置（売り気配で約定＝買い）と、前回の実行からの IV の上下から。買い・売りの分かる大口は代金の 92%。誰の取引かは分かりません。表の『代金・枚数』は、代金・その日の出来高・Δ（デルタ換算。株を何ドル分買った＋・売った−のと同じ向きか）・IV。

### 詳しく

**まとめ**: 下の支えの候補 **125**（−6.8%）・120（−10.5%）・100（−25.4%）。上の重さの候補 **140**（+4.4%）・145（+8.2%）・160（+19.3%）。既に割れたプットの壁 150（+11.9%）。次の満期（12/4・7日）の想定の幅 ±9.8%（120.97〜147.17）。ガンマはマイナス側（ゼロガンマ 158.91）→ 値動きが大きくなりやすい。

**下の支えの候補**（プットの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>133.33</td><td nowrap>−0.6%</td><td nowrap>6,413</td><td nowrap>4%</td></tr>
<tr><td nowrap>125</td><td nowrap>−6.8%</td><td nowrap>27,317</td><td nowrap>18%</td></tr>
<tr><td nowrap>120</td><td nowrap>−10.5%</td><td nowrap>28,461</td><td nowrap>18%</td></tr>
<tr><td nowrap>115</td><td nowrap>−14.2%</td><td nowrap>10,252</td><td nowrap>7%</td></tr>
<tr><td nowrap>100</td><td nowrap>−25.4%</td><td nowrap>13,340</td><td nowrap>9%</td></tr>
</tbody>
</table>

**上の重さの候補**（コールの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>135</td><td nowrap>+0.7%</td><td nowrap>4,936</td><td nowrap>7%</td></tr>
<tr><td nowrap>140</td><td nowrap>+4.4%</td><td nowrap>11,130</td><td nowrap>15%</td></tr>
<tr><td nowrap>145</td><td nowrap>+8.2%</td><td nowrap>12,789</td><td nowrap>17%</td></tr>
<tr><td nowrap>150</td><td nowrap>+11.9%</td><td nowrap>6,670</td><td nowrap>9%</td></tr>
<tr><td nowrap>160</td><td nowrap>+19.3%</td><td nowrap>8,336</td><td nowrap>11%</td></tr>
</tbody>
</table>

**次の満期 12/4（7日）**: プットの壁 122（−9.0%）・コールの壁 160（+19.3%）・最大の痛み 151.67（+13.1%）・想定の幅 ±9.8%

アウト・オブ・ザ・マネーに払われた代金: プット 10.5百万ドル・コール 20.6百万ドル（プットの割合 34%）

**建玉の増減**（前回のオプション分析の 11/25 → 今の板。45日以内の満期）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>距離</th><th nowrap>増減</th><th nowrap>想定元本</th></tr></thead>
<tbody>
<tr><td nowrap>100P</td><td nowrap>−25.4%</td><td nowrap>+11,602</td><td nowrap>116.0百万ドル</td></tr>
<tr><td nowrap>145C</td><td nowrap>+8.2%</td><td nowrap>+4,735</td><td nowrap>68.7百万ドル</td></tr>
<tr><td nowrap>115P</td><td nowrap>−14.2%</td><td nowrap>+1,975</td><td nowrap>22.7百万ドル</td></tr>
<tr><td nowrap>155C</td><td nowrap>+15.6%</td><td nowrap>−56,837</td><td nowrap>−881.0百万ドル</td></tr>
<tr><td nowrap>170C</td><td nowrap>+26.8%</td><td nowrap>−56,311</td><td nowrap>−957.3百万ドル</td></tr>
</tbody>
</table>

合計: プット −1,643.9百万ドル・コール −2,149.7百万ドル（想定元本の増減）

**全体**: IV30 64%・7日 74%・期間構造 1.15（目先の不安が強い）・プットの割高さ +6.1pt・建玉のプット/コール 1.23

**過去の検証**: 未検証（第190回で、2008〜2025年の QQQ・SPY・NVDA・AVGO・AMD・QCOM・TXN の板で確かめ中）。それまでは、下の目安は過去の効きが確かめられていない参考の値です。

## SOXL　36.57

米国 11/27 21:23（取引時間外）・直近の取引日 11/27・板 Yahoo

### 結論

<table>
<thead><tr><th nowrap>問い</th><th nowrap>答え</th></tr></thead>
<tbody>
<tr><td nowrap>建玉の偏り</td><td nowrap><b>コール（買う権利）</b><br><b>のほうが多い</b><br><b>（いつもとの比較はまだできない）</b><br>（プット 44%・コール 56%）</td></tr>
<tr><td nowrap>σ（側）</td><td nowrap><b>—</b></td></tr>
<tr><td nowrap>前日から</td><td nowrap><b>—</b><br>（前日の記録と比べられません<br>（σ を出せない日））</td></tr>
<tr><td nowrap>大きなプット</td><td nowrap>40 (+9.4%)<br>30 (−18.0%)<br>35 (−4.3%)</td></tr>
<tr><td nowrap>大きなコール☆</td><td nowrap>40 (+9.4%)<br>30 (−18.0%)<br>38 (+3.9%)</td></tr>
</tbody>
</table>

- σ: ①の毎日の記録が 1日分しかなく、σ を出せません（10日たまると出ます）。
- 大きなプット・コールの印: ★ 偏っている側、☆ 偏りは小さいが数の多い側。『○/○』は、枚数/金額（建玉 × 値段 × 100）が過去30日の平常の何倍か。
- 偏りの物差し: 満期まで 3〜75日の全ての建玉（①の毎日の記録と同じ）。建玉には買い手と売り手が同じ数だけいるので、偏りはコールとプットの数で見ています。

**プットの大きな建玉の枚数とお金**（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> ITM</td><td nowrap>13,462 (<b>—</b>)</td><td nowrap>11.1M (<b>—</b>)</td></tr>
<tr><td nowrap><b>30</b> OTM</td><td nowrap>11,294 (<b>—</b>)</td><td nowrap>4.35M (<b>—</b>)</td></tr>
<tr><td nowrap><b>35</b> OTM</td><td nowrap>11,212 (<b>—</b>)</td><td nowrap>7.05M (<b>—</b>)</td></tr>
<tr><td nowrap><b>45</b> 超ITM</td><td nowrap>4,834 (<b>—</b>)</td><td nowrap>6.07M (<b>—</b>)</td></tr>
<tr><td nowrap><b>43</b> 超ITM</td><td nowrap>4,365 (<b>—</b>)</td><td nowrap>4.28M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

**コールの大きな建玉の枚数とお金**（数の多い側）（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> OTM</td><td nowrap>40,884 (<b>—</b>)</td><td nowrap>22.6M (<b>—</b>)</td></tr>
<tr><td nowrap><b>30</b> 超ITM</td><td nowrap>11,132 (<b>—</b>)</td><td nowrap>10.1M (<b>—</b>)</td></tr>
<tr><td nowrap><b>38</b> OTM</td><td nowrap>8,212 (<b>—</b>)</td><td nowrap>4.71M (<b>—</b>)</td></tr>
<tr><td nowrap><b>39</b> OTM</td><td nowrap>7,727 (<b>—</b>)</td><td nowrap>4.49M (<b>—</b>)</td></tr>
<tr><td nowrap><b>42</b> OTM</td><td nowrap>7,672 (<b>—</b>)</td><td nowrap>3.01M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

- 枚数の平常比は同じ側・同じ順位（過去の各日の、枚数が同じ順位の建玉）、金額の平常比は同じ側の過去の大きな建玉（各日の上位5本）と比べた倍率。▲▲ 30日で最多・▲ 多い（上位25%）・▼ 少ない（下位25%）・▼▼ 30日で最少。印が無ければ平常並み。建玉の合計も▲なら、満期（特に3・6・9・12月の第3金曜）に向けて全体が増えている分を差し引いて見てください。金額は建玉 × 値段 × 100（ITM は本質的な価値を含む。今の板）。

**プットの大きな建玉**（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> (+9.4%)</td><td nowrap>13,462 (18%)</td><td nowrap>12/18 $8.95</td></tr>
<tr><td nowrap><b>30</b> (−18.0%)</td><td nowrap>11,294 (15%)</td><td nowrap>12/18 $3.90</td></tr>
<tr><td nowrap><b>35</b> (−4.3%)</td><td nowrap>11,212 (15%)</td><td nowrap>12/18 $6.15</td></tr>
<tr><td nowrap><b>45</b> (+23.1%)</td><td nowrap>4,834 (6%)</td><td nowrap>12/18 $12.50</td></tr>
<tr><td nowrap><b>43</b> (+17.6%)</td><td nowrap>4,365 (6%)</td><td nowrap>12/18 $10.12</td></tr>
</tbody>
</table>

**コールの大きな建玉**（数の多い側）（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> (+9.4%)</td><td nowrap>40,884 (34%)</td><td nowrap>12/31 $6.50</td></tr>
<tr><td nowrap><b>30</b> (−18.0%)</td><td nowrap>11,132 (9%)</td><td nowrap>12/4 $8.28</td></tr>
<tr><td nowrap><b>38</b> (+3.9%)</td><td nowrap>8,212 (7%)</td><td nowrap>12/18 $6.15</td></tr>
<tr><td nowrap><b>39</b> (+6.6%)</td><td nowrap>7,727 (6%)</td><td nowrap>12/18 $5.88</td></tr>
<tr><td nowrap><b>42</b> (+14.8%)</td><td nowrap>7,672 (6%)</td><td nowrap>12/18 $4.53</td></tr>
</tbody>
</table>

### オプションの配置（図）

![SOXL のオプションの配置](SOXL_options_chart.svg)

- 今の株価でのガンマの合計は**プラス**（+3百万ドル／1%）。
- 上の段: 株価がその値になったときの、ディーラーのガンマの合計（赤い点線がゼロガンマ）。赤い背景（マイナス）の価格帯では、ディーラーが下げで売り・上げで買うので値動きが大きくなりやすく、緑の背景（プラス）では小さくなりやすい。
- 中の段: 行使価格ごとのガンマ（コールは上、プットは下）。下の段: 行使価格ごとの建玉（45日以内の満期）と、プットの壁・コールの壁（灰色の点線）。黒い線が今の株価。
- 薄い色は 12/4 の満期で消える分（濃い色が残る分）。点線は 12/4 の満期の後のガンマの合計（IV・株価は今のまま）。4段目は、主な満期 12/31 だけのガンマ。

### 道筋（上と下の関門）


<table>
<thead><tr><th nowrap>関門</th><th nowrap>価格（距離）</th><th nowrap>中身</th></tr></thead>
<tbody>
<tr><td nowrap>コールの壁（最大）・ガンマ最大（コール）</td><td nowrap><b>40</b> (+9.4%)</td><td nowrap>建玉 40,884・<br>12/4 で 19% 消える・<br>12/31 に 67%</td></tr>
<tr><td nowrap>コールの壁</td><td nowrap><b>39</b> (+6.6%)</td><td nowrap>建玉 7,727・<br>12/4 の満期には無い・<br>12/18 に 95%</td></tr>
<tr><td nowrap>コールの壁</td><td nowrap><b>38</b> (+3.9%)</td><td nowrap>建玉 8,212・<br>12/4 で 13% 消える・<br>12/18 に 82%</td></tr>
<tr><td nowrap><b>今</b></td><td nowrap><b>36.57</b></td><td nowrap>ガンマ プラス</td></tr>
<tr><td nowrap>プットの壁</td><td nowrap><b>35</b> (−4.3%)</td><td nowrap>建玉 11,212・<br>12/4 の満期には無い・<br>12/18 に 85%</td></tr>
<tr><td nowrap>プットの壁（最大）</td><td nowrap><b>30</b> (−18.0%)</td><td nowrap>建玉 11,294・<br>12/4 の満期には無い・<br>12/18 に 77%</td></tr>
<tr><td nowrap>プットの壁</td><td nowrap><b>26</b> (−28.9%)</td><td nowrap>建玉 3,812・<br>12/4 で 24% 消える・<br>12/18 に 74%</td></tr>
<tr><td nowrap>次の支え・ガンマ最大（プット）</td><td nowrap><b>25</b> (−31.6%)</td><td nowrap>建玉 28,313・<br>12/4 の満期には無い・<br>12/18 に 54%</td></tr>
<tr><td nowrap>ガンマの谷</td><td nowrap><b>18.1</b> (−50.5%)</td><td nowrap>マイナスが最も深い。<br>下げが加速しやすい中心</td></tr>
</tbody>
</table>

**2つの筋書き**（壁の配置からの読み。確率ではありません）

- 上に抜けた場合: ゼロガンマは見つからず、ガンマはプラスのまま。最大のコールの壁 **40**（+9.4%。12/4 で 19% 消える・12/31 に 67%）で止まりやすい。
- はね返された場合: 上の壁 38 の手前で止まり、下げると、下の支えは **35**→**30**→**26**。
- 次の満期（12/4）までの想定の幅は ±22.2%（28.4〜44.7）。最大のコールの壁 40 は幅の中・最大のプットの壁 30 は幅の中。
- ガンマは値動きの大きさの目安で、上げ・下げの向きは分かりません（第105回）。

**満期の内訳**（壁の建玉のうち、次の満期 12/4 で消える分。45日以内の満期）

<table>
<thead><tr><th nowrap>壁</th><th nowrap>建玉</th><th nowrap>消える分・<br>残る主な満期</th></tr></thead>
<tbody>
<tr><td nowrap><b>40C</b> (+9.4%)</td><td nowrap>40,884</td><td nowrap><b>19%</b>（残る玉）<br>12/31 に 67%</td></tr>
<tr><td nowrap><b>39C</b> (+6.6%)</td><td nowrap>7,727</td><td nowrap><b>0%</b>（残る玉）<br>12/18 に 95%</td></tr>
<tr><td nowrap><b>38C</b> (+3.9%)</td><td nowrap>8,212</td><td nowrap><b>13%</b>（残る玉）<br>12/18 に 82%</td></tr>
<tr><td nowrap><b>35P</b> (−4.3%)</td><td nowrap>11,212</td><td nowrap><b>0%</b>（残る玉）<br>12/18 に 85%</td></tr>
<tr><td nowrap><b>30P</b> (−18.0%)</td><td nowrap>11,294</td><td nowrap><b>0%</b>（残る玉）<br>12/18 に 77%</td></tr>
<tr><td nowrap><b>26P</b> (−28.9%)</td><td nowrap>3,812</td><td nowrap><b>24%</b>（残る玉）<br>12/18 に 74%</td></tr>
<tr><td nowrap><b>25P</b> (−31.6%)</td><td nowrap>28,313</td><td nowrap><b>0%</b>（残る玉）<br>12/18 に 54%</td></tr>
</tbody>
</table>

- 12/4 の満期の後に残る最大の壁: プットの壁 30（今と同じ）・コールの壁 40（今と同じ）。
- 主な満期（12/4 を除いて、ガンマが最大の契約 12/31 40C の満期）: 12/31。図の4段目に、この満期だけのガンマを出しています。

**壁の動き**（建玉の増減と、今日の大口）

<table>
<thead><tr><th nowrap>契約</th><th nowrap>建玉の増減・大口</th><th nowrap>見立て</th></tr></thead>
<tbody>
<tr><td nowrap><b>30C</b> (−18.0%)</td><td nowrap>建玉 +8,691（今 11,132）<br>12/4 売 2,306枚 $1.9M</td><td nowrap>上の壁の建設・<br>増強<br>（コール売り）</td></tr>
<tr><td nowrap><b>40C</b>★ (+9.4%)</td><td nowrap>建玉 −4,438（今 40,884）<br>12/4 売 8,746枚 $2.3M<br>12/18 売 2,583枚 $1.3M</td><td nowrap>上の壁の建設・<br>増強<br>（コール売り）</td></tr>
<tr><td nowrap><b>35C</b> (−4.3%)</td><td nowrap>建玉 −2,379（今 4,828）<br>12/4 売 6,690枚 $3.2M</td><td nowrap>上値の重し<br>（コール売り）</td></tr>
<tr><td nowrap><b>33C</b> (−9.8%)</td><td nowrap>建玉 −578（今 2,377）<br>12/4 売 1,855枚 $1.1M</td><td nowrap>上値の重し<br>（コール売り）</td></tr>
<tr><td nowrap><b>41P</b> (+12.1%)</td><td nowrap>建玉 −6,241（今 342）</td><td nowrap>プットの建玉の減少</td></tr>
<tr><td nowrap><b>32C</b> (−12.5%)</td><td nowrap>建玉 +1,442（今 3,027）</td><td nowrap>コールの建玉の増加<br>（売り買いは不明）</td></tr>
</tbody>
</table>

- 建玉の増減は前回の記録（11/25）から今の板まで（建玉は前の営業日の引けの数）。大口は直近の取引日（11/27）の、代金の多い契約（opt_flow の推定）。その日の取引が建玉に出るのは次の営業日なので、2つを続けて見ます。★は建玉の壁（上位3本）。コール売りなら、ディーラーはそのコールを買い持ちになり、その価格の近くで値動きを抑える向きに売り買いする（壁が厚くなる）とみます。

### 大口の賭け（推定）

**ベア 🐻・強さ 小**（売買代金の 0.2%） — SOXL はレバ3倍。半導体に直すと **ベア 🐻**

- 大口のデルタ換算（株を何ドル分買った・売ったのと同じ向きか）: 差 **−30.3百万ドル**（ブル側 +11.1百万ドル・ベア側 −41.4百万ドル）。代金はブル側 4.2百万ドル・ベア側 11.0百万ドル。1日の売買代金 139.2億ドル（20日の平均）
- 大口が見ている価格: 下値の防御線（プット売り） **30**（−18.0%）・上値の重し（コール売り） **40**（+9.4%）。大口は **30〜40** の幅とみている
- 深い ITM の大口（合計に入れない）: 3本・代金 22.8百万ドル（12/18 140P買・12/4 53P買・12/18 165P買）。株と組み合わせた取引（配当の裁定・乗り換えなど）のことが多い。そのまま賭けとみると −6.1百万ドル 分

<table>
<thead><tr><th nowrap>契約</th><th nowrap>推定・意味</th><th nowrap>代金・枚数</th></tr></thead>
<tbody>
<tr><td nowrap>12/4 35C<br>−4.3%<br>建玉 3,715</td><td nowrap><b>売り</b><br>上値の重し<br>（ITM）</td><td nowrap>$3.2M<br>6,690枚<br>Δ −$15M<br>IV 201%</td></tr>
<tr><td nowrap>12/4 40C<br>+9.4%<br>建玉 7,632</td><td nowrap><b>売り</b><br>上値の重し</td><td nowrap>$2.3M<br>8,746枚<br>Δ −$13M<br>IV 194%</td></tr>
<tr><td nowrap>12/4 30C<br>−18.0%<br>建玉 5,489</td><td nowrap><b>売り寄り</b><br>上値の重し<br>組の片側かも</td><td nowrap>$1.9M<br>2,306枚<br>Δ −$3.3M<br>IV 230%</td></tr>
<tr><td nowrap>12/18 40C<br>+9.4%<br>建玉 0</td><td nowrap><b>売り</b><br>上値の重し</td><td nowrap>$1.3M<br>2,583枚<br>Δ −$4.8M<br>IV 185%</td></tr>
<tr><td nowrap>12/4 33C<br>−9.8%<br>建玉 1,377</td><td nowrap><b>売り寄り</b><br><b>（IV −1.6pt）</b><br>上値の重し<br>組の片側かも</td><td nowrap>$1.1M<br>1,855枚<br>Δ −$2.3M<br>IV 215%</td></tr>
<tr><td nowrap>12/4 34C<br>−7.0%<br>建玉 654</td><td nowrap><b>売り寄り</b><br>上値の重し<br>組の片側かも</td><td nowrap>$1.1M<br>2,014枚<br>Δ −$2.4M<br>IV 216%</td></tr>
<tr><td nowrap>12/4 30P<br>−18.0%<br>建玉 0</td><td nowrap><b>売り寄り</b><br><b>（IV −7.0pt）</b><br>下値の防御線</td><td nowrap>$1.1M<br>5,955枚<br>Δ +$2.4M<br>IV 238%</td></tr>
<tr><td nowrap>12/4 40P<br>+9.4%<br>建玉 2,465</td><td nowrap><b>売り</b><br>下値の防御線<br>組の片側かも</td><td nowrap>$1.1M<br>1,856枚<br>Δ +$4.0M<br>IV 180%</td></tr>
<tr><td nowrap>12/4 46P<br>+25.8%<br>建玉 0</td><td nowrap><b>売り</b><br>下値の防御線<br>（ITM）</td><td nowrap>$1.0M<br>880枚<br>Δ +$2.2M<br>IV 249%</td></tr>
<tr><td nowrap>12/4 36C<br>−1.6%<br>建玉 1,274</td><td nowrap><b>買い寄り</b><br>上げへの賭け<br>組の片側かも</td><td nowrap>$1.0M<br>2,314枚<br>Δ +$2.4M<br>IV 201%</td></tr>
<tr><td nowrap>12/18 140P<br>+282.8%<br>建玉 0</td><td nowrap><b>買い寄り</b><br><b>（IV +178.4pt）</b><br>深い ITM の買い</td><td nowrap>$16M<br>1,552枚<br>Δ −$2.4M<br>IV 369%</td></tr>
<tr><td nowrap>12/4 53P<br>+44.9%<br>建玉 109</td><td nowrap><b>買い寄り</b><br>深い ITM の買い</td><td nowrap>$3.4M<br>2,002枚<br>Δ −$3.2M<br>IV 201%</td></tr>
<tr><td nowrap>12/18 165P<br>+351.2%<br>建玉 0</td><td nowrap><b>買い寄り</b><br><b>（IV +156.0pt）</b><br>深い ITM の買い</td><td nowrap>$3.1M<br>236枚<br>Δ −$0.4M<br>IV 366%</td></tr>
</tbody>
</table>

推定の向きは最後の約定の位置（売り気配で約定＝買い）と、前回の実行からの IV の上下から。買い・売りの分かる大口は代金の 100%。誰の取引かは分かりません。表の『代金・枚数』は、代金・その日の出来高・Δ（デルタ換算。株を何ドル分買った＋・売った−のと同じ向きか）・IV。

### 詳しく

**まとめ**: 下の支えの候補 **35**（−4.3%）・30（−18.0%）・26（−28.9%）。上の重さの候補 **38**（+3.9%）・39（+6.6%）・40（+9.4%）。既に割れたプットの壁 40（+9.4%）。次の満期（12/4・7日）の想定の幅 ±22.2%（28.45〜44.70）。ガンマはプラス側（ゼロガンマ —）→ 値動きが小さくなりやすい。

**下の支えの候補**（プットの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>36</td><td nowrap>−1.6%</td><td nowrap>3,054</td><td nowrap>4%</td></tr>
<tr><td nowrap>35</td><td nowrap>−4.3%</td><td nowrap>11,212</td><td nowrap>15%</td></tr>
<tr><td nowrap>34</td><td nowrap>−7.0%</td><td nowrap>1,926</td><td nowrap>3%</td></tr>
<tr><td nowrap>30</td><td nowrap>−18.0%</td><td nowrap>11,294</td><td nowrap>15%</td></tr>
<tr><td nowrap>26</td><td nowrap>−28.9%</td><td nowrap>3,812</td><td nowrap>5%</td></tr>
</tbody>
</table>

**上の重さの候補**（コールの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>38</td><td nowrap>+3.9%</td><td nowrap>8,212</td><td nowrap>7%</td></tr>
<tr><td nowrap>39</td><td nowrap>+6.6%</td><td nowrap>7,727</td><td nowrap>6%</td></tr>
<tr><td nowrap>40</td><td nowrap>+9.4%</td><td nowrap>40,884</td><td nowrap>34%</td></tr>
<tr><td nowrap>42</td><td nowrap>+14.8%</td><td nowrap>7,672</td><td nowrap>6%</td></tr>
<tr><td nowrap>45</td><td nowrap>+23.1%</td><td nowrap>4,640</td><td nowrap>4%</td></tr>
</tbody>
</table>

**次の満期 12/4（7日）**: プットの壁 27（−26.2%）・コールの壁 40（+9.4%）・最大の痛み 33（−9.8%）・想定の幅 ±22.2%

アウト・オブ・ザ・マネーに払われた代金: プット 14.5百万ドル・コール 21.3百万ドル（プットの割合 41%）

**建玉の増減**（前回のオプション分析の 11/25 → 今の板。45日以内の満期）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>距離</th><th nowrap>増減</th><th nowrap>想定元本</th></tr></thead>
<tbody>
<tr><td nowrap>30C</td><td nowrap>−18.0%</td><td nowrap>+8,691</td><td nowrap>26.1百万ドル</td></tr>
<tr><td nowrap>32C</td><td nowrap>−12.5%</td><td nowrap>+1,442</td><td nowrap>4.6百万ドル</td></tr>
<tr><td nowrap>46C</td><td nowrap>+25.8%</td><td nowrap>+1,219</td><td nowrap>5.6百万ドル</td></tr>
<tr><td nowrap>41P</td><td nowrap>+12.1%</td><td nowrap>−6,241</td><td nowrap>−25.6百万ドル</td></tr>
<tr><td nowrap>39P</td><td nowrap>+6.6%</td><td nowrap>−5,244</td><td nowrap>−20.5百万ドル</td></tr>
</tbody>
</table>

合計: プット −157.8百万ドル・コール −16.7百万ドル（想定元本の増減）

**全体**: IV30 203%・7日 210%・期間構造 1.04・プットの割高さ −23.0pt・建玉のプット/コール 0.69

**過去の検証**: 未検証（第190回で、2008〜2025年の QQQ・SPY・NVDA・AVGO・AMD・QCOM・TXN の板で確かめ中）。それまでは、下の目安は過去の効きが確かめられていない参考の値です。

## SOXS　52.94

米国 11/27 21:23（取引時間外）・直近の取引日 11/27・板 Yahoo

### 結論

<table>
<thead><tr><th nowrap>問い</th><th nowrap>答え</th></tr></thead>
<tbody>
<tr><td nowrap>建玉の偏り</td><td nowrap><b>コール（買う権利）</b><br><b>のほうが多い</b><br><b>（いつもとの比較はまだできない）</b><br>（プット 36%・コール 64%）</td></tr>
<tr><td nowrap>σ（側）</td><td nowrap><b>—</b></td></tr>
<tr><td nowrap>前日から</td><td nowrap><b>—</b><br>（前日の記録と比べられません<br>（σ を出せない日））</td></tr>
<tr><td nowrap>大きなプット</td><td nowrap>40 (−24.4%)<br>50 (−5.6%)<br>38 (−28.2%)</td></tr>
<tr><td nowrap>大きなコール☆</td><td nowrap>65 (+22.8%)<br>50 (−5.6%)<br>55 (+3.9%)</td></tr>
</tbody>
</table>

- σ: ①の毎日の記録が 1日分しかなく、σ を出せません（10日たまると出ます）。
- 大きなプット・コールの印: ★ 偏っている側、☆ 偏りは小さいが数の多い側。『○/○』は、枚数/金額（建玉 × 値段 × 100）が過去30日の平常の何倍か。
- 偏りの物差し: 満期まで 3〜75日の全ての建玉（①の毎日の記録と同じ）。建玉には買い手と売り手が同じ数だけいるので、偏りはコールとプットの数で見ています。

**プットの大きな建玉の枚数とお金**（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> OTM</td><td nowrap>2,379 (<b>—</b>)</td><td nowrap>0.60M (<b>—</b>)</td></tr>
<tr><td nowrap><b>50</b> OTM</td><td nowrap>1,084 (<b>—</b>)</td><td nowrap>0.92M (<b>—</b>)</td></tr>
<tr><td nowrap><b>38</b> OTM</td><td nowrap>850 (<b>—</b>)</td><td nowrap>0.18M (<b>—</b>)</td></tr>
<tr><td nowrap><b>51</b> OTM</td><td nowrap>813 (<b>—</b>)</td><td nowrap>0.63M (<b>—</b>)</td></tr>
<tr><td nowrap><b>44</b> OTM</td><td nowrap>785 (<b>—</b>)</td><td nowrap>0.38M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

**コールの大きな建玉の枚数とお金**（数の多い側）（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>65</b> OTM</td><td nowrap>1,655 (<b>—</b>)</td><td nowrap>1.06M (<b>—</b>)</td></tr>
<tr><td nowrap><b>50</b> ITM</td><td nowrap>1,519 (<b>—</b>)</td><td nowrap>1.72M (<b>—</b>)</td></tr>
<tr><td nowrap><b>55</b> OTM</td><td nowrap>1,441 (<b>—</b>)</td><td nowrap>1.22M (<b>—</b>)</td></tr>
<tr><td nowrap><b>58</b> OTM</td><td nowrap>1,321 (<b>—</b>)</td><td nowrap>0.80M (<b>—</b>)</td></tr>
<tr><td nowrap><b>60</b> OTM</td><td nowrap>1,165 (<b>—</b>)</td><td nowrap>1.00M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

- 枚数の平常比は同じ側・同じ順位（過去の各日の、枚数が同じ順位の建玉）、金額の平常比は同じ側の過去の大きな建玉（各日の上位5本）と比べた倍率。▲▲ 30日で最多・▲ 多い（上位25%）・▼ 少ない（下位25%）・▼▼ 30日で最少。印が無ければ平常並み。建玉の合計も▲なら、満期（特に3・6・9・12月の第3金曜）に向けて全体が増えている分を差し引いて見てください。金額は建玉 × 値段 × 100（ITM は本質的な価値を含む。今の板）。

**プットの大きな建玉**（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> (−24.4%)</td><td nowrap>2,379 (17%)</td><td nowrap>12/18 $3.03</td></tr>
<tr><td nowrap><b>50</b> (−5.6%)</td><td nowrap>1,084 (8%)</td><td nowrap>12/24 $9.25</td></tr>
<tr><td nowrap><b>38</b> (−28.2%)</td><td nowrap>850 (6%)</td><td nowrap>12/31 $3.50</td></tr>
<tr><td nowrap><b>51</b> (−3.7%)</td><td nowrap>813 (6%)</td><td nowrap>12/18 $8.05</td></tr>
<tr><td nowrap><b>44</b> (−16.9%)</td><td nowrap>785 (5%)</td><td nowrap>12/31 $6.20</td></tr>
</tbody>
</table>

**コールの大きな建玉**（数の多い側）（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>65</b> (+22.8%)</td><td nowrap>1,655 (12%)</td><td nowrap>12/24 $8.32</td></tr>
<tr><td nowrap><b>50</b> (−5.6%)</td><td nowrap>1,519 (11%)</td><td nowrap>12/18 $13.68</td></tr>
<tr><td nowrap><b>55</b> (+3.9%)</td><td nowrap>1,441 (11%)</td><td nowrap>12/4 $5.55</td></tr>
<tr><td nowrap><b>58</b> (+9.6%)</td><td nowrap>1,321 (10%)</td><td nowrap>12/4 $4.65</td></tr>
<tr><td nowrap><b>60</b> (+13.3%)</td><td nowrap>1,165 (9%)</td><td nowrap>12/18 $8.55</td></tr>
</tbody>
</table>

### オプションの配置（図）

![SOXS のオプションの配置](SOXS_options_chart.svg)

- 今の株価でのガンマの合計は**プラス**（+1百万ドル／1%）。
- 上の段: 株価がその値になったときの、ディーラーのガンマの合計（赤い点線がゼロガンマ）。赤い背景（マイナス）の価格帯では、ディーラーが下げで売り・上げで買うので値動きが大きくなりやすく、緑の背景（プラス）では小さくなりやすい。
- 中の段: 行使価格ごとのガンマ（コールは上、プットは下）。下の段: 行使価格ごとの建玉（45日以内の満期）と、プットの壁・コールの壁（灰色の点線）。黒い線が今の株価。
- 薄い色は 12/4 の満期で消える分（濃い色が残る分）。点線は 12/4 の満期の後のガンマの合計（IV・株価は今のまま）。4段目は、主な満期 1/15 だけのガンマ。

### 道筋（上と下の関門）


<table>
<thead><tr><th nowrap>関門</th><th nowrap>価格（距離）</th><th nowrap>中身</th></tr></thead>
<tbody>
<tr><td nowrap>ガンマ最大（コール）</td><td nowrap><b>80</b> (+51.1%)</td><td nowrap>—</td></tr>
<tr><td nowrap>次の壁</td><td nowrap><b>78</b> (+47.3%)</td><td nowrap>建玉 2,558・<br>12/4 で 25% 消える・<br>12/24 に 75%</td></tr>
<tr><td nowrap>コールの壁（最大）</td><td nowrap><b>65</b> (+22.8%)</td><td nowrap>建玉 1,655・<br>12/4 で 35% 消える・<br>12/24 に 35%</td></tr>
<tr><td nowrap>コールの壁</td><td nowrap><b>58</b> (+9.6%)</td><td nowrap>建玉 1,321・<br>12/4 で 79% 消える</td></tr>
<tr><td nowrap>コールの壁</td><td nowrap><b>55</b> (+3.9%)</td><td nowrap>建玉 1,441・<br>12/4 で 38% 消える・<br>12/18 に 36%</td></tr>
<tr><td nowrap><b>今</b></td><td nowrap><b>52.94</b></td><td nowrap>ガンマ プラス</td></tr>
<tr><td nowrap>プットの壁</td><td nowrap><b>50</b> (−5.6%)</td><td nowrap>建玉 1,084・<br>12/4 の満期には無い・<br>12/24 に 54%</td></tr>
<tr><td nowrap>プットの壁（最大）</td><td nowrap><b>40</b> (−24.4%)</td><td nowrap>建玉 2,379・<br>12/4 で 22% 消える・<br>12/18 に 68%</td></tr>
<tr><td nowrap>プットの壁</td><td nowrap><b>38</b> (−28.2%)</td><td nowrap>建玉 850・<br>12/4 で 44% 消える・<br>12/31 に 53%</td></tr>
<tr><td nowrap>次の支え・ガンマ最大（プット）</td><td nowrap><b>30</b> (−43.3%)</td><td nowrap>建玉 2,464・<br>12/4 で 40% 消える・<br>12/18 に 58%</td></tr>
<tr><td nowrap>ガンマの谷</td><td nowrap><b>28.3</b> (−46.5%)</td><td nowrap>マイナスが最も深い。<br>下げが加速しやすい中心</td></tr>
</tbody>
</table>

**2つの筋書き**（壁の配置からの読み。確率ではありません）

- 上に抜けた場合: ゼロガンマは見つからず、ガンマはプラスのまま。最大のコールの壁 **65**（+22.8%。12/4 で 35% 消える・12/24 に 35%）で止まりやすい。超えれば次の壁 **78**（+47.3%）。
- はね返された場合: 上の壁 55 の手前で止まり、下げると、下の支えは **50**→**40**→**38**（12/4 で 44% 消える）。
- 次の満期（12/4）までの想定の幅は ±22.7%（40.9〜65.0）。最大のコールの壁 65 は幅の外・最大のプットの壁 40 は幅の外。
- ガンマは値動きの大きさの目安で、上げ・下げの向きは分かりません（第105回）。

**満期の内訳**（壁の建玉のうち、次の満期 12/4 で消える分。45日以内の満期）

<table>
<thead><tr><th nowrap>壁</th><th nowrap>建玉</th><th nowrap>消える分・<br>残る主な満期</th></tr></thead>
<tbody>
<tr><td nowrap><b>78C</b> (+47.3%)</td><td nowrap>2,558</td><td nowrap><b>25%</b>（残る玉）<br>12/24 に 75%</td></tr>
<tr><td nowrap><b>65C</b> (+22.8%)</td><td nowrap>1,655</td><td nowrap><b>35%</b><br>（半分ほど消える）<br>12/24 に 35%</td></tr>
<tr><td nowrap><b>58C</b> (+9.6%)</td><td nowrap>1,321</td><td nowrap><b>79%</b>（消える玉）<br>12/24 に 11%</td></tr>
<tr><td nowrap><b>55C</b> (+3.9%)</td><td nowrap>1,441</td><td nowrap><b>38%</b><br>（半分ほど消える）<br>12/18 に 36%</td></tr>
<tr><td nowrap><b>50P</b> (−5.6%)</td><td nowrap>1,084</td><td nowrap><b>0%</b>（残る玉）<br>12/24 に 54%</td></tr>
<tr><td nowrap><b>40P</b> (−24.4%)</td><td nowrap>2,379</td><td nowrap><b>22%</b>（残る玉）<br>12/18 に 68%</td></tr>
<tr><td nowrap><b>38P</b> (−28.2%)</td><td nowrap>850</td><td nowrap><b>44%</b><br>（半分ほど消える）<br>12/31 に 53%</td></tr>
<tr><td nowrap><b>30P</b> (−43.3%)</td><td nowrap>2,464</td><td nowrap><b>40%</b><br>（半分ほど消える）<br>12/18 に 58%</td></tr>
</tbody>
</table>

- 12/4 の満期の後に残る最大の壁: プットの壁 40（今と同じ）・コールの壁 60（今は 65）。
- 主な満期（12/4 を除いて、ガンマが最大の契約 1/15 30P の満期）: 1/15。図の4段目に、この満期だけのガンマを出しています。

**壁の動き**（建玉の増減と、今日の大口）

<table>
<thead><tr><th nowrap>契約</th><th nowrap>建玉の増減・大口</th><th nowrap>見立て</th></tr></thead>
<tbody>
<tr><td nowrap><b>60C</b> (+13.3%)</td><td nowrap>建玉 −1,976（今 1,165）<br>12/4 売 2,293枚 $0.9M</td><td nowrap>上値の重し<br>（コール売り）</td></tr>
<tr><td nowrap><b>60P</b> (+13.3%)</td><td nowrap>建玉 −619（今 195）<br>12/4 売 551枚 $0.5M</td><td nowrap>下値の防御線<br>（プット売り）</td></tr>
<tr><td nowrap><b>41C</b> (−22.6%)</td><td nowrap>建玉 −41（今 55）<br>2/19 買 160枚 $0.4M</td><td nowrap>上げの的<br>（コール買い）</td></tr>
<tr><td nowrap><b>61P</b> (+15.2%)</td><td nowrap>建玉 +5（今 186）<br>2/19 向き不明 195枚 $0.4M</td><td nowrap>プットの建玉の増加<br>（売り買いは不明）</td></tr>
<tr><td nowrap><b>50P</b>★ (−5.6%)</td><td nowrap>建玉 −1,489（今 1,084）</td><td nowrap>プットの壁の取り崩し</td></tr>
<tr><td nowrap><b>41.5P</b> (−21.6%)</td><td nowrap>建玉 +167（今 421）</td><td nowrap>プットの建玉の増加<br>（売り買いは不明）</td></tr>
</tbody>
</table>

- 建玉の増減は前回の記録（11/25）から今の板まで（建玉は前の営業日の引けの数）。大口は直近の取引日（11/27）の、代金の多い契約（opt_flow の推定）。その日の取引が建玉に出るのは次の営業日なので、2つを続けて見ます。★は建玉の壁（上位3本）。コール売りなら、ディーラーはそのコールを買い持ちになり、その価格の近くで値動きを抑える向きに売り買いする（壁が厚くなる）とみます。

### 大口の賭け（推定）

**ブル 🐂・強さ 小**（売買代金の 0.0%） — SOXS は逆レバ3倍。半導体に直すと **ベア 🐻**

- 大口のデルタ換算（株を何ドル分買った・売ったのと同じ向きか）: 差 **+2.5百万ドル**（ブル側 +5.3百万ドル・ベア側 −2.8百万ドル）。代金はブル側 2.0百万ドル・ベア側 1.3百万ドル。1日の売買代金 63.9億ドル（20日の平均）
- 大口が見ている価格: 上値の重し（コール売り） **60**（+13.3%）・上げの的（コール買い） **65**（+22.8%）・下げの的（プット買い） **26**（−50.9%）
- 深い ITM の大口（合計に入れない）: 3本・代金 1.1百万ドル（12/11 75P売・12/31 35C買・12/4 74P売）。株と組み合わせた取引（配当の裁定・乗り換えなど）のことが多い。そのまま賭けとみると +1.0百万ドル 分

<table>
<thead><tr><th nowrap>契約</th><th nowrap>推定・意味</th><th nowrap>代金・枚数</th></tr></thead>
<tbody>
<tr><td nowrap>12/4 60C<br>+13.3%<br>建玉 0</td><td nowrap><b>売り寄り</b><br>上値の重し<br>（原指数には逆）</td><td nowrap>$0.9M<br>2,293枚<br>Δ −$2.5M<br>IV 228%</td></tr>
<tr><td nowrap>12/4 60P<br>+13.3%<br>建玉 0</td><td nowrap><b>売り</b><br>下値の防御線<br>（ITM）<br>（原指数には逆）</td><td nowrap>$0.5M<br>551枚<br>Δ +$1.9M<br>IV 172%</td></tr>
<tr><td nowrap>12/18 125C<br>+136.1%<br>建玉 0</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$0.5M<br>2,096枚<br>Δ —<br>IV 275%</td></tr>
<tr><td nowrap>2/19 61P<br>+15.2%<br>建玉 204</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$0.4M<br>195枚<br>Δ —<br>IV 175%</td></tr>
<tr><td nowrap>2/19 41C<br>−22.6%<br>建玉 109</td><td nowrap><b>買い寄り</b><br><b>（IV +34.4pt）</b><br>上げへの賭け<br>（ITM）<br>（原指数には逆）</td><td nowrap>$0.4M<br>160枚<br>Δ +$0.3M<br>IV 207%</td></tr>
<tr><td nowrap>1/15 64P<br>+20.9%<br>建玉 112</td><td nowrap><b>売り寄り</b><br><b>（IV −2.0pt）</b><br>下値の防御線<br>（ITM）<br>（原指数には逆）</td><td nowrap>$0.4M<br>173枚<br>Δ +$0.2M<br>IV 187%</td></tr>
<tr><td nowrap>12/24 65C<br>+22.8%<br>建玉 587</td><td nowrap><b>買い</b><br>上げへの賭け<br>（原指数には逆）</td><td nowrap>$0.4M<br>434枚<br>Δ +$1.1M<br>IV 215%</td></tr>
<tr><td nowrap>12/4 55C<br>+3.9%<br>建玉 546</td><td nowrap><b>買い</b><br>上げへの賭け<br>（原指数には逆）</td><td nowrap>$0.4M<br>648枚<br>Δ +$1.8M<br>IV 220%</td></tr>
<tr><td nowrap>12/18 69C<br>+30.3%<br>建玉 0</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$0.3M<br>492枚<br>Δ —<br>IV 235%</td></tr>
<tr><td nowrap>2/19 26P<br>−50.9%<br>建玉 682</td><td nowrap><b>買い寄り</b><br><b>（IV +9.4pt）</b><br>下げへの賭け・<br>守り<br>（原指数には逆）</td><td nowrap>$0.3M<br>1,218枚<br>Δ −$0.3M<br>IV 162%</td></tr>
<tr><td nowrap>12/11 75P<br>+41.7%<br>建玉 103</td><td nowrap><b>売り寄り</b><br><b>（IV −53.3pt）</b><br>深い ITM の売り</td><td nowrap>$0.5M<br>204枚<br>Δ +$0.4M<br>IV 172%</td></tr>
<tr><td nowrap>12/31 35C<br>−33.9%<br>建玉 0</td><td nowrap><b>買い寄り</b><br><b>（IV +69.4pt）</b><br>深い ITM の買い</td><td nowrap>$0.4M<br>150枚<br>Δ +$0.3M<br>IV 252%</td></tr>
<tr><td nowrap>12/4 74P<br>+39.8%<br>建玉 0</td><td nowrap><b>売り寄り</b><br><b>（IV −45.6pt）</b><br>深い ITM の売り</td><td nowrap>$0.2M<br>102枚<br>Δ +$0.2M<br>IV 207%</td></tr>
</tbody>
</table>

推定の向きは最後の約定の位置（売り気配で約定＝買い）と、前回の実行からの IV の上下から。買い・売りの分かる大口は代金の 72%。誰の取引かは分かりません。表の『代金・枚数』は、代金・その日の出来高・Δ（デルタ換算。株を何ドル分買った＋・売った−のと同じ向きか）・IV。

### 詳しく

**まとめ**: 下の支えの候補 **50**（−5.6%）・40（−24.4%）・38（−28.2%）。上の重さの候補 **55**（+3.9%）・58（+9.6%）・65（+22.8%）。既に割れたプットの壁 59（+11.4%）。次の満期（12/4・7日）の想定の幅 ±22.7%（40.91〜64.97）。ガンマはプラス側（ゼロガンマ —）→ 値動きが小さくなりやすい。

**下の支えの候補**（プットの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>51</td><td nowrap>−3.7%</td><td nowrap>813</td><td nowrap>6%</td></tr>
<tr><td nowrap>50</td><td nowrap>−5.6%</td><td nowrap>1,084</td><td nowrap>8%</td></tr>
<tr><td nowrap>44</td><td nowrap>−16.9%</td><td nowrap>785</td><td nowrap>5%</td></tr>
<tr><td nowrap>40</td><td nowrap>−24.4%</td><td nowrap>2,379</td><td nowrap>17%</td></tr>
<tr><td nowrap>38</td><td nowrap>−28.2%</td><td nowrap>850</td><td nowrap>6%</td></tr>
</tbody>
</table>

**上の重さの候補**（コールの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>55</td><td nowrap>+3.9%</td><td nowrap>1,441</td><td nowrap>11%</td></tr>
<tr><td nowrap>58</td><td nowrap>+9.6%</td><td nowrap>1,321</td><td nowrap>10%</td></tr>
<tr><td nowrap>58.5</td><td nowrap>+10.5%</td><td nowrap>633</td><td nowrap>5%</td></tr>
<tr><td nowrap>60</td><td nowrap>+13.3%</td><td nowrap>1,165</td><td nowrap>9%</td></tr>
<tr><td nowrap>65</td><td nowrap>+22.8%</td><td nowrap>1,655</td><td nowrap>12%</td></tr>
</tbody>
</table>

**次の満期 12/4（7日）**: プットの壁 40（−24.4%）・コールの壁 58（+9.6%）・最大の痛み 48.5（−8.4%）・想定の幅 ±22.7%

アウト・オブ・ザ・マネーに払われた代金: プット 2.9百万ドル・コール 7.3百万ドル（プットの割合 28%）

**建玉の増減**（前回のオプション分析の 11/25 → 今の板。45日以内の満期）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>距離</th><th nowrap>増減</th><th nowrap>想定元本</th></tr></thead>
<tbody>
<tr><td nowrap>41.5P</td><td nowrap>−21.6%</td><td nowrap>+167</td><td nowrap>0.7百万ドル</td></tr>
<tr><td nowrap>47P</td><td nowrap>−11.2%</td><td nowrap>+127</td><td nowrap>0.6百万ドル</td></tr>
<tr><td nowrap>58C</td><td nowrap>+9.6%</td><td nowrap>+114</td><td nowrap>0.7百万ドル</td></tr>
<tr><td nowrap>60C</td><td nowrap>+13.3%</td><td nowrap>−1,976</td><td nowrap>−11.9百万ドル</td></tr>
<tr><td nowrap>50P</td><td nowrap>−5.6%</td><td nowrap>−1,489</td><td nowrap>−7.4百万ドル</td></tr>
</tbody>
</table>

合計: プット −22.6百万ドル・コール −37.6百万ドル（想定元本の増減）

**全体**: IV30 197%・7日 211%・期間構造 1.07（目先の不安が強い）・プットの割高さ +9.5pt・建玉のプット/コール 0.63

**過去の検証**: 未検証（第190回で、2008〜2025年の QQQ・SPY・NVDA・AVGO・AMD・QCOM・TXN の板で確かめ中）。それまでは、下の目安は過去の効きが確かめられていない参考の値です。

## QQQ　650.99

米国 11/27 21:23（取引時間外）・直近の取引日 11/27・板 Yahoo

### 結論

<table>
<thead><tr><th nowrap>問い</th><th nowrap>答え</th></tr></thead>
<tbody>
<tr><td nowrap>建玉の偏り</td><td nowrap><b>いつも並み（偏りは小さい）</b><br>（プット 51%・コール 49%）</td></tr>
<tr><td nowrap>σ（側）</td><td nowrap><b>コール側に 0.7σ</b><br><b>（1σ 未満で、偏りは小さい）</b></td></tr>
<tr><td nowrap>前日から</td><td nowrap><b>プット側へ 0.1σ</b><br>（11/25 コール側に 0.8σ<br>（プット÷コール 1.00）<br>→ 今 コール側に 0.7σ<br>（1.02））</td></tr>
<tr><td nowrap>大きなプット☆</td><td nowrap>600 (−7.8%) 0.65▼/0.31▼<br>550 (−15.5%)<br>0.68▼▼/0.10▼<br>540 (−17.0%)<br>0.59▼▼/0.07▼▼</td></tr>
<tr><td nowrap>大きなコール</td><td nowrap>680 (+4.5%) 0.78▼/4.6▲<br>715 (+9.8%) 0.69▼▼/0.91<br>725 (+11.4%) 0.64▼▼/0.24</td></tr>
</tbody>
</table>

- σ: いつも（10/9〜11/25 の 26日）のプット÷コールは平均 1.19、今は 1.02。記録が60日たまるまでは目安。
- 大きなプット・コールの印: ★ 偏っている側、☆ 偏りは小さいが数の多い側。『○/○』は、枚数/金額（建玉 × 値段 × 100）が過去30日の平常の何倍か。
- 偏りの物差し: 満期まで 3〜75日の全ての建玉（①の毎日の記録と同じ）。建玉には買い手と売り手が同じ数だけいるので、偏りはコールとプットの数で見ています。

**プットの大きな建玉の枚数とお金**（数の多い側）（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>600</b> OTM</td><td nowrap>119,439<br>(<b>0.65▼</b>)</td><td nowrap>56.2M (<b>0.31▼</b>)</td></tr>
<tr><td nowrap><b>550</b> OTM</td><td nowrap>105,932<br>(<b>0.68▼▼</b>)</td><td nowrap>17.8M (<b>0.10▼</b>)</td></tr>
<tr><td nowrap><b>540</b> OTM</td><td nowrap>86,000<br>(<b>0.59▼▼</b>)</td><td nowrap>12.4M (<b>0.07▼▼</b>)</td></tr>
<tr><td nowrap><b>640</b> OTM</td><td nowrap>75,558<br>(<b>0.59▼▼</b>)</td><td nowrap>97.4M (<b>0.53</b>)</td></tr>
<tr><td nowrap><b>610</b> OTM</td><td nowrap>66,564<br>(<b>0.59▼▼</b>)</td><td nowrap>47.2M (<b>0.26▼</b>)</td></tr>
</tbody>
</table>

- 平常（11/6〜11/25 の 14日、うち 10日は値段を推定）の中央値: 枚数 1番目 182,893枚・2番目 156,890枚・3番目 146,921枚・4番目 127,604枚・5番目 111,948枚。金額 183Mドル（大きなプット 70本）。30日分の記録がたまるまでは目安。
- プットの建玉の合計（45日以内・株価の ±30%）: 1,605,688枚＝平常の0.51倍 ▼▼。

**コールの大きな建玉の枚数とお金**（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>680</b> OTM</td><td nowrap>143,423<br>(<b>0.78▼</b>)</td><td nowrap>77.5M (<b>4.6▲</b>)</td></tr>
<tr><td nowrap><b>715</b> OTM</td><td nowrap>98,902<br>(<b>0.69▼▼</b>)</td><td nowrap>15.5M (<b>0.91</b>)</td></tr>
<tr><td nowrap><b>725</b> OTM</td><td nowrap>79,077<br>(<b>0.64▼▼</b>)</td><td nowrap>4.06M (<b>0.24</b>)</td></tr>
<tr><td nowrap><b>650</b> ATM</td><td nowrap>64,282<br>(<b>0.60▼▼</b>)</td><td nowrap>98.5M (<b>5.8▲</b>)</td></tr>
<tr><td nowrap><b>660</b> OTM</td><td nowrap>57,427<br>(<b>0.56▼▼</b>)</td><td nowrap>60.9M (<b>3.6▲</b>)</td></tr>
</tbody>
</table>

- 平常（11/6〜11/25 の 14日、うち 10日は値段を推定）の中央値: 枚数 1番目 183,708枚・2番目 143,886枚・3番目 123,251枚・4番目 106,798枚・5番目 101,722枚。金額 17.0Mドル（大きなコール 70本）。30日分の記録がたまるまでは目安。
- コールの建玉の合計（45日以内・株価の ±30%）: 1,505,757枚＝平常の0.51倍 ▼▼。

- 枚数の平常比は同じ側・同じ順位（過去の各日の、枚数が同じ順位の建玉）、金額の平常比は同じ側の過去の大きな建玉（各日の上位5本）と比べた倍率。▲▲ 30日で最多・▲ 多い（上位25%）・▼ 少ない（下位25%）・▼▼ 30日で最少。印が無ければ平常並み。建玉の合計も▲なら、満期（特に3・6・9・12月の第3金曜）に向けて全体が増えている分を差し引いて見てください。金額は建玉 × 値段 × 100（ITM は本質的な価値を含む。今の板）。

**プットの大きな建玉**（数の多い側）（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>600</b> (−7.8%)</td><td nowrap>119,439 (7%)</td><td nowrap>12/18 $5.88</td></tr>
<tr><td nowrap><b>550</b> (−15.5%)</td><td nowrap>105,932 (7%)</td><td nowrap>12/18 $1.98</td></tr>
<tr><td nowrap><b>540</b> (−17.0%)</td><td nowrap>86,000 (5%)</td><td nowrap>12/18 $1.64</td></tr>
<tr><td nowrap><b>640</b> (−1.7%)</td><td nowrap>75,558 (5%)</td><td nowrap>12/18 $14.74</td></tr>
<tr><td nowrap><b>610</b> (−6.3%)</td><td nowrap>66,564 (4%)</td><td nowrap>12/18 $7.37</td></tr>
</tbody>
</table>

**コールの大きな建玉**（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>680</b> (+4.5%)</td><td nowrap>143,423 (10%)</td><td nowrap>12/18 $6.64</td></tr>
<tr><td nowrap><b>715</b> (+9.8%)</td><td nowrap>98,902 (7%)</td><td nowrap>12/18 $1.09</td></tr>
<tr><td nowrap><b>725</b> (+11.4%)</td><td nowrap>79,077 (5%)</td><td nowrap>12/18 $0.58</td></tr>
<tr><td nowrap><b>650</b> (−0.2%)</td><td nowrap>64,282 (4%)</td><td nowrap>12/18 $20.22</td></tr>
<tr><td nowrap><b>660</b> (+1.4%)</td><td nowrap>57,427 (4%)</td><td nowrap>12/18 $14.49</td></tr>
</tbody>
</table>

### オプションの配置（図）

![QQQ のオプションの配置](QQQ_options_chart.svg)

- 今の株価でのガンマの合計は**マイナス**（−1,407百万ドル／1%）、ゼロガンマは **669.43**（+2.8%）。推定の幅 662.74〜676.12。
- 上の段: 株価がその値になったときの、ディーラーのガンマの合計（赤い点線がゼロガンマ）。赤い背景（マイナス）の価格帯では、ディーラーが下げで売り・上げで買うので値動きが大きくなりやすく、緑の背景（プラス）では小さくなりやすい。
- 中の段: 行使価格ごとのガンマ（コールは上、プットは下）。下の段: 行使価格ごとの建玉（45日以内の満期）と、プットの壁・コールの壁（灰色の点線）。黒い線が今の株価。
- 薄い色は 11/30 の満期で消える分（濃い色が残る分）。点線は 11/30 の満期の後のガンマの合計（IV・株価は今のまま）。4段目は、主な満期 12/18 だけのガンマ。

### 道筋（上と下の関門）

- 今の株価 650.99 は、ゼロガンマ 669（推定の幅 663〜676）の**下（マイナス）**。値動きが大きくなりやすい。11/30 の満期の後のゼロガンマは 672（+3.3%）。

<table>
<thead><tr><th nowrap>関門</th><th nowrap>価格（距離）</th><th nowrap>中身</th></tr></thead>
<tbody>
<tr><td nowrap>ガンマの山</td><td nowrap><b>752</b> (+15.5%)</td><td nowrap>ここまでは上げるほどディーラーのガンマ<br>（買い持ち）<br>が増え、<br>値動きが小さくなりやすい</td></tr>
<tr><td nowrap>平らになる</td><td nowrap><b>732</b> (+12.5%)</td><td nowrap>ここより上は、<br>上げてもディーラーのガンマがほとんど増えない。<br>壁の力が弱まり、<br>ニュートラルに近い</td></tr>
<tr><td nowrap>コールの壁</td><td nowrap><b>725</b> (+11.4%)</td><td nowrap>建玉 79,077・<br>11/30 で 17% 消える・<br>12/18 に 78%</td></tr>
<tr><td nowrap>コールの壁・次の壁</td><td nowrap><b>715</b> (+9.8%)</td><td nowrap>建玉 98,902・<br>11/30 で 3% 消える・<br>12/18 に 53%</td></tr>
<tr><td nowrap>コールの壁（最大）・ガンマ最大（コール）</td><td nowrap><b>680</b> (+4.5%)</td><td nowrap>建玉 143,423・<br>11/30 で 21% 消える・<br>12/18 に 70%</td></tr>
<tr><td nowrap>ゼロガンマ</td><td nowrap><b>669.43</b> (+2.8%)</td><td nowrap>超えるとガンマはプラス<br>（値動きが小さくなりやすい）。<br>推定の幅 663〜676</td></tr>
<tr><td nowrap><b>今</b></td><td nowrap><b>650.99</b></td><td nowrap>ガンマ マイナス</td></tr>
<tr><td nowrap>ガンマ最大（プット）</td><td nowrap><b>650</b> (−0.2%)</td><td nowrap>—</td></tr>
<tr><td nowrap>プットの壁（最大）・ガンマの谷</td><td nowrap><b>600</b> (−7.8%)</td><td nowrap>建玉 119,439・<br>11/30 で 12% 消える・<br>12/18 に 71%。<br>マイナスが最も深い。<br>下げが加速しやすい中心</td></tr>
<tr><td nowrap>プットの壁・次の支え</td><td nowrap><b>550</b> (−15.5%)</td><td nowrap>建玉 105,932・<br>11/30 で 15% 消える・<br>12/18 に 66%</td></tr>
<tr><td nowrap>プットの壁</td><td nowrap><b>540</b> (−17.0%)</td><td nowrap>建玉 86,000・<br>11/30 で 15% 消える・<br>12/18 に 73%</td></tr>
</tbody>
</table>

**2つの筋書き**（壁の配置からの読み。確率ではありません）

- 上に抜けた場合: ゼロガンマ 669（+2.8%）を上に超えると、ガンマはプラスになり、値動きが小さくなりやすい。最大のコールの壁 **680**（+4.5%。11/30 で 21% 消える・12/18 に 70%）で止まりやすい。超えれば次の壁 **715**（+9.8%）。732（+12.5%）より上はガンマがほぼ平らで、壁の力が弱まる（ニュートラルに近い）。
- はね返された場合: ゼロガンマ 669 の手前で止まって下げると、ガンマはマイナスのままで、値動きが大きくなりやすい（ガンマの谷は 605）。下の支えは **600**→**550**→**540**。
- 次の満期（11/30）までの想定の幅は ±1.8%（639〜663）。最大のコールの壁 680 は幅の外・最大のプットの壁 600 は幅の外。
- ガンマは値動きの大きさの目安で、上げ・下げの向きは分かりません（第105回）。

**満期の内訳**（壁の建玉のうち、次の満期 11/30 で消える分。45日以内の満期）

<table>
<thead><tr><th nowrap>壁</th><th nowrap>建玉</th><th nowrap>消える分・<br>残る主な満期</th></tr></thead>
<tbody>
<tr><td nowrap><b>725C</b> (+11.4%)</td><td nowrap>79,077</td><td nowrap><b>17%</b>（残る玉）<br>12/18 に 78%</td></tr>
<tr><td nowrap><b>715C</b> (+9.8%)</td><td nowrap>98,902</td><td nowrap><b>3%</b>（残る玉）<br>12/18 に 53%</td></tr>
<tr><td nowrap><b>680C</b> (+4.5%)</td><td nowrap>143,423</td><td nowrap><b>21%</b>（残る玉）<br>12/18 に 70%</td></tr>
<tr><td nowrap><b>600P</b> (−7.8%)</td><td nowrap>119,439</td><td nowrap><b>12%</b>（残る玉）<br>12/18 に 71%</td></tr>
<tr><td nowrap><b>550P</b> (−15.5%)</td><td nowrap>105,932</td><td nowrap><b>15%</b>（残る玉）<br>12/18 に 66%</td></tr>
<tr><td nowrap><b>540P</b> (−17.0%)</td><td nowrap>86,000</td><td nowrap><b>15%</b>（残る玉）<br>12/18 に 73%</td></tr>
</tbody>
</table>

- 11/30 の満期の後に残る最大の壁: プットの壁 600（今と同じ）・コールの壁 680（今と同じ）。
- 主な満期（11/30 を除いて、ガンマが最大の契約 12/18 680C の満期）: 12/18。図の4段目に、この満期だけのガンマを出しています。

**壁の動き**（建玉の増減と、今日の大口）

<table>
<thead><tr><th nowrap>契約</th><th nowrap>建玉の増減・大口</th><th nowrap>見立て</th></tr></thead>
<tbody>
<tr><td nowrap><b>524.78C</b> (−19.4%)</td><td nowrap>建玉 −251</td><td nowrap>コールの建玉の減少</td></tr>
<tr><td nowrap><b>650C</b> (−0.2%)</td><td nowrap>建玉 —<br>（今 64,282）<br>11/30 買 28,<br>809枚 $17M<br>12/18 向き不明 7,<br>744枚 $16M<br>12/2 買 15,<br>894枚 $15M</td><td nowrap>上げの的（コール買い）</td></tr>
<tr><td nowrap><b>645C</b> (−0.9%)</td><td nowrap>建玉 —<br>（今 15,926）<br>11/30 買 19,<br>382枚 $17M</td><td nowrap>上げの的（コール買い）</td></tr>
<tr><td nowrap><b>660P</b> (+1.4%)</td><td nowrap>建玉 —<br>（今 54,812）<br>12/18 売 6,<br>642枚 $15M</td><td nowrap>下値の防御線（プット売り）</td></tr>
</tbody>
</table>

- 建玉の増減は前回の記録（11/27）から今の板まで（建玉は前の営業日の引けの数）。大口は直近の取引日（11/27）の、代金の多い契約（opt_flow の推定）。その日の取引が建玉に出るのは次の営業日なので、2つを続けて見ます。★は建玉の壁（上位3本）。コール売りなら、ディーラーはそのコールを買い持ちになり、その価格の近くで値動きを抑える向きに売り買いする（壁が厚くなる）とみます。

### 大口の賭け（推定）

**ブル 🐂・強さ 大**（売買代金の 6.7%）

- 大口のデルタ換算（株を何ドル分買った・売ったのと同じ向きか）: 差 **+28.3億ドル**（ブル側 +29.5億ドル・ベア側 −1.2億ドル）。代金はブル側 1.1億ドル・ベア側 13.1百万ドル。1日の売買代金 419.8億ドル（20日の平均）
- 大口が見ている価格: 上げの的（コール買い） **645**（−0.9%）・下げの的（プット買い） **630**（−3.2%）
- 深い ITM の大口（合計に入れない）: 3本・代金 1.4億ドル（12/18 745P売・3/19 875P（向き不明）・12/18 740P売）。株と組み合わせた取引（配当の裁定・乗り換えなど）のことが多い。そのまま賭けとみると +3.3億ドル 分

<table>
<thead><tr><th nowrap>契約</th><th nowrap>推定・意味</th><th nowrap>代金・枚数</th></tr></thead>
<tbody>
<tr><td nowrap>11/30 645C<br>−0.9%<br>建玉 0</td><td nowrap><b>買い</b><br>上げへの賭け</td><td nowrap>$17M<br>19,382枚<br>Δ +$847M<br>IV 24%</td></tr>
<tr><td nowrap>11/30 650C<br>−0.2%<br>建玉 19,969</td><td nowrap><b>買い寄り</b><br>上げへの賭け</td><td nowrap>$17M<br>28,809枚<br>Δ +$500M<br>IV 23%</td></tr>
<tr><td nowrap>12/18 650C<br>−0.2%<br>建玉 28,830</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$16M<br>7,744枚<br>Δ —<br>IV 32%</td></tr>
<tr><td nowrap>12/18 660P<br>+1.4%<br>建玉 39,153</td><td nowrap><b>売り寄り</b><br>下値の防御線<br>（ITM）</td><td nowrap>$15M<br>6,642枚<br>Δ +$122M<br>IV 29%</td></tr>
<tr><td nowrap>12/2 650C<br>−0.2%<br>建玉 4,016</td><td nowrap><b>買い</b><br>上げへの賭け</td><td nowrap>$15M<br>15,894枚<br>Δ +$543M<br>IV 29%</td></tr>
<tr><td nowrap>11/30 647P<br>−0.6%<br>建玉 193</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$15M<br>31,128枚<br>Δ —<br>IV 28%</td></tr>
<tr><td nowrap>11/30 640C<br>−1.7%<br>建玉 0</td><td nowrap><b>買い</b><br>上げへの賭け<br>（ITM）</td><td nowrap>$14M<br>11,219枚<br>Δ +$569M<br>IV 25%</td></tr>
<tr><td nowrap>1/15 680C<br>+4.5%<br>建玉 0</td><td nowrap><b>買い寄り</b><br>上げへの賭け</td><td nowrap>$14M<br>10,090枚<br>Δ +$112M<br>IV 26%</td></tr>
<tr><td nowrap>12/18 630P<br>−3.2%<br>建玉 0</td><td nowrap><b>買い寄り</b><br>下げへの賭け・<br>守り</td><td nowrap>$13M<br>11,190枚<br>Δ −$119M<br>IV 33%</td></tr>
<tr><td nowrap>12/18 660C<br>+1.4%<br>建玉 37,264</td><td nowrap><b>買い</b><br>上げへの賭け</td><td nowrap>$13M<br>8,970枚<br>Δ +$256M<br>IV 30%</td></tr>
<tr><td nowrap>12/18 745P<br>+14.4%<br>建玉 1,342</td><td nowrap><b>売り寄り</b><br><b>（IV −5.7pt）</b><br>深い ITM の売り</td><td nowrap>$52M<br>5,562枚<br>Δ +$180M<br>IV 23%</td></tr>
<tr><td nowrap>3/19 875P<br>+34.4%<br>建玉 0</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$45M<br>2,000枚<br>Δ —<br>IV 21%</td></tr>
<tr><td nowrap>12/18 740P<br>+13.7%<br>建玉 1,237</td><td nowrap><b>売り寄り</b><br><b>（IV −3.7pt）</b><br>深い ITM の売り</td><td nowrap>$43M<br>4,846枚<br>Δ +$155M<br>IV 25%</td></tr>
</tbody>
</table>

推定の向きは最後の約定の位置（売り気配で約定＝買い）と、前回の実行からの IV の上下から。買い・売りの分かる大口は代金の 80%。誰の取引かは分かりません。表の『代金・枚数』は、代金・その日の出来高・Δ（デルタ換算。株を何ドル分買った＋・売った−のと同じ向きか）・IV。

### 詳しく

**まとめ**: 下の支えの候補 **600**（−7.8%）・550（−15.5%）・540（−17.0%）。上の重さの候補 **680**（+4.5%）・715（+9.8%）・725（+11.4%）。次の満期（11/30・3日）の想定の幅 ±1.8%（639.19〜662.79）。ガンマはマイナス側（ゼロガンマ 669.33）→ 値動きが大きくなりやすい。

**下の支えの候補**（プットの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>640</td><td nowrap>−1.7%</td><td nowrap>75,558</td><td nowrap>5%</td></tr>
<tr><td nowrap>610</td><td nowrap>−6.3%</td><td nowrap>66,564</td><td nowrap>4%</td></tr>
<tr><td nowrap>600</td><td nowrap>−7.8%</td><td nowrap>119,439</td><td nowrap>7%</td></tr>
<tr><td nowrap>550</td><td nowrap>−15.5%</td><td nowrap>105,932</td><td nowrap>7%</td></tr>
<tr><td nowrap>540</td><td nowrap>−17.0%</td><td nowrap>86,000</td><td nowrap>5%</td></tr>
</tbody>
</table>

**上の重さの候補**（コールの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>660</td><td nowrap>+1.4%</td><td nowrap>57,427</td><td nowrap>4%</td></tr>
<tr><td nowrap>680</td><td nowrap>+4.5%</td><td nowrap>143,423</td><td nowrap>10%</td></tr>
<tr><td nowrap>715</td><td nowrap>+9.8%</td><td nowrap>98,902</td><td nowrap>7%</td></tr>
<tr><td nowrap>725</td><td nowrap>+11.4%</td><td nowrap>79,077</td><td nowrap>5%</td></tr>
<tr><td nowrap>740</td><td nowrap>+13.7%</td><td nowrap>52,324</td><td nowrap>3%</td></tr>
</tbody>
</table>

**次の満期 11/30（3日）**: プットの壁 630（−3.2%）・コールの壁 680（+4.5%）・最大の痛み 660（+1.4%）・想定の幅 ±1.8%

アウト・オブ・ザ・マネーに払われた代金: プット 168.6百万ドル・コール 115.8百万ドル（プットの割合 59%）

**建玉の増減**（①の日次の記録の 11/27 → 今の板。45日以内の満期）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>距離</th><th nowrap>増減</th><th nowrap>想定元本</th></tr></thead>
<tbody>
<tr><td nowrap>524.78C</td><td nowrap>−19.4%</td><td nowrap>−251</td><td nowrap>−13.2百万ドル</td></tr>
</tbody>
</table>

合計: プット 0・コール −13.2百万ドル（想定元本の増減）

**全体**: IV30 29%・7日 33%・期間構造 1.12（目先の不安が強い）・プットの割高さ +8.5pt・建玉のプット/コール 1.12

**過去の検証**: 未検証（第190回で、2008〜2025年の QQQ・SPY・NVDA・AVGO・AMD・QCOM・TXN の板で確かめ中）。それまでは、下の目安は過去の効きが確かめられていない参考の値です。

## TQQQ　48.85

米国 11/27 21:23（取引時間外）・直近の取引日 11/27・板 Yahoo

### 結論

<table>
<thead><tr><th nowrap>問い</th><th nowrap>答え</th></tr></thead>
<tbody>
<tr><td nowrap>建玉の偏り</td><td nowrap><b>コール（買う権利）</b><br><b>のほうが多い</b><br><b>（いつもとの比較はまだできない）</b><br>（プット 35%・コール 65%）</td></tr>
<tr><td nowrap>σ（側）</td><td nowrap><b>—</b></td></tr>
<tr><td nowrap>前日から</td><td nowrap><b>—</b><br>（前日の記録と比べられません<br>（σ を出せない日））</td></tr>
<tr><td nowrap>大きなプット</td><td nowrap>40 (−18.1%)<br>50 (+2.4%)<br>45 (−7.9%)</td></tr>
<tr><td nowrap>大きなコール☆</td><td nowrap>60 (+22.8%)<br>51 (+4.4%)<br>50 (+2.4%)</td></tr>
</tbody>
</table>

- σ: ①の毎日の記録が 1日分しかなく、σ を出せません（10日たまると出ます）。
- 大きなプット・コールの印: ★ 偏っている側、☆ 偏りは小さいが数の多い側。『○/○』は、枚数/金額（建玉 × 値段 × 100）が過去30日の平常の何倍か。
- 偏りの物差し: 満期まで 3〜75日の全ての建玉（①の毎日の記録と同じ）。建玉には買い手と売り手が同じ数だけいるので、偏りはコールとプットの数で見ています。

**プットの大きな建玉の枚数とお金**（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> OTM</td><td nowrap>30,892 (<b>—</b>)</td><td nowrap>3.12M (<b>—</b>)</td></tr>
<tr><td nowrap><b>50</b> ITM</td><td nowrap>16,602 (<b>—</b>)</td><td nowrap>7.26M (<b>—</b>)</td></tr>
<tr><td nowrap><b>45</b> OTM</td><td nowrap>15,860 (<b>—</b>)</td><td nowrap>3.80M (<b>—</b>)</td></tr>
<tr><td nowrap><b>60</b> 超ITM</td><td nowrap>11,911 (<b>—</b>)</td><td nowrap>14.6M (<b>—</b>)</td></tr>
<tr><td nowrap><b>35</b> OTM</td><td nowrap>8,141 (<b>—</b>)</td><td nowrap>0.73M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

**コールの大きな建玉の枚数とお金**（数の多い側）（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>60</b> OTM</td><td nowrap>21,389 (<b>—</b>)</td><td nowrap>0.26M (<b>—</b>)</td></tr>
<tr><td nowrap><b>51</b> OTM</td><td nowrap>17,010 (<b>—</b>)</td><td nowrap>5.35M (<b>—</b>)</td></tr>
<tr><td nowrap><b>50</b> OTM</td><td nowrap>16,841 (<b>—</b>)</td><td nowrap>4.84M (<b>—</b>)</td></tr>
<tr><td nowrap><b>61</b> OTM</td><td nowrap>11,672 (<b>—</b>)</td><td nowrap>0.50M (<b>—</b>)</td></tr>
<tr><td nowrap><b>63</b> OTM</td><td nowrap>11,283 (<b>—</b>)</td><td nowrap>0.34M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

- 枚数の平常比は同じ側・同じ順位（過去の各日の、枚数が同じ順位の建玉）、金額の平常比は同じ側の過去の大きな建玉（各日の上位5本）と比べた倍率。▲▲ 30日で最多・▲ 多い（上位25%）・▼ 少ない（下位25%）・▼▼ 30日で最少。印が無ければ平常並み。建玉の合計も▲なら、満期（特に3・6・9・12月の第3金曜）に向けて全体が増えている分を差し引いて見てください。金額は建玉 × 値段 × 100（ITM は本質的な価値を含む。今の板）。

**プットの大きな建玉**（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> (−18.1%)</td><td nowrap>30,892 (21%)</td><td nowrap>12/18 $1.50</td></tr>
<tr><td nowrap><b>50</b> (+2.4%)</td><td nowrap>16,602 (11%)</td><td nowrap>12/18 $4.80</td></tr>
<tr><td nowrap><b>45</b> (−7.9%)</td><td nowrap>15,860 (11%)</td><td nowrap>12/18 $2.81</td></tr>
<tr><td nowrap><b>60</b> (+22.8%)</td><td nowrap>11,911 (8%)</td><td nowrap>12/18 $12.22</td></tr>
<tr><td nowrap><b>35</b> (−28.4%)</td><td nowrap>8,141 (5%)</td><td nowrap>12/31 $1.23</td></tr>
</tbody>
</table>

**コールの大きな建玉**（数の多い側）（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>60</b> (+22.8%)</td><td nowrap>21,389 (14%)</td><td nowrap>12/4 $0.04</td></tr>
<tr><td nowrap><b>51</b> (+4.4%)</td><td nowrap>17,010 (11%)</td><td nowrap>12/18 $3.17</td></tr>
<tr><td nowrap><b>50</b> (+2.4%)</td><td nowrap>16,841 (11%)</td><td nowrap>12/11 $2.98</td></tr>
<tr><td nowrap><b>61</b> (+24.9%)</td><td nowrap>11,672 (8%)</td><td nowrap>12/18 $0.47</td></tr>
<tr><td nowrap><b>63</b> (+29.0%)</td><td nowrap>11,283 (7%)</td><td nowrap>12/18 $0.31</td></tr>
</tbody>
</table>

### オプションの配置（図）

![TQQQ のオプションの配置](TQQQ_options_chart.svg)

- 今の株価でのガンマの合計は**プラス**（+7百万ドル／1%）、ゼロガンマは **43.58**（−10.8%）。推定の幅 42.14〜44.66。
- 上の段: 株価がその値になったときの、ディーラーのガンマの合計（赤い点線がゼロガンマ）。赤い背景（マイナス）の価格帯では、ディーラーが下げで売り・上げで買うので値動きが大きくなりやすく、緑の背景（プラス）では小さくなりやすい。
- 中の段: 行使価格ごとのガンマ（コールは上、プットは下）。下の段: 行使価格ごとの建玉（45日以内の満期）と、プットの壁・コールの壁（灰色の点線）。黒い線が今の株価。
- 薄い色は 11/30 の満期で消える分（濃い色が残る分）。点線は 11/30 の満期の後のガンマの合計（IV・株価は今のまま）。4段目は、主な満期 12/18 だけのガンマ。

### 道筋（上と下の関門）

- 今の株価 48.85 は、ゼロガンマ 43.6（推定の幅 42.1〜44.7）の**上（プラス）**。値動きが小さくなりやすい。11/30 の満期の後のゼロガンマは 43.6（−10.8%）。

<table>
<thead><tr><th nowrap>関門</th><th nowrap>価格（距離）</th><th nowrap>中身</th></tr></thead>
<tbody>
<tr><td nowrap>ガンマの山・次の壁</td><td nowrap><b>70.0</b> (+43.3%)</td><td nowrap>ここまでは上げるほどディーラーのガンマ<br>（買い持ち）<br>が増え、<br>値動きが小さくなりやすい。<br>建玉 27,188・<br>11/30 の満期には無い・<br>12/18 に 79%</td></tr>
<tr><td nowrap>平らになる</td><td nowrap><b>64.2</b> (+31.5%)</td><td nowrap>ここより上は、<br>上げてもディーラーのガンマがほとんど増えない。<br>壁の力が弱まり、<br>ニュートラルに近い</td></tr>
<tr><td nowrap>コールの壁（最大）</td><td nowrap><b>60</b> (+22.8%)</td><td nowrap>建玉 21,389・<br>11/30 で 7% 消える・<br>12/4 に 64%</td></tr>
<tr><td nowrap>コールの壁</td><td nowrap><b>51</b> (+4.4%)</td><td nowrap>建玉 17,010・<br>11/30 の満期には無い・<br>12/18 に 95%</td></tr>
<tr><td nowrap>コールの壁・ガンマ最大（コール）</td><td nowrap><b>50</b> (+2.4%)</td><td nowrap>建玉 16,841・<br>11/30 の満期には無い・<br>12/11 に 47%</td></tr>
<tr><td nowrap><b>今</b></td><td nowrap><b>48.85</b></td><td nowrap>ガンマ プラス</td></tr>
<tr><td nowrap>プットの壁</td><td nowrap><b>45</b> (−7.9%)</td><td nowrap>建玉 15,860・<br>11/30 の満期には無い・<br>12/18 に 59%</td></tr>
<tr><td nowrap>ゼロガンマ</td><td nowrap><b>43.58</b> (−10.8%)</td><td nowrap>割るとガンマはマイナス<br>（値動きが大きくなりやすい）。<br>推定の幅 42.1〜44.7</td></tr>
<tr><td nowrap>プットの壁（最大）・ガンマ最大（プット）</td><td nowrap><b>40</b> (−18.1%)</td><td nowrap>建玉 30,892・<br>11/30 で 2% 消える・<br>12/18 に 43%</td></tr>
<tr><td nowrap>ガンマの谷</td><td nowrap><b>36.9</b> (−24.5%)</td><td nowrap>マイナスが最も深い。<br>下げが加速しやすい中心</td></tr>
<tr><td nowrap>プットの壁</td><td nowrap><b>35</b> (−28.4%)</td><td nowrap>建玉 8,141・<br>11/30 で 7% 消える・<br>12/31 に 48%</td></tr>
</tbody>
</table>

**2つの筋書き**（壁の配置からの読み。確率ではありません）

- 上に抜けた場合: 今はプラスのガンマの中で、上の壁までは値動きが小さくなりやすい。最大のコールの壁 **60**（+22.8%。11/30 で 7% 消える・12/4 に 64%）で止まりやすい。超えれば次の壁 **70**（+43.3%）。64.2（+31.5%）より上はガンマがほぼ平らで、壁の力が弱まる（ニュートラルに近い）。
- はね返された場合: 上の壁 50 の手前で止まり、ゼロガンマ 43.6（−10.8%）を割ると、ガンマはマイナスになり、値動きが大きくなりやすい（ガンマの谷は 36.9）。下の支えは **45**→**40**→**35**。
- 次の満期（11/30）までの想定の幅は ±6.8%（45.5〜52.2）。最大のコールの壁 60 は幅の外・最大のプットの壁 40 は幅の外。
- ガンマは値動きの大きさの目安で、上げ・下げの向きは分かりません（第105回）。

**満期の内訳**（壁の建玉のうち、次の満期 11/30 で消える分。45日以内の満期）

<table>
<thead><tr><th nowrap>壁</th><th nowrap>建玉</th><th nowrap>消える分・<br>残る主な満期</th></tr></thead>
<tbody>
<tr><td nowrap><b>70C</b> (+43.3%)</td><td nowrap>27,188</td><td nowrap><b>0%</b>（残る玉）<br>12/18 に 79%</td></tr>
<tr><td nowrap><b>60C</b> (+22.8%)</td><td nowrap>21,389</td><td nowrap><b>7%</b>（残る玉）<br>12/4 に 64%</td></tr>
<tr><td nowrap><b>51C</b> (+4.4%)</td><td nowrap>17,010</td><td nowrap><b>0%</b>（残る玉）<br>12/18 に 95%</td></tr>
<tr><td nowrap><b>50C</b> (+2.4%)</td><td nowrap>16,841</td><td nowrap><b>0%</b>（残る玉）<br>12/11 に 47%</td></tr>
<tr><td nowrap><b>45P</b> (−7.9%)</td><td nowrap>15,860</td><td nowrap><b>0%</b>（残る玉）<br>12/18 に 59%</td></tr>
<tr><td nowrap><b>40P</b> (−18.1%)</td><td nowrap>30,892</td><td nowrap><b>2%</b>（残る玉）<br>12/18 に 43%</td></tr>
<tr><td nowrap><b>35P</b> (−28.4%)</td><td nowrap>8,141</td><td nowrap><b>7%</b>（残る玉）<br>12/31 に 48%</td></tr>
<tr><td nowrap><b>30P</b> (−38.6%)</td><td nowrap>14,978</td><td nowrap><b>0%</b>（残る玉）<br>12/18 に 87%</td></tr>
</tbody>
</table>

- 11/30 の満期の後に残る最大の壁: プットの壁 40（今と同じ）・コールの壁 60（今と同じ）。
- 主な満期（11/30 を除いて、ガンマが最大の契約 12/18 51C の満期）: 12/18。図の4段目に、この満期だけのガンマを出しています。

**壁の動き**（建玉の増減と、今日の大口）

<table>
<thead><tr><th nowrap>契約</th><th nowrap>建玉の増減・大口</th><th nowrap>見立て</th></tr></thead>
<tbody>
<tr><td nowrap><b>50C</b>★ (+2.4%)</td><td nowrap>建玉 −1,572（今 16,841）<br>1/15 買 1,610枚 $0.8M<br>12/4 買 3,095枚 $0.6M</td><td nowrap>上げの的<br>（コール買い）</td></tr>
<tr><td nowrap><b>48C</b> (−1.7%)</td><td nowrap>建玉 +1,354（今 4,833）<br>12/4 売 2,783枚 $0.8M</td><td nowrap>上の壁の建設・<br>増強<br>（コール売り）</td></tr>
<tr><td nowrap><b>46C</b> (−5.8%)</td><td nowrap>建玉 −1,272（今 1,152）<br>12/4 買 1,481枚 $0.6M</td><td nowrap>上げの的<br>（コール買い）</td></tr>
<tr><td nowrap><b>47C</b> (−3.8%)</td><td nowrap>建玉 −577（今 4,264）<br>12/4 買 1,609枚 $0.6M</td><td nowrap>上げの的<br>（コール買い）</td></tr>
<tr><td nowrap><b>60C</b>★ (+22.8%)</td><td nowrap>建玉 −39,404（今 21,389）</td><td nowrap>コールの壁の取り崩し</td></tr>
<tr><td nowrap><b>55P</b> (+12.6%)</td><td nowrap>建玉 −14,110（今 2,010）</td><td nowrap>プットの建玉の減少</td></tr>
</tbody>
</table>

- 建玉の増減は前回の記録（11/25）から今の板まで（建玉は前の営業日の引けの数）。大口は直近の取引日（11/27）の、代金の多い契約（opt_flow の推定）。その日の取引が建玉に出るのは次の営業日なので、2つを続けて見ます。★は建玉の壁（上位3本）。コール売りなら、ディーラーはそのコールを買い持ちになり、その価格の近くで値動きを抑える向きに売り買いする（壁が厚くなる）とみます。

### 大口の賭け（推定）

**ベア 🐻・強さ 小**（売買代金の 0.1%） — TQQQ はレバ3倍。ナスダック100に直すと **ベア 🐻**

- 大口のデルタ換算（株を何ドル分買った・売ったのと同じ向きか）: 差 **−7.8百万ドル**（ブル側 +11.5百万ドル・ベア側 −19.4百万ドル）。代金はブル側 3.2百万ドル・ベア側 3.0百万ドル。1日の売買代金 62.5億ドル（20日の平均）
- 大口が見ている価格: 上げの的（コール買い） **50**（+2.4%）・下げの的（プット買い） **45**（−7.9%）
- 深い ITM の大口（合計に入れない）: 3本・代金 3.2百万ドル（3/19 75P（向き不明）・12/18 65P買・1/15 18.5C（向き不明））。株と組み合わせた取引（配当の裁定・乗り換えなど）のことが多い。そのまま賭けとみると −1.2百万ドル 分

<table>
<thead><tr><th nowrap>契約</th><th nowrap>推定・意味</th><th nowrap>代金・枚数</th></tr></thead>
<tbody>
<tr><td nowrap>12/4 48C<br>−1.7%<br>建玉 614</td><td nowrap><b>売り寄り</b><br><b>（IV −8.0pt）</b><br>上値の重し<br>組の片側かも</td><td nowrap>$0.8M<br>2,783枚<br>Δ −$3.9M<br>IV 96%</td></tr>
<tr><td nowrap>1/15 50C<br>+2.4%<br>建玉 17,716</td><td nowrap><b>買い寄り</b><br>上げへの賭け</td><td nowrap>$0.8M<br>1,610枚<br>Δ +$2.1M<br>IV 80%</td></tr>
<tr><td nowrap>12/4 50C<br>+2.4%<br>建玉 3,431</td><td nowrap><b>買い寄り</b><br>上げへの賭け<br>組の片側かも</td><td nowrap>$0.6M<br>3,095枚<br>Δ +$3.4M<br>IV 93%</td></tr>
<tr><td nowrap>12/4 46C<br>−5.8%<br>建玉 983</td><td nowrap><b>買い寄り</b><br>上げへの賭け<br>（ITM）</td><td nowrap>$0.6M<br>1,481枚<br>Δ +$2.6M<br>IV 86%</td></tr>
<tr><td nowrap>12/4 47C<br>−3.8%<br>建玉 0</td><td nowrap><b>買い寄り</b><br>上げへの賭け<br>（ITM）</td><td nowrap>$0.6M<br>1,609枚<br>Δ +$2.5M<br>IV 98%</td></tr>
<tr><td nowrap>12/18 45P<br>−7.9%<br>建玉 9,321</td><td nowrap><b>買い寄り</b><br>下げへの賭け・<br>守り</td><td nowrap>$0.6M<br>1,993枚<br>Δ −$1.6M<br>IV 100%</td></tr>
<tr><td nowrap>11/30 48C<br>−1.7%<br>建玉 800</td><td nowrap><b>売り</b><br>上値の重し<br>（ITM）</td><td nowrap>$0.6M<br>2,981枚<br>Δ −$8.9M<br>IV 80%</td></tr>
<tr><td nowrap>12/18 47C<br>−3.8%<br>建玉 1,043</td><td nowrap><b>売り寄り</b><br>上値の重し<br>（ITM）</td><td nowrap>$0.5M<br>1,039枚<br>Δ −$1.6M<br>IV 94%</td></tr>
<tr><td nowrap>3/19 50C<br>+2.4%<br>建玉 7,268</td><td nowrap><b>買い寄り</b><br><b>（IV +6.0pt）</b><br>上げへの賭け</td><td nowrap>$0.5M<br>690枚<br>Δ +$0.9M<br>IV 76%</td></tr>
<tr><td nowrap>12/4 45C<br>−7.9%<br>建玉 1,452</td><td nowrap><b>売り</b><br>上値の重し<br>（ITM）</td><td nowrap>$0.5M<br>962枚<br>Δ −$3.5M<br>IV 107%</td></tr>
<tr><td nowrap>3/19 75P<br>+53.5%<br>建玉 2,559</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$1.3M<br>457枚<br>Δ —<br>IV 71%</td></tr>
<tr><td nowrap>12/18 65P<br>+33.1%<br>建玉 0</td><td nowrap><b>買い寄り</b><br>深い ITM の買い</td><td nowrap>$1.0M<br>601枚<br>Δ −$1.2M<br>IV 106%</td></tr>
<tr><td nowrap>1/15 18.5C<br>−62.1%<br>建玉 0</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$0.9M<br>180枚<br>Δ —<br>IV —</td></tr>
</tbody>
</table>

推定の向きは最後の約定の位置（売り気配で約定＝買い）と、前回の実行からの IV の上下から。買い・売りの分かる大口は代金の 100%。誰の取引かは分かりません。表の『代金・枚数』は、代金・その日の出来高・Δ（デルタ換算。株を何ドル分買った＋・売った−のと同じ向きか）・IV。

### 詳しく

**まとめ**: 下の支えの候補 **45**（−7.9%）・40（−18.1%）・35（−28.4%）。上の重さの候補 **50**（+2.4%）・51（+4.4%）・60（+22.8%）。既に割れたプットの壁 50（+2.4%）。次の満期（11/30・3日）の想定の幅 ±6.8%（45.53〜52.16）。ガンマはプラス側（ゼロガンマ 43.41）→ 値動きが小さくなりやすい。

**下の支えの候補**（プットの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>48</td><td nowrap>−1.7%</td><td nowrap>6,441</td><td nowrap>4%</td></tr>
<tr><td nowrap>45</td><td nowrap>−7.9%</td><td nowrap>15,860</td><td nowrap>11%</td></tr>
<tr><td nowrap>42</td><td nowrap>−14.0%</td><td nowrap>4,931</td><td nowrap>3%</td></tr>
<tr><td nowrap>40</td><td nowrap>−18.1%</td><td nowrap>30,892</td><td nowrap>21%</td></tr>
<tr><td nowrap>35</td><td nowrap>−28.4%</td><td nowrap>8,141</td><td nowrap>5%</td></tr>
</tbody>
</table>

**上の重さの候補**（コールの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>50</td><td nowrap>+2.4%</td><td nowrap>16,841</td><td nowrap>11%</td></tr>
<tr><td nowrap>51</td><td nowrap>+4.4%</td><td nowrap>17,010</td><td nowrap>11%</td></tr>
<tr><td nowrap>60</td><td nowrap>+22.8%</td><td nowrap>21,389</td><td nowrap>14%</td></tr>
<tr><td nowrap>61</td><td nowrap>+24.9%</td><td nowrap>11,672</td><td nowrap>8%</td></tr>
<tr><td nowrap>63</td><td nowrap>+29.0%</td><td nowrap>11,283</td><td nowrap>7%</td></tr>
</tbody>
</table>

**次の満期 11/30（3日）**: プットの壁 38.5（−21.2%）・コールの壁 60（+22.8%）・最大の痛み 45（−7.9%）・想定の幅 ±6.8%

アウト・オブ・ザ・マネーに払われた代金: プット 7.4百万ドル・コール 7.2百万ドル（プットの割合 51%）

**建玉の増減**（前回のオプション分析の 11/25 → 今の板。45日以内の満期）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>距離</th><th nowrap>増減</th><th nowrap>想定元本</th></tr></thead>
<tbody>
<tr><td nowrap>51C</td><td nowrap>+4.4%</td><td nowrap>+13,957</td><td nowrap>71.2百万ドル</td></tr>
<tr><td nowrap>46.5C</td><td nowrap>−4.8%</td><td nowrap>+2,456</td><td nowrap>11.4百万ドル</td></tr>
<tr><td nowrap>48C</td><td nowrap>−1.7%</td><td nowrap>+1,354</td><td nowrap>6.5百万ドル</td></tr>
<tr><td nowrap>60C</td><td nowrap>+22.8%</td><td nowrap>−39,404</td><td nowrap>−236.4百万ドル</td></tr>
<tr><td nowrap>55P</td><td nowrap>+12.6%</td><td nowrap>−14,110</td><td nowrap>−77.6百万ドル</td></tr>
</tbody>
</table>

合計: プット −351.0百万ドル・コール −356.6百万ドル（想定元本の増減）

**全体**: IV30 89%・7日 98%・期間構造 1.11（目先の不安が強い）・プットの割高さ +7.0pt・建玉のプット/コール 0.53

**過去の検証**: 未検証（第190回で、2008〜2025年の QQQ・SPY・NVDA・AVGO・AMD・QCOM・TXN の板で確かめ中）。それまでは、下の目安は過去の効きが確かめられていない参考の値です。

## SQQQ　45.76

米国 11/27 21:23（取引時間外）・直近の取引日 11/27・板 Yahoo

### 結論

<table>
<thead><tr><th nowrap>問い</th><th nowrap>答え</th></tr></thead>
<tbody>
<tr><td nowrap>建玉の偏り</td><td nowrap><b>コール（買う権利）</b><br><b>のほうが多い</b><br><b>（いつもとの比較はまだできない）</b><br>（プット 39%・コール 61%）</td></tr>
<tr><td nowrap>σ（側）</td><td nowrap><b>—</b></td></tr>
<tr><td nowrap>前日から</td><td nowrap><b>—</b><br>（前日の記録と比べられません<br>（σ を出せない日））</td></tr>
<tr><td nowrap>大きなプット</td><td nowrap>40 (−12.6%)<br>42 (−8.2%)<br>36 (−21.3%)</td></tr>
<tr><td nowrap>大きなコール☆</td><td nowrap>35 (−23.5%)<br>55 (+20.2%)<br>50 (+9.3%)</td></tr>
</tbody>
</table>

- σ: ①の毎日の記録が 1日分しかなく、σ を出せません（10日たまると出ます）。
- 大きなプット・コールの印: ★ 偏っている側、☆ 偏りは小さいが数の多い側。『○/○』は、枚数/金額（建玉 × 値段 × 100）が過去30日の平常の何倍か。
- 偏りの物差し: 満期まで 3〜75日の全ての建玉（①の毎日の記録と同じ）。建玉には買い手と売り手が同じ数だけいるので、偏りはコールとプットの数で見ています。

**プットの大きな建玉の枚数とお金**（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> OTM</td><td nowrap>3,018 (<b>—</b>)</td><td nowrap>0.29M (<b>—</b>)</td></tr>
<tr><td nowrap><b>42</b> OTM</td><td nowrap>2,152 (<b>—</b>)</td><td nowrap>0.35M (<b>—</b>)</td></tr>
<tr><td nowrap><b>36</b> OTM</td><td nowrap>1,995 (<b>—</b>)</td><td nowrap>0.01M (<b>—</b>)</td></tr>
<tr><td nowrap><b>33</b> OTM</td><td nowrap>1,990 (<b>—</b>)</td><td nowrap>0.03M (<b>—</b>)</td></tr>
<tr><td nowrap><b>37</b> OTM</td><td nowrap>1,957 (<b>—</b>)</td><td nowrap>0.09M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

**コールの大きな建玉の枚数とお金**（数の多い側）（建玉の多い順。( ) は過去30日の平常の何倍か）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>枚数 (倍)</th><th nowrap>金額 (倍)</th></tr></thead>
<tbody>
<tr><td nowrap><b>35</b> 超ITM</td><td nowrap>11,182 (<b>—</b>)</td><td nowrap>12.5M (<b>—</b>)</td></tr>
<tr><td nowrap><b>55</b> OTM</td><td nowrap>7,790 (<b>—</b>)</td><td nowrap>1.45M (<b>—</b>)</td></tr>
<tr><td nowrap><b>50</b> OTM</td><td nowrap>7,746 (<b>—</b>)</td><td nowrap>1.89M (<b>—</b>)</td></tr>
<tr><td nowrap><b>48</b> OTM</td><td nowrap>6,846 (<b>—</b>)</td><td nowrap>2.05M (<b>—</b>)</td></tr>
<tr><td nowrap><b>45</b> ITM</td><td nowrap>5,341 (<b>—</b>)</td><td nowrap>2.28M (<b>—</b>)</td></tr>
</tbody>
</table>

- 平常を決める記録がまだありません（①の毎日の記録がたまると、平常比が出ます）。

- 枚数の平常比は同じ側・同じ順位（過去の各日の、枚数が同じ順位の建玉）、金額の平常比は同じ側の過去の大きな建玉（各日の上位5本）と比べた倍率。▲▲ 30日で最多・▲ 多い（上位25%）・▼ 少ない（下位25%）・▼▼ 30日で最少。印が無ければ平常並み。建玉の合計も▲なら、満期（特に3・6・9・12月の第3金曜）に向けて全体が増えている分を差し引いて見てください。金額は建玉 × 値段 × 100（ITM は本質的な価値を含む。今の板）。

**プットの大きな建玉**（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>40</b> (−12.6%)</td><td nowrap>3,018 (12%)</td><td nowrap>12/18 $1.22</td></tr>
<tr><td nowrap><b>42</b> (−8.2%)</td><td nowrap>2,152 (9%)</td><td nowrap>12/11 $1.42</td></tr>
<tr><td nowrap><b>36</b> (−21.3%)</td><td nowrap>1,995 (8%)</td><td nowrap>12/4 $0.05</td></tr>
<tr><td nowrap><b>33</b> (−27.9%)</td><td nowrap>1,990 (8%)</td><td nowrap>12/18 $0.17</td></tr>
<tr><td nowrap><b>37</b> (−19.1%)</td><td nowrap>1,957 (8%)</td><td nowrap>12/18 $0.52</td></tr>
</tbody>
</table>

**コールの大きな建玉**（数の多い側）（45日以内の満期・株価の ±30% の行使価格。建玉の多い順。値段は1株あたり）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>建玉（割合）</th><th nowrap>満期・値段</th></tr></thead>
<tbody>
<tr><td nowrap><b>35</b> (−23.5%)</td><td nowrap>11,182 (19%)</td><td nowrap>12/18 $11.20</td></tr>
<tr><td nowrap><b>55</b> (+20.2%)</td><td nowrap>7,790 (13%)</td><td nowrap>12/18 $2.08</td></tr>
<tr><td nowrap><b>50</b> (+9.3%)</td><td nowrap>7,746 (13%)</td><td nowrap>12/18 $2.79</td></tr>
<tr><td nowrap><b>48</b> (+4.9%)</td><td nowrap>6,846 (11%)</td><td nowrap>12/18 $3.21</td></tr>
<tr><td nowrap><b>45</b> (−1.7%)</td><td nowrap>5,341 (9%)</td><td nowrap>12/18 $4.78</td></tr>
</tbody>
</table>

### オプションの配置（図）

![SQQQ のオプションの配置](SQQQ_options_chart.svg)

- 今の株価でのガンマの合計は**プラス**（+4百万ドル／1%）。
- 上の段: 株価がその値になったときの、ディーラーのガンマの合計（赤い点線がゼロガンマ）。赤い背景（マイナス）の価格帯では、ディーラーが下げで売り・上げで買うので値動きが大きくなりやすく、緑の背景（プラス）では小さくなりやすい。
- 中の段: 行使価格ごとのガンマ（コールは上、プットは下）。下の段: 行使価格ごとの建玉（45日以内の満期）と、プットの壁・コールの壁（灰色の点線）。黒い線が今の株価。
- 薄い色は 12/4 の満期で消える分（濃い色が残る分）。点線は 12/4 の満期の後のガンマの合計（IV・株価は今のまま）。4段目は、主な満期 1/15 だけのガンマ。

### 道筋（上と下の関門）


<table>
<thead><tr><th nowrap>関門</th><th nowrap>価格（距離）</th><th nowrap>中身</th></tr></thead>
<tbody>
<tr><td nowrap>次の壁</td><td nowrap><b>65</b> (+42.0%)</td><td nowrap>建玉 6,339・<br>12/4 で 58% 消える・<br>12/11 に 40%</td></tr>
<tr><td nowrap>ガンマの山</td><td nowrap><b>56.7</b> (+24.0%)</td><td nowrap>ここまでは上げるほどディーラーのガンマ<br>（買い持ち）<br>が増え、<br>値動きが小さくなりやすい</td></tr>
<tr><td nowrap>コールの壁（最大）</td><td nowrap><b>55</b> (+20.2%)</td><td nowrap>建玉 7,790・<br>12/4 で 11% 消える・<br>12/18 に 79%</td></tr>
<tr><td nowrap>平らになる</td><td nowrap><b>53.3</b> (+16.5%)</td><td nowrap>ここより上は、<br>上げてもディーラーのガンマがほとんど増えない。<br>壁の力が弱まり、<br>ニュートラルに近い</td></tr>
<tr><td nowrap>コールの壁・ガンマ最大（コール）</td><td nowrap><b>50</b> (+9.3%)</td><td nowrap>建玉 7,746・<br>12/4 で 23% 消える・<br>12/18 に 65%</td></tr>
<tr><td nowrap>コールの壁</td><td nowrap><b>48</b> (+4.9%)</td><td nowrap>建玉 6,846・<br>12/4 で 15% 消える・<br>12/18 に 85%</td></tr>
<tr><td nowrap><b>今</b></td><td nowrap><b>45.76</b></td><td nowrap>ガンマ プラス</td></tr>
<tr><td nowrap>プットの壁</td><td nowrap><b>42</b> (−8.2%)</td><td nowrap>建玉 2,152・<br>12/4 で 13% 消える・<br>12/11 に 41%</td></tr>
<tr><td nowrap>プットの壁（最大）・ガンマ最大（プット）</td><td nowrap><b>40</b> (−12.6%)</td><td nowrap>建玉 3,018・<br>12/4 で 35% 消える・<br>12/18 に 55%</td></tr>
<tr><td nowrap>プットの壁・次の支え</td><td nowrap><b>36</b> (−21.3%)</td><td nowrap>建玉 1,995・<br>12/4 で 97% 消える</td></tr>
<tr><td nowrap>ガンマの谷</td><td nowrap><b>24.7</b> (−46.0%)</td><td nowrap>マイナスが最も深い。<br>下げが加速しやすい中心</td></tr>
</tbody>
</table>

**2つの筋書き**（壁の配置からの読み。確率ではありません）

- 上に抜けた場合: ゼロガンマは見つからず、ガンマはプラスのまま。最大のコールの壁 **55**（+20.2%。12/4 で 11% 消える・12/18 に 79%）で止まりやすい。超えれば次の壁 **65**（+42.0%）。53.3（+16.5%）より上はガンマがほぼ平らで、壁の力が弱まる（ニュートラルに近い）。
- はね返された場合: 上の壁 48 の手前で止まり、下げると、下の支えは **42**→**40**（12/4 で 35% 消える）→**36**（12/4 で 97% 消える）。
- 次の満期（12/4）までの想定の幅は ±11.2%（40.6〜50.9）。最大のコールの壁 55 は幅の外・最大のプットの壁 40 は幅の外。
- ガンマは値動きの大きさの目安で、上げ・下げの向きは分かりません（第105回）。

**満期の内訳**（壁の建玉のうち、次の満期 12/4 で消える分。45日以内の満期）

<table>
<thead><tr><th nowrap>壁</th><th nowrap>建玉</th><th nowrap>消える分・<br>残る主な満期</th></tr></thead>
<tbody>
<tr><td nowrap><b>65C</b> (+42.0%)</td><td nowrap>6,339</td><td nowrap><b>58%</b><br>（半分ほど消える）<br>12/11 に 40%</td></tr>
<tr><td nowrap><b>55C</b> (+20.2%)</td><td nowrap>7,790</td><td nowrap><b>11%</b>（残る玉）<br>12/18 に 79%</td></tr>
<tr><td nowrap><b>50C</b> (+9.3%)</td><td nowrap>7,746</td><td nowrap><b>23%</b>（残る玉）<br>12/18 に 65%</td></tr>
<tr><td nowrap><b>48C</b> (+4.9%)</td><td nowrap>6,846</td><td nowrap><b>15%</b>（残る玉）<br>12/18 に 85%</td></tr>
<tr><td nowrap><b>42P</b> (−8.2%)</td><td nowrap>2,152</td><td nowrap><b>13%</b>（残る玉）<br>12/11 に 41%</td></tr>
<tr><td nowrap><b>40P</b> (−12.6%)</td><td nowrap>3,018</td><td nowrap><b>35%</b><br>（半分ほど消える）<br>12/18 に 55%</td></tr>
<tr><td nowrap><b>36P</b> (−21.3%)</td><td nowrap>1,995</td><td nowrap><b>97%</b>（消える玉）<br>12/31 に 3%</td></tr>
</tbody>
</table>

- 12/4 の満期の後に残る最大の壁: プットの壁 33（今は 40）・コールの壁 55（今と同じ）。
- 主な満期（12/4 を除いて、ガンマが最大の契約 1/15 55C の満期）: 1/15。図の4段目に、この満期だけのガンマを出しています。

**壁の動き**（建玉の増減と、今日の大口）

<table>
<thead><tr><th nowrap>契約</th><th nowrap>建玉の増減・大口</th><th nowrap>見立て</th></tr></thead>
<tbody>
<tr><td nowrap><b>42C</b> (−8.2%)</td><td nowrap>建玉 −410（今 883）<br>12/31 買 1,511枚 $1.1M</td><td nowrap>上げの的<br>（コール買い）</td></tr>
<tr><td nowrap><b>50C</b>★ (+9.3%)</td><td nowrap>建玉 −229（今 7,746）<br>12/4 買 1,310枚 $0.2M</td><td nowrap>上げの的<br>（コール買い）</td></tr>
<tr><td nowrap><b>46P</b> (+0.5%)</td><td nowrap>建玉 −216（今 150）<br>1/15 買 535枚 $0.3M</td><td nowrap>下げの的・守り<br>（プット買い）</td></tr>
<tr><td nowrap><b>47P</b> (+2.7%)</td><td nowrap>建玉 −118（今 261）<br>1/15 買 545枚 $0.4M</td><td nowrap>下げの的・守り<br>（プット買い）</td></tr>
<tr><td nowrap><b>40C</b> (−12.6%)</td><td nowrap>建玉 −5,511（今 935）</td><td nowrap>コールの建玉の減少</td></tr>
<tr><td nowrap><b>38P</b> (−17.0%)</td><td nowrap>建玉 −1,813（今 292）</td><td nowrap>プットの建玉の減少</td></tr>
</tbody>
</table>

- 建玉の増減は前回の記録（11/25）から今の板まで（建玉は前の営業日の引けの数）。大口は直近の取引日（11/27）の、代金の多い契約（opt_flow の推定）。その日の取引が建玉に出るのは次の営業日なので、2つを続けて見ます。★は建玉の壁（上位3本）。コール売りなら、ディーラーはそのコールを買い持ちになり、その価格の近くで値動きを抑える向きに売り買いする（壁が厚くなる）とみます。

### 大口の賭け（推定）

**ブル 🐂・強さ 小**（売買代金の 0.2%） — SQQQ は逆レバ3倍。ナスダック100に直すと **ベア 🐻**

- 大口のデルタ換算（株を何ドル分買った・売ったのと同じ向きか）: 差 **+4.9百万ドル**（ブル側 +6.0百万ドル・ベア側 −1.1百万ドル）。代金はブル側 2.5百万ドル・ベア側 0.7百万ドル。1日の売買代金 32.3億ドル（20日の平均）
- 大口が見ている価格: 上げの的（コール買い） **50**（+9.3%）・下げの的（プット買い） **46**（+0.5%）
- 深い ITM の大口（合計に入れない）: 3本・代金 1.3百万ドル（12/18 37C買・12/18 65P売・1/15 27C（向き不明））。株と組み合わせた取引（配当の裁定・乗り換えなど）のことが多い。そのまま賭けとみると +3.6百万ドル 分

<table>
<thead><tr><th nowrap>契約</th><th nowrap>推定・意味</th><th nowrap>代金・枚数</th></tr></thead>
<tbody>
<tr><td nowrap>12/31 42C<br>−8.2%<br>建玉 0</td><td nowrap><b>買い寄り</b><br><b>（IV +21.1pt）</b><br>上げへの賭け<br>（ITM）<br>（原指数には逆）</td><td nowrap>$1.1M<br>1,511枚<br>Δ +$2.3M<br>IV 92%</td></tr>
<tr><td nowrap>1/15 68P<br>+48.6%<br>建玉 0</td><td nowrap><b>売り寄り</b><br><b>（IV −2.4pt）</b><br>下値の防御線<br>（ITM）<br>（原指数には逆）</td><td nowrap>$0.6M<br>240枚<br>Δ +$0.4M<br>IV 110%</td></tr>
<tr><td nowrap>1/15 47P<br>+2.7%<br>建玉 101</td><td nowrap><b>買い寄り</b><br><b>（IV +6.2pt）</b><br>下げへの賭け・<br>守り（ITM）<br>（原指数には逆）</td><td nowrap>$0.4M<br>545枚<br>Δ −$0.6M<br>IV 89%</td></tr>
<tr><td nowrap>1/15 46P<br>+0.5%<br>建玉 0</td><td nowrap><b>買い寄り</b><br><b>（IV +4.1pt）</b><br>下げへの賭け・<br>守り<br>（原指数には逆）</td><td nowrap>$0.3M<br>535枚<br>Δ −$0.5M<br>IV 86%</td></tr>
<tr><td nowrap>12/4 50C<br>+9.3%<br>建玉 1,814</td><td nowrap><b>買い寄り</b><br>上げへの賭け<br>（原指数には逆）</td><td nowrap>$0.2M<br>1,310枚<br>Δ +$0.9M<br>IV 113%</td></tr>
<tr><td nowrap>12/18 50C<br>+9.3%<br>建玉 5,030</td><td nowrap><b>買い</b><br>上げへの賭け<br>（原指数には逆）</td><td nowrap>$0.2M<br>597枚<br>Δ +$1.1M<br>IV 101%</td></tr>
<tr><td nowrap>1/15 55P<br>+20.2%<br>建玉 0</td><td nowrap><b>売り寄り</b><br>下値の防御線<br>（ITM）<br>（原指数には逆）</td><td nowrap>$0.2M<br>129枚<br>Δ +$0.2M<br>IV 95%</td></tr>
<tr><td nowrap>1/15 65C<br>+42.0%<br>建玉 11,418</td><td nowrap><b>買い</b><br>上げへの賭け<br>（原指数には逆）</td><td nowrap>$0.2M<br>739枚<br>Δ +$0.8M<br>IV 108%</td></tr>
<tr><td nowrap>12/11 50C<br>+9.3%<br>建玉 508</td><td nowrap><b>中間</b><br>向きは不明</td><td nowrap>$0.2M<br>715枚<br>Δ —<br>IV 107%</td></tr>
<tr><td nowrap>12/24 55P<br>+20.2%<br>建玉 0</td><td nowrap><b>売り寄り</b><br><b>（IV −1.6pt）</b><br>下値の防御線<br>（ITM）<br>（原指数には逆）</td><td nowrap>$0.2M<br>138枚<br>Δ +$0.2M<br>IV 104%</td></tr>
<tr><td nowrap>12/18 37C<br>−19.1%<br>建玉 0</td><td nowrap><b>買い</b><br>深い ITM の買い</td><td nowrap>$0.8M<br>850枚<br>Δ +$3.3M<br>IV 93%</td></tr>
<tr><td nowrap>12/18 65P<br>+42.0%<br>建玉 0</td><td nowrap><b>売り寄り</b><br><b>（IV −10.2pt）</b><br>深い ITM の売り</td><td nowrap>$0.3M<br>150枚<br>Δ +$0.3M<br>IV 110%</td></tr>
<tr><td nowrap>1/15 27C<br>−41.0%<br>建玉 3</td><td nowrap><b>不明</b><br>向きは不明</td><td nowrap>$0.2M<br>100枚<br>Δ —<br>IV 144%</td></tr>
</tbody>
</table>

推定の向きは最後の約定の位置（売り気配で約定＝買い）と、前回の実行からの IV の上下から。買い・売りの分かる大口は代金の 95%。誰の取引かは分かりません。表の『代金・枚数』は、代金・その日の出来高・Δ（デルタ換算。株を何ドル分買った＋・売った−のと同じ向きか）・IV。

### 詳しく

**まとめ**: 下の支えの候補 **42**（−8.2%）・40（−12.6%）・36（−21.3%）。上の重さの候補 **48**（+4.9%）・50（+9.3%）・55（+20.2%）。既に割れたプットの壁 50（+9.3%）。次の満期（12/4・7日）の想定の幅 ±11.2%（40.63〜50.89）。ガンマはプラス側（ゼロガンマ —）→ 値動きが小さくなりやすい。

**下の支えの候補**（プットの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>42</td><td nowrap>−8.2%</td><td nowrap>2,152</td><td nowrap>9%</td></tr>
<tr><td nowrap>40</td><td nowrap>−12.6%</td><td nowrap>3,018</td><td nowrap>12%</td></tr>
<tr><td nowrap>37</td><td nowrap>−19.1%</td><td nowrap>1,957</td><td nowrap>8%</td></tr>
<tr><td nowrap>36</td><td nowrap>−21.3%</td><td nowrap>1,995</td><td nowrap>8%</td></tr>
<tr><td nowrap>33</td><td nowrap>−27.9%</td><td nowrap>1,990</td><td nowrap>8%</td></tr>
</tbody>
</table>

**上の重さの候補**（コールの建玉。45日以内の満期の合計）

<table>
<thead><tr><th nowrap>価格</th><th nowrap>距離</th><th nowrap>建玉</th><th nowrap>割合</th></tr></thead>
<tbody>
<tr><td nowrap>48</td><td nowrap>+4.9%</td><td nowrap>6,846</td><td nowrap>11%</td></tr>
<tr><td nowrap>50</td><td nowrap>+9.3%</td><td nowrap>7,746</td><td nowrap>13%</td></tr>
<tr><td nowrap>54</td><td nowrap>+18.0%</td><td nowrap>1,105</td><td nowrap>2%</td></tr>
<tr><td nowrap>55</td><td nowrap>+20.2%</td><td nowrap>7,790</td><td nowrap>13%</td></tr>
<tr><td nowrap>57</td><td nowrap>+24.6%</td><td nowrap>1,242</td><td nowrap>2%</td></tr>
</tbody>
</table>

**次の満期 12/4（7日）**: プットの壁 36（−21.3%）・コールの壁 50（+9.3%）・最大の痛み 43（−6.0%）・想定の幅 ±11.2%

アウト・オブ・ザ・マネーに払われた代金: プット 0.8百万ドル・コール 3.5百万ドル（プットの割合 19%）

**建玉の増減**（前回のオプション分析の 11/25 → 今の板。45日以内の満期）

<table>
<thead><tr><th nowrap>行使価格</th><th nowrap>距離</th><th nowrap>増減</th><th nowrap>想定元本</th></tr></thead>
<tbody>
<tr><td nowrap>57C</td><td nowrap>+24.6%</td><td nowrap>+841</td><td nowrap>4.8百万ドル</td></tr>
<tr><td nowrap>39P</td><td nowrap>−14.8%</td><td nowrap>+491</td><td nowrap>1.9百万ドル</td></tr>
<tr><td nowrap>54C</td><td nowrap>+18.0%</td><td nowrap>+467</td><td nowrap>2.5百万ドル</td></tr>
<tr><td nowrap>40C</td><td nowrap>−12.6%</td><td nowrap>−5,511</td><td nowrap>−22.0百万ドル</td></tr>
<tr><td nowrap>38C</td><td nowrap>−17.0%</td><td nowrap>−4,271</td><td nowrap>−16.2百万ドル</td></tr>
</tbody>
</table>

合計: プット −15.7百万ドル・コール −79.4百万ドル（想定元本の増減）

**全体**: IV30 91%・7日 99%・期間構造 1.09（目先の不安が強い）・プットの割高さ −8.0pt・建玉のプット/コール 0.64

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
