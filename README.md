# PSO-IPSO-LSTM-regression
this project use pso and ipso to optim lstm's hyperparams, include learning rate,hidden-nodes and training epoch number. and finally use ipso-lstm for power load forcast.



提出一种改进的粒子群算法ipso，用于lstm迭代次数，学习率，隐含层节点数的寻优，最后将ipso-lstm用于电力负荷的回归预测，以头一天平均温度、最高温度、最低温度、相对湿度、星期类型、与24个时刻的负荷，共29个特征作为输入，以预测日24个时刻的电力负荷作为输出
main1.py 为将pso与改进pso用于标准函数极值寻优
main2.py 为没有优化的两隐含层lstm
main3.py 为将pso用于优化两层lstm
main4.py 为将ipso用于优化两层lstm
main5.py 为将lstm,pso_lstm,ipso_lstm得到的结果画图
需要代码的加我qq2919218574
