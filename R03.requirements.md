

  - **1**: 
  - **Statement**:Read current and voltage data from the sensor.
  - **Evaluation Method**: Use a known voltage and current in order to compare the numbers given by the program
  - **Dependency**: All other requirements rely on this information.
  - **Priority**: Essential
  - **Requirement revision history**: I have successfully accomplished this requirement as of early October.
  
  - **Number**: 2
  - **Statement**: Calculate and record power consumption of device connected to sensor.
  - **Evaluation Method**: I will have to manually calculate the power based on the voltage and current reading, then compare the number I calculated to what is displayed.
  - **Dependency**: Keeping track of power consumption is dependent on this working properly.
  - **Priority**: Essential
  - **Requirement revision history**: This is working properly as of October. Numpy was used to keep a running average and total on the power consumption.
  
  - **3**: 
  - **Statement**: Keep a running average of power consumption in order to make a baseline for consumption.
  - **Evaluation Method**: I can calculate the mean of the power 
  - **Dependency**: (List each other requirement on which satisfaction of this requirement depends or write "None")
  - **Priority**: (Assign a priority to this requirement: essential, high, middle, low, or if time permits.)
  - **Requirement revision history**: (when, what, and why)

