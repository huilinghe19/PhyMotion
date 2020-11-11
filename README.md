# PhyMotion

PhyLOGIC is the software to control the hardware PhyMotion, which can be only executable on WINDOWS system. 

PhyLOGIC can support MCC 2 with 2 axises and PhyMotion with 10 axises. The Problem may be, how we can control the windows remotely and see the motors. The first method is with NoMachine. The other method is AnyDesk, which has been rejected by IT. There is already a camera in my office, which can be used to supervise the motors. 

How do we ensure that when a motor reaches the limit, all motors stop running? In the software, with the status check commands like X=H(X#H) or X=N(X#N), we can get the status of the individual motor. Then we use the condition sentence to transfer to check the other motors or stop the other motors.
In the Epics environment, add 6 epics motors for the axises and set a virtual motor for Hexapod to limit the GO and Stop. Combine the commands with Spec command, we can use spec to control the Hexapod. 
