# メタデータ

Hokusai API では、NFT を Mint する際に、`tokenUri` と呼ばれるものを渡す必要があります。
`tokenUri` とは、アプリケーションが NFT の情報を表示するための、メタデータを含む URI のことです。
この章では、メタデータの仕様について説明します。

メタデータは JSON 形式で記述されます。
以下はメタデータの例です。
```json
{
  "name": "Hokusai Logo",
  "description": "Cool Hokusai Logo", 
  "image": "https://docs.hokusai.app/img/hokusai.png", 
}
```

また、メタデータは以下のようなプロパティを含めることができます。

|プロパティ|説明|
|--|--|
|name|NFT の名前です。その NFT 固有の名前を付けます。|
|image|NFT の画像URLです。PNG や JPG 等の基本的な画像フォーマットに対応しています。|
|description|NFT の説明です。|

## 参考
- [Metadata Standards | OpenSea](https://docs.opensea.io/docs/metadata-standards)