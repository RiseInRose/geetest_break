# geetest_break
# 极验验证码破解-源码+破解手册
  说明：与网上已有的使用selenium自动化浏览器的方法相比，本方法更便捷，无需安装额外模块，只使用Python原生requests和lxml。
  此外，selenium方法太依赖于浏览器，稍有不慎，便得不到想要的移动方式。
  
 # 与selenium方法相比优点如下：
   1. 安装方便，python或anaconda即可；
   
   2. 不依赖于浏览器，模拟发包请求，快捷，
   
   3. 识别率极高（使用经过验证的轨迹数据），selenium方法我也试过，即使能够移动滑块至缺口处，很多情况会被远程服务器识别出是机器行为；
   
   4. 便于管理，是需提供验证过的轨迹数据即可（轨迹数据采集也很方便，可定期更新）。
   
  
（已完成文档撰写，暂不公布，机会合适再开源）
 # 在线超详细教程（图文并茂）已发表在知乎 简书
 
   https://zhuanlan.zhihu.com/p/28492887
   
   http://www.jianshu.com/p/3726581d218a
   
 # 为了下载方便，我也上传了PDF版本供下载~~~
 ## 觉得不错帮忙Star一下

# 真心没想到有这么多人star，谢谢大家！
最近忙于面试，一直未能一一回复大家，抱歉。
# 我创建了一个QQ群，方便大家一起学习讨论~  有兴趣的可以加群交流：658927203
这两天我也会整理一下代码并上传（供大家参考）。
# 源码已加注释并上传（业余项目，写的可能不鲁棒，仅供参考，谢谢）
运行： python geetest_break.py
location_list.pkl 为拼接图片所用到的位置信息
t_dict.pkl 为我之前收集的一些轨迹信息。
ps. t_dict.pkl 中的某些轨迹可能出现使用次数频繁被短暂封的情况（毕竟后台一堆程序员在维护这个验证码服务），可以自行定期更新管理。
# 若有技术问题可以在issue中提出~~~
