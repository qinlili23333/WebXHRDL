# WebXHRDL
轻量化的运行在网页内的基于XHR的下载器
[![](https://data.jsdelivr.com/v1/package/gh/qinlili23333/WebXHRDL/badge)](https://www.jsdelivr.com/package/gh/qinlili23333/WebXHRDL)
## 使用说明  
必须在同一页面上先添加[SakiProgress](https://github.com/qinlili23333/SakiProgress)，使用时直接调用XHRDL.init，无需先初始化SakiProgress  

## 接口说明  
#### init()`0.1.0`
初始化，必须先调用  
#### destroy()`0.1.0`  
销毁，同一页面上可以反复的初始化和销毁  
#### saveTaskList()`0.1.0`  
保存下载列表到LocalStorage，同域共用  
#### loadTaskList()`0.1.0`  
从LocalStorage读取下载列表  
#### newTask(地址，文件名，是否立即开始，是否显示添加任务提示)`0.1.2`  
新建下载任务并启动下载引擎  
