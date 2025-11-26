# eBusiness_63

一个基于 Spring Boot 的轻量级电商平台，用于学习开源协作与微服务架构实践。  

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## 📦 功能概览
- 用户注册/登录（JWT 认证）
- 商品浏览与搜索
- 商品收藏管理
- 购物车管理
- 订单生成（模拟）
- RESTful API 接口

## 🛠 技术栈
- Java 8
- Spring Boot 2.1.4
- Spring Data JPA
- MySQL 
- Maven
- thymeleaf
- MyBatis
- Git / GitHub


## ⚙️ 环境要求
- JDK 8
- Maven 3.6+
- MySQL 8.0+

## 🌐 访问地址
- 应用默认运行在 http://localhost:8083  （可在 application.properties中修改 server.port）。
- 默认管理员账号和密码：admin / admin、
  
🤝 贡献指南
欢迎提交 Issue 或 Pull Request！请遵循以下规范：

使用 feature/xxx 创建功能分支
提交前运行 mvn clean test
合并前确保无冲突
## 🚀 本地运行
```bash
git clone https://github.com/1DPS/eBusiness_63.git
cd eBusiness_63
mvn spring-boot:run


