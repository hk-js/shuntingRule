### 分流规则

#### 命名规范

- `loon/manual/*.list`：手动维护的 Loon 规则。
- `loon/generated/*.list`：GitHub Action 自动合并生成的 Loon 规则。
- `rules/sources/*-source.txt`：自动合并任务使用的远程规则源列表。
- `.github/workflows/build-*.yml`：自动合并任务配置。

#### 文件约定

- `loon/manual/ai.list`：手动维护的 AI 规则。
- `loon/manual/mc.list`：手动维护的 MC 规则。
- `loon/manual/dev-direct.list`：手动维护的直连规则。
- `loon/generated/ai-proxy.list`：AI 自动合并任务输出的代理规则。
- `loon/generated/mc-proxy.list`：MC 自动合并任务输出的代理规则。
