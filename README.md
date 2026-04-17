等我先学完nodejs再去学Ajax吧<br>
使用fs来进行操作<br>
先导入fs模块<br>
const fs = require（`fs`）
再写入文件基础指令
fs.writeFile(`./文件名称(如果没有文件会创建一个)`,你要输入修改的内容,(一个回调函数)err=>{})<br>
err写入失败:错误对象,写入成功为null<br>
同步写入fs.writeFileSync()这个函数跟fs.writeFile函数参数基本一样，但是没有回调函数<br>
对追加文件后面追加内容fs.appendFile(`文件路径`，追加内容，回调函数)<br>
如果想让输入内容换行是/r/n
