# mini-blog 微博客
node+koa2+mysql (欢迎star)

### 创建数据库 

登录数据库
```
$ mysql -u root -p
```
创建数据库
```
$ create database nodesql;
```
使用创建的数据库
```
$ use nodesql;
```

> database: nodesql  tables: users posts comment  (已经在lib/mysql建表)

 | users   | posts    |  comment  |
| :----: | :----:   | :----: |
| id        | id      |   id    |
| name        | name      |   name    |
| pass        | title      |   content    |
|         | content      |   postid    |
|         | uid      |       |
|         | moment      |       |
|         | comments      |       |
|        | pv      |       |      |

* id主键递增
* name: 用户名
* pass：密码
* title：文章标题
* content：文章内容和评论
* moment：创建时间
* comments：文章评论数
* pv：文章浏览数
* postid：文章id

```
$ git clone https://github.com/Ningjunhua/mini-blog.git
```
```
$ cd mini-blog
```
```
$ cnpm i supervisor
$ cnpm i 
```
```
$ supervisor --harmony index
```
暂无回复功能


