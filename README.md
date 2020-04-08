# HTML常用标签

## <a>标签的三种用法

* 1 页面跳转
写法<a href = "路径" target="属性值">这个路径在这指的是需要跳转的页面的网址</a>

* 2 定位
设定锚点：在要定位到的位置找一个标签给他加id属性，属性值就是锚点名称

* 3 下载 or其他
a 标签跳转到的文件 浏览器打不开，然后会选择提供下载
    　例如RAR文件（即href路径为rar文件）
      <a href = "../../枪.rar">内容</a>
      
## img 标签的用法    
* 在html中，<img>标签是使用来在网页中嵌入一幅图像。从技术上讲，图像并不是插入到网页中，而是链接到网页中，<img>标签的作用是为被引用的图像创建占位符。
* <img>标签属性:
      >  alt：图像的替代文本；
      >  src：显示图像的URL；
      >  height：图像的高度；
      >  width：图像的宽度；
      >  ismap：将图像规定为服务器端图像映射，值为：ismap；
      >  usemap：将图像定义为客户器端图像映射，值可以为：#mapname；
      >  crossorigin：设置图像的跨域属性，值可以为：anonymous 、use-credentials（html5新增属性）；

## table 标签的用法
* 绘制表格使用；如果是做后台管理的用户列表等类似 Excel 功能，这个标签是最佳的选择

     > <table> 标签定义 HTML 表格
     > 一个 HTML 表格包括 <table> 元素，一个或多个 <tr>、<th> 以及 <td> 元素。
     > <tr> 元素定义表格行
     > <th> 元素定义表头
     > <td> 元素定义表格单元
     > 更复杂的 HTML 表格也可能包括

     > <caption>
     > <col>
     > <colgroup>
     > <thead>
     > <tfoot>
     > <tbody>

