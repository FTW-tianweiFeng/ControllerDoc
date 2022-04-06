[General]
IsGcsCommunicatorSerialPort=true  # 船控与地面站通讯方式 True为网口，False为串口
GnssType=0 # 惯导类型，0为ANPP协议，1为Ascii协议，2为维特协议，3为瑞芬协议
WarningThreshold=10 # 雷达警告等级 ，默认，无需修改

[Actuators]
IsMonohull=true # 是否为单体船，True为单体船，False为单体船
IsThrustSbus=true # 无需修改
IsAble2Reverse=false # 是否支持正反转
IsSwitchReverse=false # 开关切换正反转，无需修改
SbusChannel1Min=65535 # 遥控器通道参数
SbusChannel1Mid=65535 # 遥控器通道参数
SbusChannel1Max=65535 # 遥控器通道参数
SbusChannel3Min=65535 # 遥控器通道参数
SbusChannel3Mid=65535 # 遥控器通道参数
SbusChannel3Max=65535 # 遥控器通道参数
SbusRudderMin=352 # 舵量参数配置
SbusRudderMid=1024 # 舵量参数配置
SbusRudderMax=1696 # 舵量参数配置
SbusThrustMin=1696 # 推力参数配置
SbusThrustMid=1024 # 推力参数配置
SbusThrustMax=352 # 推力参数配置
SbusChannel6On=65535 # 通道6参数配置
SbusChannel6Off=65535 # 通道6参数配置
SbusReverse1On=1696 # 无需配置
SbusReverse1Off=352 # 无需配置
SbusChannel7On=65535 # 通道7参数配置
SbusChannel7Off=65535 # 通道7参数配置
SbusReverse2On=1696 # 无需配置
SbusReverse2Off=352 # 无需配置
SbusChannel5Default=65535 # 通道5参数配置
SbusChannel5On=65535 # 通道5参数配置
SbusChannel5Off=65535 # 通道5参数配置
SbusIgnitionDefault=1024 # 点火通道参数配置
SbusIgnitionOn=352 # 点火通道参数配置
SbusIgnitionOff=1696 # 点火通道参数配置
SbusChannel8Default=65535 # 通道8参数配置
SbusChannel8On1=65535 # 通道8参数配置
SbusChannel8On2=65535 # 通道8参数配置
SbusSamplingDefault=1024 # 采样通道参数配置
SbusSamplingOn1=352 # 采样通道参数配置
SbusSamplingOn2=1696 # 采样通道参数配置

[Pid]
Id=0 # USV编号
HeadingP=0 # PID参数，可在线调参
HeadingI=0 # PID参数，可在线调参
HeadingD=0 # PID参数，可在线调参
SpeedP=0 # PID参数，可在线调参
SpeedI=0 # PID参数，可在线调参
SpeedD=0 # PID参数，可在线调参
PositionP=0 # PID参数，可在线调参
PositionI=0 # PID参数，可在线调参
PositionD=0 # PID参数，可在线调参
