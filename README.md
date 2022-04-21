# my_tour

## word(command)
提供编码时的单词转换功能，包含转大写，转小写，下划线单词转大写/小写驼峰格式以及驼峰格式转下划线格式。

该子命令支持各种单词格式转换，模式如下：
1：全部转大写
2：全部转小写
3：下划线转大写驼峰
4：下划线转小写驼峰
5：驼峰转下划线
```
Usage:
   word [flags]

Flags:
  -h, --help         help for word
  -m, --mode int8    请输入单词转换模式
  -s, --str string   请输入单词内容
```
## 2struct(command)
提供一种直接由数据库中表的信息生成model的功能
```
Flags:
      --charset string    请输入数据库的编码 (default "utf8mb4")
  -d, --db string         请输入数据库名称
  -h, --help              help for 2struct
      --host string       请输入数据库的HOST (default "127.0.0.1:3306")
  -p, --password string   请输入数据库的密码
  -t, --table string      请输入表名称
      --type string       请输入数据库实例类型 (default "mysql")
  -n, --username string   请输入数据库的账号
  ```
