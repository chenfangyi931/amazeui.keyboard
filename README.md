# amazeui.keyboard
###自适应虚拟键盘1.0插件是基于Amaze UI开发的一款响应式键盘
## 1、	引用js css文件
###<link rel="stylesheet" href="amazeui.min.css">// amazeui  css文件
###<link rel="stylesheet" href="amazeui.keyboard.min.css">// keyboard  css文件
###<script type="text/javascript" src="jquery.min.js">// jquery 文件
###<script type="text/javascript" src="amazeui.min.js">// amazeui js 文件
###<script type="text/javascript" src="amazeui.keyboard.min.js">// keyboard  js 文件
##2、	设置class类或ID
###<input class="keyboard" /> 
###<textarea id="keyboard" ></textarea>
##3、	最后一步,绑定事件
###  $('.keyboard').keyboard({ type: 'English' });
###  $('#keyboard').keyboard({ type: 'English' });
##键盘功能API
###type: English、Number、Chinese(英文、数字、中文)
###upset: true、false(开启混淆,中文键盘是没有这个功能的)
###extend: true、false(开启符号扩展,中文键盘是自带这个功能不能关闭)
###$().keyboard_End();(关闭键盘,考虑到需要做点击键盘以外的地方关闭键盘)
