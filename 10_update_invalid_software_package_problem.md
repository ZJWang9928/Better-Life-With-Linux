# Update Invalid Software Package Problem

Manjaro更新报错-无效或已损坏的软件包(PGP 签名)    

原因：使用了社区源且开启了验证，关闭验证即可  
  
        vim /etc/pacman.conf

找到社区源相关部分
        [archlinuxcn]
        #SigLevel = Optional TrustedOnly
        SigLevel = Optional TrustAll
        Server = http://repo.archlinuxcn.org/$arch
