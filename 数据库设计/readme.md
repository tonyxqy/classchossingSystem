# 选课管理系统

## 文件说明

account.sql->其中包含账户数据库的定义语句以及初始化语句(用于设置管理员、老师和学生的账号密码)。

define.sql->其中包含选课管理数据库中的4张表的定义，包含学生信息表、教师信息表、课程表以及选课表。

initiate.sql->其中包含上述4张表的初始化语句，为表中填入部分初始数据用于演示。

student.sql->其中包含学生选课时可能需要使用的所有sql语句，包含查询已修课程、已选课程、可选课程以及根据各种条件筛选课程等等。

teacher.sql->其中包含教师打分时可能需要使用的所有sql语句，包含教授的课程、教授课程的学生信息以及打分功能等等。

manager.sql->其中包含管理员维护数据库时可能需要使用的所有sql语句，包含添加用户信息、添加选课记录或删除选课记录等等。

## 文件结构

上述所有sql文件中都包含sql语句以及对应的注释，对于功能实现部分的sql语句而言，其注释包含sql语句的返回格式，是很重要的信息。