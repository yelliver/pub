---
title: Common
permalink: /
---

## Network

### Check a port

```shell
netstat -an | grep PORT_NUMBER
```

```shell
lsof -i :PORT_NUMBER
```

## User management

### Remove user password

```shell
sudo passwd -d USERNAME
```
