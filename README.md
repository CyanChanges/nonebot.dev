# nonebot.dev
Nonebot docs alias for Koishi Document

> [!NOTE]
> \* Currently, no public deploy supported

## Requirements
- caddy
local 80 / 443 ports availiable

### TLS Support
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

### Run Server

```sh
cd nonebot.dev
caddy start -c Caddyfile
```

### Change Hosts

#### Linux
```shell
sudo echo "127.0.0.1  nonebot.dev" >> /etc/hosts
```

#### Windows
Open your favourite editor (`nodepad`, `code`, `nvim`)
with `C:\Windows\System32\drivers\etc\hosts`

Add following line at the end of the hosts file
```hosts
127.0.0.1  nonebot.dev
```
