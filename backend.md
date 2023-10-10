## 后端设计

## 用户管理
> URI prefix： /user

### 表设计

> 用户表

| column        | type           | key  |
| ------------- |:-------------:| -----:|
| id      | int | primay key,auto increment |
| userNmae      | varchar(32)      |   not null |
| phoneNum | varchar(32)      |    not null |
|weiChatId| varchar(32) | |
| birthYear| tinyint||
| birthMonth| tinyint||
| birthDay| tinyint||
|weight| tinyint||
|height|tinyint||

> device表

| column        | type           | key  |
| ------------- |:-------------:| -----:|
| deviceId      | varchar(32) | primay key,auto increment |
| owner      | int | FOREIGN KEY userInfo(id) |
| name      | varchar(32)      |   not null |


### 用户注册

> method: POST

> URI prefix:  /user

> *TODO 补全API设计，包含request data，返回，method，uri等*


### 用户登陆

## 设备管理
> *TODO 补全API设计，包含request data，返回，method，uri等*

## 设备指标数据

> *TODO 补全API设计，包含request data，返回，method，uri等*