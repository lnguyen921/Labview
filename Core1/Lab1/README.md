Lab 1: Using Timing Function to help reduce load on CPU

Required Softwares: 
  - LabView 2020 Q3 or newer
Instructions:

A. Set Loop Period
  In this part of exercise, you set a specific loop period for your While Loop.
    1. Explore the Set Loop Period VI.
        ▪ Open Using Timing Functions in a Loop.lvproj.
        ▪ From the Project Explorer window, open the Set Loop Period VI.
    2. Run the VI.
        ▪  Notice that the loop runs as fast as possible.
    3. Set the loop to execute every 1,000ms which is 1 second.

    4. Run the VI and observe.

    5. Change the constant to 500ms. Observe the speed at which it runs the while loop.

B. Reduce CPU Usage
  In this exercise, you will use a wait function to reduce CPU usage.
  1. Open CPU Usage of Loop VI.
  2. Observe the CPU usage when you run this VI by looking in the Process Tab of Task Manager.
  3. Stop the VI, then add a Wait(ms) function.
  4. Add a constant of "100" for 100ms.
  5. Run the VI and check the CPU usuage in Process Tab.
  6. Observe and see if CPU is working less than before.


C. Run the Timestamp and Elapsed Time Functions VI
This is a challenging exercise. Use what you learned to reduce the CPU usage.

