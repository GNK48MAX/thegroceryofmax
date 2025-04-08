# Introduction 简介
A simple and fun decoration mod that provides unitypackage for players to import models themselves.
<br>Currently only offers several small decorations, will continue to update in the future.
<br>Make sure you have installed nickklmao-MenuLib-1.0.0 to provide in-game switching.
<br><br>
简单好玩的装饰模组，提供unitypackage，供玩家自行导入模型。
<br>目前仅提供了若干小装饰，未来会继续更新。
<br>确保你安装了nickklmao-MenuLib-1.0.0来提供游戏内切换。
<br><br>
![](https://i.imgur.com/7wmnl1P.png)
<br>


# How to use it 如何使用它
1.Install this mod and enter any game match
<br>2.ESC > Find "MoreHead" in the bottom left corner > Click to switch the component you want to enable
<br>
<br>1.安装本模组，并进入任何一个游戏战局
<br>2.ESC>在左下角找到MoreHead字样>点击切换你想要启用的部件
<br><br>![](https://i.imgur.com/K7alfF4.png)

# How to Add Models 如何添加模型
To avoid reading anxiety, click to expand for detailed instructions
<br>为了避免您出现阅读恐惧症，点击折叠以展开具体说明
<details>
  <summary>Click to see 点击展开</summary>

## English Tutorial

1.Set up Unity environment and import development package MoreHead-Asset-Pack_v1.0.unitypackage
<br><small>*[unitypackage download link](https://github.com/Masaicker/repo-MoreHead/releases/download/V1.0.1/MoreHead-Asset-Pack_v1.01.unitypackage)</small>
<br><small>*Unity 2022.3 environment recommended</small>
<br>2.Import your prepared model
<br>3.Drag the PlayerAvatar prefab into the scene
<br>4.Search for the following parts in PlayerAvatar, corresponding to where models will be placed:
<br>

| Name | Description | Tag |
| --- | --- | --- |
| Head decoration(Do Not Move) | Head part that raises when speaking | head |
| Neck decoration(Do Not Move) | Chin/chest area | neck |
| Body decoration(Do Not Move) | Body | body |

<small>*Note that these three positions are only coordinate anchor references to ensure your model is positioned correctly. Please do not adjust the XYZ positions of these parts</small>
<br>5. After selecting the appropriate part, create a new empty subset at that position (referred to as A), and name A (this will become the name displayed for the object in-game)
<br>6. Place your model under A, now you can adjust your model to the appropriate position
<br><small>*Note that you should adjust your model's position; it's recommended not to adjust the positions of the part and A</small>
<br>7. After adjusting the model, drag the parent containing your model (A) to any location in the project window, at which point A will become a prefab
<br><small>*It's recommended to standardize naming and directories for easy finding and modification</small>
<br>8. Run the Tools → Head Decorations Builder script
<br>9. Drag the A prefab you just saved to the prompt location in the script panel, and select the part you bound in step 4 from the dropdown menu
<br>10. Click Build AssetBundle, and a folder will automatically open when the process completes
<br>11. Find the AssetBundles folder in the automatically opened folder, and locate the file named [your decoration name.hhh]
<br><small>*Only the file with the .hhh extension is needed</small>
<br>12. Copy your .hhh decorations to any location within the BepInEx\plugins folder (it is recommended to place them in \MoreHead\Decorations for easier management).
<br><small>*Both you and your friends must have the corresponding .hhh file, otherwise it won't display</small>
<br>13. Start the game and enjoy the praise or mockery

## 中文教程

1.部署unity环境并导入开发包 MoreHead-Asset-Pack_v1.0.unitypackage
<br><small>*[unitypackage下载链接](https://github.com/Masaicker/repo-MoreHead/releases/download/V1.0.1/MoreHead-Asset-Pack_v1.01.unitypackage)</small>
<br><small>*推荐unity环境2022.3</small>
<br>2.导入你准备好的模型
<br>3.将PlayerAvatar预制体拖入场景
<br>4.找到PlayerAvatar中以下部位，对应模型将会摆放的位置：
<br>

| 名称 | 描述 | 标签 |
| --- | --- | --- |
| Head decoration(Do Not Move) | 说话时会抬起的头部 | head |
| Neck decoration(Do Not Move) | 下巴/胸口 | neck |
| Body decoration(Do Not Move) | 身体 | body |

<small>*注意这三个位置仅为坐标锚点参考，用来确保您的模型位置正确，请不要调节这些部位的XYZ位置</small>
<br>5. 选好部位后，在部位处新建一个空子集（以下称A），填写A的名字（这会成为在游戏中物体显示的名字）
<br>6. 将模型放置到A下面，此时您可以调节您模型到合适位置
<br><small>*注意是调节您模型的位置，建议别调节部位和A的位置</small>
<br>7.调整好模型后，将包含您模型的父级，也就是A拖动到project窗口中任意位置，此时A就会变成一个预制体
<br><small>*建议规范化命名和目录便于查找和修改</small>
<br>8.运行Tools→Head Decorations Builder脚本
<br>9.将您刚才保存的A预制体拖动到脚本面板的提示位置，在下拉菜单中选择您在第4步绑定的部位。
<br>10.点击Build AssetBundle，运行完毕后会自动为您打开一个文件夹
<br>11.找到自动开启的文件夹中的AssetBundles文件夹，在其中找到[你的装饰品名.hhh]的文件
<br><small>*只需要.hhh后缀的文件即可</small>
<br>12.将您的.hhh装饰品复制到 BepInEx\plugins 文件夹下任意位置 （建议放在 \MoreHead\Decorations 内便于管理）
<br><small>*您和您的朋友必须都拥有对应的.hhh，否则不会显示</small>
<br>13.启动游戏，享受赞美或嘲笑
</details>

# Future Update Plans 未来更新计划
More hats
<br>Provide screenshots for decorations to help with selection (not guaranteed)

<br>更多的帽子
<br>给装饰物提供截图以便更好地选择（不保证）

# Author Information 作者信息

**Masaicker** 马赛克了：[BILIBILI](https://space.bilibili.com/1542613)
<br>
**YurisCat Calypso** 尤里的猫·卡里普索：[BILIBILI](https://space.bilibili.com/1704421)

For questions and suggestions, please submit issues through this link
<br>如有问题和建议，请通过此链接提交 issues
<br>[https://github.com/Masaicker/repo-MoreHead/issues](https://github.com/Masaicker/repo-MoreHead/issues)

<br>If you want to buy us coffee and yellow energy crystals:
<br>如果你想给我们购买咖啡以及黄色能量水晶:
<br>[https://ko-fi.com/masaicker](https://ko-fi.com/masaicker)

<br><small>Whispering, we are making an indie game!悄悄说一句,我们正在制作独立游戏！</small>




