# ue_test_content_proj

# Analytic Fog
  reference https://blog.mmacklin.com/2010/05/29/in-scattering-demo/

  球 及び 球面円錐 に対するレイの通過経路上でのInscatterをレイマーチではなく解析的に計算するフォグのUEマテリアル実装です.
  <img alt="Image" src="https://github.com/user-attachments/assets/56a80d21-239a-4b77-a703-2bd2db8f0a59" />

  Naga/AnalyticFog にあるマテリアルが該当します.

  描画領域の指定のためにBox等のマテリアルをアサインして利用します.

  |1|2|
  |---|---|
  |![](https://github.com/user-attachments/assets/85942275-d129-4032-a6db-118c4c4c0bfd)|![](https://github.com/user-attachments/assets/60eef174-9fd0-45db-a746-43911e300d56)|
  |3|4|
  |---|---|
  |![](https://github.com/user-attachments/assets/8d7d8b0c-ce33-46fb-8619-b7885ae53acf)|![](https://github.com/user-attachments/assets/6fddc1ec-51a4-41f4-a0ee-d3a71eb48245)|

  マテリアルパラメータでPointLightモードとSpotLightモードの切り替え, ライト強度, SpotLightの広がりをコントロールします.
  位置や向き, 範囲は適用したオブジェクトでコントロールします.
  
  |1|2|
  |---|---|
  |![](https://github.com/user-attachments/assets/5ab1ca72-15e0-4ee6-b34b-9ddfa7cae645)|![](https://github.com/user-attachments/assets/8f8fa2cb-4301-4d1b-a9fa-cf1883ff574e)|
  
  
