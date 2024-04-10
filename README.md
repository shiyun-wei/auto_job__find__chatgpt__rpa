作者已经去打工了，现在在sider做产品经理，义务为我们的产品打一下广告，各位见谅
[![banner](https://github.com/Frrrrrrrrank/auto_job__find__chatgpt__rpa/assets/82270228/0fff88f5-670c-4126-b6aa-3df1763fe757)](https://sider.ai/ad-land-redirect?source=github&p1=mi&p2=kk)

欢迎大家使用

## 更加便于操作的版本
另外，如果一些用户确实布置这个项目遇到很多问题，我提供一个收费的版本，加了美工服务器，跑的是我自己的api，一键无脑使用，网站上也有教学视频和使用手册


www.aijobpathfinder.com


差不多就是成本价+服务器还有美工的成本，当然各位要是技术ok，免费版本和付费版本是完全一样的，甚至这里还支持langchian


这是一个完全免费的脚本，只需要你们自己配置好openai的api即可

希望您能给我点个 **star**

如果在这个寒冷的招聘季，这个脚本能给您一些帮助，带来一些温暖，将让我非常荣幸

希望不要有人拿着我的脚本去割韭菜，都已经被逼到用这种脚本投简历的地步了，身上也没啥油水可榨了吧。

## 操作步骤

1. 请首先配置好 openai 的 api（使用.env文件或者在代码中配置）
2. 将pdf简历上传到文件夹 auto_job_find 里，命名为 **“my_cover.pdf"**
3. 将需要的包安装好
4. 执行 write_response.py

## 关于 asistant

会自动生成 openai 的 asistant，并在本地产生一个 .json 文件，只有第一次运行的时候才会产生，后面每次运行如果检测到这个 json ，就会调用已有的 asistant。

## 使用到的包

- `python-dotenv`
- `openai`
- `selenium`
- `robotframework`
- `robotframework-seleniumlibrary`
- `robotframework-pythonlibcore`
- `faiss-cpu不支持3.12（faiss-gpu不清楚）。建议大家用3.11及以下版本的python运行脚本。` from @[huanmit](https://github.com/huanmit)

## About RPA

tutorial video about how to learn [rpa](https://www.youtube.com/watch?v=65OPFmEgCbM&list=PLx4LEkEdFArgrdD_lvXe_hYBy8zM0Sp3b&index=1)

Plugin: Intellibot@Selenium Library

------------------下面是简单的教学视频---------------------

[B站链接](https://www.bilibili.com/video/BV1UC4y1N78v/?share_source=copy_web&vd_source=b2608434484091fcc64d4eb85233122d)

[油管链接](https://youtu.be/TlnytEi2lD8?si=jfcDj2MZqBptziZc)

## 运行方式
先将该项目clone到本地，然后在项目根目录下执行
```bash
pip install -r requirements.txt
```

### assistant方式运行
打开.env文件，在里面配置好OpenAI的API key
随后将pdf简历上传到文件夹auto_job_find里，命名为“my_cover".随后执行write_response.py即可
这种方式不支持使用自定义api，优势是执行速度更快
如果需要使用自定义api，请使用下面的方式运行

### langchain方式
同样打开.env文件，在里面配置好OpenAI的API key和你想要请求的api地址
随后将pdf简历放到文件夹resume里
最后执行write_response.py即可

## 简化付费版

可以一键下载直接运行，里面甚至不需要自己配置API，如果当前的免费版本让您头痛，难以使用，您也可以在下面链接找到一个更加易用的版本，抛除API和服务器我几乎
不赚钱，就当请我喝一杯咖啡吧，感谢各位的支持
https://www.123pan.com/s/0kebjv-gQIZ3.html




------------下面是其他朋友基于js构建的更加易于使用的代码---------------

我一直也在考虑如何可以降低各位的使用门槛，基于现在项目的热度，我发现很多朋友都需要这个东西来帮助自己，但是我相信对于更多的人而言，甚至vpn都是一个障碍

下面这位朋友基于js实现了一个更加简易的版本，虽然因为调用的免费api，无法使用assistant进行retrival，需要自己对简历进行简单的处理，但我依然认为这是个很棒的项目

感谢朋友的贡献，以下是链接：

[https://github.com/noBaldAaa](https://github.com/noBaldAaa/find-job)https://github.com/noBaldAaa/find-job

------------下面是其他朋友基于azure的openai api构建的版本的更加易于使用的代码---------------
https://github.com/LouisCaixuran/auto_job_find_azure


