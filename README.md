#### 传奇2 服务端 go 语言实现
参照 C# Mir2 (https://github.com/Suprcode/mir2)

#### 用到的开源库/工具
- .NET Core 3.0
- [SqlSugar](https://github.com/sunkaixuan/SqlSugar)
- SQLite
- [Cellnet](https://github.com/davyxu/cellnet)
- [GORM](https://github.com/jinzhu/gorm)

#### 编译步骤
新建项目文件夹，设置为 gopath
```bash
mkdir ~/mir
export GOPATH=~/mir
```
获取依赖
```bash
go get -u -v github.com/mattn/go-sqlite3
go get -u -v github.com/jinzhu/gorm
go get -u -v github.com/davyxu/cellnet
go get -u -v github.com/davyxu/golog
go get -u -v github.com/davyxu/goobjfmt
go get -u -v github.com/davyxu/protoplus
```
编译
```bash
cd $GOPATH/src/github.com/yenkeia/mirgo/server
go build
```
运行
```bash
./server
```

#### 客户端
代码: https://github.com/yenkeia/mir2

资源链接: https://pan.baidu.com/s/12hpQDbOO6uNYNJDSyHbgDg  密码:86zz