# LSSY量化交易系统

该项目是本人3年来研究量化慢慢积累开发的一套系统，属于早期作品慢慢修改而来，仅供学习研究，回测分析。

支持A股和可转债市场并且可以实盘全自动交易的量化交易系统。

开源的目的是希望能有更多的人来参与社区维护，共同打造最完美的量化交易系统。

目前市场上集量化回测、实盘交易的系统并不多，适用A股的更是寥寥无几，要么收费高昂，LSSY量化交易系统为了让研究量化交易的朋友人人都能用，所以在此开源，并且完全免费，希望更多的人来参与完善系统，贡献自己的一份力量，避免大家重复劳动。

LSSY量化交易系统致力于量化交易，不再主观交易，通过数据，做大概率，让量化交易变得更容易，大家都可以参与完善，**为了更好的利于社区发展，目前采用邀请制，使用邀请码才能完整的使用LSSY量化交易系统**，提交代码或者推广都可以免费获得邀请码。

使用LSSY量化交易系统编写**海龟交易法则**

https://edu.csdn.net/course/detail/31900

LSSY量化交易系统的**全面详细分析视频教程**

https://edu.csdn.net/course/detail/31906


# 环境安装

  * Python 3.7+

  * Redis
  
    Windows
    
    https://github.com/microsoftarchive/redis/releases

    Linux

    ```
    sudo apt install redis
    ```

# 执行安装脚本

  Windows

  ```
  install.bat
  ```

  Linux

  ```
  ./install.sh
  ```

# 启动LSSY量化交易系统

  * **Windows**

  进入实盘交易

  ```
  win_backtest.bat
  ```

  进入回测

  ```
  win_realtime.bat
  ```

  * **Linux**

  进入实盘交易

  ```
  ./runWork.py
  ```

  进入回测

  ```
  ./runWork.py b
  ```

# 访问前端

  推荐分辨率>=2k

  ```
  http://127.0.0.1:8000/
  ```

# 初次启动注意事项

首次部署LSSY量化交易系统，会下载大量财务历史等数据，根据网络情况可能会很慢，建议晚上睡觉前启动系统，一般到第二天就全部下载完成了，仅首次运行，后续每天只需要更新k线即可，速度会快很多。

QQ群讨论社区：174647513

微信: qiji_hello




