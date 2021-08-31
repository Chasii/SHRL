
# 当前版本
## 2.5
- 新增的功能：
    - a.适配多重应用环境
    - b.支持应用配置变更
    - c.工作日志收敛至数据库
    - d.优化发布信息卡片
    - e.集中提醒信息，映射为错误代码

- 修复的功能：
    - a.某种情况下发布发送失败
    - b.修复GB2312中文乱码
 - - -
# 已发布版本
## 2.3 (2019.3.9)

- 新增的功能
    - a.配置文件启用字典替代configparser配置文件方式
    - b.构建失败提供以链接形式完整日志文档
    - c.实现预约上线功能;

- 修复的功能：
    - a.去除因日志过长而导致钉钉发送失败形式

## 2.2 (2019.2.28)

- 新增的功能：
    - a.修复Job中某些情况下构建分支而非Tag，出现的Tag不存在情况

## 2.1 (2019.2.18)

- 新增的功能：
    - a.增加对不同类型Jobs适配，如maven、multijob等类型；
    - b.优化markdown字体大小，增强上线信息可读性；
    - c.隐藏ansible执行过程中输出的主机名；

- 修复的功能：
    - a.屏蔽含有print，修复：OSError: [Errno 5] Input/output error
    - b.修复Jobs nextbuildnumber不存在问题

## 2.0 (2019.1.2)
- 新增的功能：
    - a.收敛Jira单变更信息通知，完成上线后统一推送
    - b.增强构建前的上线信息校验，如Tag检查；
    - c.增加颜色标识上线状态，如蓝色-"正在上线"，绿色-"上线完成"；
    - d.判断当前Jenkins构建Jobs数量，如Jobs超过系统限制，则友情提醒等待；
    - e.加入数据汇总功能，方便日后周报、日报分析；
    - f.实时显示Jobs构建信息，了解构建的每个细节【重磅】；

## 1.0 (2018.12.12)
- 新增的功能：
    - a.第一版发布