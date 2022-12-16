# EquipmentController

仪器状态管理和控制的示例 使用Stateless来进行状态管理

![ui](https://user-images.githubusercontent.com/20536182/208009122-2991382d-8e35-41d4-a410-addd727a0a3b.png)

流水线控制多个设备，实现多个仪器的控制和管理。流水线有启动，暂停和停止的控制功能。
仪器控制器是控制单独一个仪器的动作，当仪器错误时可以恢复仪器。
仪器的状态是仪器的运行状态模拟，通过通信控制来模拟设备状态。

仪器的状态图
![c501](https://user-images.githubusercontent.com/20536182/208004608-c063193f-81a9-498e-86ef-b041fca8f17e.png)


仪器控制器的状态图
![c501m](https://user-images.githubusercontent.com/20536182/208004618-5cdae478-4310-41b4-9b8a-9d629d20f277.png)


仪器流水线的状态图
![c501dl](https://user-images.githubusercontent.com/20536182/208004613-86ff2a3e-d580-4005-88bd-eb1da6286654.png)

