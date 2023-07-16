检查配置语法是否正确
1 修改了nginx配置文件需要检查配置是否正确，
nginx -tc /etc/nginx/nginx.conf
-> nginx: the configuration file /etc/nginx/nginx.conf syntax is ok
-> nginx: configuration file /etc/nginx/nginx.conf test is successful
2 关闭原来的配置
nginx -s stop -c /etc/nginx/nginx.conf
3 重启nginx配置
nginx -c /etc/nginx/nginx.conf

# 在线服务
ssh root@47.98.181.79
访问地址 wenlong.live:6006 # react-ts-comp 文档storybook
访问地址 wenlong.live:6007 # web3： build-puffgo-web

查看日志
tail -f /var/log/nginx/error.log
 ssh root@47.98.181.79  zwl@157351
查看本机ip
浏览器中输入 www.ip138.com
您的iP地址是：[103.75.152.102] 来自：中国北京海淀 电信&联通&移动

yum-config-manager --add-repo http://mirrors.aliyun.com/docker-ce/linux/centos/docker-ce.repo


https://link.juejin.cn/?target=https%3A%2F%2Flink.zhihu.com%2F%3Ftarget%3Dhttp%253A%2F%2Fmirrors.aliyun.com%2Fdocker-ce%2Flinux%2Fcentos%2Fdocker-ce.repo
nginx完整语法查看官网 https://nginx.org/en/docs/  页面搜索关键词 auth_basic



systemctl
监视和控制systemd 的主要命令是 systemctl
该命令可用于查看系统状态和管理系统及服务
- 启动 systemctl start nginx.servie
- 停止 systemctl stop nginx.servie
- 重启 systemctl restart nginx.servie
- 状态 systemctl status nginx.servie
- 重新加载 systemctl reload nginx.servie

每次对nginx配置文件变更后，都需要重启nginx
第一种方式
nginx -s reload
第二种方式 ： 表示执行上一次命令
!! 
第三种方式 ： 通过history 查看命令序列号 表示执行上一次命令
!28


修改文件执行权限
chmod -R 777 /data

nginx 安装指南 https://zhuanlan.zhihu.com/p/378409850

安装中难点解决
  https://stackoverflow.com/questions/11213520/yum-crashed-with-keyboard-interrupt-error