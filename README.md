# aliyun-ddns-shell
Dynamic public network ip binding Alibaba Cloud domain name
- 当前只支持阿里云域名
- 支持IPV6解析（支持设置解析记录类型：A、NS、MX、TXT、CNAME、SRV、AAAA、CAA、REDIRECT_URL、FORWARD_URL）
- - 需要通过阿里云域名解析Api操作，所以需要申请阿里云的Acesskeys
    - 登录阿里云 控制台 https://account.aliyun.com/login/login.htm
    - 新建子账号（随你，用主账号也行）https://ram.console.aliyun.com/users
    - 创建新的AccessKey https://ram.console.aliyun.com/users/domian
    - 给子账号授权：权限管理-个人权限 权限策略名称：AliyunDNSFullAccess

