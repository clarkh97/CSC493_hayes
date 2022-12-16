#Requirements

  - **1**: 
  - **Statement**: Read current and voltage data from the sensor.
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
  - **Evaluation Method**: I can calculate the mean of the power and hae it match what is displayed by my program.
  - **Dependency**: This is needed in order to detect the changeover from regular speed charging to trickle charging once the device is full.
  - **Priority**: essential
  - **Requirement revision history**: This is working as of November.

  - **4**: 
  - **Statement**: Keep a total of the power consumed by the device
  - **Evaluation Method**: Check that the total watt hours only goes up and adds up to the wattage measurement divided by 3600 (measurements taken every second)
  - **Dependency**: Nothing directly requires the total power consumed, but the method for adding up power is the same as when measuring during trickle charging.
  - **Priority**: high
  - **Requirement revision history**: This is working as of November.
  
  - **5**: 
  - **Statement**: Detect the change from regular charging to trickling to maintain full charge.
  - **Evaluation Method**: Does my program start adding the consumed power once the device is plugged in and charged to 100%.
  - **Dependency**: None
  - **Priority**: essential
  - **Requirement revision history**: This is not yet working.
