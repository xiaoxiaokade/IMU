
​      IMU_base_V7是IMU底板的第七版，更换了DCDC芯片，换成SY8303，电源已稳定，但电感选型有误，其饱和电流太小。

​     IMU_base_V7.1在IMU_base_V7的基础上，换了饱和电流更大的功率电感，并且改正了一些如丝印错误、元件位置放置不佳等小问题。

​     IMU_base_V7.2重新换回TD1469，并去掉了前馈电容，但是有一个奇怪的现象，在学生电源上电没问题，但使用电池上电就会烧。

​     IMU_BMI088是FPC软板。由于BMI088的工作温度在45°左右，故需将其与底板隔开。 
