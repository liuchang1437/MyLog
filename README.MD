#工作&生活 记录
自*2016年4月26日*

## 简介

本项目以周为单位，分为两个模块——Work & Life，记录我的日常工作和生活状态。

## 格式

1. 文档**名称**规则：

   `<start_month_day>-<end_month_day>.md`

   例如：`0425-0429.md`

2. 文档**内容**规则：

   1. Header:

      ```markdown
      [TOC]
      #<tiem period>

      eg:
      #04.25 - 05.01
      ```

   2. Body:

      ```markdown
      ## <WeekDay> / <datetime>
      ### 1. <record1>;
      *<time>,<how_long>*
      1. <tip1>
      2. <tip2>
      ---
      ### 2. <time>  <record2>;
      ---
      ### 3. ...
      ---
      ...
      ```


## 规划

1. 将这个项目做成一个Web应用，可以在线添加、删除、修改记录（一定要方便），在线显示、查询记录（一定要简洁美观）。
2. 使用Pyqt（暂定）开发一个桌面应用。