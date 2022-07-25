# プロジェクト作成

```
yarn create next-app auth0-front --ts -e with-tailwindcss
```

# Auth0 SDK install

```
yarn add @auth0/auth0-react
```

# localhost のポート番号変更（バックエンドと被るため）

package.json

```
"scripts": {
  "dev": "next dev -p 8000"
}
```

# React の Store、Recoil の導入

```
yarn add recoil
```
