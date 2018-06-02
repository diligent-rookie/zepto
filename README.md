## zepto的使用以及bug解决
>* 由于zepto和jQuery的语法极其相似，所以学会使用jQuery就可以使用zepto，相对于jQuery来说zepto更适合移动端开发，因为它封装了相关的移动端事件，虽然摒弃了IE678的兼容，但是这不是它的缺点，恰好移动端的浏览器基本上实现了webkit内核，不必担心zepto的兼容问题，如果实在担心IE兼容问题，我建议将jQuery的1.x版本以IE的if判断作为其后备兼容维护。
>* 使用方法便是在zepto官网上下载zepto.js,但由于tap事件还需要touch.js的辅助，所以需到相关的github下，下载touch.js,并进行处理
>* 在使用zepto的时候，它有一个bug，就是tap事件和click事件的“点透”现象，对此解决的办法下面我的笔记链接中会详细介绍
附链接：https://app.yinxiang.com/shard/s64/nl/20894685/e4c7b3c6-53b6-4e9c-ae9f-2c57926f0ff4?title=%E7%A7%BB%E5%8A%A8%E7%AB%AF%E6%A1%86%E6%9E%B6Zepto
