# Yannis Scripts

个人代理工具脚本集合。

---

## Ecosia Search Redirect

Safari 默认搜索引擎设置为 Ecosia 时的搜索重定向脚本。

**规则：**
- 搜索词以 `dd` 开头 → 跳转 DuckDuckGo
- 其余搜索 → 跳转 Google

**使用前提：** 需要在代理工具中开启 MITM，并信任证书。

### 一键安装

| 工具 | 安装链接 |
|------|----------|
| Quantumult X | [点击安装](https://quantumult.app/x/open-app/add-resource?remote-resource=%7B%22rewrite_remote%22%3A%20%5B%22https%3A//github.com/CHEN1016/yannis_scripts/raw/refs/heads/main/QuantumultX/ecosia-search-redirect.conf%2C%20tag%3Decosia-search-redirect%22%5D%7D) |
| Egern | [点击安装](https://egernapp.com/modules/new?url=https://raw.githubusercontent.com/CHEN1016/yannis_scripts/refs/heads/main/egern/ecosia-search-redirect.yaml&name=ecosia-search-redirect) |
| Loon | [点击安装](https://www.nsloon.com/openloon/import?plugin=https%3A%2F%2Fraw.githubusercontent.com%2FCHEN1016%2Fyannis_scripts%2Frefs%2Fheads%2Fmain%2Floon%2Fecosia-search-redirect.plugin) |

### 手动安装

| 工具 | 文件 |
|------|------|
| Quantumult X | [ecosia-search-redirect.conf](QuantumultX/ecosia-search-redirect.conf) |
| Egern | [ecosia-search-redirect.yaml](egern/ecosia-search-redirect.yaml) |
| Loon | [ecosia-search-redirect.plugin](loon/ecosia-search-redirect.plugin) |
