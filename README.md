# LegendSock Server
自动安装基于 ShadowsocksR 所修改的 LegendSock 服务端。

配合 LegendSock 可实现自定义加密方式、混淆插件、协议插件等功能。

原版 ShadowsocksR 请查阅: https://github.com/breakwa11/shadowsocks/tree/manyuser

相应的 Shell Script 内容使用 lnmp.org 改写，在此感谢两位作者的无私奉献。

# 注意事项
当前脚本`仅支持 CentOS 6.x 系统`，若需要其他环境、请从当前 Github 下载后手动安装。

# 安装方法
在 Terminal 中执行如下命令:
```
wget -O /tmp/install.sh https://www.legendsock.com/box/server/install.txt;
chmod +x /tmp/install.sh;
/tmp/install.sh;
```
执行后按照提示输入相应的信息完成安装即可。

# 卸载方法
在 Terminal 中执行如下命令:
```
wget -O /tmp/uninstall.sh https://www.legendsock.com/box/server/uninstall.txt;
chmod +x /tmp/uninstall.sh;
/tmp/uninstall.sh;
```
执行后按照提示输入相应的信息完成安装即可。

# 使用方法
在 Terminal 中可选执行如下命令:
```
legendsock start     # 启动
legendsock stop      # 停止
legendsock restart   # 重启
legendsock status    # 状态
```
若使用相应的命令出现报错，请检查是否已成功安装 LegendSock 服务端。

# 软件网址
合作站点: https://neworld.org
官方网址: https://www.legendsock.com