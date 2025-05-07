# 小信号MOSFET
## 功率耗散
使用场景：低电流、低功率，直接安装在PCB上，无需散热器
![[Pasted image 20250507145903.png]]

## 热阻模型
![[Pasted image 20250507150848.png]]
T_jactual：实际结温（不易测量）
T_ambient：环境温度
R_thja：结温到环境的热阻

## 最大结温限制
![[Pasted image 20250507151109.png]]
P_diss_MOSFET_max：MOSFET最大损耗功率
T_jmax：最大允许结温


## 结温计算
![[Pasted image 20250507151335.png]]


# 高功率MOSFET
功率耗散、结温计算、最大结温限制等公式在没有散热器时都是一样的
在有散热器时，热量先从结传到外壳，再通过散热器胶传到散热器，最后热量通过传导到空气中。
## 功率耗散
![[Pasted image 20250507152548.png]]
T_jactual：实际结温
T_cactual：实际壳温
R_thjc：结到壳的热阻
R_thchs：壳到散热器的热阻（散热器胶）
R_thhsa：散热器到空气热阻
## 结温计算
![[Pasted image 20250507152814.png]]
T_cactual：实际壳温
R_thjc：结到壳的热阻
R_thchs：壳到散热器的热阻（散热器胶）
R_thhsa：散热器到空气热阻