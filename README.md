# MyBSTile
The Google Colab Notebook to displays BeatSaber's play history in a tiled format.

- [MyBSTile_Lite](https://colab.research.google.com/github/hatopopvr/MyBSTile/blob/main/MyBSTile_En.ipynb): Recommended version. Lightweight as only the minimum data is retrieved. No authentication required.

- [MyBSTile_Pro](https://colab.research.google.com/github/hatopopvr/MyBSTile/blob/main/MyBSTilePro_En.ipynb): Google authentication is required as it uses Google drive. UnRanked accuracy & Keyword filters are available.

![Tile](images/images_001.jpg)

## Data
- Score Data from [ScoreSaber](https://scoresaber.com/) Public API - [doc](https://docs.scoresaber.com/)  
- Cover Image from - https://cdn.scoresaber.com/covers/{hash}.png  

## how to use

1. When the [notebook](https://colab.research.google.com/github/hatopopvr/MyBSTile/blob/main/MyBSTile_En.ipynb)  opens, input information below.
 - `player_id` : enter the ScoreSaber PlayerID 
 - `view_score_type` : Select `top` or `recent` as the content to be retrieved. 
 
![Input Form](images/images_002.jpg)
 
2. Press the `Runtime` tab, then Press the `Run All` or `Restart and Run All` button to get the results.  
  (Please run it despite the warning.)

![Input Form](images/images_003.jpg)

## Author
- hatopop ([@hatopop_vr](https://twitter.com/hatopop_vr))
