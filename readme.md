### github action workflows 笔记

- 创建git仓库

    git init

- 创建github action脚本

    mkdir -p .github/workflows/test.yml

    脚本名可以自定义，在此目录下github自动识别

- 绑定远程github仓库

    git remote add https:///.git

- 修改git标签为main
 
    git branch -M main

- 上传

    git push origin main