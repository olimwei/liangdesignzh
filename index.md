---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_0.jpg
widget1:
  title: "住宅设计"
  url: '/house-design'
  image: widget-1-302x400.jpg
  text: '<em>明设计事务所</em> 为大温地区客户量身定制属于您自己的梦想家园。'
widget2:
  title: "室内设计"
  url: '/interior-design'
  image: widget-2-303x400.jpg
  text: '室内装潢设计，材料搭配，配色，厨房设计，家居布置等，<em>良明设计事务所</em> 提供全程现场跟踪监理服务'
widget3:
  title: "商业店铺设计"
  url: '/commercial-design'
  image: widget-3-303x400.jpg
  text: '珠宝店，饭店，美容院，托儿所，教育机构，办公等等。<em>良明设计事务所</em> 可帮您完成政府报批所需文件和施工文件。'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: http://liangdesign.com
#  url: https://tinyletter.com/feeling-responsive
  text: ---------- 咨询请拨打中文热线：778-300-2111 ----------
  style: alert
permalink: /
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: false
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/fQaiZhNx8B0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
