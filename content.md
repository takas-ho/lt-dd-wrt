
# 2019.10.9

---

<!-- 結論 -->

## WiFiルーターが壊れた

- USB付きで <!-- .element: class="fragment" -->
- 安くて <!-- .element: class="fragment" -->
- <!-- .element: class="fragment" --> <span style="color: orange;">dd-wrt</span>対応を買おう！

---

<!-- あらすじ -->
<!-- .slide: style="background-color:rgba(0,0,0,0.5); " -->
<!-- .slide: data-background-iframe="https://www.buffalo.jp/product/detail/wzr-hp-ag300h.html" data-background-interactive -->

# 現在

## WZR-HP-AG300H(2010年製)

- USB2.0付き
- <span style="color: orange;">dd-wrt</span>で運用してた

Note:

- USB付きでネットワークプリンタやNAS代わりになる
- NTFSの2TB付けてるけど、便利だけど、遅い
- とても遅い
- 設定で改善できそうなんだけどわからない
- 5年くらい使ってる
- 2年前からmacbookにしたが、このNTFSへの書き込みができない。読み取りはできるが。「thinkpadで要検証」

--

# 問題発生

- Web設定画面が開かなくなった
- Macアドレス制限の追加変更できない

Note:

dd-wrtはwebから設定できるが、この画面が開かなくなったことに日曜10/6気づいた、繋がらないだと、、、、
sshでも繋がる設定にしとくべきだったと後悔

--

# 原因は？

- 3ヶ月くらい前にやった<span style="color: orange;">dd-wrt</span>のverupか？

Note:

仕方ないので買い足し
planexとかfonとか、聞いたことのない使ったことのないメーカーにも惹かれるんだけどdd-wrtが絡むと情報が少なくバッファローに

--

<!-- .slide: style="background-color:rgba(0,0,0,0.5); " -->
<!-- .slide: data-background-iframe="https://www.buffalo.jp/product/detail/wzr-1166dhp2.html" data-background-interactive -->

# ポチる

## WZR-1166DHP2(2013年製)

- USB3.0付き
- <span style="color: orange;">dd-wrt</span>で運用予定

Note:

- 3年も進化したぜ
- dd-wrtが対応してる機種で、まあまあ新しそう
- \5000-

---

<!-- 疑問と検証 -->
<!-- .slide: style="background-color:rgba(0,0,0,0.5); " -->
<!-- .slide: data-background-iframe="https://dd-wrt.com/" data-background-interactive -->

# FAQ

## <span style="color: orange;">dd-wrt</span>ってなに？

- WiFiルーターのフリーのファームウェア
- 対応Hardは結構多い
- 7~8割は日本語化されてるから安心だ

Note:

- 純正ファームにない機能も使える、多機能
- 日本では電波法に触れる設定もできちゃうくらい多機能
- DD-Wrtは、ゲートウェイ、無線LANアクセスポイントなどの組み込みシステム用ファームウェアとして開発されているLinuxディストリビューションの一種である。OpenWRTを元にして作られている。組み込みシステムはパソコンとは違い、規格が統一されていないため、各製品毎に対応が図られている。各製品毎の対応状況は、公式サイトの"Router Database"で型番から検索して確認することが出来る。家庭用ルーターの非公式ファームウェアの中では最も有名である。

--

# FAQ

## メーカー保証受けられない？

- その通りだが、サポート終了したらどうするの？
- <span style="color: orange;">dd-wrt</span>は、長いこと続いててサポート終了にならないぜ
- オーバークロックと同じノリだ

---

# まとめ

- 新ルーター1166はDual coreのメモリ256MBらしい
- 週末<span style="color: orange;">dd-wrt</span>入れてルーター差し替えだ
- USBが早くなってほしい(切実)

Note:

- 楽しみ
