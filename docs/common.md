---
title: Common
permalink: /
---

## SSH Key

#### Start the SSH Agent

```shell
eval $(ssh-agent -s)
```

#### List SSH Keys Added to the SSH Agent

```shell
ssh-add -l
```

```shell
ssh-add -L
```

#### Add the Private Key to the SSH Agent

```shell
ssh-add ~/.ssh/id_rsa
```

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
