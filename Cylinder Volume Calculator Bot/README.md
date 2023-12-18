# Project Overview

Build a bot which calculates the volume of a cylinder. 
The calculation must be performed in a separate xaml file which gets invoked into the main workflow. 
Arguments must be used to pass the calculation parameters in and out of the process which calculates the volume.

### Instructions

- Create three sequences in the main.xaml file and name them "Input", "Process" and "Output" respectively.
- Add in two Input Dialog activities to get the Cylinder Height and Radius. Set both variable types to System.Double.
- Create a new sequence workflow and call it "CalculateVolume.xaml". Invoke this workflow in the Process sequence of the main workflow.
- Create three arguments in the CalculateVolume workflow and call them 'height' set to 'in' direction, 'radius' set to 'in' direction and 'result' set to 'out' direction.
- Pass the arguments in and out of the Invoked Workflow in the main workflow.
- Calculate the volume (V) of a cylinder using the arguments in the CalculateVolume workflow using an Assign activity. Hint: V=π*(r^2)*h where r = radius and h = height.
- Use the math.pi expression for the value of pi.
- Display the result in a Message Box activity in the Output sequence of the main workflow.
