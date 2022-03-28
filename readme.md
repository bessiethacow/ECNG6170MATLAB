# ECNG6170MATLAB
###########################################################################################################
Health Diagnostics Center Data Upload & Plot Generator App
###########################################################################################################
------Attributions-----------------------------------------------------------------------------------------

Made by: Tariq Mohammed (816010063)
For: ECNG 6710 Research Methods
Date: 27 March 2022 
Link to clone repo: https://github.com/bessiethacow/ECNG6170MATLAB

###########################################################################################################
------Requirements-----------------------------------------------------------------------------------------

1. Machine capable of running MATLAB
2. MATLAB R2021b (recommended)
3. Project folder (see steps below to download)

###########################################################################################################
------Instructions-----------------------------------------------------------------------------------------

--Installing and opening the app
1. Clone the repo at: https://github.com/bessiethacow/ECNG6170MATLAB, if not already downloaded
2. Unzip folder with the project's files
3. Open MATLAB 
4. Set the MATLAB path to that of the downloaded files
5. Close MATLAB
6. Open the "HealthDiagnosticsCentreData.xlsx" file. 
   The Data Upload window should appear after a short while


--Importing and loading of files
1. Click the "Select File" button on the Data Upload Window
2. Browse your computer for the "" file.
   Note that any files used in this project should be Excel files, and should contain the same format
3. Select your file (). You will notice that the path next to the "" button updates
4. Click the "Load Data" button. 
   Error messages displayed if: 
	 (i) incorrect file path is chosen
	(ii) data contains non-numeric data


-- Plotting Data 
1. Follow the importing and loading of files steps
2. Click on the "Plot Data" button
   Error message displayed if imported data contains non-numeric data
3. If there are no errors, the Plot Generator Window should automatically open and reveal a default 3D plot


-- Configuring Plots

- Changing Plot Type:
1. Locate the 
2. Click on the "2D" or "3D" radio buttons to toggle between 2D and 3D plots.
   Note that only one plot type can be displayed at a time

- Changing Axes:
1. Locate the axes selector dropdown menus, to the left of the plot
2. Click on the dropdown menus to change the x, y, or z axes
   Note: You cannot select z-axis data when displaying 2D plots
   Error message displayed if:
	 (i) The same data is selected for any of the axes
	(ii) "patientWaiting" is sleected on either the x or z axes. This is an ongoing problem which our
	     team will be resolving in the coming updates
3. On selection, and if there are no errors, the plots will automatically update to show the selected data

- Toggling the grid:
1. Locate the "Show Grid" checkbox to the left of the plot
2. Click on the checkbox to turn the grid on (if check is placed in box) or off (if check removed)
3. On click, the plots should instantaneously update to show/hide the grid

- Changing your Plot's Colour Scheme:
1. Locate the "Colour Schemes" selection box at the bottom left of the plot generator window
2. Click on one of the three colours to change the plot
3. On click, the plot colours should instantaneously update to the selected colour


--Closing the Plot Generator Window
1. Click on the "X" icon in the top right corner of the Plot Generator window
2. On click, a popup should appear, asking to confirm whether you wish to exit
3. To close the window, click on the "Yes" button. If you do not wish to close, click on the "Cancel"    button


--Closing the Data Upload Window
1. Click on the "X" icon in the top right corner of the Plot Generator window
2. On click, a popup should appear, asking to confirm whether you wish to exit
3. To close the window, click on the "Yes" button. If you do not wish to close, click on the "Cancel"    button

###########################################################################################################
------Known Bugs-------------------------------------------------------------------------------------------

1. May not perform 3D plot with "patientData" configured as y or z axes

###########################################################################################################
------END OF FILE------------------------------------------------------------------------------------------
###########################################################################################################
