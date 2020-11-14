# --CPU
用vivado实现一个CPU去计算斐波那契数列
编写程序，实现指令周期中的取指令 IF、指令译码 ID、存储器访问 MEM、指 令执行 EXE、结果写回 WB 这五个阶段。通过设计 PC、PCadd、ROM、ID、ControlUnit、 register、ALU、extend、rtrd_select、shift_select、imm_select、reg_select、 ram 这些模块，并用顶层文件 top 进行调用，实现 MIPS 的二十条指令。
在实现此单周期 CPU 的条件下，通过加入 IOManager 对 ram 包装，并根据实 现斐波那契数列的 MIPS 指令编写 ROM 代码，完成在 CPU 上实现斐波那契数列。
