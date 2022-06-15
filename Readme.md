# Git 用法测试
## 问题汇总
- IDEA 纳入版本控制的文件在 .gitignore 中如何取消
  - 发我
  - ```git
    $ 清理缓存
    git rm -r . --cached
    $ 跟踪所有文件
    git add .
    $ 重新提交
    git commit -m 'update .gitignore'
    ```