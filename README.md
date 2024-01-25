# random_chance
predicateのrandom_chanceに関するデータパックサンプルになります。

詳しくはブログ記事『[【マイクラ】random_chanceで成功確率を扱える【predicate】](https://natsumake.com/random_chance/)』を参考にしてください。

<h3>使い方</h3>

導入後、以下のコマンドでrandom_chanceが適用されたコマンド、ルートテーブルを実行できます。

50％の確率で成功するコマンドの実行<br>
```/execute if predicate sample:random_chance run give @a diamond 1```

50％の確率で成功する（付与される）ルートテーブルを実行<br>
```/loot give @a loot sample:random_chance```
