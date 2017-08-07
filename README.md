css
===
---for test
css intro


#### GRID可实现label content多列布局####

1fr 1fr 1fr  　推荐
70% 20% 10%  会有 margin padding issues

grid-template-columns: repeat(3, 1fr); // 1fr重复3次  相当于grid-template-columns: 1fr 1fr 1fr;
grid-template-columns: repeat(3, 1fr, 2fr); // 1fr重复3次  相当于grid-template-columns: 1fr 2fr 1fr 2fr 1fr 2fr;


####  justify-items 水平方向的对齐方式 参考grip-align.html#### 
 justify-items: stretch; //  start (显示能容纳的最小宽度) , center (显示能容纳的最小宽度), end(显示能容纳的最小宽度),, stretch 默认值 自动扩展
