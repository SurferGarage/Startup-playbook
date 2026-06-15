# 如何为本指南做贡献？

> 面向 **第一次提 PR** 的同学。5 分钟读完即可动手。

---

## 1. 准备环境

1. 注册 [GitHub](https://github.com) 账号
2. 打开本仓库，点击右上角 **Fork**
3. 在你 Fork 的仓库页面，点击 **Code** → 复制 HTTPS 地址
4. 本地执行：

```bash
git clone https://github.com/你的用户名/Startup-playbook.git
cd Startup-playbook
```

---

## 2. 选一个任务

**方式 A — 领悬赏：** 查看 [Bounty Board](./docs/BOUNTY_BOARD.md)，选 `🟢 待认领` 任务

**方式 B — 自由贡献：**

- 补充 `docs/` 章节正文
- 在 `toolkit/` 添加实测工具或模板
- 修正错别字、死链、排版

---

## 3. 新建分支并修改

```bash
git checkout -b docs/my-contribution
# 编辑文件后
git add .
git commit -m "docs: 简短说明你的改动"
git push origin docs/my-contribution
```

---

## 4. 提交 Pull Request

1. 打开你 Fork 的仓库 on GitHub
2. 点击 **Compare & pull request**
3. 标题示例：`[docs] 补充 Mom's Test 访谈脚本` 或 `[bounty B-002] 添加 3 个 AI 工具`
4. 在描述里写：做了什么、为什么对小白有帮助
5. 提交 PR，等待 Maintainer Review

---

## 5. 写作提醒

- ✅ 真实经验、可执行步骤、 checklist
- ❌ 搬运二手鸡汤、未脱敏隐私、投资建议

完整标准见 [浪前开源指南](https://github.com/SurferGarage/.github/blob/main/docs/GUIDE.md)。

---

## 6. 合并之后

- 名字进入 README **Hall of Fame**
- Bounty 任务会在榜单更新你的 GitHub ID

有问题可开 Issue，或加入浪前微信社群（见 [组织 README](https://github.com/SurferGarage)）。
