---
title: Common
permalink: /
---

## User management

### Remove user password

```shell
sudo passwd -d USERNAME
```

## Network

### Check a port

```shell
netstat -an | grep PORT_NUMBER
```

```shell
lsof -i :PORT_NUMBER
```
