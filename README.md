# halo-plugin-project

> 📃 计划: 开源项目
> 
> 🕒 当前阶段：未开始

project插件用于在站点展示开源或推荐的开源项目列表，类似github的pin功能。

## 📁 TODO

- [ ] 开源列表的基础增删改查
- [ ] 为前台提供`project`路由
- [ ] 添加Github、Gitlab开源项目
- [ ] 项目链接至某个文章

## 💻 开发环境

插件开发的详细文档请查阅：<https://docs.halo.run/developer-guide/plugin/hello-world>

```bash
git clone git@github.com:justice2001/halo-plugin-project

# 或者当你 fork 之后

git clone git@github.com:{your_github_id}/plugin-starter.git
```

```bash
cd path/to/plugin-starter
```

```bash
# macOS / Linux
./gradlew pnpmInstall

# Windows
./gradlew.bat pnpmInstall
```

```bash
# macOS / Linux
./gradlew build

# Windows
./gradlew.bat build
```

修改 Halo 配置文件：

```yaml
halo:
  plugin:
    runtime-mode: development
    fixedPluginPath:
      - "/path/to/plugin-starter"
```

## 📖 开源

仓库镜像自个人Gitlab，各个开源仓库的同步进度可能不一致

[Github](https://github.com/justice2001/halo-plugin-project)