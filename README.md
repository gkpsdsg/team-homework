# team-homework
团队仓库
# team-homework 团队作业仓库

欢迎来到我们的课程团队作业仓库！
这里是项目的统一管理与协作平台。

---

## 📂 仓库目录分工
- `/docs`：存放作业报告、设计文档、说明文档
- `/code`：存放项目核心代码
- `/tests`：存放测试用例、测试报告
- `/assets`：存放图片、资源文件（可选）

---

## 📌 协作规则（所有人必须遵守）
1.  **禁止直接修改 `main` 主分支！** 所有修改都必须在个人分支上完成。
2.  每个人创建自己的分支，命名格式：`姓名/功能`
    - 示例：`zhangsan/login-page`、`lisi/backend-api`
3.  完成开发后，提交 **Pull Request (PR)** 给组长审核，通过后再合并到 `main` 分支。
4.  提交信息格式要清晰：`完成XX功能 / 修改XX文档 / 修复XX问题`
    - ✅ 示例：`完成用户登录页面代码`
    - ❌ 禁止：`改了一点东西`

---

## 🚀 队友本地操作指南（复制给队友）
```bash
# 1. 克隆仓库到本地
git clone https://github.com/gkpsdsq/team-homework.git

# 2. 进入仓库目录
cd team-homework

# 3. 创建并切换到自己的分支（把名字换成你的）
git checkout -b 你的名字/你的功能

# 4. 完成代码/文档修改后，提交
git add .
git commit -m "提交信息（写清楚做了什么）"
git push origin 你的名字/你的功能

# 5. 去 GitHub 仓库页面，提交 Pull Request 给组长审核
