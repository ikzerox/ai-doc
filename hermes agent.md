# Hermes Agent - MAC版

## 命令

```bash

# 重启 Hermes Gateway
hermes gateway restart

# 查看 Hermes Gateway 状态
hermes status

# 升级命令
hermes update

```

## web工具
```bash
# 更新
npm install -g hermes-web-ui@latest \                                                                         
  --registry=https://registry.npmjs.org/ \
  --proxy=http://127.0.0.1:7897 \
  --https-proxy=http://127.0.0.1:7897

# 重启
hermes-web-ui restart


```