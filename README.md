# RedmiBook-13-10th-Gen-Intel-Hackintosh
红米笔记本13寸 配置i7-10510u 16G内存 500G硬盘
Fork from  https://github.com/MoZyo/RedmiBook-13-10th-Gen-Intel-Hackintosh 非常感谢

HDMI输出不正常，感谢b站这位UP主提供的思路，https://www.bilibili.com/video/BV1AT4y157oJ?from=search&seid=197191053196037945
通过opencore configurator模拟成2013款的macbook pro并生成序列号之后，hdmi接口输出正常，不过还是需要每次开机后再插入才可以，直接连着线开机不能显示扩展屏幕

TODO：
1.大佬的issues里面有人留言已经解决了intel网卡的问题，查询资料后应该是要big sur beta6版本以后的才可以，暂时不想用big sur
2.因为catalina后可能会将硬盘拆分成系统盘和数据盘2个，喜欢用timemachine的同学，建议从安装系统那个步骤直接restore from timemachine，不然可能出现只备份了数据盘，没有系统安装过的app或者缺失的情况。
3.目前应该话筒是用不了的，另外这款没有摄像头
