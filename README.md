### 分流规则

#### 命名规范

- `loon/*.list`：手动维护的 Loon 规则。
- `loon/auto-*.list`：GitHub Action 自动合并生成的 Loon 规则。
- `rules/*-source.txt`：自动合并任务使用的远程规则源列表。
- `.github/workflows/build-*.yml`：自动合并任务配置。

#### 文件约定

- `loon/AI.list`：手动维护的 AI 规则。
- `loon/mc.list`：手动维护的 MC 规则。
- `loon/dev-direct.list`：手动维护的直连规则。
- `loon/auto-ai-proxy.list`：AI 自动合并任务输出的代理规则。
- `loon/auto-mc-proxy.list`：MC 自动合并任务输出的代理规则。
