目前国内所有奥迪MHI2P的carplay投屏都是本人原创开发的，本人抖音和咸鱼：Carplay 。 网络用名AUDIJI AUDIJIJQ
现在各大平台上出现未经本作者许可的大规模数据盗用牟利行为，其中有头部改装连锁企业，不知真假的“奥迪官方” ，还有不胜枚举的“刷机大师”倒卖数据，甚至还有知名大众车机网红在本人明确告知不要开源我的数据情况下，用AI逆向分析本人数据后冒充自己的发布到github上面沽名钓誉。
所以现在把最新版本奥迪MH2P_AS区域的仪表carplay投屏完美版无偿公开出来供所有人使用。
原创不易 熬夜伤身 无数个夜晚加班修改调试解决bug，成功不是一蹴而就.........

本最新版本修复了冷启动连接超时卡滞问题，并且取消了一机一码mmx_challenge 绑定，作为通用安装包发布。
文件解压后的Meta和Data为最新版投屏文件 其余各个文件夹为工具包 全网的投屏文件和工具包都是本人原创开发制作的。

#准备32G以下的U盘或者SD卡 并格式化为FAT32格式
#准备32G以下的U盘或者SD卡 并格式化为FAT32格式
#准备32G以下的U盘或者SD卡 并格式化为FAT32格式

1.新装直接操作
将Data Meta两个文件夹放入U盘
车机开机运行之后将U盘插入等待升级自动完成
安装过程系统将自动重启几次 观察中控屏幕直到最后显示“Insert update medium”这个开头的提示即表示安装完成，可以拔掉U盘，点击音量开关自动退出

2.安装过最老的一代屏幕镜像版本的
先按照前面的新装投屏操作一遍，然后把“安装二代后卸载一代”文件夹内两个自动运行脚本放入U盘 车机开机后插上车 几秒后黑屏立即拔掉U盘，即卸载完老的镜像卸载

3.后改三代仪表+做了老的一代镜像投屏的 *安装完二代最新版 卸载掉镜像版本后仪表媒体地图不显示的* 修复仪表
把“安装二代卸载一代后修复仪表地图媒体显示”文件夹内的三个文件放在放在U盘 车机开机后插上车 几秒后黑屏立即拔掉U盘，即完成修复

4.安装过二代第一版不支持厂字居中的 没有RGI信息卡片的基础版投屏
先把“二代基础版投屏卸载”内的两个自动脚本复制到U盘 车机开机插上去几秒后黑屏立即拔掉U盘，基础班投屏即卸载完成，再按照前面步骤1的新装操作安装一遍新版

5.安装过新版带RGI信息卡片前期版本，但是有连接超时卡滞问题的
先把“二代RGI版卸载”内的两个自动脚本复制到U盘 车机开机插上去几秒后黑屏立即拔掉U盘，新版投屏即卸载完成，再按照前面步骤1的新装操作安装一遍最新版

6.后改2.5主机不能自动启动更新 两指并拢按屏幕右上角进入工程模式后 升级提示"Variant mismatch" "M3P-H-ML-CN-AU-XJB-AL"这是主机卖家篡改了设备名称禁止正常更新
把升级文件夹“Data"，拷贝到U盘，再把"后改2.5主机不能升级定制Meta引导替换"文件夹中"Meta"拷贝到U盘，即可开始升级。
---

# English

All Audi MHI2P CarPlay instrument-cluster projection solutions currently available in China were originally developed by me. My accounts on Douyin and Xianyu are named “Carplay”; my online names are AUDIJI and AUDIJIJQ.

Large-scale unauthorized copying and commercial resale of my work has appeared across major platforms. Those involved include a leading vehicle-modification chain, a supposedly “official Audi” source of uncertain authenticity, and countless “flashing masters” reselling the data. There is even a well-known Volkswagen infotainment influencer who, after I explicitly told them not to open-source my data, used AI to reverse-engineer it and published it on GitHub while presenting it as their own in order to gain recognition.

I have therefore made the latest complete version of the instrument-cluster CarPlay projection solution for Audi MH2P_AS systems available free of charge for everyone to use.

Original development is not easy, and working through the night takes its toll. Countless nights were spent modifying, debugging, and resolving issues. Success was not achieved overnight.

This latest release fixes connection timeouts and stalls during cold starts. It also removes the per-device `mmx_challenge` binding and is distributed as a universal installation package.

After extracting the archive, the `Meta` and `Data` directories contain the latest projection package. The remaining directories contain supporting tools. All projection packages and toolkits available online were originally developed and produced by me.

**Prepare a USB drive or SD card smaller than 32 GB and format it as FAT32.**

**Prepare a USB drive or SD card smaller than 32 GB and format it as FAT32.**

**Prepare a USB drive or SD card smaller than 32 GB and format it as FAT32.**

## 1. New installation

Copy the `Data` and `Meta` directories to the USB drive.

After the vehicle head unit has fully started, insert the USB drive and wait for the update to complete automatically.

The system will restart several times during installation. Watch the center display until a message beginning with “Insert update medium” appears. This indicates that installation is complete. Remove the USB drive, then press the volume/power control to exit automatically.

## 2. Vehicles with the oldest first-generation screen-mirroring version installed

First complete the new-installation procedure above. Then copy the two autorun scripts from the `安装二代后卸载一代` directory to the USB drive. After the head unit starts, insert the USB drive. When the screen goes black after a few seconds, remove the USB drive immediately. The old mirroring version is then uninstalled.

## 3. Vehicles retrofitted with a third-generation instrument cluster and the old first-generation mirroring solution

If the instrument-cluster media and map display no longer work after installing the latest second-generation version and uninstalling the mirroring version, copy the three files from the `安装二代卸载一代后修复仪表地图媒体显示` directory to the USB drive. After the head unit starts, insert the USB drive. When the screen goes black after a few seconds, remove the USB drive immediately to complete the repair.

## 4. Vehicles with the first second-generation basic version installed

This applies to the basic projection version that does not support centered display of the Chinese character “厂” and has no RGI information card.

Copy the two autorun scripts from the `二代基础版投屏卸载` directory to the USB drive. After the head unit starts, insert the USB drive. When the screen goes black after a few seconds, remove the USB drive immediately. The basic projection version is then uninstalled. Next, follow the new-installation procedure in Section 1 to install the latest version.

## 5. Vehicles with an earlier RGI information-card version installed

This applies to an earlier release that includes RGI information cards but suffers from connection timeouts or stalls.

Copy the two autorun scripts from the `二代RGI版卸载` directory to the USB drive. After the head unit starts, insert the USB drive. When the screen goes black after a few seconds, remove the USB drive immediately. The earlier projection version is then uninstalled. Next, follow the new-installation procedure in Section 1 to install the latest version.

## 6. Retrofitted 2.5 head units that cannot start the update automatically

If pinching two fingers together in the upper-right corner of the screen to enter engineering mode produces the update errors “Variant mismatch” and “M3P-H-ML-CN-AU-XJB-AL”, the head-unit seller has modified the device name and prevented normal updates.

Copy the update package's `Data` directory to the USB drive. Then copy the `Meta` directory from `后改2.5主机不能升级定制Meta引导替换` to the USB drive. The update can then be started.
