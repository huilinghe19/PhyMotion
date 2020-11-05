# PhyMotion

PhyLOGIC is the software to control the hardware, which can be only executable on WINDOWS system. 

PhyLOGIC can support MCC 2 with 2 axises and PhyMotion with many axises. The Problem may be, how we can control the windows remotely and see the motors. The first method is with NoMachine. The other method is AnyDesk, which has been rejected by IT. There is already a camera in my office, which can be used to supervise the motors. 

The last problem that we have not solved is, How do we ensure that when a motor reaches the limit, all motors stop running? This is not easy to achive in the programm process, because the execution is serial. There is no status check phase.  Just in a higher ebene we can set a status check regarding the limit switch for all the motors. It may be necessary to wait for the equipment to arrive, take a closer look at the file, and try different methods to solve this problem.
