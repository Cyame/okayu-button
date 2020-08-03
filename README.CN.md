# 饭团猫按钮

饭团猫按钮 —— VTuber猫又小粥的音声按钮站 [国际版点此访问](http://button.okayu.me) [大陆地区可使用镜像站](https://cyame.gitee.io/okayu-button)

![NODEJS_VERSION](https://img.shields.io/static/v1?label=Node.js&message=12.16.3&color=339933&style=flat-square&logo=node.js) ![NPM_VERSION](https://img.shields.io/static/v1?label=NPM&message=6.14.4&color=CB3837&style=flat-square&logo=NPM) ![JQUERY_VERSION](https://img.shields.io/static/v1?label=jQuery&message=3.5.0&color=0769AD&style=flat-square&logo=jQuery) ![VUE_VERSION](https://img.shields.io/static/v1?label=Vue&message=2.5.17&color=4FC08D&style=flat-square&logo=Vue.js) ![BUTTON_VERSION](https://img.shields.io/static/v1?label=okayu-button&message=1.0&color=B463F5&style=flat-square&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAyNC4wLjEsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0ib25pZ2lyaV94QTBf5Zu+5YOPXzFfIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIg0KCSB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iMCAwIDQzMiA0MzIiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDQzMiA0MzI7IiB4bWw6c3BhY2U9InByZXNlcnZlIj4NCjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI+DQoJLnN0MHtmaWxsOiMwNjA2MDY7fQ0KCS5zdDF7ZmlsbDojRkZGRkZGO30NCjwvc3R5bGU+DQo8cGF0aCBjbGFzcz0ic3QwIiBkPSJNMjE2LjEsNDE4LjJjLTE1LjksMC0zMS45LTAuMS00Ny44LTAuNmMtMTMuMi0wLjQtMjYuNC0xLjEtMzkuNi0yLjFjLTktMC43LTE3LjktMS4yLTI2LjgtMi41DQoJYy0zNS42LTUuMy02Mi42LTIyLjktNzguNS01NS44Yy00LjktMTAuMS03LjYtMjAuOS04LjYtMzIuMWMtMS42LTE3LjksMS40LTM1LDcuNy01MS43YzE4LjgtNDkuOCw0MC42LTk4LjMsNjYtMTQ1LjENCgljMTMuNi0yNS4xLDI4LjEtNDkuNyw0My45LTczLjVjOS4xLTEzLjcsMjAuMi0yNS4zLDM0LjEtMzQuM2MxMC43LTYuOSwyMi4zLTExLjcsMzUtMTMuNGMyOC40LTMuOSw1My45LDIuOCw3NS45LDIxLjcNCgljOS43LDguNCwxNy44LDE4LjEsMjQuOCwyOC44QzMzMSwxMDEuOCwzNTYsMTQ4LjEsMzc4LDE5Ni4xYzEyLjIsMjYuOCwyMy42LDUzLjksMzMuNyw4MS41YzUuNCwxNC43LDcuNSwzMCw2LjQsNDUuNw0KCWMtMi44LDM4LTI2LjcsNjkuOS02Mi40LDgzLjVjLTkuNSwzLjYtMTkuNCw1LjgtMjkuNSw2LjhjLTExLjUsMS4xLTIzLDIuMS0zNC41LDIuOGMtMTIuNywwLjgtMjUuNSwxLjItMzguMiwxLjUNCglDMjQwLjgsNDE4LjEsMjI4LjQsNDE4LjEsMjE2LjEsNDE4LjJ6Ii8+DQo8cGF0aCBjbGFzcz0ic3QxIiBkPSJNMjE2LjcsNDIuOGMtNS42LDAtMTAuNiwwLjUtMTUuNSwxLjdjLTExLjIsMi44LTIwLjksOC41LTI5LjcsMTUuOWMtMTAuNCw4LjgtMTguOSwxOS4zLTI2LjEsMzAuOA0KCWMtMTEuOCwxOC44LTIyLjcsMzguMS0zMy4xLDU3LjZjLTE2LjMsMzAuNi0zMS4yLDYxLjgtNDUuNiw5My4zYy02LjMsMTMuNy0xMiwyNy42LTE1LjcsNDIuM2MtMi44LDExLjQtNC41LDIyLjktMy4zLDM0LjcNCgljMC43LDYuOSwyLjQsMTMuNCw1LjUsMTkuNmM1LjEsMTAuNCwxMy4xLDE4LjIsMjIuOCwyNC4yYzEyLjEsNy41LDI1LjQsMTEuOSwzOS4xLDE1LjFjNy4zLDEuNywxNC43LDMuMSwyMi4xLDQuMQ0KCWM1LjIsMC43LDEwLjMsMS40LDE1LjUsMS45YzEsMC4xLDEtMC4zLDEtMWMwLjMtMTAuNiwwLjYtMjEuMywwLjgtMzEuOWMwLjQtMTYuNywwLjgtMzMuNCwxLjItNTAuMWMwLjQtMTUsMC43LTMwLDEtNDUNCgljMC4xLTQuMiwwLjMtOC4zLDAuMy0xMi41YzAtMC45LDAuMy0xLDEuMS0xYzE3LjMsMCwzNC42LTAuMSw1MS45LTAuMWMyMS4yLDAsNDIuNCwwLjEsNjMuNSwwLjFjMSwwLDEuMiwwLjMsMS4yLDEuMg0KCWMwLjMsMTEuMSwwLjUsMjIuMywwLjgsMzMuNWMwLjIsOC40LDAuNCwxNi44LDAuNiwyNS4yYzAuMywxMS4yLDAuNiwyMi40LDAuOSwzMy42YzAuMywxMS44LDAuNSwyMy42LDAuOCwzNS40DQoJYzAuMSw0LDAuMiw3LjksMC4zLDExLjljMCwwLjcsMC4xLDAuOSwwLjksMC44YzYuMy0wLjYsMTIuNi0xLjUsMTguOC0yLjRjOS44LTEuNSwxOS41LTMuNSwyOS02LjNjMTEtMy4yLDIxLjYtNy41LDMxLjItMTMuOQ0KCWMxNS43LTEwLjUsMjQuOC0yNSwyNi40LTQ0YzAuOC05LjUtMC4zLTE4LjgtMi4yLTI4Yy0yLjUtMTEuOC02LjQtMjMuMS0xMS4xLTM0LjJjLTYuMy0xNS0xMy4zLTI5LjYtMjAuMi00NC4zDQoJYy0xNS41LTMyLjgtMzEuOS02NS4xLTUwLjEtOTYuNWMtNi4xLTEwLjUtMTIuMS0yMS0xOS4xLTMwLjljLTcuNS0xMC42LTE2LjEtMjAuMS0yNi42LTI3LjdDMjQzLjYsNDcuNywyMzAuNyw0Mi43LDIxNi43LDQyLjh6Ii8+DQo8L3N2Zz4NCg==)

**相关链接**

* [猫又小粥的Youtube频道](https://www.youtube.com/channel/UCvaTdHTWBGv3MKj3KVqJVCw)

* [猫又小粥的Twitter](https://twitter.com/nekomataokayu)

* [猫又小粥的Bilibili主页](https://space.bilibili.com/412135222?from=search&seid=730740916312043238)

## 参与完善本项目

请Fork本项目进行修改，完成修改后在本项目中发起一个Pull Request。

### 添加或修改音频

请以文件夹的形式分类，并将音频文件以 中文_日文.mp3 的格式命名后，将文件下载地址贴至issue里，或直接按下列手动编辑后发送Pull request来添加音频。

**简述**: 所有的音频信息都存储在 [src/voices.json](src/voices.json)中. 若要添加或修改音频，则需要修改文件中对应内容。

音频一律采用mp3或wav格式，存储在 [public/voices](public/voices)中.对应的URL为`voices/`.

添加的新音频请先进行音量标准化。可以使用MP3GainGUI之类的软件，目前音量全部标准化为80。

由于本站采用强缓存策略，除`index.html`外,文件名一致的文件，即使进行过修改也**永远** 不会被客户端刷新。因此新添加音频的文件名**必须**和之前的任何文件名都不同。

如果是修改音频，请在修改之后删除原音频文件。

### 参与音频翻译

请为我们英文与日文的翻译工作贡献你的一份力量！

对主程序的翻译请在[src/locales](src/locales)中三个以语言名命名的`.js`文件内进行。

对语音的翻译请在[src/voices.json](src/voices.json)内进行。

相关修改能够自动地被识别为有效的翻译文本并在对应语种界面下生效

## 部署本地开发环境

本站使用 Vue2.0 + jQuery + Bootstrap 3 开发。

要部署本地开发环境，请先安装最新版的Node.js LTS(12.0+)。然后按照如下步骤操作：

1. Clone代码到本地。

2. 进入代码目录，运行 `npm install`.

3. 运行本地开发服务器 `npm run serve`，在代码修改过程中，本地开发服务器可以即时反映修改的结果。

4. 要编译可供部署的文件，请运行 `npm run build`,这会生成 `dist`目录。 本站为全静态，将整个`dist`目录部署即可。

> 若要为本项目贡献你的代码，你不必在本地编译。在开发服务器中测试通过并推送至GitHub后，直接给本项目提交Pull Request即可。

### 关于Clone本项目的说明

#### 项目大小

本项目截止Version-0.9版本，全部仓库大小已经有20M以上，以HTTP协议Clone本项目可能会出现缓存区溢出的情况。

因此在Clone前，请先执行

```shell
git config --global http.postBuffer 5242880000
```

*注：本命令由于对全局生效，因此需要管理员权限。请使用管理员打开Shell或执行时加上`sudo`字段以正确配置*

#### 下载速度缓慢

对于中国大陆的开发者，GitHub可能存在DNS污染，因此访问速度较慢。因此对于本项目Clone时可采用四种替代方案：

1.  (首选)直接从[Gitee镜像仓库](https://gitee.com/cyame/okayu-button)拉取

   目前开发会将主要更新同时镜像到Gitee上，因此两条master分支本身是相关联的。因此在从Gitee仓库拉取后,

   ```shell
   git clone https://gitee.com/cyame/okayu-button.git
   ```

   在本地仓库添加新远程即可同时推送。

   ```shell
   git remote add github https://github.com/Cyame/okayu-button.git
   ```

   Push时使用

    - Gitee
      ```shell
      git push origin master
      ```
   
    - GitHub
      ```shell
      git push github master
      ```

2. 使用代理服务器

   可配置HTTP代理如下：

   ```shell
   git config --global http.proxy <IP>
   ```

3. 使用VPS转发

   可使用私有云端进行Clone下载后，通过FTP或SFTP或其他各类云业务转存至本地。

4. 配置Hosts以减少DNS解析所需时间

   可访问[IPAddress](https://www.ipaddress.com/)查询以下地址DNS解析后的IP，并对应写入Host

   ```
   github.com
   assets-cdn.github.com
   github.global.ssl.fastly.net
   ```

   具体操作可参考：

   https://blog.csdn.net/qq_44670803/article/details/102661104

   https://zc95.github.io/2017/11/28/hostsChange/

#### 静态网站部署

目前本项目虽已上线，但大部分功能还有待补充和完善，因此静态网站暂时使用GitHub-Pages被部署在`master/docs`中。因此，在Clone本项目时，会收到两份音频文件，这显然会让项目体积变得很大。因此在1.0版本上线后，我们会将网站移动至`gh-pages`分支，因此可以减少Clone`master`分支的大小。


目前可以使用的方法，是将`.git`文件的大小进行压缩，具体方法是通过设置深度仅Clone最近一次提交：

```shell
git clone --depth 1 https://github.com/Cyame/okayu-button.git
```

如果Clone之后想获得完整仓库，可使用

```shell
git fetch --unshallow
```

进行二次拉取。

## LICENCE

程序部分：MIT

音频部分：根据 [Hololive二次创作条例](https://www.hololive.tv/terms)进行

本项目为爱好者作品，其行为与hololive官方无关

## Special Thanks

This project is modified based on the [Meamea button](https://github.com/zyzsdy/meamea-button).
