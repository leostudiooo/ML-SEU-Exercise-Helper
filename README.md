# ML SEU Exercise Helper

## 概述
本项目旨在帮助 SEU 的本科生更好地进行课外锻炼，完全开源，请勿商业化，请自觉遵循 [GPLv3 许可证](LICENSE)。

本项目有着简洁美观的 WebUI, 操作简单，是本科生们课外锻炼的得力助手。

如果大家喜欢本项目，请给颗小星星哦~

欢迎 Star、Fork 和 PR！

## 界面截图
![Screenshot-Main](screenshots/main-page.png)

## 使用方法
下载 [Release](https://github.com/midairlogn/ML-SEU-Exercise-Helper/releases) 中的最新版本，用浏览器打开 `.html` 。(推荐在电脑上操作)

填入你的Token，选择场地、时间，并上传两张照片作为开始、结束照片。

> 这里照片采用自拍，人脸尽量占据整个画面。   
> 可以使用相同的照片，但是一定要本人的。

> 作者 [Midairlogn](https://github.com/midairlogn) 推测此照片仅用于人脸识别，验证是否是本人在跑。

点击 `提交跑步记录` 按钮即可 ( **需要校园网** )，**在成功提示窗口弹出前切勿离开、关闭页面**！

等待弹出成功提示窗口(见下图)，就可以在微信小程序中看到上传的跑步记录了。

### Token获取说明
> Token形如 `Bearer [part1].[part2].[part3]`。

这里作者仅介绍较为简单的方法。

1. 打开 [https://tyxsjpt.seu.edu.cn/h5/#/pages/home/index](https://tyxsjpt.seu.edu.cn/h5/#/pages/home/index) ，登录账号。

2. 按 `F12` (有的电脑是 `Fn + F12` )打开浏览器的开发人员工具，进入 `控制台` ( `console` )。

3. 展开 `request res========` 后面的 `object` ，找到 `request.headers.token` 。

4. 右键复数字符串内容。**注意: 不需要引号!**

#### 图解

![screenshot-Get-Token](screenshots/get-token.png)

##### 顺便提一嘴较为复杂的方法。

打开相应的微信小程序, 用CE搜索: `Bearer ey`, 复制找到的Token即可。

## 声明

本项目遵循 [GPLv3 许可](LICENSE)，强烈反对任何形式的商业化使用。

**作者不对用户使用本项目可能造成的后果负责，也不对用户使用本项目上传的数据真实性负责。**

## 致谢 / Credits

本项目部分内容基于或参考 [GOOSE](https://github.com/leostudiooo/GOOSE) 项目。

Portions of this project are based on GOOSE (GOOSE Opens workOut for SEU undErgraduates):
- Repository: https://github.com/leostudiooo/GOOSE
- Copyright © 2025 GOOSE Team
- Licensed under GPL-3.0: https://www.gnu.org/licenses/gpl-3.0.html

感谢 GOOSE 团队的开源贡献，本项目包含了 GOOSE 的 GPS 运动轨迹数据。

**本项目的所有修改和改编内容版权归 Midairlogn 所有，同样遵循 GPL-3.0 许可证。**

详细信息请参阅 [NOTICE](NOTICE) 文件。