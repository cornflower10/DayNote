# DayNote

## 2020/02
### 2/24 
* 去除recycleView局部刷新图片闪烁问题 
  ```javascript
  ((SimpleItemAnimator)recyclerView.getItemAnimator()).setSupportsChangeAnimations(false);
  ```


