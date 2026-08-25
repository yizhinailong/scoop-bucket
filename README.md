# scoop-bucket

[![Tests](https://github.com/yizhinailong/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/yizhinailong/scoop-bucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/yizhinailong/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/yizhinailong/scoop-bucket/actions/workflows/excavator.yml)

个人维护的 [Scoop](https://scoop.sh) 应用仓库。

## 使用方式

添加 bucket：

```pwsh
scoop bucket add scoop-bucket https://github.com/yizhinailong/scoop-bucket
```

安装应用：

```pwsh
scoop install scoop-bucket/<manifest-name>
```

更新 bucket 和已安装的应用：

```pwsh
scoop update
scoop update --all
```

## 应用清单

应用清单位于 [`bucket`](bucket) 目录。新增或修改清单时，请参考 Scoop 的
[App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests) 文档。
