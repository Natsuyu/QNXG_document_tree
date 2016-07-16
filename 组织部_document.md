目录结构说明：

.
├── Common				核心公共函数文件
│   └── common.php
├── Conf					配置文件
│   ├── config.php
│   └── setup.php
├── Lang					
├── Lib					框架类库目录
│   ├── Action				控制器目录
│   ├── Behavior
│   ├── Model				模型目录
│   └── Widget			组件扩展目录
└── Tpl					视图模板目录



文件夹内部文件说明：

Action文件夹：

​	AdminLogAction.class.php			admin登录

​	ArticleAction.class.php			文章版块操作

​	ArticleCateAction.class.php		文章分类管理操作（少了activity分类）

​	CommonAction.class.php			基础的数据库相关操作（少了默认读取账号名方法）

​	IndexAction.class.php				后台首页显示	

​	MenuGroupAction.class.php		菜单版块

​	NewDocAction.class.php			

​	NewsAction.class.php				新闻模块操作（缺少责任编辑列表和通过状态读取）

​	NodeAction.class.php				节点操作

​	NoticeAction.class.php			通知模块操作（缺少editor field）

​	PublicAction.class.php			登录、登出、文件上传操作（上传操作有别）

​	RoleAction.class.php				用户组操作（缺少update_data操作）

​	SetupAction.class.php				系统设置更新，首页海报设置，密码重置

​	UrlAction.class.php				快捷导航操作

​	UserAction.class.php				用户模块操作



Model文件夹：

用户模型和用户关系模型定义

