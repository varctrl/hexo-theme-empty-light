# Hexo Theme Empty Light
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/varctrl/hexo-theme-empty-light/master/LICENSE)
## Demo
[在线预览 Demo](http://varctrl.me)

## Installation
```
$ git clone https://github.com/varctrl/hexo-theme-empty-light themes/empty-light
```
#### 修改站点配置文件中的 `theme` 字段为 `empty-light`
```
# Extensions
## Plugins: http://hexo.io/plugins/
## Themes: http://hexo.io/themes/
theme: empty-light
```
#### 建议每页4篇以上文章
```
index_generator:
  path: ''
  per_page: 4
  order_by: -date
```
```
per_page: 4
pagination_dir: page
```

#### 修改主题配置文件中的icon_url
```
icon_url: your_favicon_url(16*16px)
```
### 创建About界面
```
hexo new page "about"
```
## Change Log
####  V1.0.0 OK
