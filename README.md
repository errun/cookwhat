# Cookwhat：YouTube 海外版

本仓库旨在复刻并改造开源项目 [`YunYouJun/cook`](https://github.com/YunYouJun/cook)，以服务主要内容来源为 YouTube 视频的海外市场用户。

## 仓库初始化清单

1. **创建 Git 仓库**：在项目目录中运行 `git init`，如果尚未初始化仓库。
2. **配置 Git 用户信息**，确保提交记录拥有正确的作者元数据：
   ```bash
   git config user.name "Your Name"
   git config user.email "your.email@example.com"
   ```
3. **添加初始项目文件**，例如本 README、许可证以及基础配置文件，命令为 `git add .`。
4. **创建首个提交**，以建立仓库历史：
   ```bash
   git commit -m "chore: initialize project"
   ```
5. **关联 GitHub 远程仓库**：在 GitHub 上创建新仓库，并添加为远程地址：
   ```bash
   git remote add origin git@github.com:YourAccount/cookwhat.git
   ```
6. **推送初始提交到 GitHub**：
   ```bash
   git push -u origin main
   ```

完成上述步骤后，即可在构建功能前确保仓库初始化就绪。

## `YunYouJun/cook` 项目能否复刻？

可以——`YunYouJun/cook` 采用 [MIT 许可证](https://github.com/YunYouJun/cook/blob/main/LICENSE) 发布，只要遵守许可证条款，即可自由复制、修改与分发软件，包括商业用途。在改造项目时请注意：

- **保留 MIT 许可证声明**，确保原作者权益。
- **记录所有修改**，让后续使用者了解差异。
- **尊重商标与品牌形象**，未经许可不要暗示获得原作者背书。

## 面向 YouTube 内容与海外市场的改造规划

若要将项目调整为面向国际用户的 YouTube 内容平台，可参考以下路线图：

1. **内容采集**：构建使用 YouTube Data API 拉取视频元数据与统计信息的流程（需遵守 YouTube 服务条款）。
2. **多语言本地化**：提供英语、西班牙语等多种语言，翻译食材名称与操作步骤。
3. **菜谱数据模型**：扩展数据结构，包含视频链接、步骤时间戳以及字幕/隐藏式字幕信息。
4. **界面与体验优化**：针对视频优先呈现优化布局，支持响应式播放器与行动号召覆盖层。
5. **SEO 与分享**：实现 JSON-LD 等结构化数据，适配海外搜索引擎与社交媒体的富预览。
6. **变现准备**：预留联盟营销或赞助内容的集成入口，并遵循各地区法规。
7. **部署流程**：在 Vercel、Netlify 等全球托管平台上配置 CI/CD，并启用 CDN 交付静态资源。

## 下一步计划

- 补充项目脚手架（前端框架、构建工具等）。
- 编写 YouTube API 使用规范与访问频率限制说明。
- 创建 Issue 模板与贡献指南，方便协作。

按照该计划执行，即可在保持开源项目精神的同时，将其成功改造为面向海外市场的 YouTube 内容平台。
