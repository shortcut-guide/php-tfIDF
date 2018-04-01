# php-tfIDF
PHPで特徴抽出(tfIDF)を実装

# 実装方法
```
//class 実行
$tfIDF = new phpTfIDF();

//特徴抽出単語選択
tfIDF::$word = array("hello","world");

//抽出元テキスト
tfIDF::$document = "Welcome hello world world world";
$tfIDF->action();

//結果
array(2) {
  [0]=>
  float(0.2)
  [1]=>
  float(0.6)
}
```
