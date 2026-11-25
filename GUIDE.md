# Git 常用命令速查

## 基本流程

```bash
# 查看当前状态
git status

# 把改动加入暂存区
git add .

# 提交一个版本
git commit -m "说明这次改了什么"

# 推送到 GitHub
git push

# 拉取远端最新代码
git pull
```

## 常用概念

- 仓库（repository）：一个项目的文件夹，里面放着代码和每次修改的记录
- 提交（commit）：给当前代码存一个版本快照
- 分支（branch）：从主线上分出来的独立开发线
- 合并（merge）：把分支上的改动并回主线
- Pull Request（PR）：请求别人审核并把你的改动合并进去

## 克隆这个仓库

```bash
git clone https://github.com/Ggg-itaotao/hello-github.git
cd hello-github
python3 hello_world.py
```
