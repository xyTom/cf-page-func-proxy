# cf-page-func-proxy
Use Cloudflare Pages Functions as a reverse proxy with custom domain support.

## Getting Start
1.下载或是Fork本仓库

2.修改`_worker.js`中的`url.hostname`为你需要反代的网址
https://github.com/xyTom/cf-page-func-proxy/blob/291f504f9be4a65d2daa39a954a41bd8088561f3/_worker.js#L5

3.打开Cloudflare Dashboard，进入Pages管理页面，选择创建项目，如果在第一步中选择的是fork本仓库，则选择1`Connect to Git`，如果第一步中选择的是下载本仓库则选择2`Direct Upload`



# 绑定自定义域名