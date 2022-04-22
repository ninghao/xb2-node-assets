# Ravent 服务端应用演示数据

```
├── README.md
├── database
│   └── xb2_node.sql
├── insomnia-workspace
│   └── xb2-node.yaml
└── uploads
    ├── 01245b953f80b39f401506d10a6e3598
    ├── ...
```

## 准备数据库

database/xb2_node.sql 是演示数据，新建一个数据库，然后导入这个 .sql 文件，会在数据仓库里创建好应用需要的数据表，还有一些演示数据。

## 准备上传文件

_uploads/_ 目录里的东西是一些上传的图片还有用户头像。你准备好 Ravent 服务端应用以后，要把这个 _uploads_ 这个目录放在项目的根目录的下面。

## 客户端接口测试

在开发应用的时候可以使用 Insomnia 这个客户端软件测试开发的应用接口，你可以在 Insomnia 里面导入 _insomnia-workspace/xb2-node.yaml_ 这个文件，这样会为你创建好测试应用需要的连接。

## 服务端应用项目

https://github.com/ninghao/xb2-node
