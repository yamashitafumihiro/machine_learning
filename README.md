# machine_learning

## transfer_learning_penguins.ipynb

大学2年時に行った3種のペンギンを分類する分類器を転移学習を利用して作成したときのものです. 

各種100枚ずつ学習用データとしてスクレイピングして収集し, 合計300枚で90%超の正解率の精度にすることが出来ました. 

モデルの改良はあまりできませんでしたが, 学習用データを水増ししたりノイズを加えることで精度上昇を達成しました. 

転移学習なしで300枚程度でモデルを作ったら10%程度の正解率が出るくらいだったので転移学習の恐ろしさを痛感しました. 

参考資料です. 
https://colab.research.google.com/github/pytorch/tutorials/blob/gh-pages/_downloads/62840b1eece760d5e42593187847261f/transfer_learning_tutorial.ipynb
