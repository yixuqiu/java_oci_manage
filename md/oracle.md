### 甲骨文云获取API参数
```text
【操作导航，任意一种均可】
- 1.甲骨文后台=>用户设置>>资源>>API秘钥>>添加API秘钥->(在指纹右侧三个点处查看参数)

- 2.如没有用户设置的请直接搜用户(切中文语言) 点击选择某个用户名 API秘钥>>添加API秘钥->(在指纹右侧三个点处查看参数)

- 3.不会搜的点击左边菜单一栏 找到身份和安全=>用户=>点击选择某个用户名=>API秘钥>>添加API秘钥）->(在指纹右侧三个点处查看参数)
- 说明∶此处配置是连接甲骨文云接口的所必须参数

格式大致如下↓
[DEFAULT]
user=ocid1.user.oc1..aaaaaaaaxxxxgwlg3xuzwgsaazxtzbozqq
fingerprint=b8:33:6f:xxxx:45:43:33
tenancy=ocid1.tenancy.oc1..aaaaaaaaxxx7x7h4ya
region=ap-singapore-1
key_file=记得写你的密钥文件路径
```
- 将在甲骨文用户设置添加api密钥的配置文件预览里面的参数 放入到client_config配置文件内(请注意 key_file的私钥位置要正确，【私钥文件】在你添加api的时候生成下载或上传的，然后放入你想放的位置，如：key_file=/root/oci/oci_api_key.pem)
- ![image](https://github.com/semicons/java_oci_manage/blob/main/1646021119866.jpg)