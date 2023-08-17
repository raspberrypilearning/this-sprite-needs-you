## 作って試す

さあ、あなたのプロジェクトを作る時が来ました。 小さなことから始めて、時間があればプロジェクトにさらに追加してください。

![](images/step3_image.png)

**ヒント：** 何かを追加するたびに、プロジェクトをテストすることを忘れないでください。 バグを見つけて修正するのは、変更を加える前のほうがはるかに簡単です。

--- task ---

プロジェクトをどのような順番で作っていくかを決める必要があります。 こんなことができます:

+ 変数を 1 つ作成し、ユーザーがそれを制御できるようにします。 アニメーション、コスチューム、サウンド、エフェクト、会話を追加して、スプライトに命を吹き込みます。
+ ユーザーが簡単に制御できる方法で複数の変数を作成し、後でさらに効果を追加します。

スプライトを追加して、 `変数`{:class="block3variables"} を作成するのが良いスタートです。

--- /task ---

あなたはいくつかの本当に役立つスキルを身につけました。 プロジェクトを作成するのに役立つリマインダーは次のとおりです。

### 変数を使う

```blocks3
set [my variable v] to (0)
```

[[[scratch3-create-set-variable]]]

[[[scratch3-set-variable-with-button]]]

[[[scratch3-change-variable-in-loop]]]

### 条件をチェックする

```blocks3
if <(my variable) = (0)> then
```

[[[scratch3-forever-condition]]]

[[[scratch3-operators-conditions]]]

[[[scratch3-if-then-else]]]

[[[scratch3-set-block-input-colour-with-eyedropper]]]

### メッセージを送信したり受信したりする

```blocks3
broadcast [message1 v]
```

[[[generic-scratch3-broadcast-message]]]

### テキストを操作する

```blocks3
say (join[こんにちは ](名前)) for (2) seconds
```

[[[scratch3-emoji-text]]]

[[[scratch3-ask-answer-chat]]]

[[[scratch3-join-text]]]

### 背景、動き、グラフィック効果

```blocks3
set [ghost v] effect to (0)
```

[[[scratch3-glide-to-object]]]

[[[scratch3-changing-backdrops-pages-levels]]]

[[[scratch3-change-costumes-to-show-mood]]]

[[[scratch3-animate-movement-costumes]]]

[[[scratch3-graphic-effects]]]

[[[scratch3-show-hide-sprites-backdrops]]]

[[[scratch3-positioning-with-layers]]]

[[[scratch3-jiggle-a-sprite]]]

### 音：

```blocks3
start sound (Pop v)
```

[[[scratch3-add-sound]]]

[[[scratch3-record-sound]]]

[[[scratch3-text-to-speech]]]

### ペイントエディタ ー 背景とコスチューム：

[[[scratch3-paint-a-new-backdrop-extended]]]

[[[scratch3-backdrops-and-sprites-using-shapes]]]

[[[scratch3-use-text-tool]]]

[[[scratch3-copy-parts-between-sprite-costumes]]]

[[[scratch3-add-costumes-to-a-sprite]]]

### Scratchエディター

[[[scratch3-copy-code]]]

[[[scratch3-full-screen]]]

[[[scratch3-duplicate-sprite]]]

[[[scratch-backpack]]]


--- task ---

**テスト：** プロジェクトを他の人に見せて、フィードバックをもらいます。 何か変更を加えたいですか?

--- /task ---

--- task ---

**デバッグ：** プロジェクトに修正が必要なバグが見つかる場合があります。 一般的なバグは次のとおりです。


--- collapse ---

---
title: 変数が正しく更新されない
---

よくある間違いの 1 つは、 `Change`{:class="block3variables"} ブロックと `set`{:class="block3variables"} ブロックを混同することです。

+ `set`{:class="block3variables"} は、変数の値を新しい値に置き換えます。
+ `change`{:class="block3variables"} は変数に値を加えます。 `change by`{:class="block3variables"} を正の数と共に使用すると、変数の値は増加します。 `change by`{:class="block3variables"} を負の数と共に使用すると、変数の値は減少します。


もう 1 つのよくある問題は、 `Variables`{:class="block3variables"} ブロック メニューから変数をドラッグするのではなく、変数の名前を入力することです。 変数はオレンジ色です。

```blocks3
say (名前) for (2) seconds
```

**次のようではありません**:

```blocks3
say [名前] for (2) seconds
```

--- /collapse ---

--- collapse ---

---
title: 変更がいつもではなく一度だけ起こる
---

実行し続ける必要があるコード ブロックが `forever`{:class="block3control"} ブロック内に配置されていることを確認してください。 これを忘れることは本当によくあることです。

--- /collapse ---

--- collapse ---

---
title: 数の比較条件がうまくいかない
---

`>`{:class="block3operators"} (より大きい) 演算子と `<`{:class="block3operators"} (より小さい) 演算子を正しく使用しましたか?

```blocks3
<(健康) > (0)> // health変数は0より大きくなければいけません
<(健康) < (5)> // health変数は5より小さくなければいけません
```

**ヒント:** 大きくなければならない数値は、演算子記号の幅の広い (大きい) 側に配置されます。

--- /collapse ---

--- collapse ---

---
title: メッセージを送っても何も起こらない
---

メッセージを`broadcast`{:class="block3events"} したときに何かを行う `when I receive`{:class="block3events"} ブロックをがあることを確認してください。 メッセージ名が一致していることを確認してください。

--- /collapse ---

ここに記載されていないバグが見つかるかもしれません。 あなたはそれを修正する方法を見つけることができますか？

行き詰まった場合は、コードを声に出して読むか、友人に問題を説明してみてください。 問題が見つかるかもしれません。

私たちはあなたのバグと、あなたがそれらをどのように修正したかについて教えてほしいです。 プロジェクトで別のバグを見つけた場合、このページの一番下にあるフィードバックを送信 ボタンを使ってお知らせください。

--- /task ---


--- save ---

