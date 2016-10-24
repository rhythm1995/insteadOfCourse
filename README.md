# insteadOfCourse
A platform for instead of course.
### 数据字段
##### 用户库
* 用户名（必填）
* 密码（必填）
* 性别（必填）
* 注册日期（生成）
* qq（必填）
* 邮箱（必填）
* 手机号（必填）
* 微信支付账号（非必填）
* 支付宝支付账号（非必填）
* 头像（非必填，不上传有默认，上传后修改）
* 用户评级
##### 课程库
* 发布时间（必填）
* 发布人（必填）
* 上课时间（必填）
* 上课教室(必填)
* 课程名（必填）
* 校区（必填）
* 标题（非必填，若为空，课程名为标题）
* 详情（非必填）
* 价格（必填）
* 是否已付费（用户确认，若未确认，一天后自动算作付费）
* A的评级（一天后自动五星级）
* B的评级（一天后自动五星级）
##### 已完成课程库（数据全部从课程库中获取，过期自动添加入）
* 发布时间（必填å）
* 发布人（必填）
* 上课时间（必填）
* 上课教室(必填)
* 课程名（必填）
* 校区（必填）
* 标题（非必填，若为空，课程名为标题）
* 详情（非必填）
* 价格（必填）

### 功能概述
##### 找人代课
找代者A发布代课信息，等人与之联系，多个代课者BCD点击接受，找代者A最终确定后选择代课者，选择后其他人代课信息被删除。
##### 为人代课
游览代课大厅，看到信息后点击接受代课，等待联系，若到时间，删除信息。
##### 内置聊天SDK