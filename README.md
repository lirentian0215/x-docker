**一、主要特点：**

1. 节点在日志可看，粘贴到软件即可食用，高手可以随意更改

2. 进程名称与MD5值随机变化，每次部署都不一样

3. Super与Chatdog双进程守护

4. 采用Apline最小化
   
5. 可以自行替换二进制程序,kano就是x-ray,cff就是argo,nez就是哪吒

**二、变量建议设置：**

PW  : 启动密码，必须，否则无法启动。防扩散密码，固定值，不可更改，群里获取

TOK： Argo TOKEN ，必须。

UUID： 默认 f0177922-2dcc-4c0f-819c-7b74b7bbbfac ，可选,建议更改

VMPATH：默认vm123456 ，可选,建议更改

VLPATH：默认vl123456 ，可选,建议更改

URL  :伪装的主页，默认www.aifure.com，建议更改

DOMAIN： 隧道域名或套了CF的域名,可选,建议小白更改。（DOMAIN填写只是为了小白粘贴节点方便，高手随意）。

PORT：端口，默认7860 ，不建议更改，只要能正常使用即可（huggingface不可更改，其他容器根据需要可改）

NEZHA_SERVER： 哪吒 ，可选，有平台封杀，建议不设置

NEZHA_KEY： 哪吒 ， 可选，有平台封杀，建议不设置

NEZHA_PORT： 哪吒 ，默认443， 可选，建议不设置

NEZHA_TLS： 哪吒TLS ，默认1,设置0关闭，建议不设置

新增：

BAOHUO_URL: 可以输入容器保活网址实现自保活，可选，需要保活的容器可填，比如render

说明：这里面的所有变量都可以不改，也都可以改，只是为了小白提供了设置建议，高手随意改

**三、常见容器平台部署方法：**

**1、PATR部署，其他可以参考：**

![image](https://github.com/dsadsadsss/x-docker/blob/main/png/patr1.PNG)

![image](https://github.com/dsadsadsss/x-docker/blob/main/png/patr2.PNG)

**2、render部署，其他可以参考：**

   [点击查看](https://github.com/dsadsadsss/render.git)

**3、codesandbox部署，其他可以参考 ：**

 [点击查看](https://github.com/dsadsadsss/codesandbox.git)

**4、huggingface部署，其他可以参考 ：**

   只需2步操作
   
**第1步：进入https://huggingface.co/spaces/Donna11/tews ，点击右上角Settings右边的三点选最后一项复制空间**

   ![image](https://github.com/dsadsadsss/x-docker/blob/main/png/fuzhi.PNG)
   
**第2步：设置UUID、VMPATH,VLPATH,PW、TOK、URL变量，最好不要哪吒，其他变量默认即可**

**四、节点查看： 直接到日志里面复制粘贴到软件，修改host,优选IP等即可，节点已经通过v2rayN软件测试，其他软件需要自己修改**

**五、手动设置参考**

**1、ARGO设置：**

   ![image](https://github.com/dsadsadsss/x-docker/blob/main/png/argo1.PNG)

**2、V2rayN设置：**

  ![image](https://github.com/dsadsadsss/x-docker/blob/main/png/vless.PNG)

