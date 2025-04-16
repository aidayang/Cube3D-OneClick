# Cube3D-OneClick
Cube3D文本转3D模型软件免安装一键启动整合包

![](https://raw.githubusercontent.com/aidayang/Cube3D-OneClick/refs/heads/main/jietu.webp)

## Cube3D介绍
Roblox 3D智能基础模型

Cube 3D是我们迈向3D智能的第一步，它涉及形状标记器和文本到形状生成模型。我们正在释放生成3D资产和增强所有艺术家创造力的力量。我们最新版本的Cube 3D现在可供各种规模的个人、创作者、研究人员和企业使用，以便他们能够负责任地实验、创新和扩展他们的想法。

## Cube3D软件一键启动整合包使用说明
首先将网盘内的软件压缩包下载到本地电脑上并解压，然后双击【启动软件.exe】打开软件操作界面。

文本转3D

首先输入待生成模型的文本描述词，用英文描述，然后选择输出结果保存位置。

【快速推理】如果电脑显卡配置比较高的话可以勾选这项，加快推理速度，或是忽略此项。

【输出gif】如果想要输出3D模型旋转效果gif图片文件的话，可以勾选此项。电脑上必须安装Blender（版本>=4.3）并配置系统环境变量PATH，才能渲染转盘GIF。可忽略此项。

【低分辨率】如果电脑显卡配置比较低，或是用于快速测试，可设置该值。较低的分辨率将创建更粗糙、质量更低的输出网格，但解码速度更快。建议使用4.0到9.0之间的值。可忽略此项。

然后点击按钮开始处理即可开始生成3D模型文件。

标记化处理

Tokenization（标记化）
将输入的 3D形状（如.obj文件中的网格模型） 编码为一系列离散的 符号索引，类似于将图像压缩为一串数字编码。

De-tokenization（逆标记化）
将符号索引解码回 近似原始的3D形状，验证编码的保真度或用于后续生成任务。

选择obj文件或鼠标左键按住文件拖动到软件窗口里，然后点击开始处理按钮，软件就会对obj文件进行标记化和去标记化处理。输出recovered_mesh.obj

视频教程及演示：https://www.youtube.com/watch?v=HPY_PF_FNHw

## 注意事项
整合包只支持Windows 10或11

软件运行路径中不要有非英文字符和空格

建议英伟达显卡显存6G以上用户体验

## 文本转3D模型软件Cube3D整合包下载链接
https://pan.quark.cn/s/a6b441f89bc7

https://pan.baidu.com/s/1RJIFpXkAUe29JXt5qPaVTQ?pwd=fecc

## 项目链接
https://github.com/Roblox/cube
