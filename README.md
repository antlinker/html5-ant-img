# html5-ant-img

## 例子
```html
<style>
 ant-img {
            display: inline-block;
            width:200px;
            height:150px;
  }
 </style> 
 <link rel="import" href="ant-img.html" >
  .
  .
  .
  <ant-img   src="1.jpg"   def="load.gif" err="404.jpg" duration="2s"></ant-img>
  .
  .
  .
  
```

## 说明

1. 需要为ant-img标签指定宽高
1. `src` 指定要加载的图片
1. `def` 指定未加载或加载中显示的图片
1. `err`指定加载失败时显示的图片
1. `duration` 指定加载过渡动画时长，2s两秒不设置或设置为0则不显示过渡动画
