# Trivial matters


## 包管理工具
```
Ubuntu推荐使用APT（Advanced Packaging Tool）作为默认软件包管理工具，它简化了软件的安装、更新和移除。相比apt-get，apt命令提供了更简洁、用户友好的命令行界面，适合日常操作，而 apt-get 适用于脚本。

sudo apt update  // 先更新本地软件列表，确保获取到最新的版本信息
```

## pnpm切换：package manager
```

1、备份你的项目，特别是 package.json 和锁文件（package-lock.json 或 yarn.lock）。 清理旧的依赖和锁文件：为了确保干净的迁移，可以删除 node_modules 文件夹和旧的锁文件。


```
