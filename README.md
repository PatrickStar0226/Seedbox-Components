# 本项目FORK自杰大项目,感谢杰大!

暂时只做了我个人需要修改的部分,修改内容如下:
- 去除Deluge和autoremove-torrents 相关设置
   - 现在使用Vertex + qBittorrent,感觉更方便. 感谢栗佬!

- 更改qb默认配置
  1. 修改webui端口 
  2. 修改连接端口
  3. 使qb默认分配空间关闭
  4. 默认关闭CSRF保护,方便vt直接访问
  5. 默认关闭trackers的https校验,防止tarckers连接问题


# Seedbox-Install-Components
Components used for Seedbox Installation Script
- https://github.com/jerry048/Dedicated-Seedbox
- https://github.com/jerry048/Shared-Seedbox

## Credit
qBittorrent Install - https://github.com/userdocs/qbittorrent-nox-static

qBittorrent Password Set - https://github.com/KozakaiAya/libqbpasswd & https://amefs.net/archives/2027.html

Deluge Password Set - https://github.com/amefs/quickbox-lite

autoremove-torrents - https://github.com/jerrymakesjelly/autoremove-torrents

BBR Install - https://github.com/KozakaiAya/TCP_BBR
