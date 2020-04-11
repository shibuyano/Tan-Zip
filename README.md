# Tan-Zip
 ファイル毎に圧縮ファイルを作成する。

## 作成背景
仕事などで、サンプルの試験などを実施していると、評価データがファイルサーバの容量を圧縮するることがある。
本来データフォルダごとに圧縮してしまってもよいが、ファイル名での検索ができにくくなる。
このため、ファイル名での検索が可能なようにファイル毎に単独ZIP圧縮するソフトを作成しようと考えた。

orgファイル名：200420_WLTC_Test20.dat →圧縮後 200420_WLTC_Test20.dat.zip

## 構想
- 圧縮ソフトは、7zipを使用する。
- 指定したフォルダ以下を再帰的に圧縮する。
- 対象のファイルを選ぶことができる(ex *.datのみ)
- 圧縮後に、オリジナルファイルを削除 もしくは他のフォルダに移動させる。





## history
- 2020/04/11 初期構想案投稿