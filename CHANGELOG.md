## 版本号：v1.6.8 日期：2019-10-23
### 变更内容
 - 增加：支持上传链接子目录
 - 增加：支持单级目录而非递归目录上传、下载以及copy
 - 增加：支持工具绑定指定ip地址（针对用户多网卡场景）
 - 增加：支持本地循环链接文件或者目录检测
 - 增加：支持并发带宽上传和下载测速
 - 增加：sign命令可以选择将path中的符号/不进行编码
 - 增加：cp命令上传时可以选择不为目录生成object
 - 修复: cp命令的失败重试会导致进度条超过100%
 
## 版本号：v1.6.7 日期：2019-09-17
### 变更内容
 - 修复：使用最新oss go sdk v2.0.3编译,修复无法分块上传归档object的bug
 
## 版本号：v1.6.6 日期：2019-08-06
### 变更内容
 - 增加：支持http/https/socks5代理
 - 增加：增加du、policy、request-payment、object-tagging命令
 - 增加：appendfromfile,cat,symlink,ls,restore,rm,stat支持访问者付费模式
 - 增加：url签名支持http连接限速参数x-oss-traffic-limit
 - 增加：read-symlink支持多版本
 - 增加：修复批量rm objects异常时，错误信息提示错误
 
## 版本号：v1.6.5 日期：2019-07-18
### 变更内容
 - 增加：cherry-pick之前的多版本特性

## 版本号：v1.6.4 日期：2019-07-12
### 变更内容
 - 增加：增加user-qos, bucket-qos命令
 - 增加: 支持利用ecs绑定的角色操作
 - 增加: ls & rm命令支持include、exclude选项
 - 修复: cp命令传输速度统计不准
 - 修复: windows平台配置项长度不能超过256字符
 - 修复: 无法删除key中带有特殊字符的object
 
## 版本号：v1.6.3 日期：2019-06-19
### 变更内容
 - 增加：增加lifecycle, website, cors-options命令

## 版本号：v1.6.2 日期：2019-06-06
### 变更内容
 - 增加：增加多版本versioning特性
 
## 版本号：v1.6.1 日期：2019-05-29
### 变更内容
 - 增加：增加bucket-tagging命令
 - 增加：增加bucket-encryption命令
 - 增加：为下载支持snapshot-path选项
