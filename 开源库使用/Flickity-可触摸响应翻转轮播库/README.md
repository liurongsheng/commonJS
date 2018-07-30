
# 插件名 Flickity

## 描述：触摸，响应，可翻转的旋转木马插件 

[插件地址](https://flickity.metafizzy.co/)
[代码托管地址](https://github.com/metafizzy/flickity)

### CDN

Link directly to Flickity files on [unpkg](https://unpkg.com).

``` html
<link rel="stylesheet" href="https://unpkg.com/flickity@2/dist/flickity.min.css">
```

``` html
<script src="https://unpkg.com/flickity@2/dist/flickity.pkgd.min.js"></script>
```

### Package managers

Bower: `bower install flickity --save`

npm: `npm install flickity --save`

### Options

``` js
var flky = new Flickity( '.gallery', {
  // options, defaults listed

  accessibility: true, 
  // enable keyboard navigation, pressing left & right keys 
  //启用键盘导航，按左右键

  adaptiveHeight: false,
  // set carousel height to the selected slide
  //将轮播高度设置为所选幻灯片

  autoPlay: false,
  // advances to the next cell
  // if true, default is 3 seconds
  // or set time between advances in milliseconds
  // i.e. `autoPlay: 1000` will advance every 1 second
  //前进到下一个单元格
  //如果为true，则默认为3秒
  //或者在进度之间设置时间，以毫秒为单位//即“autoPlay：1000”将每1秒前进一次

  cellAlign: 'center',
  // alignment of cells, 'center', 'left', or 'right'
  // or a decimal 0-1, 0 is beginning (left) of container, 1 is end (right)
  //单元格对齐，'center'，'left'或'right' 
  //或小数0-1,0是容器的开头（左边），1是end（右边）

  cellSelector: undefined,
  // specify selector for cell elements
  //指定单元格元素的选择器

  contain: false,
  // will contain cells to container
  // so no excess scroll at beginning or end
  // has no effect if wrapAround is enabled
  //将包含细胞的容器
  //在开头或结尾所以没有多余的滚动
  //如果启用回绕，效果不生效

  draggable: '>1',
  // enables dragging & flicking
  // if at least 2 cells
  //使拖动＆轻拂
  //如果至少2个细胞

  dragThreshold: 3,
  // number of pixels a user must scroll horizontally to start dragging
  // increase to allow more room for vertical scroll for touch devices
  //用户必须水平滚动以开始拖动的像素数
  //增加以允许更多空间用于触摸设备的垂直滚动

  freeScroll: false,
  // enables content to be freely scrolled and flicked
  // without aligning cells
  //使内容可以自由滚动和轻弹
  //无需对齐单元格

  friction: 0.2,
  // smaller number = easier to flick farther
  //较小的数字=更容易轻弹更远

  groupCells: false,
  // group cells together in slides
  //将单元格组合在幻灯片中

  initialIndex: 0,
  // zero-based index of the initial selected cell
  //初始选定单元格的从零开始的索引

  lazyLoad: true,
  // enable lazy-loading images
  // set img data-flickity-lazyload="src.jpg"
  // set to number to load images adjacent cells
  //启用延迟加载图像
  //设置img data-flickity-lazyload =“src.jpg” 
  //设置为数字以加载邻近单元格的图像

  percentPosition: true,
  // sets positioning in percent values, rather than pixels
  // Enable if items have percent widths
  // Disable if items have pixel widths, like images
  //以百分比值而不是像素设置定位
  //如果项目具有百分比宽度则启用
  //如果项目具有像素宽度则禁用，如图像

  prevNextButtons: true,
  // creates and enables buttons to click to previous & next cells
  //创建并启用按钮以单击上一个和下一个单元格

  pageDots: true,
  // create and enable page dots
  //创建并启用页面点

  resize: true,
  // listens to window resize events to adjust size & positions
  //侦听窗口调整大小事件以调整大小和位置

  rightToLeft: false,
  // enables right-to-left layout
  //启用从右到左的布局

  setGallerySize: true,
  // sets the height of gallery
  // disable if gallery already has height set with CSS
  //设置图库的高度
  //如果图库已经使用CSS 设置了高度，则禁用

  watchCSS: false,
  // watches the content of :after of the element
  // activates if #element:after { content: 'flickity' }
  //观看内容：在元素之后
  //激活如果#element：after {content：'flickity'}

  wrapAround: false
  // at end of cells, wraps-around to first for infinite scrolling
  //在单元格的末尾，包装到第一个无限滚动
});
```