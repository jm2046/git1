title: my
date: 2016-01-08 21:47:41
tags:
---
有网友反应右键菜单中没有git bash选项，可以进入开始菜单找到git bash，然后通过cd进入相应目录执行命令。
在github部署完成之后，马上访问可能出现404错误，这是正常的，（最多）等待十分钟左右就可以访问了。如果还不行，那很可能是 github 发送给你的验证邮件你没有打开看，据多方反映，验证后就没问题了。
如果在hexo d之后出现fatal: 'username.github.io' does not appear to be a git repository，一是检查 repo 的名字是否合乎规范、是否含有大写字母、config.yml 中的 deploy 配置是否正确，二是把 git bash 关掉，重新打开再执行命令。
有的同学可能不是 IT 界的，或者对shell 命令不太了解。在要求输入密码时，你输入之后密码是不显示的，这是为了安全，并非是你没输上。
出现乱码的，不要使用 windows 中的「记事本」打开并编辑文件，推荐使用 sublime text，很简单。如果已经在「记事本」中编辑过，需要使用 sublime text 转码为「utf8」。
安装 hexo 时卡在那儿不动，很可能是网络不给力，能全局 break wall 就好了。
遇到什么其他的问题，不妨删除.deploy 和db.json 再重新生成试一试。
tips