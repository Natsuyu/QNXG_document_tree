目录结构说明.

.

├── App					应用目录
│   └── Tpl
│       └── Index			入口文件
├── Common				核心公共函数文件
│   └── common.php
├── Conf					配置文件
│   ├── config.php
│   └── setup.php
├── Lib					框架类库目录
│   ├── Action				控制器文件
│   ├── Model				模型目录
│   │   ├── UserModel.class.php
│   │   └── UserRelationModel.class.php
│   └── Widget			组件扩展目录
├── Tpl					视图模板目录
└── static					静态文件目录





文件夹内部文件说明：

Action文件夹：

​	ActivityAction.class.php		活动版块操作

​	AdminLogAction.class.php		admin登录

​	ArticleAction.class.php		文章版块操作

​	ArticleCateAction.class.php	文章分类管理操作

​	CommonAction.class.php		基础的数据库相关操作

​	CountAction.class.php		浏览量、发稿统计

​	HrAction.class.php			报名统计信息

​	IndexAction.class.php			后台首页显示

​	MenuGroupAction.class.php	菜单版块

​	MovieAction.class.php		该模块已删除……

​	NewDocAction.class.php		

​	NewsAction.class.php			新闻模块操作

​	NodeAction.class.php			节点操作

​	NoticeAction.class.php		通知模块操作

​	PublicAction.class.php		登录、登出、文件上传操作

​	RoleAction.class.php			用户组操作

​	SetupAction.class.php			系统设置更新，首页海报设置，密码重置

​	UserAction.class.php			用户模块操作

​	VoteAction.class.php			投票模块操作

​	ZhiTuAction.class.php			知图模块操作

​	ZtAction.class.php			专题模块操作

Model文件夹：

​	用户模型和用户关系模型定义













​	