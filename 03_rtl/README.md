# 03_rtl

只放可综合的 RTL 源码：`common`（公共库）、`tx`（发射链路）、`rx`（接收链路）、`agc`（自动增益控制）、`regs`（寄存器与总线）、`top`（顶层与集成）。

严禁放入仿真激励、testbench、波形文件（vcd/fst/wlf）与各类 log；验证相关内容一律放 `04_verif`。本目录代码须通过可综合性与 lint 检查后方可提交。
