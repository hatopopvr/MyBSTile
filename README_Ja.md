# MyBSTile
ScoreSaberのプレイ履歴データのタイル表示を行う[Google Colab Notebook](https://colab.research.google.com/github/hatopopvr/MyBSTile/blob/main/MyBSTile_En.ipynb) です。  
MyBeatSaberAnalyticsに実装した機能の抜粋であり、データ取得量を減らしたライト版です。   
データは何も保存しないですが、手軽に結果を確認するには便利です。

![Tile](images/images_001.jpg)

## 使い方

1. [notebook](https://colab.research.google.com/github/hatopopvr/MyBSTile/blob/main/MyBSTile_En.ipynb) を開き、以下の情報を入力します。
 - `player_id` : ScoreSaberのPlayerIDを入力してください。 
 - `view_score_type` : 取得する内容を`top` か`recent`か選択してください。 
 
![Input Form](images/images_002.jpg)
 
2. `ランタイム`タブを選択し、 `すべてのセルを実行`か `再起動してすべてのセルを実行` を選択し、実行すると結果が得られます。

![Input Form](images/images_004.jpg)

## データ元
- Score Data form ScoreSaber Public API - [doc](https://docs.scoresaber.com/)  
- Cover Image form - https://cdn.scoresaber.com/covers/{hash}.png  

## 作者
- hatopop ([@hatopop_vr](https://twitter.com/hatopop_vr))
