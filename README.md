# 竜宮城
# 概要
Shadowverseの効果処理で気になる点を簡単なスケールでの実装を試みた。
竜宮城の効果は対象選択を含まないファンファーレ能力が発動したとき、もう一度そのファンファーレ能力を働かせるものである。
この「対象選択を含まないファンファーレ能力」に限られている理由が「対象選択を含むファンファーレまで対象に入れると仕様
上実装が大規模または困難になってしまうから」なのか、「ルールバランスを考えたうえでの意図的な実装」なのかを考察するた
めに自身の環境での実装を試みた。

# フローチャート
下図がファンファーレを起動してからのフローチャートである。<br/>
![スクリーンショット 11111](https://github.com/syuuiti/SV_Ryuuguuzyou/assets/168068060/df676443-e798-4310-a11d-79ee4fbaf011)

下図は上図の”ファンファーレ効果処理”の部分の中身のフローチャートを表している。今回の対象選択を含むファンファーレを持つフォロワーはウロボロスを再現している。<br/>
![スクリーンショット11112](https://github.com/syuuiti/SV_Ryuuguuzyou/assets/168068060/ba993a92-2a04-4f5b-8db9-eb1e69ffaca2)
