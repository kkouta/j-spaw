# J-SpAW: Japanese speech corpus for speaker verification and anti-spoofing / 話者照合となりすまし検出のための日本語音声コーパス
The Coco-Nut corpus is a corpus including Japanese voice and free-form texts describing the voice characteristics (hereinafter, characteristics prompt.)

J-SpAW コーパスは，話者照合と音声なりすまし検出を目的とした，人間の実発話音声と攻撃者によるなりすまし音声を含むコーパスです．

## Download / ダウンロード
(TBD)

## Description / 内容
　(TBD)

## On meta-labels

* 収録部屋ID(実際には場所じゃなくて部屋の大きさを書く)
    * `R1,r1`: 都立大室内
    * `R2,r2`: 都立大屋外 
    * `R3,r3`: 東大室内
    * `R4,r4`: 東大屋外
* 再生機器
    * `S1,s1`: bose
    * `S2,s2`: iPad
    * `S3,s3`: MacBook Pro
    * `S4,s4`: Sony
* 収録機器
    * `M1,m1`: pixel
    * `M2,m2`: iPhone
    * `M3,m3`: iPad
* 収録環境
    * `E1,e1`: 無音
    * `E2,e2`: 空調
    * `E3,e3`: 音楽
    * `E4,e4`: 屋外
* `spoof`: key. It can be
    * `bonafide`: bona fide
    * `spoof`: spoof
* `notrim`: whether non-speech frames are 

L2がtts
trimmed. It can be
    * `notrim`:  not trimmed
    * `trim`: trimmed
* `eval`: name of subset. It can be
    * `eval`: evaluation subset
    * `progress`: progress subset
    * `hidden`: hidden subset (there non-speech frames are trimmed)



## Terms of use / 使い方
- Non-commercial purpose only / 非商用利用に限る

## Contributors / 作成者
- Kouta Kanno / 菅野 滉大 (Tokyo Metropolitan University / 東京都立大学)
- Shinnosuke Takamichi / 高道 慎之介 (Keio University / 慶應義塾大学)
- Sayaka Shiota / 塩田 さやか (Tokyo Metropolitan University / 東京都立大学)


## Paper / 論文
- 菅野 滉大, 高道 慎之介, 塩田 さやか, "J-SpAW:話者照合となりすまし検出のための日本語音声コーパス" 情報処理学会 音声言語処理研究会 , 2024
