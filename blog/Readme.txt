TODO:
  - 分页优化
  - 头像,图标和超链接修改
  - ...


启动: 
  # jekyll项目在blog/里
  cd blog
  bundle exec jekyll serve
  
部署(静态):
  # 将生成的静态页面复制到git根目录
  cd blog
  cp _site/* ../
  
  # 提交到git
  git add .
  git commit -a -m '更新'
  git pull
  git push
  
