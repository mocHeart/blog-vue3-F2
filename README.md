## 1. 项目构建

### 1.1 Vite构建项目

```shell
C:\home\Code>pnpm create vite
.../190da3fe51a-2508                     |   +1 +
.../190da3fe51a-2508                     | Progress: resolved 1, reused 0, downloaded 1, added 1, done
√ Project name: ... blog-vue3-F2
√ Package name: ... blog
√ Select a framework: » Vue
√ Select a variant: » TypeScript

Scaffolding project in C:\Users\haige\Documents\JYnote\home\Code\blog-vue3-F2...

Done. Now run:

  cd blog-vue3-F2
  pnpm install
  pnpm run dev


C:\home\Code>cd blog-vue3-F2

C:\home\Code\blog-vue3-F2>pnpm install
Packages: +48
++++++++++++++++++++++++++++++++++++++++++++++++
Progress: resolved 86, reused 32, downloaded 16, added 48, done

dependencies:
+ vue 3.4.33

devDependencies:
+ @vitejs/plugin-vue 5.0.5
+ typescript 5.5.3
+ vite 5.3.4
+ vue-tsc 2.0.28

Done in 28.8s

C:\home\Code\blog-vue3-F2>pnpm run dev

> blog@0.0.0 dev C:\home\Code\blog-vue3-F2
> vite


  VITE v5.3.4  ready in 2181 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h + enter to show help
```


### 1.2 依赖添加

+ 参数说明：

  1）`--save` 等同于 `-S`（默认，保存在package.json文件中），安装包信息将加入到*dependencies*（生产阶段的依赖，也就是项目运行时的依赖，就是程序上线后仍然需要的依赖）；
  2）`--save-dev` 等同于 `-D`，安装包信息将加入到*devDependencies*（开发阶段的依赖，就是我们在开发过程中需要的依赖，只在开发阶段起作用）。

|        依赖名称        | 安装命令                               |
| :--------------------: | -------------------------------------- |
|        SCSS样式        | pnpm i sass                            |

