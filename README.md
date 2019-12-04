# Export kubernetes configuration

## Overview
This is a kubectl plugin that exports config to use kubectl as a service user.

## Install
- Execute the folloing command. (path is an example.)
```
$ git clone https://github.com/m3y/export-kubecfg.git
$ cd export-kubecfg
$ cp kubectl-export_kubecfg /usr/local/bin/kubectl-export_kubecfg
$ chmod +x /usr/local/bin/kubectl-export_kubecfg
$ kubectl plugin list
```

## Requirement
- kubectl
- jq
