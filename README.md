# sshchecker

[![Build Status](https://travis-ci.com/lazytools/sshchecker.svg?token=S9wbQbp5C4dcPWszHpyt&branch=master)](https://travis-ci.com/lazytools/sshchecker)

sshchecker is a fast tool to check ssh login on giving ips.

## Install

```bash
▶ go get -u github.com/lazytools/sshchecker
```

## usage

```bash
▶ cat testfiles/ips.txt | sshchecker -U testfiles/testuser -P testfiles/testpass
```
## Flags
```bash
sshchecker -h
```
## TODO
* Add timeout for quick bruteforcing.
