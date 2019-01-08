### [Bassoon](https://github.com/zhanglintc/Bassoon)
尝试着实现了一个 WSGI 服务器和一个简单的 Framework. 不要问我为什么叫 Bassoon(巴松管), 这就是随机出来的一个单词. Bassoon.py 里主要有两个大类: **BassoonServer** 是一个 WSGI 服务器, 比 wsgiref 还简单. **BassoonApp** 可以说就是框架, 使用其中的 get 和 post 就可以完成路由功能了. 可以查看 example.py 中的用法. 实现的时候参考了 [Bottle](https://bottlepy.org/) 框架. 还需要继续完善模版等功能.

-----

### [Mmrz-Extension](https://github.com/zhanglintc/Mmrz-Extension)
Chrome 浏览器插件, 特意为 [Mmrz-Sync](https://github.com/zhanglintc/Mmrz-Sync) 开发, 功能非常简单, 仅仅是为浏览器添加一个右键快捷方式, 能够直接打开新标签页使用 Mmrz-Sync 查询当前选中的日语单词.

Chrome Web Store 访问地址: [Mmrz search helper](https://chrome.google.com/webstore/detail/mmrz-search-helper/oeeiknpedgobffmdmgpeloongnaklphl).

-----

### [sudoku-solver](https://github.com/zhanglintc/sudoku-solver)
媳妇儿做数独, 半天没做出来, 于是我想为啥不用程序做? 虽然网上也有, 但是我还是想自己搞一个. 原理很简单: 递归暴力尝试. 单 HTML 页面, 托管在GitHub 上, 没有后台, 纯 JavaScript 计算. PS: 刚才发现我其实两年前就在 LeetCode 上做过这个题...

访问地址: [sudoku-solver](http://zhanglintc.co/sudoku-solver).

-----

### [Mmrz-Sync](https://github.com/zhanglintc/Mmrz-Sync)
本来只是 [Mmrz](https://github.com/zhanglintc/Mmrz) 项目的同步服务器. 现在却承担起了网页版的任务, 不但是一个同步服务器, 同时也是一个全平台访问的网页版. 使用 bottle.py 作为后台开发框架.

网页版访问地址: [mmrz.zhanglintc.co](https://mmrz.zhanglintc.co).

-----

### [MySpring](https://github.com/zhanglintc/MySpring)
简单实现了一下 Spring 中的一些基本功能. 主要是为了加深对 Java 反射机制的理解.

-----

### [Mmrz](https://github.com/zhanglintc/Mmrz)
一个用于背诵日语单词的小工具. 思路类似于有道单词本的, 按照艾宾浩斯遗忘曲线的时间点进行提醒. 每次背诵需要每个单词都选择记住, 否则会一直重复背诵, 直到记住为止. 并且本次没有记住的单词会很快进入下一次提醒, 加深印象. 根据以前背诵英语的经验来看, 绝对异常有效.

-----

### [Weather](https://github.com/zhanglintc/weather)
Android 平台下的天气 App. 使用 World Weather Online 提供的 API( [Addr](http://www.worldweatheronline.com) ). 不会有什么太难的东西, 就是想和大家一起练练手而已.

-----

### [wb](https://github.com/zhanglintc/wb)
命令行访问微博的客户端, 能够在 Linux/Mac/Windows 平台下使用. 但是最近微博开放平台越来越坑爹, 感觉也玩儿不出什么花样了. 尾巴也肯定申请不到了! :cry:

-----

### [tools-lite](https://github.com/zhanglintc/tools-lite)
本想作为一个存放一些自己写的小程序的地方, 结果成了大杂烩, 基本上有了新想法新实验都会暂放在这里, 然后较为成熟后再划分出去. 目前主要以 Python 工具为主, Batch 文件次之, 其外有一些自己用的配置文件什么的. 并且在努力增加 Ruby 工具的数量.

-----

### [leetcode](https://github.com/zhanglintc/leetcode)
存放 [leetcode.com](http://leetcode.com) 上所有我已经完成题目的答案. 优先使用 Python 解决问题, 然后有空的时候再用 C++ 和 Java 重写. 如果以后有时间再考虑使用 JavaScript 以及 Ruby 等都重写一遍.

-----

### [5th](https://github.com/zhanglintc/5th)
最近翻出来的大概两年前做的一个 Android 小项目, 实现的功能就是音乐播放器. 貌似当时 Android 还正处于逐渐火起来的状态. 当时是为了完成一个任务, 作为一个团队写的这个音乐播放器, 署名是一个团队, 其实可以负责任的说: 全是我一个人搞的啊! :joy:

-----

### [tetris](https://github.com/zhanglintc/tetris)
在用 C++ 实现了贪吃蛇以后, 又想尝试着做一个俄罗斯方块, 于是有了这个项目. 很多函数都是直接拷贝 [snake](https://github.com/zhanglintc/snake) 中的, 只是逻辑和显示变成了俄罗斯方块. 同样支持 中文/日文 的电脑系统.

-----

### [snake](https://github.com/zhanglintc/snake)
C++ 实现的一个贪吃蛇. 主要是刚入职新公司时需要学习 C++, 于是便编写了一个 C++ 程序作为练习. 只能在 Windows 下运行使用, 能够支持 中文/日文 的电脑系统. 最新的计划是如果可以, 增加 AI 自动寻找食物直到完全填充完屏幕为止.(路径算法什么鬼的, 肯定很难...)

## 友情链接:

-----

- [IMLANE](http://imlane.top)

-----

[渝ICP备17002936号](http://www.miitbeian.gov.cn/)

<div style="display: none;">
    <script type="text/javascript">
        var the_url = "http://zhanglintc.work:8000/send?text=zhanglintc.co has been viewed from: " + (document.referrer || "direct");
        document.write('<scr' + 'ipt src="' + the_url + '"></scr'+'ipt>');
    </script>
</div>
