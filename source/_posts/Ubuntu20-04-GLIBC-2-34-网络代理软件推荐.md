---
title: Ubuntu20.04(GLIBC < 2.34)网络代理软件推荐
date: 2026-05-09 16:38:59
categories:
  - Linux
tags:
  - Ubuntu
  - Proxy
  - Mihomo
  - GLIBC
---
- Q：目前Ubuntu很多代理软件，为什么推荐Mihomo？
- A：原因有两点：
    - 第一点：本人现在使用的梯子是支持Hysteria2 / Vless Reality，很多客户端不支持这个协议，而且本人之前使用的代理软件V2rayn和NekoRay都会漏掉许多节点。
    - 第二点：本人使用的ubuntu版本较老（GLIBC < 2.34），现在很多支持Hysteria2 / Vless Reality协议的代理软件，如Hiddify，Fclash等都没办法安装。
- 亲测使用Mihomo最方便，而且机场节点一个不漏
- 以下是整理的 **Ubuntu20.04(GLIBC < 2.34)网络代理软件推荐笔记**，适合作为开发者文档长期保存。
---
# 🚀 Ubuntu 下 Mihomo配置笔记

## 1. 环境背景

* **系统版本**: Ubuntu (GLIBC < 2.34)，如果GLIBC > 2.34有很多软件选择，如Hiddify，Fclash等
* **核心选择**: Mihomo (原 Clash Meta) - 兼容性强，支持 Hysteria2/Vless Reality。

## 2. 核心程序准备
为了规避系统依赖库（GLIBC）版本过低的问题，采用 **gz 压缩包形式** 的静态编译版，不使用 `.deb` 安装包。
[Github链接](https://github.com/MetaCubeX/mihomo/releases/tag/v1.19.24)，
[gz 压缩包下载链接](https://github.com/MetaCubeX/mihomo/releases/download/v1.19.24/mihomo-linux-amd64-v1.19.24.gz)
```bash
# 1. 解压下载的 gz 包
gunzip mihomo-linux-amd64-v1.19.24.gz

# 2. 重命名为简洁的名称
mv mihomo-linux-amd64-v1.19.24 mihomo

# 3. 赋予可执行权限
chmod +x mihomo

```

## 3. 获取配置文件 (YAML)

利用 `curl` 模拟 Clash 客户端请求头，确保从机场订阅链接获取的是正确的 YAML 格式，并开启 Meta 协议支持。

```bash
# 替换为你的订阅链接，注意末尾的 ?flag=meta
curl -L -A "clash-verge/1.0" -o config.yaml "https:xxxxxx这里填你的订阅链接xxxxxxxx"

```
**这一步完成后直接跳到第五步，后续执行有问题才看第四步**
## 4. 关键配置修改

通过 `nano config.yaml` 修改以下核心参数，解决端口冲突并启用控制台。

* **API 控制端口**: 将 `external-controller` 从 `9090` 改为 `9091`（避开 占用端口）。
* **混合代理端口**: 确认 `mixed-port` 为 `7890`（用于系统代理连接）。

## 5. 启动与控制

### 后端启动

```bash
./mihomo -f config.yaml

```
### 前端控制台

访问网页版控制面板进行节点切换和测速：

* **访问面板**: [\[http://clash.razord.top/\](https://www.google.com/search?q=http://clash.razord.top/) (HTTP 版，无拦截风险)](https://metacubex.github.io/metacubexd/)
* **后端地址**: `http://127.0.0.1:9090`
* **密钥**: 默认为空
* 访问进去后选择节点再去第6步配置
* 如果这一步访问不进去，说明是端口被占用了，看第四步解决方案，然后在[访问面板](https://metacubex.github.io/metacubexd/)的后端地址输入你修改的端口号
## 6. 系统流量接管

在 **Ubuntu 系统设置 -> 网络 -> 网络代理** 中配置：

* **方法**: 手动 (Manual)
* **HTTP/HTTPS/Socks**: `127.0.0.1`
* **端口**: `7890`

---
