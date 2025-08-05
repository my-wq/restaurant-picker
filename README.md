# 🍽️ 随机选饭店工具

> 智能餐厅推荐助手，告别选择困难症！

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Website](https://img.shields.io/website?url=https%3A//xuanmojinxue.com)](https://xuanmojinxue.com)

## 🌟 功能特色

- 🎯 **精准定位**：自动获取您的当前位置
- 🗺️ **地图选点**：点击地图任意位置搜索附近餐厅
- 📏 **自定义范围**：支持米/公里单位，灵活设置搜索范围
- 🎲 **随机推荐**：智能随机推荐，告别选择困难症
- 🏷️ **分类筛选**：按餐厅类型精准筛选（中餐、西餐、快餐等）
- 🧭 **一键导航**：直接跳转到地图应用进行导航
- 📱 **响应式设计**：完美适配手机、平板、电脑

## 🚀 在线体验

**立即体验**: [https://xuanmojinxue.com](https://xuanmojinxue.com)

## 📱 使用方法

1. **定位授权**：允许网站获取您的位置信息
2. **设置范围**：输入搜索范围（如"2公里"、"500米"）
3. **等待搜索**：系统自动搜索附近餐厅
4. **选择餐厅**：
   - 浏览列表选择心仪餐厅
   - 点击"随机推荐"获得惊喜推荐
   - 使用分类筛选缩小选择范围
5. **导航到达**：点击导航按钮直达目标餐厅

## 🛠️ 技术实现

### 核心技术
- **前端**: 纯HTML + CSS + JavaScript
- **地图服务**: 高德地图API
- **定位服务**: HTML5 Geolocation API
- **设计风格**: 响应式设计，Microsoft Fluent Design风格

### API支持
- 高德地图 Web API v2.0
- POI搜索API
- 地理编码API
- 逆地理编码API

## 🎯 项目特点

- ✅ **零依赖**：纯原生JavaScript开发，无需任何框架
- ✅ **离线友好**：核心功能支持离线使用（地图除外）
- ✅ **轻量级**：单文件部署，体积小加载快
- ✅ **SEO友好**：完整的meta标签和语义化HTML
- ✅ **跨平台**：支持所有现代浏览器

## 📂 项目结构

```
restaurant-picker/
├── index.html          # 主应用文件
├── LICENSE             # MIT许可证
├── README.md           # 项目说明
└── 部署指南.md         # 详细部署指南
```

## 🚀 部署指南

### 快速部署到Vercel

1. Fork本仓库到您的GitHub账号
2. 访问 [Vercel](https://vercel.com)
3. 导入GitHub仓库
4. 自动部署完成！

### 其他部署方式

详细部署说明请参考：[部署指南.md](./部署指南.md)

支持的部署平台：
- Vercel（推荐）
- Netlify
- GitHub Pages
- 传统虚拟主机
- 云服务器 + Nginx

## 🤝 贡献指南

欢迎提交Issue和Pull Request！

### 开发环境

1. **克隆仓库**
   ```bash
   git clone https://github.com/yourusername/restaurant-picker.git
   cd restaurant-picker
   ```

2. **本地预览**
   - 直接用浏览器打开 `index.html`
   - 或使用本地服务器：`python -m http.server 8000`

3. **提交修改**
   ```bash
   git add .
   git commit -m "feat: 添加新功能"
   git push origin main
   ```

## 📊 更新日志

### v2.0 (2025.8.5)
- 🎉 重构代码架构，优化性能
- ✨ 新增随机推荐功能
- 🏷️ 完善餐厅分类系统
- 📱 优化移动端体验
- 🔧 修复搜索范围解析问题

### v1.0 (2025.8.1)
- 🎯 基础定位和搜索功能
- 🗺️ 地图交互功能
- 📏 自定义搜索范围

## 🙋‍♂️ 常见问题

**Q: 为什么定位失败？**
A: 请确保浏览器已授权位置权限，或手动输入地址进行搜索。

**Q: 为什么搜索不到餐厅？**
A: 可能是搜索范围太小，建议扩大搜索范围到1-5公里。

**Q: 支持哪些地区？**
A: 基于高德地图API，主要支持中国大陆地区。

## 📞 联系方式

- 🌐 **官网**: [xuanmojinxue.com](https://xuanmojinxue.com)
- 📧 **邮箱**: contact@xuanmojinxue.com
- 🐛 **问题反馈**: [GitHub Issues](https://github.com/yourusername/restaurant-picker/issues)

## 📄 许可证

本项目基于 [MIT License](./LICENSE) 开源，欢迎自由使用和修改。
