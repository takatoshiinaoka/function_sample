# Azure Functions の作成
## ローカルにプロジェクトを作成する
```function_sample```という名前のプロジェクトを作成します。
```
func init function_sample
```

## 関数の作成
```MyHttpTrigger``` という名前の ```Http Trigger``` 関数を作成します。
```
func new --template "Http Trigger" --name MyHttpTrigger
```
テンプレート一覧は、```func templates list ``` コマンドで確認できます。

## 動作確認
[READMEに戻る](./README.md#動作確認)