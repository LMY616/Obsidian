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


# 高功率MOSFET功率耗散
功率耗散、结温计算、最大结温限制等公式在没有散热器时都是一样的
在有散热器时，热量先从j