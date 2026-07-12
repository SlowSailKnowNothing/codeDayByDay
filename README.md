# Code Day by Day

一个用于长期刷算法题、沉淀解法、按记忆曲线复习的个人仓库。

## 每日最小闭环

1. 打开 `REVIEW_QUEUE.md`，先完成今天到期的复习。
2. 新做 1 题；卡住时先记录思路，再看提示或题解。
3. 用 `templates/daily.md` 新建当天日志到 `records/YYYY/MM/YYYY-MM-DD.md`。
4. 将代码与关键注释放入 `solutions/java/`，并把题目加入复习队列。

忙碌时的降级版本：复习 1 题 + 新做 1 题（总计 20 分钟）。

## 复习节奏

每道新题在首次完成后，于第 **1、3、7、14、30 天**复习。

一次复习不要只看答案：先在纸上或脑中重建思路，再检查代码边界和复杂度。

## 目录

```text
.
├── records/              # 每日刷题与复盘日志
├── solutions/java/       # Java 解法，按题目主题组织
├── templates/daily.md    # 每日记录模板
└── REVIEW_QUEUE.md       # 复习队列
```

## 命名约定

代码文件：`solutions/java/<topic>/<序号>-<slug>.java`

例如：`solutions/java/array/0001-two-sum.java`

日志文件：`records/2026/07/2026-07-12.md`
