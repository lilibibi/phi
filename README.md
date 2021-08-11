# [Demo](https://lch&#122;h&#51;473.github.io/canvas/phi/index "Phigros模拟器")

## 简介

如题，用js/canvas模拟Phigros游戏画面

## 更新日志

### [1.3.1] - 2021-08-11

#### 新内容

* 新增功能：视频录制(测试功能，录制时无法暂停)

#### 优化

* 优化`Note`绘制逻辑

#### 更改

* 实装`info.csv`和`line.csv`，简介新增悬浮提示
* 画面连击字样`combo`改为`Autoplay`
* `显示定位点`功能：左下角显示不同种类`Note`的实时连击数，负数`Note`以半透明显示

### [1.3] - 2021-07-11

#### 新内容

* 对pec谱面的bpm变速功能进行适配
* 新增功能：过渡动画(包含开头淡入和结尾淡出，不包含结算)
* 新增输入框(曲绘、谱师)，对应过渡动画
* 通过添加`line.csv`以修改判定线贴图(测试功能)
* 通过添加`info.csv`以自动填写谱面信息(测试功能)

#### 优化

* 优化zip文件读取逻辑(数组→对象)
* 优化判定线和背景的绘制顺序
* 调整背景和UI对不同尺寸屏幕的适配
* 打击特效动画采用缓动函数
* 调整打击音效与官方v1.6.10一致
* 优化`播放/停止`和`暂停/继续`按钮相关逻辑

#### 更改

* `宽高比`下拉列表新增`10:7`(适配iPad Pro 11)，将`256:175`改为`19:13`(适配Phi Editor)
* `显示定位点`功能：判定线数字透明度随判定线透明度变化，`Note`打击后变为半透明
* `Hold`尾判调整为提前0.2秒得分
* `Hold`连续打击特效间隔由12tick缩短为9tick

#### 修复

* 修复了部分谱面`Note`打击时间异常的bug
* 修复了有关pec谱面判定线事件time不精确导致排序错误的bug
* 修复了点击`停止`按钮后按住的`Hold`无法关闭导致连击得分溢出的bug

### [1.2.2] - 2021-07-03

#### 新内容

* `显示定位点`现在能对`Note`进行定位(测试功能)

#### 修复

* 修复包含文件夹的zip无法正确加载的问题
* 修复了部分谱面`Note`速度异常及`Hold`错位的bug

#### 更改

* 谱面默认速度：`1.0`→`1.2`(json)，`1/5.75`→`1/7.0`(pec)
* 打击特效颜色：`#fce491`(Perfect)，`#9ed5f3`(Good)

### [1.2.1] - 2021-06-22

#### 新内容

* 添加下拉列表(宽高比、按键缩放、背景变暗)
* 对pec谱面的`Fake Note`进行适配(测试功能)

#### 修复

* 修复了有关pec判定线演出的若干bug

### [1.2] - 2021-06-12

#### 新内容

* 支持导入pec(暂未适配`Fake Note`和`Alpha值扩展`)

### [1.1] - 2021-05-04

#### 新内容

* 支持导入zip、选择谱面及一些基本操作

#### 已删除

* 暂时移除`模拟Demo`

### [1.0.1] - 2021-04-18

#### 更改

* `模拟Demo`改为Phigros愚人节谱`Spasmodic SP`

### [1.0] - 2021-01-28
