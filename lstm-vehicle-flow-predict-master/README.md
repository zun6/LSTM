# lstm-vehicle-flow-predict
利用DeepLearning4j框架提供的lstm神经网络实现对车流量预测

数据准备：
    修改数据库配置:resources/jdbc.properties
    创建MySQL数据库：jtt_new
    执行sql脚本：resources/testdata.sql

模型训练阶段:
    initPreTrain(inoutType, highway);
    trainModel();
    testModel(highway);

预测数据阶段:
    initPrePredict(inoutType, highway);
    predict();

#VehicleFlowPredictionUI类为可视化训练123
