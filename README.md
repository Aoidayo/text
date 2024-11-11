# text

测试git工具的功能



## 测试`.gitignore`

Q1: `dir/*`不忽略子文件夹中的文件，那么git上去的文件结构是什么样的？

A

目录结构

```
F:.
│  .gitignore
│  README.md
│
├─assets
└─dir1
    │  file1.txt
    │
    └─subdir1-1
            file1-1.txt
```

`.gitignore`

```
# Q1 dir1/*
dir1/*
```

