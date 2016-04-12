# android-performance
android性能优化笔记,收集android性能优化文章，个人笔记等

#<h1>工具</h1>#
UI性能:HierarchyViewer<br/>
调试GPU过度绘制<br/>
Lint<br/>

Memory监测分析：<br/>
&nbsp;&nbsp;&nbsp;&nbsp;*leakcanary</br>
&nbsp;&nbsp;&nbsp;&nbsp;*android studio的Memory</br>
&nbsp;&nbsp;&nbsp;&nbsp;*dumpsys meminfo</br>

GC日志(Explicit concurrent mark sweep GC freed):<br/>
&nbsp;&nbsp;&nbsp;&nbsp;*GC_MALLOC——内存分配失败时触发;<br/>
&nbsp;&nbsp;&nbsp;&nbsp;*GC_CONCURRENT——当分配的对象大小超过384K时触发;<br/>
&nbsp;&nbsp;&nbsp;&nbsp;*GC_EXPLICIT——对垃圾收集的显式调用(System.gc());<br/>
&nbsp;&nbsp;&nbsp;&nbsp;GC_EXTERNAL_ALLOC——外部内存分配失败时触发;<br/>
Allocation Tracker<br/>
Traceview和dmtracedump<br/>
Systrace<br/>
MAT<br/>


#blog
伯乐头条技术分享：<br/>
* http://android.jobbole.com/81746/<br/>
* http://android.jobbole.com/81274/<br/>
[Gracker博客androidperformance](http://www.androidperformance.com/archives/)<br/>
[正确使用TraceView](http://blog.jobbole.com/78995/)

##[awesome-android-performance](https://github.com/Juude/awesome-android-performance)今天发现这个库已经终结得很好了
##[todo:文章翻译](https://github.com/chenxiruanhai/awesome-android-performance)

