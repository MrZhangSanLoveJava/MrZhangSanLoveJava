# 更新日志

## 1.0.0

### 1、日期

创建时间：2022-1-19

完成时间：2022-1-29

### 2、变动类型

- Added

  -  新增增删改查等按钮，运行还有菜单
  - 错误类型的总结和输出
  - 增加操作日志、帮助、更新日志等功能
  - 增加判断用户输入的指令操作

- Fixed

  - 解决运行无法判断后是否是 `;` 和 ` ` 等问题

  - 优化用户输入 

    ```sql
    SELECT * FROM t_table
    ```

    时输出的问题

  - 解决大小写问题

  - 优化执行输出时的问题

  - 将非用户输入的区域设置为可读

- Deprecated

  - 准备将操作日志移除（争议性很大）

### 3、发布版本

版本：v1.0.0

名称：`SQLoperation(compression)`

介绍：此版本为我编写后的压缩版只有一个`.py`文件。三个文件合二为一。