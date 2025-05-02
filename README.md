# Renovate 配置

Zotero 中文社区关于 Renovate Bot 的可共享配置预设。

## 用法

在 `renovate.json5` 文件中：

```jsonc
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["local>zotero-chinese/renovate-config"],

  // 在此处覆盖配置
  "automerge": false
}
```

## 参考

[Renovate 文档](https://docs.renovatebot.com/config-presets/#grouporganization-level-presets)
