# 云端耀斑挡泥板

## 介绍

云端耀斑挡泥板是一个基于 Web 的 Cloudflare 资源管理控制台，支持管理 Cloudflare Workers、DNS 记录等云服务资源。

## 项目来源

本项目基于 [Gitee 开源项目 - cloudflare-mudguard](https://gitee.com/ling-xukun/cloudflare-mudguard) 进行智能搬运与二次开发。

### 致谢与授权

- 原始项目作者：**ling-xukun**
- 原始项目地址：[https://gitee.com/ling-xukun/cloudflare-mudguard](https://gitee.com/ling-xukun/cloudflare-mudguard)
- 本项目已获得原作者授权，允许在原有代码基础上进行搬运、修改和再分发。

### 与原项目的关系

| 项目 | 说明 |
|------|------|
| 原项目 | Cloudflare 管理面板的基础实现 |
| 本项目 | 在原项目基础上进行功能扩展、界面优化及 Bug 修复 |

我们尊重开源精神，感谢 ling-xukun 的卓越贡献。本项目的所有修改和新增内容同样遵循 MIT 开源协议。

## 功能特性

- **用户认证** - 安全的登录功能
- **Workers 管理** - 查看和管理 Cloudflare Workers
- **DNS 解析管理** - 管理域名 DNS 记录（支持 A、CNAME、MX、TXT 等记录类型）
- **仪表盘** - 查看资源概览信息

## 技术栈

- 前端：HTML5 + JavaScript
- 样式：Tailwind CSS
- API：Cloudflare API

## 使用说明

### 前提条件

- Cloudflare 账户
- 已配置 Cloudflare API Token 或 API Key

### 部署

1. 将项目部署到 Web 服务器
2. 配置 Cloudflare API 凭证
3. 访问控制台登录页面

### 配置

在控制台中添加您的 Cloudflare 邮箱和 API Key 即可连接 Cloudflare 账户。

## 参与贡献

1. Fork 本仓库
2. 新建特性分支 (`git checkout -b feat/xxx`)
3. 提交更改
4. 创建 Pull Request

## 许可证

MIT License

---

了解更多 Cloudflare 服务，请访问：[cloudflare.com](https://www.cloudflare.com)