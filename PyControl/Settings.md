# 参数设置

## General

| 字段                          | 说明                                                              |
|-----------------------------|-----------------------------------------------------------------|
| IsGcsCommunicatorSerialPort | 船控与地面站通讯方式：true为串口，false为网口                                     |
| GnssType                    | 惯导类型：<br/>0为BIN协议<br/>1为ASCII协议<br/>2为维特协议<br/>3为瑞芬协议<br/>4为FDI |
| WarningThreshold            | 按默认值10                                                          |

## Actuators

| 字段                  | 说明                        |
|---------------------|---------------------------|
| IsMonohull          | 是否为单体船，true为单体船，false为双体船 |
| IsThrustSbus        | 无需修改                      |
| IsAble2Reverse      | 是否支持正反转                   |
| IsSwitchReverse     | 开关切换正反转，无需修改              |
| SbusChannel1Min     | 遥控器通道参数                   |
| SbusChannel1Mid     | 遥控器通道参数                   |
| SbusChannel1Max     | 遥控器通道参数                   |
| SbusChannel3Min     | 遥控器通道参数                   |
| SbusChannel3Mid     | 遥控器通道参数                   |
| SbusChannel3Max     | 遥控器通道参数                   |
| SbusRudderMin       | 舵量参数配置                    |
| SbusRudderMid       | 舵量参数配置                    |
| SbusRudderMax       | 舵量参数配置                    |
| SbusThrustMin       | 推力参数配置                    |
| SbusThrustMid       | 推力参数配置                    |
| SbusThrustMax       | 推力参数配置                    |
| SbusChannel6On      | 通道6参数配置                   |
| SbusChannel6Off     | 通道6参数配置                   |
| SbusReverse1On      | 无需配置                      |
| SbusReverse1Off     | 无需配置                      |
| SbusChannel7On      | 通道7参数配置                   |
| SbusChannel7Off     | 通道7参数配置                   |
| SbusReverse2On      | 无需配置                      |
| SbusReverse2Off     | 无需配置                      |
| SbusChannel5Default | 通道5参数配置                   |
| SbusChannel5On      | 通道5参数配置                   |
| SbusChannel5Off     | 通道5参数配置                   |
| SbusIgnitionDefault | 点火通道参数配置                  |
| SbusIgnitionOn      | 点火通道参数配置                  |
| SbusIgnitionOff     | 点火通道参数配置                  |
| SbusChannel8Default | 通道8参数配置                   |
| SbusChannel8On1     | 通道8参数配置                   |
| SbusChannel8On2     | 通道8参数配置                   |
| SbusSamplingDefault | 采样通道参数配置                  |
| SbusSamplingOn1     | 采样通道参数配置                  |
| SbusSamplingOn2     | 采样通道参数配置                  |

## Pid

| 字段        | 说明          |
|-----------|-------------|
| VehicleId | PID参数，可在线调参 |
| HeadingP  | PID参数，可在线调参 |
| HeadingI  | PID参数，可在线调参 |
| HeadingD  | PID参数，可在线调参 |
| SpeedP    | PID参数，可在线调参 |
| SpeedI    | PID参数，可在线调参 |
| SpeedD    | PID参数，可在线调参 |
| PositionP | PID参数，可在线调参 |
| PositionI | PID参数，可在线调参 |
| PositionD | PID参数，可在线调参 |
