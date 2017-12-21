# 第1章 Node.jsと環境の設定

## ESLintの設定（ルートディレクトリ）

p.46のJS標準スタイル（JavaScript Standard Style）に合わせて、ESLintの設定を済ませておく。

コマンド：

```bash
$ cd node-react-book  # このリポジトリ
$ npm init
$ npm i -D eslint-config-standard eslint-plugin-standard eslint-plugin-promise eslint-plugin-import eslint-plugin-node

```

`.eslintrc`に次を追加：

```json
{
  "extends": "standard"
}
```

このとき、VS Codeのユーザー設定にeslint.optionsが設定されていると、そっちが優先されるので注意。

## p.33

```bash
$ npm i request
$ node request-downloadfile.js
```

## p.38

- `colors`パッケージ面白い。端末テキストに色を付けてくれる。
- `npm run start`は`npm run`でもいける。
- `npm run`で実行できるコマンドの一覧を表示