兼容性 不行
scroll-behavior: smooth

chrome 支持css 但是其他主流浏览器怎么办？ scroll-behavior 失效
用js来写

scroll-behavior  chrome支持 ie不支持
兼容 hack   ie js window.scrollTo(0, 1/8)
requestAnimationFrame(递归函数)
浏览器判断