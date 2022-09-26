# Function_Sample
## 前提条件
- Azure CLIの[インストール](https://learn.microsoft.com/ja-jp/cli/azure/install-azure-cli)
- Azure Functons Core Tools のインストール（[CoreToolsのReadme](https://github.com/Azure/azure-functions-core-tools/blob/v4.x/README.md#windows)）

    ↓バージョン3をインストールする場合(グローバル)

    ```
    npm install -g azure-functions-core-tools@3 --unsafe-perm true
    ``` 

## プロジェクトを作成する
- [自分で作成する場合](./makeproject.md)
- このリポジトリをクローンする場合
    ```
    git clone https://github.com/takatoshiinaoka/function_sample.git
    ```

## 動作確認
```
yarn install
yarn start
```

- [http://localhost:7071/api/MyHttpTrigger ](http://localhost:7071/api/MyHttpTrigger)にアクセスすると、  
```This HTTP triggered function executed successfully.```と表示されます。
- [http://localhost:7071/api/MyHttpTrigger?name=World ](http://localhost:7071/api/MyHttpTrigger?name=World)にアクセスすると、  
```Hello, World. This HTTP triggered function executed successfully.```と表示されます。

> ```Ctrl``` + ```C```でサーバーを停止します。
