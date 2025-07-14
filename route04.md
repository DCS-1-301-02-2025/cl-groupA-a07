# 佐藤の通学経路

[メンバー表に戻る](member.md#メンバー表)

```graphviz
digraph {
    edge [dir=both]
    
    八王子国際キャンパス -> 高尾駅 [label=バス]
    高尾駅 -> 西国分寺駅 [label=中央線]
    西国分寺駅　-> 武蔵浦和駅 [label=武蔵野線]
    武蔵浦和駅 -> 戸田公園駅 [label=埼京線]
    戸田公園駅 ->自宅 [label=徒歩]
}
```
