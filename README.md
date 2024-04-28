demoV1.circ是一个实现部分龙芯指令的5段流水CPU参考样例，分为IF, ID, EXE, MEM, WB。
使用Logisim来设计和仿真，设计时考虑了后续需要根据电路图写出verilog代码，因此在大量使用了tunnel标签。在转换为代码时，电路里的每一个tunnel标签可以看出是一个变量。
