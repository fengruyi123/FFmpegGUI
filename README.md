# FFmpegGUI
基于 FFmpeg 的 GUI 工具

最初是因为我和朋友有批量视频截取的需求，网上找了一圈剪辑软件，但是大多功能臃肿/操作复杂，找软件加摸索使用就花了几个小时，还没找到好用的，所以干脆就自己写了一个基于 FFmpeg 的 GUI 工具。

	目前已实现功能：
		A.视频转换
		B.视频裁剪
		C.视频提取音频
		D.视频去除音频
		E.视频、音频倍速
		F.视频、音频信息提取
		G.音频转换
		H.音频裁剪

	设计目标：功能明确，一键式UI操作，批量处理，后台自动运行

	后续计划
		1、持续优化开发高频功能（个人业余时间维护）
		2、欢迎交流同类需求（bug反馈）

 	联系邮箱：2143213151@qq.com

（注意：使用本ui需要提前下载FFmpeg并配置环境变量path；或者可以直接把下载好的FFmpeg解压后，把里面bin文件的三个文件ffmpeg.exe、ffplay.exe、ffprobe.exe和本程序放在同一个文件夹即可）
	
 	最新版本：
		FFmpegGUI V3.3.0 日志
		1.标签页名称、顺序调整
		2.视频转换页，新增扩展“单流智能”、“多流智能”2个按钮
		3.视频裁剪页，新增扩展“复制流”、“单流重编码”、“多流重编码”3个按钮
		4.视频、音频倍速页，新增扩展“单流重编码”、“多流重编码”2个按钮
		5.音频转换页，新增“智能复制流、重编码”功能
		6.修复bug

![image](https://github.com/user-attachments/assets/7f012a3b-515d-43f7-b556-0b8c7be859a9)
![image](https://github.com/user-attachments/assets/de515c3b-eca7-406b-a498-5977582f2b57)
![image](https://github.com/user-attachments/assets/234c8147-6aac-48ed-a450-619de88ed015)
![image](https://github.com/user-attachments/assets/a30d10be-95cf-4bdd-8917-a4e5d4ba89f0)
![image](https://github.com/user-attachments/assets/af315aac-0c47-4e31-bc51-15a2b00c0193)
![image](https://github.com/user-attachments/assets/b4d0b936-ef9d-4904-b22a-6a37cfc07905)
![image](https://github.com/user-attachments/assets/77b330dc-bfe1-413d-a3a6-b51231c0cb6c)
![image](https://github.com/user-attachments/assets/6fd95a22-5601-4d4b-97cf-b1e9aaaa999b)

如果本项目对您有所帮助，不妨打赏一下，您的支持是我最大的动力：
![image](https://github.com/user-attachments/assets/9731ecc8-3662-4b8c-84eb-23db13de9033)
