# nonebot.dev
简单方便的自建 " Nonebot 文档 "  
Nonebot docs alias for Koishi Document

> [!NOTE]
> \* Currently, no public deploy supported
> \* 暂不支持公共部署

## Requirements | 要求
- caddy  

80 and 443 ports availiable  
80 和 443 端口未被占用

### TLS Support | TLS 支持
See <https://caddyserver.com/docs/command-line#caddy-trust>

## Quick Start

### Clone

#### git
```sh
git clone [https://](https://github.com/CyanChanges/nonebot.dev)https://github.com/CyanChanges/nonebot.dev
```
#### GitHub CLI
```sh
gh repo clone CyanChanges/nonebot.dev
```

### Run Server | 启动!

```sh
cd nonebot.dev
caddy start -c Caddyfile
```

### Modify Hosts | 修改 Hosts 文件

#### Linux

SH:
```sh
sudo echo "127.0.0.1  nonebot.dev" >> /etc/hosts
```

Nushell:
```nu
echo "127.0.0.1  nonebot.dev" | save -a /etc/hosts
```


#### Microsoft Windows | M$ 视窗
Open `C:\Windows\System32\drivers\etc\hosts`
with your favourite editor (`nodepad`, `code`, `nvim`, etc.) as Administrator  

用你喜欢的编辑器
打开 `C:\Windows\System32\drivers\etc\hosts` (需要以管理员权限运行)

Add following line at the end of the hosts file  
加入以下内容到文件结尾
```hosts
127.0.0.1  nonebot.dev
```
