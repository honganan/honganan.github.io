# 修改博客步骤
1. 切换到 main 分支
1. 修改 source/_post/ 下博客内容
1. 执行 hexo server，点击生成的链接查看效果，验证没问题
1. 执行 hexo generate
1. 执行 hexo deploy，会自动提交内容到 github 的 gh-pages 分支并触发网站重新生成
- main 分支用来维护原始内容
- deploy 时自动提交到 gh-pages 分支并生成静态内容覆盖原来的 gh-pages 内容
1. 提交 main 分支原始内容
