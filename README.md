# Asus-device-discover
New device notifer to telegram from asus router


You can remove while-true cycle and sleep inside and use cron instead with stock fw.

```shell
cru a discover "*/5 * * * * /tmp/home/root/device_discover"
```


Inspired by https://github.com/r0ck3r/device_discover
