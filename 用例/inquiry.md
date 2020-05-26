﻿<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# “查看成绩”用例 [返回](../README.md)
## 1. 用例规约
<table border=0 cellpadding=0 cellspacing=0 width=320 style='border-collapse:
 collapse;table-layout:fixed;width:240pt'>
 <col width=64 span=5 style='width:48pt'>
 <tr height=18 style='height:13.8pt'>
  <td height=18 width=64 style='height:13.8pt;width:48pt'>用例编号</td>
  <td align=right width=64 style='width:48pt'>14</td>
  <td width=64 style='width:48pt'>名称</td>
  <td colspan=2 width=128 style='mso-ignore:colspan;width:96pt'>设置评分规则</td>
 </tr>
 <tr height=18 style='height:13.8pt'>
  <td height=18 style='height:13.8pt'>创建日期</td>
  <td>2020.5.10</td>
  <td>最后更新<span style='display:none'>日期</span></td>
  <td>2020.5.15</td>
  <td></td>
 </tr>
 <tr height=18 style='height:13.8pt'>
  <td height=18 style='height:13.8pt'>参与者</td>
  <td colspan=3>老师</td>
  <td></td>
 </tr>
 <tr height=18 style='height:13.8pt'>
  <td height=18 style='height:13.8pt'>前置条件</td>
  <td colspan=3 class=xl65 width=192 style='width:144pt'>1教师已经成功登录到系统，进入主界面<br>
    2用户需要进入自己教学的某一课程</td>
  <td></td>
 </tr>
 <tr height=18 style='height:13.8pt'>
  <td height=18 style='height:13.8pt'>后置条件</td>
  <td colspan=3>用户设置评分成功。</td>
  <td></td>
 </tr>
 <tr height=18 style='height:13.8pt'>
  <td height=18 style='height:13.8pt'>流程</td>
  <td colspan=3 class=xl65 width=192 style='width:144pt'>1用户进入系统的登陆界面。
  2输入正确的用户名和密码，并且成功进入系统。 <br>3在主界面上了选择教学列表的某一课程。<br>4.进入课程,点击设置评分细则。<br>5.填入评分和占比，提交。</td>
  <td></td><br>
 </tr>
 <tr height=18 style='height:13.8pt'>
  <td height=18 style='height:13.8pt'>拓展流程</td>
  <td colspan=3 class=xl65 width=192 style='width:144pt'>无</td>
  <td></td>
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


## 2. 业务流程（顺序图） [源码](../src/查看成绩时序图.puml)
![sequence1](../查看成绩时序图.svg) 

## 3. 界面设计
- 界面参照: https://yangyam.github.io/is_analysis_test6/ui/inquiry.html
- API接口调用
    - 接口1：[getOneStudentScore](../接口/getOneStudentScore.md) 

## 4. 算法描述
    无
    
## 5. 参照表
- [STUDENTS](../Database.md/#STUDENTS)
- [GRADES](../Database.md/#GRADES)
- [TESTS](../Database.md/#TESTS)
- [COURSE](../Database.md/#COURSE)
