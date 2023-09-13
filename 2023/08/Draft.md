9/13

## 1. 取り組んだ課題一覧
#### 【Lv08】Web技術の基本を学ぶ / Learn the Basics of Web Technology
 ❌[読む] 『プロになるためのWeb技術入門』――なぜ，あなたはWebシステムを開発できないのか（最後まで）  
 ❌[書く] 課題をまとめる(草稿)（提出まで）

#### 【Lv14】gitに触れながら学ぶ / Learn Git Branching
 ✅[見る] システム開発プロジェクト応用第一 第5,6回 Gitによるバージョン管理（最後まで）

## 2. わかったこと
- `.git`とは何か
- 「ステージングエリア」=「インデックス」
- 「コミット」とは？(自分のコトバで説明できる)
- `git config user.name`と`git config user.email`を登録する理由
- 次のコマンドが何を意味しているのか説明できるようになった
```
git ls-files
git log --stat
```
- `git commit`と`git commit -a`の違い、及び`git commit -a`の使いどころが分かった

- ワーキングツリーで新規ファイルsample.txtを作成直後、`git commit -a`でsample.txtのコミットが失敗する理由を説明できるようになった

- `git diff`の結果の読み方がよくわかった。(とりわけココの部分)
```
$ git diff
diff --git a/file.txt b/file.txt //ココ
index e69de29..001b90b 100644
--- a/file.txt //ココ
+++ b/file.txt //ココ
@@ -0,0 +1,2 @@ //ココ
+Helo^M
+World 
```
- 次のコマンドが何を意味しているのか説明できるようになった
```
git diff HEAD
```

- gitで追跡対象となっていないファイルを確認する方法がわかった。

- `git add -u`の意味とつかいどころ
## 3. 次やること(明日の目標)
#### 【Lv14】gitに触れながら学ぶ / Learn Git Branching
　⏹[見る] システム開発プロジェクト応用第一 第8,9回GitHub & Pull Request

## 4. 感じたこと
- [Git] Gitのモヤモヤ感を打破したい。今日～金曜日位までは中心にやることにしました。

## 5. 学習時間
●●●●●●●●●●
今日の学習時間:3H / 今月の学習時間40.5H / 総学習時間:42.5H
