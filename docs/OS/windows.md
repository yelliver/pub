---
title: Windows
parent: OS Setup
---

### Software

#### Common

- [ChatGPT](https://openai.com/chatgpt/download/)
- [OpenKey](https://open-key.org/)
- [Slack](https://slack.com/downloads/)
- [TeamViewer](https://www.teamviewer.com/apac/download/)
- [Windows, Office](https://massgrave.dev/genuine-installation-media)

#### Dev

- [Docker](https://www.docker.com/)
- [Git](https://git-scm.com/download)
- [IntelliJ](https://www.jetbrains.com/idea/download/)
- [Rapid Environment Editor](https://www.rapidee.com/en/download)
- [Sublime Text](https://www.sublimetext.com/download)

#### Activators

- [JetBrains Activator](https://3.jetbra.in/)
- [Microsoft Activation Scripts](https://massgrave.dev/)
- [M0nkrus](https://w14.monkrus.ws/)

## WSL

### Install WSL

```shell
wsl --install
```

```shell
wsl --list --online
```

```shell
wsl --install -d Ubuntu
```

### Advanced Packaging Tool

```shell
sudo apt update
```

```shell
sudo apt upgrade
```

### User management

#### Create a user

```shell
net user USERNAME /add
```

```shell
net user USERNAME PASSWORD /add
```

#### Convert to a guest user

```shell
net localgroup USERNAME GuestUser /add
```

### BitLocker

#### [manage-bde](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/manage-bde)

#### Status

```shell
manage-bde -status
```
