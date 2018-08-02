### このリポジトリについて

Software Design 2018年9月号(技術評論社)の特集"ITエンジニアのための統計学入門" 第5章「使えばわかる！データ分析にPythonが選ばれる理由」の参考資料です。

`scikit-learn`に付属している「ボストン市の地域別平均住宅価格」データセットをテーマに、可視化と線形回帰を試みる内容になっています。

[Software Design 2018年9月号]()

### リポジトリ構成

```
python_stat_start
├ notebook
│ └ python_stats_start.ipynb : notebookファイル
├ README.md : このファイル
└ requirements.txt : パッケージ一覧
```

### 必要条件

このリポジトリの利用は`Python3.6.x`以上の使用を想定しています。

### 仮想環境の作成

```
$ python3 -m venv env

# Windowsの場合
$ env¥Scripts¥activate

# macOS・Linuxの場合
$ source env/bin/activate

# requirements.txtに書かれたパッケージをすべてインストールする
(env) $ pip install -r requirements.txt
```