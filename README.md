## git でファイルをあげる練習

### 課題

1. github リポジトリを作成する
2. 手元に clone する
3. 初期化してプッシュする

これは git レポジトリにファイルをあげる練習です．
以下のコマンドは課題2,3を実行するコマンドです．これらを使う前に，以下の「練習を行う前に」に従って progit を読んでみてください．リポジトリが作れたら，とりあえず

```
> cd Desktop
> git clone [githubのhttpをコピー]
> git init
> [このディレクトリにsample.pyを追加]
> git add sample.py
> git commit -m "hello world"
> git push -u origin master
```

---

## 練習を行う前に

17-b4seminar のリポジトリを手元に持っていると思いますが，17-b4seminar/doc/progit-ja.1016.pdf のファイルがgitの教本になります．

まず，p29~p48を読んで，gitとは何かを勉強してください．次にp49~p80あたりをみて，上記のコマンドの意味を理解してください．

練習のコマンドは結構適当にやってるかもしれませんので，みなさんが実際に実行したときに不具合があったら教えてください．サポートしますので．


## 17-b4seminer にプッシュする

実際にscipy lecture note の作成した資料をアップロードする際に行うコマンドです．

これも progit を読んで意味を理解してから実行してください．

```
> cd [localのディレクトリ]
> git pull
> git status # 変更を確認．大丈夫だったらコミット
> git add .  # 変更を全て add
> git commit -m "1.2.*のファイルを追加"
> git push
```