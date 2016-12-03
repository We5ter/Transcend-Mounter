<a href="https://fishshell.com" target="_blank">fishshell</a>是一个Unix shell。fish是friendly interactive shell的缩写。fish会根据你的历史输入和补完来提供命令建议，就像Netscape Navigator 4.0!

* 安装见官网安装FAQ，macOS可直接使用homebrew、macports安装
 
* 使用<a href="https://github.com/oh-my-fish/oh-my-fish" target="_blank">oh-my-fish</a>
   <code>curl -L http://get.oh-my.fish | fish</code>

* 配置

> oh-myfish对于fish犹如oh-my-zsh对于zsh一样, fish和oh-my-fish在Github里有详细的安装方法

下面是配置文件的位置:
<pre><code>~/.config/fish/config.fish #fish的原始配置
~/.local/share/omf #oh-my-fish的安装目录
~/.config/omf/ #oh-my-fish的配置
其中oh-my-fish配置里又有下面四个文件:

theme - 当前主题
bundle - 显示当前已安装的插件/主题列表
init.fish - shell开始后执行的自定义脚本
before.init.fish - shell开始前执行的自定义脚本
</code></pre>
>oh-my-fish和oh-my-zsh不一样的是他提供类似插件管理的命令omf, 类似brew或者pip一样通过命令就可以管理插件和theme, 非常的方便

* 主题安装
<pre><code>#官方主题介绍页面
https://github.com/oh-my-fish/oh-my-fish/blob/master/docs/Themes.md
===================================
omf theme  #列举全部主题
omf install xxx
</code></pre>



* 更多请参阅<a href="https://github.com/We5ter/Fishshell-Docs" target="_blank">fishshell简明中文文档</a>（挖个坑）
