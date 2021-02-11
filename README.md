# nav
效果预览：
<a>https://woshidw.github.io/nav/dist/index.html</a>


# 开发

```
yarn global add parcel-bundler

parcel src/index.html

```

# build 命令

```
yarn build
```

## 如何一键build

1. 创建一个package.json

```
yarn init -y
```

2. 我在package.json最上面里添加一个脚本

```
{
  "scripts": {
    "build": "rm -rf dist && parcel build src/index.html --no-minify --public-url ./"
  },
```
