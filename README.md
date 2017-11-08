# lazyLoad Img

## 预览

![](view.gif)


## 定义规则

| cls(可选)   | src(可选)    |  initImg(可选)  |
| :----: | :----:   | :----: |
| .lazyLoad | data-src   | 占位图  |


```
<img class="lazyLoad" data-src="http://www.wclimb.site/images/imgLoading.svg" alt="">

wclimb.lazyLoad()
		or
wclimb.lazyLoad({
	cls:'.lazyLoad',
	src:'data-src',
	initImg:'http://www.wclimb.site/images/imgLoading.svg'
})

```


