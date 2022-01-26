---
name: Bug report
about: Ran into some unexpected behaviour?
title: ''
labels: 'type: bug'
assignees: ''

---

**Metadata (please complete the following information):**
Version: [e.g. v1.2.0 run `ani-cli -V` to get the version]
OS: [e.g. Windows 10 / Linux Mint 20.3]
Shell: [e.g. zsh, run `echo $SHELL` to get your shell]

**Describe the bug**
Downloading is broken and spits out `Exception: [download_helper.cc:451] errorCode=1 Unrecognized URI or unsupported protocol`

**To Reproduce**
1. Run `ani-cli -d flcl`
2. Choose 2 (fooly-cooly)
3. Choose episode 1

**Expected behavior**
Downloading should work

**Screenshots (if applicable)**
![image](https://user-images.githubusercontent.com/82055622/151030428-2e78d15f-4ba9-4d86-b6f3-8307557b4b29.png)

**Additional context**