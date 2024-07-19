# 免费节点：https://github.com/Zsfan1224/FreeProxy/tree/main
# Cloudflare Pages

<p align="center">
  <img src="" alt="edgetunnel" style="margin-bottom: -50px;">
</p>

GitHub 存储库 [https://github.com/Zsfan1224/Cloudflare-Pages-Proxy](https://github.com/Zsfan1224/Cloudflare-Pages-Proxy)

[![Repository](https://img.shields.io/badge/View%20on-GitHub-blue.svg)](https://github.com/Zsfan1224/Cloudflare-Pages-Proxy)

## 变量解释

| Branch Name   | Description                                                   |
| ------------- | ------------------------------------------------------------- |
| remote-socks5 | Branch for remote SOCKS5 proxy pool used implementation       |
| socks5        | Branch for SOCKS5 proxyIP implementation                      |
| vless         | Branch for outbound VLESS protocol implementation             |
| vless2        | Branch for alternative outbound VLESS protocol implementation |
| code1         | Branch for code1 feature development                          |
| code2         | Branch for code2 alternative feature development              |
| dns           | Branch for DNS alternative related development                |
| main          | Main branch for the project                                   |
| pages         | New version for deployment on Cloudflare Pages                |

## UUID Setting (Optional)

1. When deploy in cloudflare pages, you can set uuid in `wrangler.toml` file. variable name is `UUID`. `wrangler.toml` file is also supported. (recommended) in case deploy in webpages, you can not set uuid in `wrangler.toml` file.

2. When deploy in worker.dev, you can set uuid in `_worker.js` file. variable name is `userID`. `wrangler.toml` file is also supported. (recommended) in case deploy in webpages, you can not set uuid in `wrangler.toml` file. in this case, you can also set uuid in `UUID` enviroment variable.

Note: `UUID` is the uuid you want to set. pages.dev and worker.dev all of them method supported, but depend on your deploy method.

## Usage

frist, open your pages.dev domain `https://zsfan-cloudflare-pages.pages.dev` in your browser, then you can see the following page:
The path `/uuid your seetting` to get the clash config and vless:// link.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Zsfan1224/Cloudflare-Pages-Proxy&type=Timeline)](https://star-history.com/#Zsfan1224/Cloudflare-Pages-Proxy&Timeline)
