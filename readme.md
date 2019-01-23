# vscode deno starter

解决 `deno` 代码提示和`.ts`后缀名问题

Solve the problems of deno code hints and. TS suffix names

# use

```
git clone https://github.com/iwe7/deno-starter you-project-name
```

# 配置 tsconfig.json 中`deno`路径

> `/Users/imeepos` 是我的路径,替换成自己的

```
"paths": {
    "http://*": ["/Users/imeepos/.deno/deps/http/*"],
    "https://*": ["/Users/imeepos/.deno/deps/https/*"]
}
```

# 问题

> 如果不成功，点击右下角`Typescript`后面的版本号，选择本机

![图片](./dest.jpg)
