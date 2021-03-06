# uptimestatus

基于[酷Q状态](https://github.com/CoolQ/Cup) (酷Q状态基于[Upscuits](https://github.com/digibart/upscuits))，以 [UptimeRobot](https://uptimerobot.com/) 为数据源的在线状态统计页面。

**2016-10-06** Uptime Robot 已经新增 Public Status Pages 功能，详见 [官网](https://blog.uptimerobot.com/introducing-public-status-pages-yay/)。

**2019-02-15** Cup 已支持 Uptime Robot APIv2，请尽快更新您的 Cup 版本，Uptime Robot 已停止支持 APIv1。

**2020-05-04** 增加获取最近24h平均响应时间(不会做前端，加了文字后bar行的表格行高始终是17px，干脆给bar高度17px)，bar从左到右递减不变，反转日期排序从左到右递减。

## 使用方法

1. 注册 [UptimeRobot](https://uptimerobot.com/)，获取 [Monitor-Specific / Read-Only API Key(s)](https://uptimerobot.com/dashboard.php#mySettings)
2. 将 `API Keys` 填入 `js/config.js`
3. 修改 `index.html` 内的页面标题等信息
4. 完成！

## 演示

https://xhlgr.github.io/uptimestatus

## License

This work is licensed under [GPLv3](https://github.com/CoolQ/Cup/blob/master/LICENSE).
