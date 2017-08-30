# sell

>  本项目是基于vue2，使用了vue2 +vue-router2 + es6 +webpack，demo地址 [demo](http://112.74.60.57/#/goods)。


***
>  demo地址 [demo](http://112.74.60.57/#/goods) （请用chrome的手机模式预览）

>  本项目地址[github地址](https://github.com/jxy5969/sell-food/edit/master/sellFood)

>  手机demo地址 (扫一扫)


![1504081882.png](https://github.com/jxy5969/sell-food/blob/master/sellFood/screenShots/1504081882.png)



***
### 项目技术架构
*  vue-cli
*  vue2
*  vue-resource //因为上线项目使用了本地的data数据，使用vue-resource会导致无法接受到数据，故没用用到vue-resource
*  vue-router2
*  better-scroll //使用了黄轶老师的better-scroll,github地址[github地址](https://github.com/ustbhuangyi/better-scroll)
*  stylus
*  webpack

***
### 效果演示
* 商品页

![goods.gif](https://github.com/jxy5969/sell-food/blob/master/sellFood/screenShots/goods.gif)

* 购物车

![shorcatr.gif](https://github.com/jxy5969/sell-food/blob/master/sellFood/screenShots/shopcart.gif)

* 商品 评价页

![food.gif](https://github.com/jxy5969/sell-food/blob/master/sellFood/screenShots/food.gif)

* 页

![seller.gif](https://github.com/jxy5969/sell-food/blob/master/sellFood/screenShots/seller.gif)


***
### 安装
项目地址：（`git clone`）
```shell
git clone https://github.com/jxy5969/sell-food.git
```
通过`npm`安装本地服务第三方依赖模块(需要已安装[Node.js](https://nodejs.org/))

```
npm install
```
启动服务(http://localhost:8080)

```
npm run dev
```
构建打包

```
npm run build

```

***
### 目录结构
<pre>
├── build              // 构建服务和webpack配置
├── config             // 项目不同环境的配置
├── dist               // 项目build目录
├── index.html         // 项目入口文件
├── package.json       // 项目配置文件
├── src                // 生产目录
│   ├── common          // 公共的font css js 资源
│   ├── components     // 组件目录
│   ├── App.vue         // 主页面 
│   └── main.js        // Webpack 预编译入口
</pre>


***
### 实现的功能
* 商品滚动 ，商品滚轮滚动
* 商品联动
* 加入购物车，移除购物车
* 显示评论 评论筛选
* 图片左右滑动
* 商品详情  父子组件的通信
* 等等


***
### 正在实现的功能
* vuex
* 购物车结算组件
*  顶部下拉刷新

