# Zero-Cup-2022

 **白手起家工作室**

##  一、 食用方式

- **在vscode里安装live server插件，用open with live server打开。**

- 原因：由于我们在iframe里进行了对其父元素的dom操作，而又因为同源安全策略，必须在协议、ip地址、端口号完全一样才可以，而默认资源路径为在本机地址，并没有所谓的协议，ip地址和端口号，所以必须在有服务器的状态打开。

## 二、总介绍

我们的网页分为五个部分：

1.  武大传送门主页，以轮播图的形式让用户可以传送到武大各个景点，还有其他景点的概览。
2.  对牌坊，行政楼，宋卿这些武大古建筑的总介绍（分为两页）。
3.  介绍了樱花城堡（分为三页）。
4.  介绍了老图书馆（武汉大学校史馆）。
5.  介绍了万林艺术博物馆。

## 三、 项目目录及其说明

**见同目录文本文档tree.txt**

## 四、 内容相关（page1~6指首页轮播图跳转的页面）

### Index(首页)

- 首页左边的自动播放轮播图选取了武大最具特点的六个风景以响应主题。
- 右边的滑动窗口放置相对次要的风景,添加简单的CSS动画效果和简要的介绍。
- 首页轮播图下方自动变化的按钮增加了互动,可以点击.箭头可以用来切换轮播图页面.了解图片详情可以点击图片,然后会出现传送门效果进入图片描述地点,切合主题。

### PAGE-1，2(武汉大学牌坊，行政楼，宋卿体育馆)

- 牌坊，行政楼，宋卿体育馆的历史源远流长，早已成为每一个whuer心中无法磨灭的那份烙印。与其说他们是一处景点，不如说他们是承载着whu的历史厚重的一份寄托物。所以我使用了一个不太贴切但是意蕴十足的标题名: OLDWHU。用简单的描述加图片表现的出的是他们是什么，他们长何样，说不尽的是它们承载着的那无数份精神寄托。

- 在介绍页面的背景是类似于樱花飘落的动态效果。粉色的樱花，承载着的不仅是每个whuer对于学校的那份热爱，还承载着全国各个地区的学子对于whu的那份澄澈的向往。

- 在查找资料的过程中，我了解到原牌坊已于2012年拆除， 且原图片已不可考究，但我认为牌坊的“OLD”并不只在于时间的沉淀，它的历史意义才是这份“OL D”的根源。

### PAGE-3,4 (樱花城堡)

樱花城堡可谓是武大最知名也是最具特色的建筑群，但多数人(包括我)对它的了解可能并不多，只是惊叹与它的华美气质与恢弘气势。

- 于是在最初的制作过程中，我使用视差滚动及百叶窗这样最能展示图片的样式，想要最大限度地用图片的形式将樱花城堡的景色直观地展示出来。为了衬托出该建筑群的不凡，我搜寻诗句去填充第一个子页面的文字区域，后来找不到合适的诗句，索性自己结合图片作了几句放在第一个子页面。

- 但随着网页的制作，我在查资料的过程中对这个建筑群的历史有了更深的了解，知道了它经历的战争磨难和它的深刻意义。于是我制作了第三个子页面，图片在页面中的占比变小，文字的篇幅加长，背景的色调变暗。一切都是为了将这座建筑的历史和内涵以我所能想到的方式呈现给用户。

### PAGE-5（老图书馆）

- 页面从老图书馆整体开始，点开标题出现其整体介绍和武汉大学校史馆入口
- 然后到达第一个展厅"百年沧桑"，再后面到达"世纪华章"展厅，最后到达"珞珈黉宫"展厅。
- 页面带领观众一步步走入老图书馆，让观众一步步的了解老图书馆的魅力。

### PAGE-6（万林艺术博物馆）

- 首页是万林的名称，把观众带入万林。
- 继续下滑，标题向上淡出，随即出现渐渐放大的万林logo，logo放大之后变得透明，露出后面的对万林介绍的一个视频。
- 继续下滑，万林又从远处渐渐进入页面，滑到最底处便可窥见全貌。
- 最后一页通过轮播图展现了各次展览，点击图片还会出现本次展览的海报，让观众在展览中进一步走进万林，走进艺术。

