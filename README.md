# よくないね。

[![GitHub release](https://img.shields.io/github/release/mzyy94/yokunaine.svg?maxAge=259200&style=flat-square)](https://github.com/mzyy94/yokunaine/releases)
[![Chrome web store release](https://img.shields.io/chrome-web-store/v/fceocghaogpidgglkglhdadcaechdeln.svg?style=flat-square)](https://chrome.google.com/webstore/detail/fceocghaogpidgglkglhdadcaechdeln)
[![Chrome web store downloads](https://img.shields.io/chrome-web-store/d/fceocghaogpidgglkglhdadcaechdeln.svg?style=flat-square)](https://chrome.google.com/webstore/detail/fceocghaogpidgglkglhdadcaechdeln)
[![GitHub stars](https://img.shields.io/github/stars/mzyy94/yokunaine.svg?style=flat-square)](https://github.com/mzyy94/yokunaine/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/mzyy94/yokunaine.svg?style=flat-square)](https://github.com/mzyy94/yokunaine/issues)
[![GitHub license](https://img.shields.io/github/license/mzyy94/yokunaine.svg?style=flat-square)](https://github.com/mzyy94/yokunaine/blob/master/LICENSE)
[![JavaScript Style Guide](https://img.shields.io/badge/JS-Standard-000000.svg?style=flat-square&colorA=000000)](https://github.com/feross/standard)

いいね　だけじゃ　だめだよ

![icon](docs/icon.png)

## よくないよね

うん。

## 使い方

1. https://yokunaine.mzyy94.com からChrome拡張機能をダウンロードしてインストール
2. 拡張機能ページ(chrome://extensions)を開く
3. *よくないね。* のオプション画面を開く
4. **Get Token**
5. _👍いいね_

## 開発者向け情報

### Chrome拡張

```
cd chrome-extension
npm i
npm run build
```

### サーバアプリケーション

```
cd server
npm i
export NODE_ENV=development
export client_id=da39a3ee5e6b4b0d3255bfef95601890afd80709
export client_secret=adc83b19e793491b1c6ea0fd8b46cd9f32e592fc
npm start
```

## FAQ

### こんなの作ってよかったの？

よくないね。

### 使ってて大丈夫なの？

よくないね。
OAuthの認証後は[すぐにTokenを破棄](server/index.js#L61-L64)しているから悪用はされないはずだよ。

### よくないねボタンが動かないんだけど

サーバが落ちてるかもね。もしくはすでに「👍いいね」されてるとか。

### ソースコードがきもわるい

[![JavaScript Style Guide](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

## LICENSE

[MIT](LICENSE)
