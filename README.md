

* 复制`oilprice`文件夹到HA配置目录下的`custom_components`文件夹

* 在`/config/configuration.yaml`添加如下内容

```yaml
sensor:
  - platform: oilprice
    name: 当地油价
    region: anhui  # 此处为你要获取油价的省份全拼
```
* 重启 HA
