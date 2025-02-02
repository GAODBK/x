# x

玩配音的基本都知道，微软的edge-tts是好用免费的语音合成利器，唯一缺点是对国内限流越来越严，不过可以通过部署到 cloudflare 来规避，并且还能白嫖 cloudflare的服务器和带宽资源。

先看效果，完成后将有一个配音api接口和一个web配音界面

这是接口调用js版函数，并兼容 openai tts 接口

[接下来说说如何部署到 cloudflare 上](https://pyvideotrans.com/edgettscf)
