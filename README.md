# lightgbm_demand_forecast
# LightGBMによる需要予測サンプル

このノートブックは、**Python + LightGBM** を使って小売商品の需要予測を行うサンプルです。  
Google Colabでそのまま実行可能で、実務で使える簡易予測パイプラインを示しています。

## 特徴

- ダミーデータを生成して日次の売上を予測  
- カレンダー特徴量（月や曜日など）
- ラグ特徴量（過去1週間）
- プロモーションや在庫情報の特徴量（※サンプル用にランダム生成しています。）  
- LightGBMモデルでの予測  
- 予測精度評価（RMSE）  
- 予測結果の可視化（実績 vs 予測）  
- 特徴量重要度の可視化  


## 実行環境

- Python 3.10+  
- Google Colab 推奨  
- ライブラリ: pandas, numpy, matplotlib, seaborn, lightgbm, scikit-learn, japanize-matplotlib  

## 実行方法

1. Google Colabで `lightgbm_demand_forecast_sample.ipynb` を開く  
2. 上から順にセルを実行する  
3. 予測結果のグラフと特徴量重要度のグラフが表示される  

## 注意点

- 本ノートブックは**サンプル用途**のため、簡略化しています  
- 実務で使用する場合は欠品処理、在庫ロジック、特徴量チューニングなどを拡張してください  
- 本リポジトリは **No License** で公開しています（閲覧・学習用）
