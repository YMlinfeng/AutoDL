# AutoDL
解决AotoDL的ssh总是在windows系统下抽风的补丁

由于 GitHub 限制上传超过 100MB 的文件，`AutoDL.exe` 已通过百度网盘分享：

- 📦 **下载链接**：[点击下载 AutoDL.exe](https://pan.baidu.com/s/1-B3kkUEDq89eOa6CMUi08g?pwd=1209)
- 🔐 **提取码**：`1209`


# 用法



## 设置 HTTP/HTTPS 代理

打开 PowerShell 或 CMD，执行：
```bash

git config --global http.proxy http://127.0.0.1:7890

git config --global https.proxy http://127.0.0.1:7890

```

## 设置 SOCKS5 代理（如 V2rayN）

```bash

git config --global http.proxy socks5://127.0.0.1:10808

git config --global https.proxy socks5://127.0.0.1:10808

```

> 📌 注意：请根据你实际代理端口修改 `7890` 或 `10808`

## 重试克隆仓库

```bash

git clone https://github.com/YMlinfeng/AutoDL.git

```

## 可选：克隆完成后取消代理配置

（防止影响其他网络）

```bash

git config --global --unset http.proxy

git config --global --unset https.proxy

```