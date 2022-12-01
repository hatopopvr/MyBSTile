# MyBSTile
[ScoreSaber](https://scoresaber.com/)のデータを用いてBeatSaberのプレイ履歴データのタイル表示を行う[Google Colab Notebook](https://colab.research.google.com/github/hatopopvr/MyBSTile/blob/main/MyBSTile_En.ipynb) です。  
[MyBeatSaberAnalytics](https://github.com/hatopopvr/MyBeatSaberAnalytics)に実装した機能の抜粋であり、データ取得量を減らした超ライト版です。   
データ保存等も廃しているため、現在データの蓄積を想定する場合はMyBeatSaberAnalyticsを使用してください。
※データ保存を行うPro版も作りました。

- [MyBSTile](https://colab.research.google.com/github/hatopopvr/MyBSTile/blob/main/MyBSTile_En.ipynb):通常版。軽量。  
- [MyBSTilePro](https://colab.research.google.com/github/hatopopvr/MyBSTile/blob/main/MyBSTilePro_En.ipynb):Pro版。Google認証要。データ保存あり。単キーワードでの絞り込み可。

![Tile](images/images_001.jpg)

## データ元
- Scoreデータ元 - ScoreSaber Public API - [doc](https://docs.scoresaber.com/)  
- Cover画像元 - https://cdn.scoresaber.com/covers/{hash}.png  

## 使い方

1. [notebook](https://colab.research.google.com/github/hatopopvr/MyBSTile/blob/main/MyBSTile_En.ipynb) を開き、以下の情報を入力します。
 - `player_id` : ScoreSaberのPlayerIDを入力してください。 
 - `view_score_type` : 取得する内容を`top` か`recent`か選択してください。 
 
![Input Form](images/images_002.jpg)
 
2. `ランタイム`タブを選択し、 `すべてのセルを実行`か `再起動してすべてのセルを実行` を選択し、実行すると結果が得られます。  
　(※警告は無視して実行してください)

![Input Form](images/images_004.jpg)

## 作者
- hatopop ([@hatopop_vr](https://twitter.com/hatopop_vr))
