![航海之路](https://i-young.guokr.net/FmoBwM-9802FuEKF3uV2i7SU_prv)
## 项目简介
《海贼王》动画剧情数据库。包含故事线、角色登场顺序、对战记录等。
## 项目地址
[航海之路](https://datamuse.guokr.com/opd)

## 数据说明

* 表bounty

  | 字段名        | 释义                       |
  | ---- | ---- |
  | id | 赏金id |
  | cid | 角色表id |
  | value | 赏金值 |
  | bounty_order | 赏金排名 |



* 表character

  | 字段名        | 释义                       |
  | ---- | ---- |
  | id | 角色id |
  | name | 名字 |
  | cn_name | 中文名字 |
  | birth_place | 出生地 |
  | debut | 首次亮相 |
  | nick_name | 昵称 |
  | saying | 名言 |
  | voice | 声优 |
  | en_name | 英文名字 |
  | age | 年龄 |
  | organization | 组织 |
  | ship | 战船 |
  | birthday | 生日 |
  | height | 身高 |
  | haki | 霸气 |
  | avatar | 头像 |
  | Intro | 简介 |
  | anime_debut | 动漫出场时间 |
  | comics_debut | 漫画出场时间 |
  | color | 颜色 |



* 表devil_fruit

  | 字段名        | 释义                       |
  | ---- | ---- |
  | id | 爆炸果实id |
  | type | 恶魔果实类别 |
  | name | 恶魔果实名字 |
  | power | 恶魔果实能力 |
  | intro | 恶魔果实介绍 |
  | debut | 恶魔果实出场时间 |



* 表fight

  | 字段名        | 释义                       |
  | ---- | ---- |
  | id | 战斗id |
  | cid | 角色id |
  | enemy | 对手 |
  | result | 结果 |
  | fight_order | 战斗顺序 |



* 表haki

  | 字段名        | 释义                       |
  | ---- | ---- |
  | id | 霸气id |
  | haki_type | 霸气类型 |
  | cid | 角色id |



* 表history

  | 字段名        | 释义                       |
  | ---- | ---- |
  | id | 霸气id |
  | cid | 角色id |
  | years | 年 |
  | intro | 历史介绍 |



* 表mainline

  | 字段名        | 释义                       |
  | ---- | ---- |
  | id | 事件id |
  | name | 事件名字 |
  | start | 事件开始时间 |
  | end | 事件结束时间 |
  | color | 颜色 |
  | intro | 事件介绍 |
  | players | 参与者 |
  | characters | 角色id |
  | is_original | 是否是动画原创 |
  | video | 片段 |



* 表organization

  | 字段名        | 释义                       |
  | ---- | ---- |
  | id | 组织id |
  | name | 组织名字 |
  | intro | 组织介绍 |
  | avatar | 组织头像 |



* 表organization_mapping

  | 字段名        | 释义                       |
  | ---- | ---- |
  | id | 映射id |
  | org_id | 组织id |
  | cid | 角色id |


