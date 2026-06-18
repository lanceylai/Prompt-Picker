# Prompt Picker

**Language:** [English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | 日本語 | [한국어](README.ko.md)

Prompt Picker は、プロダクトマネージャーとエンジニアがページ上で変更が必要な内容を、AI コーディング向けの明確で実行可能なプロンプトに変換するための Chrome 拡張機能です。

「カード右側のボタン」のような曖昧な説明ではなく、ページ上の要素を直接クリックし、変更内容を書き、Claude Code、Codex、Cursor などに貼り付けられる構造化プロンプトをコピーできます。

[Chrome Web Store から Prompt Picker をインストール](https://chromewebstore.google.com/detail/prompt-picker/lgcmgmlbomeodhmikhiphmonogmfdeeg)

## できること

Prompt Picker では次のことができます。

1. 変更が必要な要素を選択：ページ上で対象要素を直接選択し、変更したい内容を説明できます。
2. コンテキスト付き Prompt を自動生成：Selector、DOM 構造、コンポーネント情報、ページコンテキストを含む AI Prompt を生成できます。
3. AI による変更の成功率を高める：AI Agent が対応するコードを素早く見つけられるようにし、やり取りを減らして変更の精度を高めます。

![Prompt Picker でページ上の要素を直接選択する](assets/guide_1.png)

![変更指示を書いて生成されたプロンプトをコピーする](assets/guide_2.png)

## 対象ユーザー

**プロダクトマネージャー**

UI の変更点や改善提案を、スクリーンショットだけに頼らず、より具体的に伝えたいときに使えます。

**エンジニア**

AI コーディングツールに「どの要素を変更するのか」を正確に伝えたいときに使えます。

## よくある使い方

- 正確な UI コンテキスト付きでプロダクトフィードバックを作成する。
- AI Agent にボタン、カード、メニュー、フォーム、セクションの変更を依頼する。
- プロダクトレビュー中に修正依頼をすばやく記録する。
- 「ここが少し違う」という感覚を実行しやすいタスクに変える。
- 複数ページにまたがるフローの修正点を集める。

## 使い方

1. Chrome Web Store から Prompt Picker をインストールします。
2. レビューしたい Web ページを開きます。
3. ブラウザの Prompt Picker アイコンをクリックします。ショートカットも使えます。Mac は `Option + Q`、Windows は `Alt + Q` です。
4. 要素をクリックするか、ドラッグして複数選択します。
5. 変更指示を書きます。
6. **Pick & Copy** をクリックします。
7. コピーされたプロンプトを AI コーディングツールに貼り付けます。

## なぜ役に立つのか

AI コーディングツールは、正確なコンテキストがあるほど期待通りに動きやすくなります。Prompt Picker は次の情報をプロンプトに含めます。

- 選択したページ要素。
- 役に立つ DOM と selector の情報。
- 周辺のテキストと構造。
- あなたの変更指示。

これにより、プロダクトと開発のやり取りを減らし、AI Agent がより的確にコードを変更しやすくなります。

## プライバシー

Prompt Picker はブラウザ内で動作します。選択したページコンテキストを収集し、クリップボードにコピーします。どこに貼り付けるかはユーザーが決められます。

## インストール

[Chrome Web Store から Prompt Picker をインストール](https://chromewebstore.google.com/detail/prompt-picker/lgcmgmlbomeodhmikhiphmonogmfdeeg)
