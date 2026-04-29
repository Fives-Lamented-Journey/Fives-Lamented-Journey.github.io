# # 国内镜像源，解决rubygems访问慢
# source "https://gems.ruby-china.com"

# # 核心 Jekyll
# gem "jekyll", "~> 4.3"

# # GitHub Pages 官方兼容套件（如需部署Github Pages必加）
# group :jekyll_plugins do
#   gem "github-pages", "~> 232"
#   gem "jekyll-feed"          # 订阅RSS
#   gem "jekyll-seo-tag"       # SEO优化
#   gem "jekyll-sitemap"       # 站点地图
#   gem "jekyll-gist"          # Gist代码嵌入
#   gem "jekyll-paginate"      # 分页
#   gem "jekyll-coffeescript"
#   # gem "jekyll-markdown-parser"
# end

# # 代码高亮、压缩、美化
# gem "rouge"                  # 代码高亮
# gem "webrick"                 # Ruby3.0+ 必备server依赖




source "https://gems.ruby-china.com"

# Jekyll 4.x 本地开发（和 github-pages 解耦）
gem "jekyll", "~> 4.3"
gem "webrick"   # Ruby 3.0+ 运行 Jekyll 必备
gem "rouge"    # 代码高亮

# 插件
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jemoji"   # 新增这一行，解决表情依赖问题
end

# 本地主题依赖（你的 Hydrogen 主题）
# gem "jekyll-theme-hydrogen", path: "."