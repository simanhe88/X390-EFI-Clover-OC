# X390-EFI-Clover-OC
Thinkpad X390 黑苹果Clover和OpenCore双引导文件
Clover 5103
OpenCore 6.1

Tested on：
10.15.4
10.15.6

公司配的电脑，配置信息：
CPU: i5 8265U
内存：8G
硬盘：东芝512G固态
显卡：Intel UHD Graphics 620
屏幕：FHD 1920x1080
无线网卡：Intel 9560 AC
蓝牙：内置

目前可用： 
触摸板上三个按键、单指，小红点，type-C接口，摄像头，睡眠 正常
声音、无线、蓝牙、亮度调节、电池状态、节电五项、声音和亮度调节快捷键支持

目前不可用：
HDMI接口、指纹、多指手势

marks：
1、首次安装mac，界面字体太小，且显示器分辨率选项不可用
为中低分辨率的屏幕开启 HiDPI 选项，并且具有原生的 HiDPI 设置
bash -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/master/hidpi.sh)"

2、wifi正常使用，默认没有状态栏图标，账号需要在plist文件中配置
如需界面效果，可使用HeliPort软件，接近原生效果
https://github.com/OpenIntelWireless/HeliPort

3、流量监控软件下载速度一直是0，可通过桥接方式修复
https://github.com/OpenIntelWireless/itlwm/issues/172



References：
https://github.com/Liu-wenxiang/Thinkpad-X390-Yoga-Clover
https://github.com/tuanctob48/x390-hackintosh
https://github.com/SukkaW/ThinkPad-E480-Hackintosh
