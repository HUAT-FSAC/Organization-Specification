# 项目规范说明

## 规范文件列表

本项目包含以下规范文件：

1. **DEVELOPMENT_FLOW_SPEC.md** - 开发流程规范
   - 项目初始化与规划
   - 代码开发流程
   - 代码审查与测试
   - 版本控制与发布
   - 团队协作与沟通
   - 文档管理
   - 代码质量保证
   - 问题追踪与修复
   - 性能优化
   - 安全规范
   - 持续集成与持续部署
   - 项目维护与迭代
   - 团队建设与知识共享
   - 规范执行与改进

2. **CODE_STYLE.md** - 代码风格规范
   - 命名规范
   - 代码格式
   - 注释规范
   - 代码结构
   - 语言特定规范
   - 代码质量
   - 工具配置
   - 规范执行

3. **GIT_COMMIT_SPEC.md** - Git Commit 规范
   - 提交信息格式
   - 提交类型
   - 作用域
   - 提交信息示例
   - 提交规范执行
   - 常见问题处理
   - 工具推荐
   - 最佳实践

4. **PR_FLOW_SPEC.md** - PR 流程规范
   - PR 创建前准备
   - PR 创建流程
   - PR 审查流程
   - PR 合并流程
   - PR 模板
   - 常见问题处理
   - 最佳实践

5. **.github/pull_request_template.md** - PR 模板
   - PR 描述模板
   - 检查列表
   - 相关链接

## 规范使用说明

### 1. 开发流程规范
- 所有项目成员应熟悉并遵循开发流程规范
- 项目负责人应确保项目开发按照规范进行
- 定期回顾和更新规范，以适应项目发展

### 2. 代码风格规范
- 所有代码应符合代码风格规范
- 使用 ESLint、Prettier 等工具自动检查和格式化代码
- 在代码审查中检查代码风格是否符合规范

### 3. Git Commit 规范
- 所有 Git 提交信息应符合规范
- 使用 commitizen、commitlint 等工具辅助生成和检查提交信息
- 提交前应检查提交信息是否符合规范

### 4. PR 流程规范
- 所有代码变更应通过 PR 进行
- 严格按照 PR 流程进行代码审查和合并
- 使用 PR 模板确保 PR 信息的完整性

## 工具配置

### 1. ESLint 配置
- 安装：`npm install --save-dev eslint`
- 配置文件：`.eslintrc.js`

### 2. Prettier 配置
- 安装：`npm install --save-dev prettier`
- 配置文件：`.prettierrc.js`

### 3. commitlint 配置
- 安装：`npm install --save-dev @commitlint/cli @commitlint/config-conventional`
- 配置文件：`.commitlintrc.js`

### 4. husky 配置
- 安装：`npm install --save-dev husky`
- 配置：在 `package.json` 中添加 husky 配置

## 规范执行监督

- 项目负责人应监督规范的执行情况
- 定期组织规范培训和学习
- 对违反规范的行为进行适当的处理
- 持续改进规范，以适应项目发展

## 结语

本项目规范旨在确保团队协作的效率和代码质量的提高。团队成员应严格遵守本规范，并在实践中不断完善和改进。通过规范的开发流程，我们可以提高代码质量，减少问题发生，提升团队协作效率，最终交付高质量的项目成果。