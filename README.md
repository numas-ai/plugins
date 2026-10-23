# plugins

numas 的 OpenCode 插件源码（独立仓库）。

## 约定

- 每个插件一个目录，自带 `README.md`（用途、加载方式、依赖）；
- 插件只通过 OpenCode 的插件接口工作，不改宿主代码；
- 本仓公开可见（public）：不要放令牌、内网地址、私有配置。

## 加载方式

OpenCode 从配置的 `plugins` 目录加载插件；具体路径与入口以各插件 README 为准。
