# 🏫 基于Spring Boot的高校管理系统

> 🔥 全网最全的高校管理系统开源项目，覆盖学生、教师、管理员、教务处、后勤等多角色，包含教务、学工、后勤、财务等全模块功能。
>
> 💡 **毕设/课设/学习必备项目**，Star收藏不迷路！
>
> 📱 有问题或需要完整代码加微信：**xunmaw001** （备注：GitHub高校系统）

[![GitHub stars](https://img.shields.io/github/stars/yourname/springboot-university-management-system.svg?style=social)](https://github.com/yourname/springboot-university-management-system/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/yourname/springboot-university-management-system.svg?style=social)](https://github.com/yourname/springboot-university-management-system/network/members)
[![GitHub issues](https://img.shields.io/github/issues/yourname/springboot-university-management-system.svg)](https://github.com/yourname/springboot-university-management-system/issues)
[![GitHub license](https://img.shields.io/github/license/yourname/springboot-university-management-system.svg)](https://github.com/yourname/springboot-university-management-system/blob/master/LICENSE)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7-brightgreen.svg)](https://spring.io/projects/spring-boot)
[![Vue](https://img.shields.io/badge/Vue-3-blue.svg)](https://vuejs.org/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-orange.svg)](https://www.mysql.com/)

---

## 📢 项目说明
本项目是一套完整的高校信息化管理系统，采用前后端分离架构，基于 Spring Boot + Vue 3 开发，涵盖了高校日常运营的所有核心业务模块。代码结构清晰，注释完善，非常适合作为毕业设计、课程设计、学习参考使用。

> 🎁 **福利**：加微信 **xunmaw001** 免费领取：
> - 完整前后端源码
> - 配套数据库脚本
> - 部署文档和运行教程
> - 毕设论文模板和参考资料
> - 免费技术答疑和远程调试帮助

---

## ✨ 功能特性

### 👨‍🎓 学生端功能
- ✅ 个人信息管理：学籍信息、成绩查询、课表查询
- ✅ 选课管理：在线选课、退课、选课结果查询
- ✅ 考试管理：考试安排查询、成绩查询、绩点计算
- ✅ 奖惩管理：奖励查询、处分查询、奖学金申请
- ✅ 住宿管理：宿舍信息查询、宿舍调换申请、维修上报
- ✅ 缴费管理：学费查询、缴费记录、欠费提醒
- ✅ 请假管理：在线请假、审批进度查询
- ✅ 毕业设计：选题、开题、中期检查、答辩管理

### 👨‍🏫 教师端功能
- ✅ 个人信息管理：教师信息、授课信息、科研信息
- ✅ 教学管理：课程管理、成绩录入、学生名单管理
- ✅ 考勤管理：学生考勤记录、考勤统计
- ✅ 成绩管理：成绩录入、成绩分析、成绩单打印
- ✅ 科研管理：项目申报、论文管理、获奖管理
- ✅ 指导学生：毕业设计指导、论文评阅、答辩评分
- ✅ 审批管理：学生请假审批、宿舍调换审批

### 🛠️ 管理员端功能
- ✅ 系统管理：用户管理、角色管理、权限管理、菜单管理
- ✅ 基础数据管理：院系、专业、班级、课程、教室管理
- ✅ 教务管理：教学计划管理、排课管理、考试安排管理
- ✅ 学工管理：学生管理、教师管理、奖惩管理、评优评先
- ✅ 后勤管理：宿舍管理、资产管理、维修管理、收费管理
- ✅ 统计分析：学生统计、教师统计、成绩统计、教务统计
- ✅ 系统监控：在线用户、操作日志、登录日志、服务器监控

### 🏢 教务处功能
- ✅ 培养方案管理：专业培养方案、课程体系设置
- ✅ 教学质量监控：教学评价、听课记录、质量分析
- ✅ 教材管理：教材采购、教材发放、教材库存
- ✅ 实践教学：实习管理、实训管理、竞赛管理

### 🍚 后勤处功能
- ✅ 资产管理：固定资产、低值易耗品、设备管理
- ✅ 后勤服务：报修管理、食堂管理、校园卡管理
- ✅ 基建管理：楼宇管理、场地管理、维修工程
- ✅ 采购管理：采购申请、招投标管理、供应商管理

### 💰 财务处功能
- ✅ 收费管理：学费收取、住宿费收取、其他收费
- ✅ 工资管理：教师工资、绩效计算、个税申报
- ✅ 预算管理：部门预算、预算执行、财务报表
- ✅ 报销管理：费用报销、审批流程、支付管理

---

## 🏗️ 技术架构

### 后端技术栈
| 技术 | 版本 | 说明 |
|------|------|------|
| Spring Boot | 2.7.x | 后端框架 |
| Spring Security | 5.7.x | 安全框架 |
| JWT | 0.11.x | 身份认证 |
| MyBatis Plus | 3.5.x | ORM框架 |
| MySQL | 8.0.x | 数据库 |
| Redis | 6.x | 缓存 |
| MinIO | 8.x | 文件存储 |
| RabbitMQ | 3.x | 消息队列 |
| Elasticsearch | 7.x | 全文检索 |
| Swagger 3 | 3.0.x | API文档 |

### 前端技术栈
| 技术 | 版本 | 说明 |
|------|------|------|
| Vue | 3.x | 前端框架 |
| TypeScript | 4.x | 类型系统 |
| Element Plus | 2.x | UI组件库 |
| Pinia | 2.x | 状态管理 |
| Vue Router | 4.x | 路由管理 |
| Vite | 4.x | 构建工具 |
| ECharts | 5.x | 图表库 |
| Axios | 1.x | HTTP客户端 |

### 系统架构
```
┌─────────────────────────────────────────────────────────┐
│                     前端层 (Vue 3)                      │
├─────────────────┬─────────────────┬─────────────────────┤
│   PC管理端      │    移动端H5     │    微信小程序        │
└─────────────────┴─────────────────┴─────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────┐
│                      网关层 (Nginx)                      │
└─────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────┐
│                     后端层 (Spring Boot)                 │
├─────────────────┬─────────────────┬─────────────────────┤
│  认证授权模块   │  业务功能模块   │  系统管理模块        │
└─────────────────┴─────────────────┴─────────────────────┘
                              ↓
┌─────────────────┬─────────────────┬─────────────────────┐
│   MySQL数据库   │    Redis缓存    │    MinIO文件存储     │
├─────────────────┼─────────────────┼─────────────────────┤
│ RabbitMQ消息队列│ Elasticsearch检索│ 定时任务            │
└─────────────────┴─────────────────┴─────────────────────┘
```

---

## 🚀 快速开始

### 环境要求
- JDK 1.8+
- Node.js 16+
- MySQL 8.0+
- Redis 6.0+
- MinIO（可选）

### 后端启动
```bash
# 1. 克隆项目
git clone https://github.com/yourname/springboot-university-management-system.git

# 2. 导入数据库
cd springboot-university-management-system/sql
mysql -u root -p < university_management.sql

# 3. 修改配置文件
cd ../src/main/resources
# 复制 application-dev.yml.example 为 application-dev.yml
# 配置数据库、Redis、文件存储等信息

# 4. 启动后端
mvn spring-boot:run
```

### 前端启动
```bash
# 进入前端目录
cd frontend

# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 生产环境构建
npm run build
```

### 默认账号
| 角色 | 账号 | 密码 | 权限说明 |
|------|------|------|----------|
| 超级管理员 | admin | 123456 | 系统最高权限 |
| 教务处管理员 | jwc | 123456 | 教务处全部功能 |
| 教师 | teacher | 123456 | 教师端功能 |
| 学生 | student | 123456 | 学生端功能 |
| 后勤管理员 | hq | 123456 | 后勤管理功能 |
| 财务管理员 | cw | 123456 | 财务管理功能 |

> 📢 更多账号和完整权限说明，请加微信 **xunmaw001** 获取

---

## 📸 系统截图

### 登录页面
![登录页面](docs/images/login.png)

### 管理员控制台
![管理员控制台](docs/images/admin-dashboard.png)

### 学生课表查询
![学生课表查询](docs/images/student-schedule.png)

### 教师成绩录入
![教师成绩录入](docs/images/teacher-score.png)

### 排课管理
![排课管理](docs/images/course-schedule.png)

### 统计分析
![统计分析](docs/images/statistics.png)

> 📢 完整系统截图和演示视频，请加微信 **xunmaw001** 获取

---

## 📁 项目结构
```
springboot-university-management-system/
├── backend/                     # 后端代码
│   ├── src/main/java/com/university/
│   │   ├── common/              # 公共模块（工具类、异常处理、常量）
│   │   ├── framework/           # 框架核心（安全、认证、数据源）
│   │   ├── modules/             # 业务模块
│   │   │   ├── system/          # 系统管理模块
│   │   │   ├── educational/     # 教务管理模块
│   │   │   ├── student/         # 学生管理模块
│   │   │   ├── teacher/         # 教师管理模块
│   │   │   ├── logistics/       # 后勤管理模块
│   │   │   ├── financial/       # 财务管理模块
│   │   │   └── examination/     # 考试管理模块
│   │   └── UniversityApplication.java # 启动类
│   └── src/main/resources/
│       ├── mapper/              # MyBatis XML文件
│       ├── application.yml      # 主配置文件
│       └── application-dev.yml  # 开发环境配置
├── frontend/                    # 前端代码
│   ├── src/
│   │   ├── api/                 # API接口定义
│   │   ├── assets/              # 静态资源
│   │   ├── components/          # 公共组件
│   │   ├── views/               # 页面视图
│   │   │   ├── system/          # 系统管理页面
│   │   │   ├── educational/     # 教务管理页面
│   │   │   ├── student/         # 学生相关页面
│   │   │   ├── teacher/         # 教师相关页面
│   │   │   └── dashboard/       # 控制台页面
│   │   ├── router/              # 路由配置
│   │   ├── store/               # 状态管理
│   │   └── utils/               # 工具函数
│   └── package.json
├── sql/                         # 数据库脚本
│   ├── university_management.sql # 完整数据库脚本
│   └── update/                  # 升级脚本
└── docs/                        # 文档和截图
    ├── images/                  # 系统截图
    ├── deploy.md                # 部署文档
    ├── api.md                   # API文档
    └── development.md           # 开发文档
```

---

## 🎯 核心功能模块

### 1. 系统管理模块
- 用户管理、角色管理、权限管理、菜单管理
- 部门管理、岗位管理、字典管理、参数设置
- 通知公告、操作日志、登录日志、在线用户
- 服务监控、缓存监控、Druid监控

### 2. 教务管理模块
- 院系管理、专业管理、班级管理、课程管理
- 培养方案管理、教学计划管理、排课管理
- 选课管理、成绩管理、绩点计算、成绩单生成
- 考试安排、考场管理、监考安排、成绩分析

### 3. 学生管理模块
- 学籍管理、信息采集、异动管理、毕业管理
- 奖惩管理、奖学金管理、助学金管理、助学贷款
- 宿舍管理、住宿安排、调换申请、维修管理
- 请假管理、考勤管理、综合素质评价

### 4. 教师管理模块
- 教师信息管理、职称管理、科研管理
- 授课管理、成绩录入、教学评价、听课记录
- 毕业设计指导、论文评阅、答辩管理
- 工作量统计、绩效计算、工资查询

### 5. 后勤管理模块
- 房产管理、楼宇管理、教室管理、场地管理
- 资产管理、设备管理、耗材管理、采购管理
- 报修管理、维修派单、工程管理、验收管理
- 食堂管理、校园卡管理、车辆管理、卫生管理

### 6. 财务管理模块
- 收费项目管理、学费收取、住宿费收取
- 缴费记录、欠费管理、票据管理
- 工资管理、绩效计算、个税申报
- 预算管理、报销管理、财务报表

---

## 🔧 系统特色
- 🎯 **模块齐全**：覆盖高校所有核心业务场景，可直接上线使用
- 📱 **多端支持**：PC端、移动端、小程序多端适配
- 🔒 **安全可靠**：基于Spring Security的细粒度权限控制
- 📊 **数据可视化**：丰富的统计图表和BI分析功能
- ⚡ **高性能**：Redis缓存、异步处理、分库分表支持
- 📝 **文档完善**：详细的开发文档和部署教程
- 🎨 **界面美观**：基于Element Plus的现代化UI设计
- 🔧 **易于扩展**：模块化设计，便于二次开发和功能扩展

---

## 🎓 适合场景
1. **毕业设计/课程设计**：完整的项目架构和功能，轻松应对毕设答辩
2. **学习参考**：学习Spring Boot、Vue全栈开发的优秀案例
3. **企业二次开发**：可在此基础上开发定制化的高校管理系统
4. **技术研究**：研究微服务架构、权限控制、工作流等技术的实践项目

---

## 🤝 技术支持
💡 有任何问题或需要完整源码，欢迎加微信交流：

**微信：xunmaw001** （备注：GitHub高校系统）

提供服务：
- ✅ 完整源码交付（前后端+数据库）
- ✅ 免费技术答疑和问题解决
- ✅ 远程部署调试服务
- ✅ 毕设指导和论文写作辅导
- ✅ 功能定制和二次开发服务

---

## 📄 许可证
本项目采用 [MIT](LICENSE) 许可证，可自由使用和修改，请保留作者信息。

---

## ⭐ 支持项目
如果这个项目对您有帮助，请点个 Star ⭐ 支持一下！

您的支持是我们持续更新的最大动力！

---

### 📞 联系我们
- 微信：**xunmaw001**
- GitHub：https://github.com/yourname/springboot-university-management-system
- 邮箱：your_email@example.com

> 💡 加微信免费领取《Spring Boot项目实战手册》和《高校管理系统需求规格说明书》！
