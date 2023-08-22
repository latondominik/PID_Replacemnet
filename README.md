# PID_REPLACMENT
 
In domestic hot water installation case, it is a fast-changing process, where the response of the installation to a change in valve position is immediate. In this case, the PID controller is used for control. The domestic hot water control algorithm based on PID generates large oscillations in valve operation and water temperature, which has a negative impact on the lifetime of the valve and user comfort, as well as energy consumption. The main goal of this project is application of machine learning and deep learning methods to improve the quality of control. The first part of the research will be building a test stand, that could emulate processes in domestic hot water installation and choosing appropriate metrics, that would help to compare all the control algorithms. The next part is the application and calibration of the PID controller, which will be used as a reference in further research. After this, the regression models will be prepared and applicate to the test stand to compare it with the PID controller based on chosen metrics. The next part is preparing and applicate on stand Neural Network and LSTM models and compare it with the rest models. The last part of the research is the application of reinforcement learning algorithms on the test stand. To do it correctly, without any risk of destroying the test stand, it is obligated to prepare a model that will simulate the stand. The simulation model based on LSTM will be prepared. After this, the reinforcement learning model will be prepared based on the simulator and applicate on the test stand. In the end, the results of all models will be compared based on chosen metrics to choose the best solution.

![image](https://github.com/latondominik/PID_Replacemnet/assets/45373822/2dd56eaf-3f30-4501-b63d-43655497b467)

Figure shows a diagram of the test stand. The water tank is supplied with cold water and has the option of releasing hot water. A temperature sensor and a heater have been installed in the tank. The hater is connected to Solid state relay (SSR) that could modulate a heater’s input voltage which translates into heating power. The SSR and Temperature sensor are connected to Control Unit that read the temperature and could set the choosing voltage to heater input. The time step (the time between one sample and another) was taken as 5 sec. The control unit was selected in such a way as to be able to implement various control algorithms such as PID, Regression Models or Neural Networks. 
