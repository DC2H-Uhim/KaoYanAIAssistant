# KaoYanAIAssistant

项目目录结构：
KaoYanAIAssistant/
├── kaoyan-ai-assistant-server/ # 后端代码
│ ├── src/ # 源代码目录
│ │ ├── main/ # 主代码目录
│ │ │ ├── java/ # Java 源代码
│ │ │ │ └── com/
│ │ │ │ └── example/
│ │ │ │ └── kaoyanaiassistant/
│ │ │ │ ├── controller/ # 控制器
│ │ │ │ ├── service/ # 服务层
│ │ │ │ ├── dao/ # 数据访问对象
│ │ │ │ ├── model/ # 数据模型
│ │ │ │ ├── config/ # 配置文件
│ │ │ │ └── KaoYanAIAssistantApplication.java # 应用启动类
│ │ │ └── resources/ # 资源文件
│ │ │ ├── application.properties # 应用配置
│ │ │ ├── logback.xml # 日志配置
│ │ │ ├── static/ # 静态资源
│ │ │ └── templates/ # 模板文件
│ │ └── test/ # 测试代码
│ │ └── java/ # 测试 Java 源代码
│ ├── .gitignore # Git 忽略文件
│ ├── pom.xml # Maven 项目配置文件
│ └── README.md # 后端说明文档
├── kaoyan-ai-assistant-client/ # 前端代码 (UniApp)
│ ├── pages/ # 页面
│ │ ├── index/ # 首页
│ │ │ ├── index.vue # 首页组件
│ │ │ └── index.json # 首页配置
│ │ └── ... # 其他页面
│ ├── static/ # 静态资源
│ ├── uniapp.config.js # UniApp 配置文件
│ ├── App.vue # 应用根组件
│ ├── main.js # 应用入口
│ ├── manifest.json # 应用配置
│ ├── pages.json # 页面路由配置
│ ├── README.md # 前端说明文档
│ └── .gitignore # Git 忽略文件
├── kaoyan-ai-assistant-admin/ # 后台管理系统 (Vue.js)
│ ├── public/ # 静态资源
│ ├── src/ # 源代码目录
│ │ ├── assets/ # 资源文件
│ │ ├── components/ # 组件
│ │ ├── router/ # 路由配置
│ │ ├── store/ # 状态管理 (Vuex)
│ │ ├── views/ # 视图
│ │ ├── App.vue # 根组件
│ │ ├── main.js # 入口文件
│ │ └── ... # 其他文件
│ ├── .env.\* # 环境变量
│ ├── babel.config.js # Babel 配置
│ ├── package.json # 项目依赖和脚本
│ ├── README.md # 后台管理系统说明文档
│ └── .gitignore # Git 忽略文件
├── models/ # 大语言模型相关
│ ├── data/ # 训练数据
│ ├── pretrained/ # 预训练模型
│ ├── fine-tuned/ # 微调后的模型
│ ├── scripts/ # 训练和微调脚本
│ ├── requirements.txt # Python 依赖
│ └── README.md # 模型相关说明文档
├── recommendation/ # 个性化推荐系统
│ ├── algorithms/ # 推荐算法
│ ├── data/ # 用户数据和推荐数据
│ ├── scripts/ # 推荐系统脚本
│ ├── requirements.txt # Python 依赖
│ └── README.md # 推荐系统说明文档
├── docs/ # 文档
│ ├── architecture.md # 架构设计文档
│ ├── api-docs/ # API 文档
│ ├── user-guide/ # 用户指南
│ └── ... # 其他文档
├── scripts/ # 脚本
│ ├── build.sh # 构建脚本
│ ├── deploy.sh # 部署脚本
│ └── ... # 其他脚本
├── .gitignore # 项目级别的 Git 忽略文件
