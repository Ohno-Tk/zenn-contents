# Developing

* [Branch Name Guidelines](#branch)
* [Commit Message Guidelines](#commits)

## <a name="branch"></a>Branch Name Guidelines
Branch名に対するルールになります。

```
<Issue Number>-<Type>
```

### Issue Number
* コミットに紐づくIssue番号を記載します  
  リンクになってトラッキングしやすいため
* Issueを作ってないケースは省略可
* Issueがあると、修正意図などが理解しやすいのでIssuesを作成することを強く推奨します

### Type
次のいずれかである必要があります。

* feat: 新機能
* fix: バグ修正
* docs: ドキュメントのみの修正
* style: コードの意味に影響を与えない変更(空白、書式変更など)
* refactor: バグの修正も機能の追加も行わないコード変更
* perf: パフォーマンスを向上させるコード変更
* test: 不足しているテストを追加または既存のテストの修正
* chore: ビルドプロセスや補助ツール、ドキュメントなどのライブラリへの変更

## <a name="commits"></a>Commit Message Guidelines
gitのコミットメッセージのフォーマットに対するルールになります。  
プロジェクト履歴を確認する時に分かりやすい読みやすいメッセージを書きましょう。

```
<Type>: <Subject>(Issue Number)
```

### Type
[Branch Name Guidelines](#branch)を参照

### Subject
* 変更の簡潔な説明を書きます
* 20～30文字以内で記載する

### Issue Number
[Branch Name Guidelines](#branch)を参照