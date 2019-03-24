text-rendering: optimizeLegibility;
文本抗锯齿
-webkit-tap-highlight-color: rgba(0, 0, 0, 0);   ?
 overflow-x: hidden; 在水平方向超出则隐藏
 overflow-y:scroll;  scroll为默认值
-webkit-overflow-scrolling: touch; 能让滑动的时候更平滑

max-width  +  margin:0 auto 轻松构建跨设备自适应
从PC端到移动端  屏宽在变
      适配时考虑的是宽度
      max-width 在PC时生效，960px  左右留白，
      PC上OK,移动设备时<600  max-width失效  平铺整个宽度

搭盒子 语义化 main标签 主体
header 外面放一个DIV 盒子的责任划分
语义化 + 盒子 （margin-botton）

