# 招娉网站对用户前端项目日志

**请前端人员在更改项目时以如下格式写明自己正在做以及做完的组件或者其他文件**
```markdown
### 18年03月31日08时-18年03月31日09时 
  
  更新内容：创建项目 
  
  更新人员：李新阳
```
## 4月日志
 
 ### 18年04月02日12时-18年04月02日16时 
  
  更新内容：重编部分html为组件，在main.js里添加路由，并搭建基本的路由逻辑path及对应component。
  - 其中更新的组件有：
    + 用户界面的页面头部（XhwlHeader）
    + 用户界面首页的中部（Home）
    + **用户界面的页面底部遇到一些问题暂未完成**
  - 添加的路由（暂时指向空组件）有：
    + 首页（）
    + 社会招聘 （/Social）
    + 校园招聘分
        + 招聘职位（/Campus/Post）
        + 招聘流程（/Campus/Procedure）
        + 培养计划（/Campus/Plan）
    + 实习生招聘（/Trainee）
    + 关于兴海物联（/AboutUs）
  
  更新人员：李新阳
  
  ### 18年04月03日12时-18年04月02日18时 
  
  更新内容：更新部分组件以及未创建简历时提示创建简历的页面，添加部分路由。
  - 其中更新的组件有：
    + 搜索栏（Selector）
    + 用户界面头部的登录后下拉框及提示信息（更新了XhwlHeader）
    + 未创建简历时提示创建简历的提示动画组件（MyResume）
    +  **暂时使用的职位卡片（等待更新）**
  - 添加的路由有：
    + 我的简历（/MyResume）
    
  更新人员：李新阳
  
   ### 18年04月05日12时-18年04月06日12时 
  
  更新内容：更新部分组件以及部分页面毛胚，添加部分路由。
  - 其中更新的组件有：
    + 填写表单页面（ResumeForm）
    + 表单页面子组件有：
       + 基本信息
       + 教育经历
       + **其余八个表单已搭建完成但未修改其中的表单内容**
    + 投递信息（MyJobApplication）
  - 添加的路由有：
    + 我的投递（/MyJobApplication）
    + 填写简历及其子路由（/ResumeForm/1~/ResumeForm/10）
    
  更新人员：李新阳
