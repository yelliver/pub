---
title: Git
parent: Dev
---

### SSH Key

#### Start the SSH Agent

```shell
eval $(ssh-agent -s)
```

#### List SSH Keys

```shell
ssh-add -l
```

```shell
ssh-add -L
```

#### Check SSH Keys

```shell
ls -lh ~/.ssh
```

#### Add the Private Key

```shell
ssh-add ~/.ssh/id_rsa
```

#### Generate a new SSH key

```shell
ssh-keygen -t ed25519 -C EXAMPLE@DOMAIN.COM
```

### Config

#### Config user name & email

```shell
git config user.name "DISPLAY NAME"
git config user.email EXAMPLE@DOMAIN.COM
```

### Working

#### Hard Reset to Last Commit

```shell
git reset --hard HEAD
```

#### Delete Unversioned Files

```shell
git clean -fd
```
