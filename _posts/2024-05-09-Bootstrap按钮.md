---
layout: post
author: k
---
# 实例
<!-- 标准的按钮 -->
<button type="button" class="btn btn-default">默认按钮</button>
<!-- 提供额外的视觉效果，标识一组按钮中的原始动作 -->
<button type="button" class="btn btn-primary">原始按钮</button>
<!-- 表示一个成功的或积极的动作 -->
<button type="button" class="btn btn-success">成功按钮</button>
<!-- 信息警告消息的上下文按钮 -->
<button type="button" class="btn btn-info">信息按钮</button>
<!-- 表示应谨慎采取的动作 -->
<button type="button" class="btn btn-warning">警告按钮</button>
<!-- 表示一个危险的或潜在的负面动作 -->
<button type="button" class="btn btn-danger">危险按钮</button>
<!-- 并不强调是一个按钮，看起来像一个链接，但同时保持按钮的行为 -->
<button type="button" class="btn btn-link">链接按钮</button>

# 按钮大小
<p>
  <button type="button" class="btn btn-primary btn-lg">大的原始按钮</button>
  <button type="button" class="btn btn-default btn-lg">大的按钮</button>
</p>
<p>
  <button type="button" class="btn btn-primary">默认大小的原始按钮</button>
  <button type="button" class="btn btn-default">默认大小的按钮</button>
</p>
<p>
  <button type="button" class="btn btn-primary btn-sm">小的原始按钮</button>
  <button type="button" class="btn btn-default btn-sm">小的按钮</button>
</p>
<p>
  <button type="button" class="btn btn-primary btn-xs">特别小的原始按钮</button>
  <button type="button" class="btn btn-default btn-xs">特别小的按钮</button>
</p>
<p>
  <button type="button" class="btn btn-primary btn-lg btn-block">块级的原始按钮</button>
  <button type="button" class="btn btn-default btn-lg btn-block">块级的按钮</button>
</p>

# 按钮状态
<p>
  <button type="button" class="btn btn-default btn-lg ">默认按钮</button>
  <button type="button" class="btn btn-default btn-lg active">激活按钮</button>
</p>
<p>
  <button type="button" class="btn btn-primary btn-lg ">原始按钮</button>
  <button type="button" class="btn btn-primary btn-lg active">激活的原始按钮</button>
</p>

# 禁用状态
<p>
  <button type="button" class="btn btn-default btn-lg">默认按钮</button>
  <button type="button" class="btn btn-default btn-lg" disabled="disabled">禁用按钮</button>
</p>
<p>
  <button type="button" class="btn btn-primary btn-lg ">原始按钮</button>
  <button type="button" class="btn btn-primary btn-lg" disabled="disabled">禁用的原始按钮</button>
</p>
<p>
  <a href="#" class="btn btn-default btn-lg" role="button">链接</a>
  <a href="#" class="btn btn-default btn-lg disabled" role="button">禁用链接</a>
</p>
<p>
  <a href="#" class="btn btn-primary btn-lg" role="button">原始链接</a>
  <a href="#" class="btn btn-primary btn-lg disabled" role="button">禁用的原始链接</a>
</p>

# 按钮标签
<a class="btn btn-default" href="#" role="button">链接</a>
<button class="btn btn-default" type="submit">按钮</button>
<input class="btn btn-default" type="button" value="输入">
<input class="btn btn-default" type="submit" value="提交">

# 按钮组
<div class="btn-group">
  <button type="button" class="btn btn-primary">Apple</button>
  <button type="button" class="btn btn-primary">Samsung</button>
  <button type="button" class="btn btn-primary">Sony</button>
</div>
<div class="btn-group btn-group-lg">
  <button type="button" class="btn btn-primary">Apple</button>
  <button type="button" class="btn btn-primary">Samsung</button>
  <button type="button" class="btn btn-primary">Sony</button>
</div>
<div class="btn-group-vertical">
  <button type="button" class="btn btn-primary">Apple</button>
  <button type="button" class="btn btn-primary">Samsung</button>
  <button type="button" class="btn btn-primary">Sony</button>
</div>

# 自适应大小的按钮
<div class="btn-group btn-group-justified">
  <a href="#" class="btn btn-primary">Apple</a>
  <a href="#" class="btn btn-primary">Samsung</a>
  <a href="#" class="btn btn-primary">Sony</a>
</div>
<div class="btn-group btn-group-justified">
  <div class="btn-group">
    <button type="button" class="btn btn-primary">Apple</button>
  </div>
  <div class="btn-group">
    <button type="button" class="btn btn-primary">Samsung</button>
  </div>
  <div class="btn-group">
    <button type="button" class="btn btn-primary">Sony</button>
  </div>
</div>

# 内嵌下拉菜单的按钮组
<div class="btn-group">
  <button type="button" class="btn btn-primary">Apple</button>
  <button type="button" class="btn btn-primary">Samsung</button>
  <div class="btn-group">
    <button type="button" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">
    Sony <span class="caret"></span></button>
    <ul class="dropdown-menu" role="menu">
      <li><a href="#">Tablet</a></li>
      <li><a href="#">Smartphone</a></li>
    </ul>
  </div>
</div>

# 分割按钮
<div class="btn-group">
  <button type="button" class="btn btn-primary">Sony</button>
  <button type="button" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">
    <span class="caret"></span>
  </button>
  <ul class="dropdown-menu" role="menu">
    <li><a href="#">Tablet</a></li>
    <li><a href="#">Smartphone</a></li>
  </ul>
</div> 