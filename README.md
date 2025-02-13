﻿基于Vue.js和SpringBoot的宠物咖啡馆平台是一个综合性的Web应用程序，旨在为宠物爱好者提供一个一站式服务，包括宠物信息管理、宠物体验活动、宠物订单处理、宠物寄养服务、咖啡菜品展示以及看护师管理等。

项目录屏：https://www.bilibili.com/video/BV1Xe411Y7DW

### 1. 管理后台

管理后台是为管理员和看护师设计的，提供全面的管理功能，包括：

#### 1.1 宠物信息管理

- **宠物注册**：允许管理员添加新宠物的详细信息，如品种、年龄、健康状况等。
- **宠物档案**：查看和管理所有宠物的档案，包括更新和删除宠物信息。
- **健康记录**：记录和跟踪宠物的健康检查和疫苗接种情况。

#### 1.2 宠物体验活动

- **活动创建**：管理员可以创建宠物体验活动，如宠物瑜伽、宠物游泳等。
- **活动管理**：管理活动日程、参与宠物和用户反馈。

#### 1.3 宠物订单处理

- **订单管理**：查看、处理和跟踪宠物订单，包括寄养、美容、医疗等服务。
- **订单统计**：生成订单统计报告，帮助分析业务趋势。

#### 1.4 宠物寄养服务

- **寄养申请**：管理宠物寄养申请，包括审核和安排寄养时间。
- **寄养记录**：记录宠物寄养的详细信息，包括寄养期间的护理和活动。

#### 1.5 咖啡菜品管理

- **菜单管理**：添加、更新和删除咖啡和菜品信息。
- **库存管理**：监控库存水平，自动提醒补货。

#### 1.6 看护师管理

- **看护师注册**：允许管理员添加新的看护师，并管理他们的个人信息。
- **看护师调度**：安排看护师的工作日程，确保服务的高效和公平。

### 2. 用户网页端

用户网页端面向普通用户，提供以下功能：

#### 2.1 宠物信息浏览

- **宠物档案**：用户可以查看宠物的详细信息和健康记录。
- **宠物体验活动**：浏览即将举行的宠物体验活动，并进行报名。

#### 2.2 宠物服务预订

- **寄养服务**：用户可以为宠物预订寄养服务，并查看寄养期间的活动安排。
- **美容和医疗服务**：预订宠物美容和医疗服务。

#### 2.3 咖啡菜品预订

- **查看菜单**：浏览咖啡和菜品菜单。
- **在线预订**：用户可以在线预订咖啡和菜品。

#### 2.4 用户账户管理

- **个人信息**：用户可以查看和更新自己的个人信息。
- **订单管理**：查看和管理自己的订单历史。

### 技术栈

- **前端**：Vue.js，用于构建动态的用户界面。
- **后端**：Spring Boot，提供RESTful API服务。
- **数据库**：MySQL或MongoDB，存储用户数据、宠物信息等。
- **身份验证**：JWT（JSON Web Tokens）用于安全的用户认证。

这个平台的设计旨在提供一个用户友好、功能全面的宠物咖啡馆服务，同时确保数据的安全性和系统的稳定性。