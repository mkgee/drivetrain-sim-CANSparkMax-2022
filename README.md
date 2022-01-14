This example was copied from https://github.com/wpilibsuite/allwpilib/tree/main/wpilibjExamples/src/main/java/edu/wpi/first/wpilibj/examples/simpledifferentialdrivesimulation
It was also updated to work with the 2022 FRC® Control System software (WPILib).  
This runs in 2022 WPILib VS Code.

To run this demo:
1. Load this project in 2022 WPILib VS Code
2. Enable simulation mode:
    <Ctrl><Shift>P - type/choose WPILib Change Desktop Support Enable Setting and ensure its enabled
3. Start the robot simulation:
    <Ctrl><Shift>P - type/choose WPILib: Simulate Robot Code
    The code will build and after a successful build, you will see Sim GUI checkbox checked, click on OK
    The Robot Simulation app will start.
4. A window titled "Robot Simulation" should appear.  
	a. In this window, open the 2D field: Network Tables -> SmartDashboard -> Field.  
		You should only need to do this the first time.  
	b. You can then load an image that matches this years competition from 
		https://github.com/wpilibsuite/PathWeaver/blob/main/src/main/resources/edu/wpi/first/pathweaver/2022-field.png.  
		Click on the "Download" button.  Then right mouse on it and click on "Save as..." 
		and save it to your computer.  
	c. In the "Robot Simulation" window, right click on the title of the Field widget, 
		then click on Field to open the Field menu, then click on "Choose image..", 
		then navigate to where you saved "2020-field.png" and open it.
5. To start the motion of the sim robot, we need to be in autonomous mode.  
   In the "Robot Simulation", click on "Autonomous" in the "Robot State" widget.  
   You should see the green triangle move in the Field widget from the bottom left of the field, move up,
   across from left to right, then down on thr right side.
6. To end the simulation, click on the orange square button at the top of vscode.