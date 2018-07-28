The aim of this project is to develop a vision-based sudoku solver that is capable of solving printed sudoku puzzles on paper using computers with camera inputs. This project is called SudokuN, which indicates 'Mr.Sudoku' in Japanese.

**1. Instruction**
To use SudokuN, please open and run the file 'Webcam_gui.m' in the folder 'Sudokun_Matlab'. 
After running the file, there will be two buttons on the user interface: 'preview' and 'phot and solve'. Please 
follow the instructions below:
	--Click the button 'preview' to access the camera. It may take a few seconds, depending on your computer.
	--Click the button 'photo and solve'.
	--Select the  region of interest (RoI) and make sure the sudoku puzzle stands right in the middle of RoI.
	--Double click to confirm the RoI.
	--The result will display after a few seconds. An evaluation of the sudoku difficulty will also be shown.

We have converted the Matlab codes to a software application. Please click '.\Sudokun_exe\for_testing\Sudokun.exe' 
to have a try. The following operations are the same as the instruction above. A demonstration of how to use this
software is also provided in '.\Sudokun_exe\Demo.mp4'.
 
**2. Prerequisites for deployment**
	Software:
	-- Windows Platform
	-- Matlab version 9.4 (R2018a)
	-- Neural Network Toolbox
	-- Image Processing Toolbox
	-- MATLAB Support Package for USB Webcams
	-- Computer Vision System Toolbox
	-- Image Acquisition Toolbox
	-- Image Acquisition ToolboxSupport Package for OS Generic Video Interface
	-- Mapping Toolbox
	-- YALMIP Toolbox, available in the folder YALMIP-master(from https://yalmip.github.io/download/)
	Hardware:
	-- A connected camera (resolution >= 1920*1080)

**3. Common Problems:**
	--If your webcam is inaccessible, you can feed provided images into the function 'sudokuBrain.m'
	  to check the performance. We have provided 6 testing images in '.\Sudokun_Matlab\Testimage'.
	--Please add the folder 'YALMIP-master' to the Matlab's path.
	--If your computer is under MacOs platform, please change the 'winvideo' to 'macvideo' in the file
	  'Webcam_gui.m'. Please refer to Matlab's inbuilt function webcam() for more information.
	--Please guarantee a normal illuminance for testing.

**4. Notes:**
The testing computer is Microsoft Surface Pro4.
The default camera is 'Microsoft Camera Rear'.