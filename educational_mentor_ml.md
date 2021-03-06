# ワークサンプル for 教育メンター（機械学習コース）

## 概要

機械学習コースのワークサンプルでは、メンター業務を想定した2つのタスクに取り組んでいただきます。

- メンタリング質問対応
- 課題回答・改善案作成

重要なことは、本当に自分がメンバーになったかのように体験することです。これは、ただの筆記テストではありません。  
あなたと私たちの双方にとって、とても大切なことです。  

### 取り組み方の基本原則

ワークサンプルへの取り組む方の基本原則をお伝えします。  

- 受講生に対して優しく丁寧に対応すること
- 受講生が卒業後自立できるような教え方をすること
- 事前に説明していない言葉や受講生のレベルを考慮すること

### 取り組みへの質問について

ご質問がある場合は、ワークサンプル担当者にお気軽にご質問ください。  
ワークサンプルに取り組むためであれば、DIVE INTO CODEの自習室や教室の利用が可能です。積極的にご利用ください。

### 前提知識

DIVE INTO CODEは未経験であっても必要な知識をキャッチアップできる人、それをずっと続けることができる人を採用しています。  
現時点の知識があれば理想的ですが、完全にゼロでもチャレンジする機会を設けています。  
知識がゼロの方は、この機会にご自分がどこまで知識をつけられそうかを確かめましょう。  

現時点で知識が身についていない方を対象に、推薦学習教材をお伝えします。

[推薦学習教材](https://github.com/DiveintoCode-corp/worksample/blob/master/learning_material_machine_learning.md)

## メンタリング質問対応

最初のワークサンプルはメンタリング質問対応です。

コース受講1週目の方から教室で「PythonでNumPyを使いドット積を計算しようとしたがエラーが出た。なぜこうなるのか」と質問されたとします。この場合にあなたならばどのように対応するかを文章で説明してください。

あなたは以下の前提情報を持っているとします。

- この質問をされた方はPythonや大学レベルの数学を扱った経験がほとんどない
- コースでは今後NumPyによる配列の操作を扱う機会が多い

**Jupyter Notebookの実行画面**

[![Image from Gyazo](https://t.gyazo.com/teams/diveintocode/e9e3c6e91b7d4abd99001aa0848e4059.png)](https://diveintocode.gyazo.com/e9e3c6e91b7d4abd99001aa0848e4059)

**実行したコード**

```py
import numpy as np

a = np.array([[-1,2,3]])
b = np.array([[0,2,1]])
np.dot(a,b)
```

### 作成した文章をGithubに公開

`worksample`というGithubリポジトリを作成し、作成した文章を`1_mentoring.md`というファイル名で`Github`上で見れるようにしましょう。

## 課題回答・改善案作成

次のワークサンプルは課題回答・改善案作成です。以下の3種類の課題から指定された課題の回答および改善案の作成行っていただきます。

- A Week1授業前課題1 Pythonを使ってみよう
- B Week4授業前課題3 オブジェクト指向に慣れよう
- C Sprint10課題 深層学習スクラッチニューラルネットワーク

Jupyter Notebookを用いてipynbファイルにPythonコードとMarkdownによる説明を記述してください。

課題回答はコースの受講生に対して配布することを想定しています。単純に答えを書くのではなく、問題に応じて以下のような内容を含めることが望まれます。受講生に向けた文章ですので、その点を考慮したものにしてください。

- 間違えやすい点
- 別解
- 発展的な内容

また、回答作成と並行してこの課題自体を改善していくことも求められます。以下のような観点で改善案を同じipynbファイルに記述してください。こちらは一緒に働くメンバーに向けて伝える文章です。

- 追加すると良さそうな記述や問題の案
- 分かりにくい記述や不適切な記述の修正案

回答や改善案を記述するためのフォーマットはここでは決まっておりませんので、見やすい形で完成させてください。

**各課題の説明**

それぞれの課題は2019年1月期の受講生に公開されているものと同内容になっています。課題の中の説明は受講生に向けたものです。

なお、課題の中に数式が登場する場合、GitHub上ではTexが変換されずに表示されています。これらはJupyter NotebookでMarkdownとして貼り付けることで数式に変換して表示できます。

- A Week1授業前課題1 Pythonを使ってみよう

https://github.com/DiveintoCode-corp/worksample/blob/master/ml_week1.md

コースを受講して最初の自習課題です。数時間以内で解くことを想定しています。この課題には基礎的なPythonのコーディングを練習していただくとともに、メンターが各受講生の実力を測る目的もあります。（受講生には事前にPythonの基礎を学んでおくことを伝えています）回答を作成する際は初心者向けであることを特に意識してください。

- B Week4授業前課題3 オブジェクト指向に慣れよう

https://github.com/DiveintoCode-corp/worksample/blob/master/ml_week4.md

コースを受講して4週目の自習課題です。数時間以内で解くことを想定しています。次の週から本格的にはじまる機械学習モデルのスクラッチ課題の準備として、オブジェクト指向に触れることが目的の課題です。

なお、問題1と問題2には「これまでの課題で利用してきた」とありますが、それらの課題はワークサンプルを行っていただく上では公開されていませんので、仮のクラスやメソッドを考えてみてください。

- C Sprint10課題 深層学習スクラッチニューラルネットワーク

https://github.com/DiveintoCode-corp/worksample/blob/master/ml_sprint10.md

コースを受講して2ヶ月目、教室で2日間かけて解く課題です。受講生はここではじめてニューラルネットワークに触れることになります。線形回帰、ロジスティック回帰、SVM、決定木、K-meansに続いて6つ目のスクラッチ課題ですので、教師あり学習の基本的な部分などは理解している状態です。この次の課題は「Sprint11課題 深層学習スクラッチディープニューラルネットワーク」として、ここで作成したニューラルネットワーククラスを拡張していきます。

### 作成した文章をGithubに公開

Githubリポジトリ`worksample`内に、作成した回答・改善案を`2_example_answer.ipynb`というファイル名で`Github`上で見れるようにしましょう。複数の課題の回答を作成した場合は区別できる名前にしてください。

## 提出方法

上記の内容に取り組んだものを反映した、あなたのGithubリポジトリのURLをご提出ください。  
なお、ご提出前に以下の項目をすべて満たしているかを確認しましょう。  

- [ ] `1_mentoring.md`にメンタリング質問対応方法を文章で記述した
- [ ] `2_example_answer.ipynb`に回答・改善案を記述した

### 提出期限

提出期限は、採用面接時にお話ができていればその期限までに。そうではない場合は、ご自分で決めてください。  
DIVE INTO CODEは、言われたからやるのではなく、自ら業務にコミットして達成していく姿勢を重視しています。  

以上でワークサンプルは終了です。  
お疲れ様でした。
