# Powerflow
输入数据格式
1.	第一行依次输入网络的节点数、连接支路数、PQ节点数、PU节点数、平衡节点序号。从第二行开始每一行分别按照支路连接的两个节点序号、电阻、电抗、电纳、是否有变压器、变压器变比的顺序输入。
	需要特别注意的是，如果该支路存在变压器，根据变压器的π型等效模型，图中q,p节点的对应顺序需要按照K:1的关系填写。例如本设计中使用的样例应该在该行输入的数据格式为：
1  4  0.04  0.12  0  1  1.05
2.	在输入完成连接支路相关参数后紧接着按照节点序号、节点类型（1-PQ节点 2-PU节点 3-平衡节点）、给定的P、Q、U和计算起始电压初值。
