# BG Global Digital Limited 官网

这是可直接部署的静态网站，无需安装依赖或运行构建。

## 上传 GitHub
1. 新建 GitHub 仓库。
2. 将压缩包解压后的全部文件上传到仓库根目录，确保 index.html 直接位于根目录。
3. 在仓库 Settings → Pages 中，选择 Deploy from a branch。
4. 选择 main 分支和 / (root)，保存后等待 GitHub Pages 发布。

Git 负责版本管理；GitHub Pages 负责网站托管。也可将这些文件部署到其他静态网站托管服务。

## 文件说明
- index.html：页面内容
- styles.css：基础样式
- experience.css：新版视觉与动效
- script.js：中英切换
- experience-translations.js：扩展内容中文文案
- experience.js：币种交互、场景切换与动效
- assets/：本地图片
- .nojekyll：供 GitHub Pages 直接发布静态资源

## 自定义域名
目前包内未设置 CNAME，避免在域名尚未确认时自动绑定。
确认已拥有 bgglbdgt.com 后，在 GitHub Pages 的 Custom domain 中填写域名，并按 GitHub 提示配置域名 DNS 与 HTTPS。
域名注册、DNS 配置及邮箱开通不包含在代码包内。

## 内容与外部资源
- 页面为公司信息展示与咨询，不提供交易功能或实时报价。
- 联系邮箱：compliance@bgglbdgt.com。
- 样式使用 Google Fonts；无法加载时会回退到系统字体。
- 发布前请核实公司资料、实际服务范围与资质表述。

## 图片授权
图片来源与许可也已保留在网页底部的 Image credits 中。
1. assets/bermuda.jpg：Hamilton, Bermuda，Jeff Bellinger，CC BY-SA 3.0。
   来源：https://commons.wikimedia.org/wiki/File:Hamilton,_Bermuda_-_panoramio.jpg
   许可：https://creativecommons.org/licenses/by-sa/3.0/
2. assets/bermuda-coast.jpg：Horseshoe Bay beach, Bermuda，Captain-tucker，CC BY-SA 4.0。
   来源：https://commons.wikimedia.org/wiki/File:Horseshoe_Bay_beach,_Bermuda_IMG_0356.jpg
   作者：https://commons.wikimedia.org/wiki/User:Captain-tucker
   许可：https://creativecommons.org/licenses/by-sa/4.0/
照片在页面中裁切展示；修改或继续使用照片时请遵守相应许可并保留署名。
