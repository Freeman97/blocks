百步梯考核任务附加说明（前端方向）
1、	开始时试图使用while(true)进行连续的帧绘制，以及使用class来定义类型。发现问题后经过周志伟大佬提醒之后改用setInterval()进行连续的帧绘制（line67，column13），并直接使用function定义块的类型的构造函数（line18，column9）。
2、	禁止窗口缩放的代码摘自网络（line5，column5）
3、	鼠标事件传递的代码写法 event || window.event 的写法摘自网络（line91，column13）
4、	在测试移动端适配（canvas大小适应浏览器窗口大小）时另写了一份测试用代码（写出一个可以适应浏览器窗口大小的canvas，并能正确判定变形后鼠标点击的坐标。）但是由于个人文档管理问题，文件丢失，故无法再此附上。
5、	开发全程使用git进行版本控制，并push到了github上。地址：https://github.com/Freeman97/blocks
