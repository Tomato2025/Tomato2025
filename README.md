## 基本框架
前端：用 Vue 框架（配合 Vue Router + Vite），负责交互和页面结构。
后端：用 Supabase，提供数据库、认证、存储，不需要再搭建 Spring Boot 这样的传统后端。
部署：代码放在 GitHub，由 Vercel 自动拉取并发布，免费且支持 HTTPS。

## 基本页面
你的网站可以包含：
简历信息（教育、成绩、项目、时间线）
动态博客（文章存储在 Supabase，前端调用展示）
知识网络（关键词节点，未来可扩展交互式图谱）
朋友圈卡片（数据存储在 Supabase，前端渲染）
登录验证：Supabase 内置认证，返回 JWT，前端只需保存并带上即可。

## 目录结构
my-website/
├── src/
│   ├── pages/                # 页面组件
│   │   ├── Home.vue          # 首页
│   │   ├── About.vue         # 关于我（教育、成绩、课程、时间线）
│   │   ├── Projects.vue      # 项目与收获
│   │   ├── Blog.vue          # 博客文章列表
│   │   ├── BlogPost.vue      # 单篇博客文章
│   │   ├── Knowledge.vue     # 知识网络（关键词星系）
│   │   ├── Concept.vue       # 知识节点详情
│   │   ├── Friends.vue       # 朋友圈卡片
│   │   ├── Contact.vue       # 联系方式
│   ├── components/           # 公共组件
│   │   ├── Navbar.vue        # 导航栏
│   │   ├── Footer.vue        # 页脚
│   ├── App.vue               # 主应用入口
│   ├── main.js               # Vue 启动入口
│   └── router/
│       └── index.js          # 路由配置
├── public/
│   └── index.html            # 根 HTML 模板
├── package.json              # 项目配置
├── README.md                 # 项目说明


<!--
**Tomato2025/Tomato2025** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
