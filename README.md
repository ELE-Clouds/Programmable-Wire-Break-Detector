# 可编程线路通断检测器
## Programmable wire break Detector
本工具主要适用于频繁对多芯线缆及排线进行线路通断与排序检测。最大可测线数为40芯（单端）。如网线、DB9串口线、DB25串口线、IOS数据线等。可根据当前连接方式，通过PC端或手机端（安卓系统）对检测器进行逻辑编程，并保存为检测模板，方便检测器调用。
<br><br>
其主要功能：<br>
1、通过率IO口发出信号，同时，检测其它各IO口的信号状态，若检测到信号，判断其是否与实际情况判断其是否与实际情况相符，若相符，则检测下一条线路，若不符，则判定为线路故障；<br>
2、……

| 类别 | 位置  |   字符    |     位数     |
| :--- | ---  | --------- | ------------ |
|     |      | 大写字母   | 0-255        |
|     |  左  | 小字字母   | 0-255        |
|     |      | 数    字   | 0-255        |
|     |      | 特殊字符   | 0-255        |
|     |      | 大写字母   | 0-255        |
|     |  中  | 小字字母   | 0-255        |
|     |      | 数    字   | 0-255        |
|     |      | 特殊字符   | 0-255        |
|     |      | 大写字母   | 0-255        |
|     |  右  | 小字字母   | 0-255        |
|     |      | 数    字   | 0-255        |
|     |      | 特殊字符   | 0-255        |
| 手势密码 |      | 数    字   | 3-9        |
