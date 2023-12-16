# 12306-code-database-2023-12-15

2023年12月15日 12306车次数据库

## 简要信息

本数据库是你椒利用Python爬下来的，耗时三天（主要是编代码呢）

工具不提供下载

## 使用方法

本仓库内包含三个文件

<ul>
<li>db.zip
<li>utf8.zip
<li>gbk.zip
</ul>

#### db.zip

为已经整理好的数据库压缩包，其中包含

<ul>
<li>ful_code_index.db
<li>station_based_code.db
<li>train_basic.db
<li>train_timetable_info.db
</ul>

数据库由SQLite3整理
其中
full_code_index.db 与 train_timetable_info.db 已按照车次等级分好文件夹。
可根据实际情况调用

#### utf8.zip 与 gbk.zip

为车次原始数据，以 .json 文件为主，包含一个 index.csv 索引文件
可根据实际情况调用

## 结尾

本数据库免费使用，不建议用在商业用途，一切责任与本人（Huxiaojiao233）无关。
