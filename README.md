# 嘎嘎的斯芬克斯文档
## 常用命令
### 克隆仓库命令
```sh
git@github.com:pixars-burger/GaGa-sphinx-docs.git
```
### 生成 SSH 密钥
```sh
ssh-keygen -t ed25519 -C "your_email@example.com"
```
### 编译 Sphinx 文档
```sh
make.bat html
```
### 编译完成后复制更新后的文档到docs目录
```sh
xcopy build\html docs\ /E /I /Y
```
### 上传代码
```sh
git add .
git commit -m "描述你的更改内容"
git push origin branch_name
```
### 拉取最新代码
```sh
git pull origin branch_name
```
