![低分电影宇宙](https://i-young.guokr.net/FrskVM2_OdXxMLwRJYjSm-5gMLrD)
## 项目简介
豆瓣4分以下电影、导演、演员数据，以及他们之间的相互关系。
## 项目地址
[低分电影宇宙](https://datamuse.guokr.com/wmu)

## 数据说明

数据存储为非关系型数据库（Postgres），导出为json文件。

* 表cast

  | 字段名 | 释义         |
  |--------|------------|
  | id     | 演员id       |
  | name   | 演员名字     |
  | rating | 演员评分     |
  | intro  | 演员介绍     |
  | image  | 演员图片     |
  | width  | 演员图片宽度 |
  | height | 演员图片高度 |


* 表cast_mapping

  | 字段名  | 释义     |
  |---------|--------|
  | id      | 映射id   |
  | cast_id | 演员id   |
  | mid     | 电影id   |
  | order   | 映射顺序 |

* 表comment

  | 字段名       | 释义     |
  |--------------|--------|
  | id           | 评论id   |
  | movie_id     | 电影id   |
  | useful_count | 有用数   |
  | rating       | 评论评分 |
  | uid          | 用户id   |
  | user_avatar  | 用户头像 |
  | user_name    | 用户名   |
  | content      | 评论内容 |
  | created_at   | 创建时间 |


* region

  | 字段名 | 释义   |
  |--------|------|
  | id     | 地区id |
  | region | 地区   |


* 表region_mapping

  | 字段名    | 释义   |
  |-----------|------|
  | id        | 映射id |
  | region_id | 地区id |
  | mid       | 电影id |


* 表director

  | 字段名 | 释义         |
  |--------|------------|
  | id     | 导演id       |
  | name   | 导演名字     |
  | rating | 导演评分     |
  | intro  | 导演介绍     |
  | image  | 导演图片     |
  | width  | 导演图片宽度 |
  | height | 导演图片高度 |


* 表director_mapping

  | 字段名      | 释义     |
  |-------------|--------|
  | id          | 映射id   |
  | director_id | 导演id   |
  | mid         | 电影id   |
  | order       | 导演顺序 |


* 表genres

  | 字段名 | 释义     |
  |--------|--------|
  | id     | 类型id   |
  | name   | 类型名称 |


* 表genres_mapping

  | 字段名    | 释义   |
  |-----------|------|
  | id        | 映射id |
  | genres_id | 类型id |
  | mid       | 电影id |


* 表language

  | 字段名   | 释义   |
  |----------|------|
  | id       | 语言id |
  | language | 语言   |


* 表language_mapping

  | 字段名      | 释义   |
  |-------------|------|
  | id          | 映射id |
  | language_id | 语言id |
  | mid         | 电影id |


* 表pubdate

  | 字段名     | 释义     |
  |------------|--------|
  | id         | 日期id   |
  | mid        | 电影id   |
  | date       | 时间     |
  | day        | 日期     |
  | area       | 地点     |
  | created_at | 创建时间 |


* 表tag

  | 字段名 | 释义   |
  |--------|------|
  | id     | 标签id |
  | name   | 标签名 |


* 表tag_mapping

  | 字段名 | 释义   |
  |--------|------|
  | id     | 映射id |
  | tag_id | 标签id |
  | mid    | 电影id |

* 表writer

  | 字段名 | 释义   |
  |--------|------|
  | id     | 编剧id |
  | name   | 编剧名 |
  | rating | 评分   |


* 表writer_mapping

  | 字段名    | 释义   |
  |-----------|------|
  | id        | 映射id |
  | writer_id | 编剧   |
  | mid       | 电影id |
