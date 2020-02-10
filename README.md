# train-record

```
课程 course    uni.名称+时间  fk.部门
学员 student   uni.身份证号   fk.部门
部门 department   uni.名称
评估 appraisal    uni.uuid
手册 manual       uni.uuid

签到 sign    uni.uuid    fk.课程&学员
评估 mark    uni.uuid    fk.课程&评估&学员
```
