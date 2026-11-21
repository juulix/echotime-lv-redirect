# echotime.lv → www.echotime.app

GitHub Pages repo whose only job is to send every echotime.lv / www.echotime.lv address
(path, query and hash kept) to https://www.echotime.app — the real Echo Time site (repo juulix/echotime-site).
`index.html` and `404.html` are identical client-side redirects; canonical points to www.echotime.app.

DNS for echotime.lv is edited in the NIC.LV client system (nic.lv → Mani domēna vārdi → echotime.lv):
- A @ → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- CNAME www → juulix.github.io.
