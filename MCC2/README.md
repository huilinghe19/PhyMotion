# MCC 2 controller 


MCC 2 controller is an older product from PhyMotion firm. We use it just to understand the theory of PhyMotion control and learn something for the future use. 

There are 2 axises: X and Y. One axis runs with a normal frequency 6000, one runs with a normal frequency 2000. The acceleration are set as 4000. In principle,
the data process is slow, a small program with 100 lines needs almost 4.5 seconds. Of course, the delay time for data transfer can be 0.5-1.5 second. 
When the moving path of axis Y is over 30000, axis Y should be moving faster with a high velocity in oder to reduce the time. Once the Y velocity(start frequency) is set as 6000, the axis Y can be stopped before the whole path is done.  

With different moving paths we can set the different velocity to adapt the lengths, this simple numerical calculation can be used in simple situations.
When the situation is complex, it takes many tests to get the best solution. In addition, the speed range and required time of each axis need to be known in advance.
The delay time is different by different axises for a long path.
