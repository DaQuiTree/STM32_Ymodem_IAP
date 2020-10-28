一、工程说明
    1、时间：    2017年11月11日
    2、作者：    strongerHuang
    3、开发环境：MDK-ARM V5.24a
    4、标准库：  V3.5.0
    5、工程版本：V1.0.0
    6、目标芯片：STM32F10x中容量芯片

二、提示
    本工程适合于STM32F10x大容量芯片(即:STM32F101, STM32F102, STM32F103中FLASH为64K - 128K的芯片), 包含:
              36Pin        48Pin        64Pin       100Pin
      64K: STM32F101T8  STM32F101C8  STM32F101R8  STM32F101V8
                        STM32F102C8  STM32F102R8
           STM32F103T8  STM32F103C8  STM32F103R8  STM32F103V8
     128K: STM32F101TB  STM32F101CB  STM32F101RB  STM32F101VB
                        STM32F102CB  STM32F102RB
           STM32F103TB  STM32F103CB  STM32F103RB  STM32F103VB

    只要没有特别说明，工程都适合以上芯片;
    可根据自己芯片型号选择相应的"工程目标", 比如：选择STM32F103RB
    (提示: 若目标选项中没有对应的型号,可自己修改型号，一般这系列芯片,型号不对应,软件也可兼容。
    修改型号:Project -> Options for Target ->Device选择对应型号即可)

三、帮助
    微信搜索公众号：EmbeddDeveloper, 关注, 查看更多精彩内容。
	
四、项目说明
	基于EmbededdDeveloper的F1 demo 和 洋桃1号开发板，移植的Ymodem + IAP 功能
