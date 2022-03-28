# VC16_Greyservice_Automation
This is a test script for the automation of VC16 greyservice's test, and it is should only be accessed by password, due to privacy policy
Q&A:
1. 为什么使用夜神模拟器而不使用其他模拟器或实际机器

  这里已经测试过a win11的基于HyperV的安卓子系统，连通调试工具后会有黑色悬浮窗遮挡，在weditor的issue下作者未回复相关解决办法；且win11装机率还较低
  mumu模拟器和bluestack没法开启相关的USB安装选项
  实际机型测试过程中出现了与电脑信息同步不及时，经常出现无响应，且受到手机云服务干扰等问题，故最终选择了模拟器联调
2. 本项目使用了什么框架

  weditor+uiautomator2
  具体文档可以参考：
  https://crifan.github.io/android_automation_uiautomator2/website/
3. 代码和相关文件在哪里

  在7z压缩包当中，里面有adb连接工具，咱们的v0.5.1版本工程app，调通的部分脚本，以及使用方法
  密码是咱们的试验车密码，qq那个
