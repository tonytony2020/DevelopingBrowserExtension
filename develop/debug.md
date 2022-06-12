# 调试

市场份额排前 5 的浏览器里，如果按内核分类：

- Blink 浏览器内核, 如 Chrome、Edge、其他国产包皮浏览器
- Gecko 内核, 如 Firefox
- Webkit 内核, 如 Safari

其中 Chrome 和 Edge 调试工具 [devtools](https://developer.chrome.com/docs/devtools/) 在体验上最好。

## 使用 XPath 定位 DOM 元素

在 Chrome 中按 F12 快捷键调出控制台，输入

    $x('XPath 表达式')

## 使用 CSS 选择器定位 DOM 元素

在 Chrome 中按 F12 快捷键调出控制台，输入

    $x('CSS 选择器表达式')

## 复制或保存控制台(console)中定位的元素数据

场景：复制一个列表类结构多个元素的文本值。

下面以复制电影 [「WALL·E」](https://www.imdb.com/title/tt0910970/) 配音演员表为例。

在 Chrome 中按 F12 快捷键调出控制台，输入

    $x('//*[@data-testid="title-cast-item__actor"]/text()').forEach((item) => console.log(item))

右击输入行，弹出菜单中选择“另存为……”，保存文本结果类似

    $x(`//*[@data-testid="title-cast-item__actor"]/text()`).forEach((item) => console.log(item))
    VM823:1 "Ben Burtt"
    VM823:1 "Elissa Knight"
    VM823:1 "Jeff Garlin"
    VM823:1 "Fred Willard"
    VM823:1 "MacInTalk"
    VM823:1 "John Ratzenberger"
    VM823:1 "Kathy Najimy"
    VM823:1 "Sigourney Weaver"
    VM823:1 "Teddy Newton"
    VM823:1 "Bob Bergen"
    VM823:1 "John Cygan"
    VM823:1 "Pete Docter"
    VM823:1 "Paul Eiding"
    VM823:1 "Donald Fullilove"
    VM823:1 "Teresa Ganzel"
    VM823:1 "Jess Harnell"
    VM823:1 "Sherry Lynn"
    VM823:1 "Mickie McGowan"
    undefined
