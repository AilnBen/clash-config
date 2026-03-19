# clash-config

每日自动更新的 Clash 订阅配置，其中 `freecloud` 机场节点每天自动从 [free-nodes/clashfree](https://github.com/free-nodes/clashfree) 获取最新节点。

## 订阅链接

**PR 合并前（立即可用）：**

```
https://raw.githubusercontent.com/AilnBen/clash-config/copilot/automate-daily-node-update/config.yaml
```

**PR 合并到 main 后（长期稳定链接）：**

```
https://raw.githubusercontent.com/AilnBen/clash-config/main/config.yaml
```

**PR 国内加速链接（长期稳定链接）：**

```
https://cdn.jsdelivr.net/gh/AilnBen/clash-config@main/config.yaml
```

## 自动更新说明

- GitHub Actions 每天北京时间 14:00（UTC 06:00）自动运行
- 自动将 `freecloud` 的节点链接更新为当天最新版本
- 更新后自动提交到本仓库，订阅链接内容随之刷新
