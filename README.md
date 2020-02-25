# DayNote

## 2020/02
### 2/24 
* 去除recycleView局部刷新图片闪烁问题 
  ```javascript
  ((SimpleItemAnimator)recyclerView.getItemAnimator()).setSupportsChangeAnimations(false);
  ```
### 2/25
* MPChart图表库可通过数据坐标值获取对应图表中像素坐标，可用来在图表中绘制自定义view
  ```javascript
  var lineDataSet = lineData.getDataSetByIndex(0) as LineDataSet
  var transformer = getTransformer(lineDataSet.axisDependency)
  var data = transformer.getPixelForValues(x, y)//x,y为数据值
  ```
  


