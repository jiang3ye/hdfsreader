##说明
该项目源代码来自 [alibaba - DataX/hdfsreader](https://github.com/alibaba/DataX/tree/master/hdfsreader/)

##主要功能
[alibaba - DataX/hdfsreader](https://github.com/alibaba/DataX/tree/master/hdfsreader/)不支持parquet格式文件
通过改写ORC文件的相关代码，目前仅在本人开发环境下测试通过。
欢迎各位朋友使用本代码

##使用说明
编译后的hdfsreader-0.0.1-SNAPSHOT.jar替换DataX程序下的plugin/reader/hdfsreader下的hdfsreader-0.0.1-SNAPSHOT.jar
在配置json格式时

配置方式与ORC相同
###_"fileType": "par"_