## 五、制作相关

- 代码规范地分离，将影视文件、结构层、样式层、逻辑层分离开。

- 为了初次合作的团队成员能更好地协作，也为了靠近项目的工程化，我们学习了git和github的使用， 并在本次比赛中加以运用，使用分支处理解决bug

- 为了适应不同的设备和屏幕大小，我们团队成员统一使用vh、vw、rem作为单位，多处使用flex布局，并在css内做了-定的响应式处理，使我们设计的网页能具备更广泛的应用场景。

- 为了完成本次比赛的作品，来自不同学院的我们也顶着期中的压力，尽力抽出大家重合的空闲时间进行了多次小组讨论，才有了最终的这份作品。

### PAGE1

- 标题的OLDWHU采用鼠标移进自动填充的动态效果，提高 了互动性

- 在介绍的文章盒子采用滑入式设计，在盒子内由一段介绍和一组图片构成。图片采用百叶窗的形式进行叠放设计，使得观者的交互感和观赏感更强。盒子的背景采用类似于毛玻璃的效果——~~显然让这八十年代的网页多了很多高级感~~--~~使得画面的整体观赏感有子质的飞跃~~ ——更上一层楼。

-  页面中按钮的字体颜色都采用移上变色的动态效果，也提高了互动性。
- ~~当然页面中还有几个外跳链接可以作为小彩蛋~~~

### PAGE 2

- 打开页面是一个从官方宣传视频截取下来的片段(因为实际上是两个媒体文件的播放，所以在有时候因为加载过程中的问题，会出现上下略有细微的时间误差）

- 用视差图的方式对几个画面进行了观赏，使观感有一定的提高。

### PAGE-3,4 (櫻花城堡)

- 全部三个子页面均可使用左上角的按钮呼出快捷键进行页面的跳转。

- 第一个子页面利用充满高级感视差滚动的效果从上至下的展示了樱花城堡的景色。同时下方有一个带有箭头动画效果的按钮用以跳转到第二个子页面。

- 第二个子页面采用了百叶窗的样式进行展示，背景是个波纹的动画效果。百叶窗展开后下方会有阴影效果和文字描述。仔细观察还会发现五个窗口下方圆圈内的文字连起来是“WHU2022”,算是一个小小彩蛋吧。

- 第三个子页面的背景图会随用户滑动而切换，同时在正文的另-侧还有“國立武漢大學”的字样。

### PAGE-5

- 整个页面采用滚动贴合的方式（通过设置css：``` scroll-snap-type: y mandatory; ```）,让用户体验更流畅
- 通过js监听元素到页面顶部距离动态添加类名，再配合transform实现滚动出现动画
- 百年沧桑部分通过css的``` transform-style: preserve-3d; ```创建出3d环境，再将子元素设置正反两面的图片，悬浮时rotateY实现翻转效果。
- 珞珈黉宫部分通过设置``` column-count: 3;  ```实现瀑布流效果。

### PAGE-6

- 整个页面通过监听滚动事件动态设置元素的大小和透明度，实现平滑的过渡效果。
- 最后部分通过监听mousemove事件追踪鼠标位置，再为轮播图部分设置``` perspective: 3000px; ``` 使其有3d效果，然后根据鼠标的位置动态旋转和移动轮播图，实现轮播图跟随鼠标转的效果
- 轮播图部分通过js动态添加内容

## 六、 第三方库和资源

### 第三方库

- jQuery：用来进行dom操作和一些过渡动画的实现，主要是fadeIn（）之类的

### 资料来源

- [视觉中国 (vcg.com)](https://www.vcg.com/)
- [哔哩哔哩 (゜-゜)つロ 干杯~-bilibili](https://www.bilibili.com/)
- 知乎 (zhihu.com)](https://www.zhihu.com/)
- [百度文库 (baidu.com)](https://wenku.baidu.com/?_wkts_=1667701085979)

**由于时间紧迫，技术有限，页面中存在一些bug，请多多包涵~**

