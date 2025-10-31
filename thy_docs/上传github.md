
# 1. 完全删除 Git 历史
rm -rf .git

# 2. 确认 .gitignore 已存在并正确
cat .gitignore

# 3. 重新初始化 Git
git init

git config --global user.email "2745794229@qq.com"

git config --global user.name "hzqjgthy"

# 4. 添加文件(大文件会被 .gitignore 排除)
git add .

# 5. 检查哪些文件会被提交(确保没有大文件)
git status

# 6. 创建提交
git commit -m "Initial commit (excluding tutorial materials)"

# 7. 添加远程仓库
git remote add origin https://github.com/hzqjgthy/qwen.git

# 8. 强制推送
git push -u origin master
git push -u origin master --force




