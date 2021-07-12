# CVN-B460i-EFI-Opencore
 七彩虹B460I黑苹果OC配置，支持Big Sur 11.4，opencore 7.1，理论通用
## 测试环境
CPU: Intel i5 10400
显卡: HD630
内存: 酷兽32G 2666MHz
主板:七彩虹CVN B460i
网卡:原装（螃蟹卡和AX200）
硬盘:西数SN550 1T
## 使用注意事项
* 核显HD630可直接使用，独显只支持免驱A卡，其他卡请自行添加配置
* Big Sur移除了软件DRM解码，所以你必须使用独显，并在Whatevergreen中添加相应参数才能硬解Apple Music的无损音乐、Apple TV+等等DRM内容
* EFI包含了官方主题与开机音效（Duang）
* EFI中包含了Windows启动项，如果与你的Windows EFI文件不同，请自行参考修改，修改默认启动项在Big Sur系统偏好设置-启动磁盘直接修改即可
## 已知问题
* 睡眠后无法唤醒，只能强制重启
* 前置USB端口需要你自己定制，我ITX没有前置USB
