# stm32_dual_modbus
support master and slave modbus
 本工程参考了freemodbus的思路，集成了主站和从站模式，但是只添加了RTU模式的部分操作功能码
 另外需要注意的是由于本人的测试板是stm32RCT6配12MHz的晶振，所以对于8MHz的晶振就需要将时钟修改成8MHz的，具体怎么修改自己baidu或者google就行
