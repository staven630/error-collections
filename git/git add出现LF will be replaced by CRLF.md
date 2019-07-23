# 根源

&emsp;&emsp;git执行Linux命令行，在Linux下的换行符为LF，而windows下的换行符为 CRLF

# 解决办法

```bash
rm -rf .git
// 禁用自动转换
git config --global core.autocrlf false

git init
git remote add origin xxxxx
git add .
```