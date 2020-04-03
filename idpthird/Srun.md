# 2.3.2 深澜 Srun-LDAP

深澜提供标准 LDAP 身份校验模块--Srun-LDAP，只要您使用的是深澜 Srun4000 认证计费系统，无论当前是何种网络架构（传统三层或大二层扁平化）、何种认证模式（PPPoE、Portal、MAC、802.1x）都没有关系，也无需复杂的系统升级，增加该模块即可快速支持 CARSI IDP 端身份校验。

### 安装手册

步骤1：下载深澜LDAP模块安装包Srun-LDAP.bin

步骤2：上传安装包到深澜服务器

步骤3：执行命令1:【chmod +x Srun-LDAP.bin】

步骤4：执行命令2:【./Srun-LDAP.bin】

步骤5：输入y，完成安装启动

### Readme
MD5sum:e93ecee8377fb2c3e29d663e1dbb67ec

LDAP Configure Path: /srun3/etc/srun-ldap.conf

Service Restart Command: /srun3/bin/server_ldap restart


