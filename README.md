# datatoolfor2pollutionsurvey
本软件用于自动将第二次全国污染源普查国家普查软件系统里面的广西有关报表数据导出的脚本程序和一些格式转换、自动登录的小工具。实现的功能主要有：自动获取包括工业园、农业源、、移动源、生活源等五类源的所有报表以及所有普查对象名单信息的导出 ;实现了五类源近4万个普查对象的报表数据归档格式的导出，并自动全部转换成pdf格式 。程序主要有3类 ：一是对应的污染源报表的查询，通常名称是与报表名称对应,不同的查询选项用A、B、C.....等英文字母顺序标记;二是 一些综合汇总结果的查询和保留并转换到excel;三是自动登录、自动转换以及将归档格式污染源数据下载成excel格式数据并将之自动转换成pdf格式以便归档的一些python小程序和shell脚本。
软件基于ubuntu trusty  14.04平台，主要工具为火狐和谷歌浏览器的分析调试功能、python、bash shell脚本，json 转换工具 jq,curl,wget，tesseract 图像ocr识别等工具。为了不影响服务器性能，采取单线程顺序下载模式，按短平快的原则写的,为自用。
上传到github上主要用于本人备份留存之用。
