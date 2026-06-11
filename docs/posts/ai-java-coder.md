---
date: 2025-06-11
category:
  - Java
  - AI
tag:
  - Java
  - AI
  - Spring Boot
  - 代码生成
---

# 🚀 AI Java Coder - AI驱动的Java代码生成器

## 简介

在Java开发中，编写CRUD代码是日常工作中最繁琐的部分之一。每次都要重复编写Entity、Repository、Service、Controller，不仅耗时，而且容易出错。

今天我给大家推荐一个我开发的工具 —— **AI Java Coder**，它可以通过自然语言描述，自动生成完整的Spring Boot CRUD代码。

## 示例

输入：
```bash
python ai_java_coder.py "用户管理系统，包含用户ID、用户名、密码、邮箱、手机号、创建时间"
```

自动生成8个文件：
- UserEntity.java (JPA实体类)
- UserRepository.java (数据访问层)
- UserService.java (业务接口)
- UserServiceImpl.java (业务实现)
- UserController.java (REST控制器)
- UserCreateDTO.java / UserUpdateDTO.java / UserResponseDTO.java

## 特性

- 🎯 **中文输入** - 用中文描述需求，AI自动理解
- 📦 **完整CRUD** - 全套代码，开箱即用
- 📝 **中文注释** - 所有注释均为中文
- 🏗️ **最佳实践** - 遵循阿里巴巴Java开发规范
- 🔧 **双框架** - 支持 JPA 和 MyBatis-Plus
- 📊 **Swagger** - 自动添加API文档注解

## 快速开始

```bash
# 克隆仓库
git clone https://github.com/zyggood/ai-java-coder.git
cd ai-java-coder

# 安装依赖
pip install -r requirements.txt

# 配置API密钥
cp .env.example .env
# 编辑 .env 文件

# 生成代码
python ai_java_coder.py "你的需求描述"
```

## 支持我们

如果您觉得这个工具有帮助，欢迎赞助支持！

**比特币 (BTC) 捐赠:**
- SegWit: `bc1q5s8srtuuqvl25fax3ylqscrjvfyes89akmwq0h`
- Legacy: `1FxTo8tgQJHuvpG5rpw3UP31ca3Q5RWPnc`

项目地址: [https://github.com/zyggood/ai-java-coder](https://github.com/zyggood/ai-java-coder)
