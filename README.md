# GBF Nginx 反代加速

## 使用方法

- 创建 2 个目录 ``/cache/gbf`` 及 ``/cache/temp``。

- 下载对应的配置文件到 ``/etc/nginx/conf.d`` 目录下，编译安装的 Nginx 请自行修改配置文件配置。

- ```bash
  nginx -t
  nginx -s reload
  ```

- 修改 hosts 将 IP 指向这个机器，可参考示例文件。

