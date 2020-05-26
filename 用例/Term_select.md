﻿<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# “查看成绩”用例 [返回](../README.md)
## 1. 用例规约

<table border=0 cellpadding=0 cellspacing=0 width=320 style='border-collapse:
 collapse;table-layout:fixed;width:240pt'>
 <col width=64 span=5 style='width:48pt'>
 <tr height=18 style='height:13.8pt'>
  <td height=18 class=xl1525875 width=64 style='height:13.8pt;width:48pt'>用例编号</td>
  <td class=xl1525875 align=right width=64 style='width:48pt'>4</td>
  <td class=xl1525875 width=64 style='width:48pt'>名称</td>
  <td class=xl1525875 colspan=2 width=128 style='width:96pt'>名称：	成绩查询</td>
 </tr>
 <tr height=18 style='height:13.8pt'>
  <td height=18 class=xl1525875 style='height:13.8pt'>创建日期</td>
  <td class=xl1525875>2020.5.10</td>
  <td class=xl1525875>最后更新<span style='display:none'>日期</span></td>
  <td class=xl1525875>2020.5.15</td>
  <td class=xl1525875></td>
 </tr>
 <tr height=18 style='height:13.8pt'>
  <td height=18 class=xl1525875 style='height:13.8pt'>参与者</td>
  <td colspan=3 class=xl1525875>学生、老师</td>
  <td class=xl1525875></td>
 </tr>
 <tr height=18 style='height:13.8pt'>
  <td height=18 class=xl1525875 style='height:13.8pt'>前置条件</td>
  <td colspan=3 class=xl6525875 width=192 style='width:144pt'>1用户已经成功登录到系统，进入主界面。<br>
    2用户需要选修相应的课程.<br>
    3用户通过查询课程的信息已经确定要选择的课程,或者想要查询或者修改已选的课程<br>
    4课程开设且考试完成。</td>
  <td class=xl1525875></td>
 </tr>
 <tr height=18 style='height:13.8pt'>
  <td height=18 class=xl1525875 style='height:13.8pt'>后置条件</td>
  <td colspan=3 class=xl1525875>用户查询选取课程的成绩。</td>
  <td class=xl1525875></td>
 </tr>
 <tr height=18 style='height:13.8pt'>
  <td height=18 class=xl1525875 style='height:13.8pt'>流程</td>
  <td colspan=3 class=xl6525875 width=192 style='width:144pt'>1用户进入系统的登陆界面。<br>
    2输入正确的用户名和密码，并且成功进入系统。<br>
    3在主界面上了选择成绩查询的功能。</td>
  <td class=xl1525875></td>
 </tr>
 <tr height=18 style='height:13.8pt'>
  <td height=18 class=xl1525875 style='height:13.8pt'>拓展流程</td>
  <td colspan=3 class=xl6525875 width=192 style='width:144pt'>学生可以显示全部课程的成绩，也可以按照课程名或者课程号显示。教师按照课程号或课程名称查看自己学生的成绩，也可以按照学生学号查看成绩。</td>
  <td class=xl1525875></td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=64 style='width:48pt'></td>
  <td width=64 style='width:48pt'></td>
  <td width=64 style='width:48pt'></td>
  <td width=64 style='width:48pt'></td>
  <td width=64 style='width:48pt'></td>
 </tr>
 <![endif]>
</table>

## 2. 业务流程
- 无 

## 3. 界面设计
- 界面参照: https://z915287285.github.io/is_analysis_test6/ui/term_select.html
- API接口调用
    - 接口1：[getTerm_Course](../接口/getTerm_Course.md) 

## 4. 算法描述
    无
    
## 5. 参照表
- [COURSES](../DataBase.md/#COURSES)
