---
layout: page
title: 赞赏列表
description: Appreciate
keywords: tea9
comments: true
menu: About
permalink: /appreciate/
header-img: 
---

# 感谢各位客官赏赐

<style >
  .wechat img,.alipay img{
	width: 200px;
  	height: 200px;
  	display:inline;
  	vertical-align:middle;
  	margin-right: 40px;
  	/*float:right;*/
  }
  .wechat {
  	float: left;
  	/*margin-right: 20px;*/
  	padding-right: 20px;

  }
  
  table {
  	clear: both;
  }
</style>

{% if site.reward.enable %}
{% if site.reward.wechatpay %}
<div class="wechat" >
  <img class="wechat_qr" src="{{ site.reward.wechatpay }}" title="用微信请{{ site.author }}喝杯咖啡？" alt="用微信请{{ site.author }}喝杯咖啡？" />
  <p>微信支付</p>
</div>
{% endif %}

{% if site.reward.alipay %}
<div class="alipay" >
  <img class="alipay_qr" src="{{ site.reward.alipay }}" title="用支付宝请{{ site.author }}喝杯咖啡？" alt="用支付宝请{{ site.author }}喝杯咖啡？" />
  <p>支付宝</p>
</div>
{% endif %}

{% endif %}

## 赞赏列表


 名字 | 金额 | 途径 | 时间 
-----|-----|-------
Miracles | 6.66| 微信 | 2018-09-06

