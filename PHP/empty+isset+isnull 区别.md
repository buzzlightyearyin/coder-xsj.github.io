# empty+isset+isnull 区别

## 1. empty()

| 参数                                                         | 返回  |
| ------------------------------------------------------------ | ----- |
| 空值、零值 `“”`, `‘’`, `0`, `“0”`, `NULL`, `False`, `array()`, `var $var` | True  |
| 反之                                                         | False |



## 2. isset()

| 参数            | 返回  |
| --------------- | ----- |
| 存在（非 NULL） | True  |
| NULL、未定义    | False |



## 3. is_null()

检测传入 [ 值，变量，表达式 ] 是否是 `null`

| 参数                           | 返回                     |
| ------------------------------ | ------------------------ |
| `var $var`, `var $var = null;` | True                     |
| 反之                           | False                    |
|                                | 未定义变量传入后会出错！ |



1. php java go c，
2. 主要 java，c， 框架 ci，新起 
3. go
4. 财务系统，主营业务 p2p
5. 营销系统，su 一个项目，下载站点

