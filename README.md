# AWS Step Functions サンプル

AWS Step Functionsを使用したステートマシンのサンプルプロジェクトです。

## プロジェクト構造

```
sample-step-functions/
├── statemachines/
│   └── hello-world.asl.json    # Hello Worldステートマシン
└── README.md
```

## ステートマシンの説明

### Hello Worldステートマシン

シンプルなPassステートを使用したHello Worldの例です。

#### ステートマシンの構成

- 開始状態: `Pass`
- 終了状態: `Pass`
- 出力: `{"result": "Hello"}`

#### 実行結果

```json
{
  "result": "Hello"
}
```

## 使用方法

1. AWS Step Functionsコンソールにアクセス
2. ステートマシンの作成を選択
3. `hello-world.asl.json`の内容をコピーして貼り付け
4. ステートマシンを実行

## 開発環境のセットアップ

1. AWS CLIのインストール
2. AWS認証情報の設定
3. AWS Step Functionsのアクセス権限の確認

## 注意事項

- このサンプルは基本的なPassステートの使用例です
- 実際のユースケースに応じて、より複雑なステートマシンを構築できます
- コスト最適化のため、不要なステートマシンは削除することをお勧めします 