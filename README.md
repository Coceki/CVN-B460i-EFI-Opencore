# CVN-B460i-EFI-Opencore
 七彩虹B460I黑苹果OC配置，只支持Monterey，BigSur请使用旧版，12.0.1测试通过，opencore 7.4，理论通用
## 测试环境
CPU: Intel i5 10400  
显卡: 讯景RX550 4G(开启核显，Polris核心，已开核768sp)  
内存: 酷兽32G 2666MHz  
主板:七彩虹CVN B460i  
网卡:原装（螃蟹卡和AX200）  
硬盘:西数SN550 1T  
## 使用注意事项
* 请修改SMBIOS的序列号，参考三码生成教程
* 核显HD630和Polris核心的RX550可直接使用，其他卡请自行添加配置
* Big Sur开始移除了软件DRM解码，所以你必须使用独显，并在Whatevergreen中添加相应参数才能硬解Apple Music的无损音乐、Apple TV+等等DRM内容
* 睡眠唤醒需要刷官网最新版本BIOS才能实现，出厂BIOS无法正常睡眠
## 已知问题
* 暂未发现
