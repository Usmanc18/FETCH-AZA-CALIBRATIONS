Axial Seamount Pressure Data Analysis
This repository contains Jupyter notebooks and related scripts for analyzing pressure data from the Sonardyne FETCH A-Z-A instrument at Axial Seamount. The analysis focuses on calibrating the pressure data, correcting for drift, and comparing the performance of the FETCH instrument with nearby sensors to assess its effectiveness in monitoring volcanic activity and seafloor inflation.

Project Overview
Objective: To evaluate the accuracy and reliability of the FETCH A-Z-A instrument in capturing pressure variations at Axial Seamount, with a focus on removing drift from the pressure measurements and comparing them to a nearby sensor.
Data: The dataset includes 2 years of pressure measurements from the FETCH A-Z-A instrument, with time series data in the format YYYY/MM/DD HH:MM:SS, followed by depth, pressure, and temperature values.
Notebooks

Taking aza calibration data, and performing correction equations with pressure data
aza.ipynb


Loading the raw pressure data.
Initial exploration and visualization of the time series.
Applying drift correction techniques to the pressure data.
Comparing the corrected pressure data from the FETCH instrument to a nearby sensor.
Assessing the performance and accuracy of the FETCH instrument in monitoring seafloor pressure and volcanic activity.
Visualizing the corrected data and comparing it to the raw measurements.
Corrections.ipynb



Calculating seafloor inflation values based on the corrected pressure data.

How to Use:
Clone the repository:

git clone https://github.com/YourUsername/AxialSeamountPressureAnalysis.git

Install required dependencies:

Ensure you have a Python environment set up (e.g., using venv or conda).
Install necessary Python packages:

pip install -r requirements.txt
Run the Jupyter notebooks:

Start Jupyter Notebook:

Open and run the notebooks in the order listed above.


Results and Conclusion
The results from the analysis will help determine the effectiveness of the FETCH A-Z-A instrument in monitoring volcanic activity at Axial Seamount and contribute to understanding the processes occurring at mid-ocean ridges.

Contact
For any questions or further discussion, please feel free to contact usmanchoudhary2882@gmail.com.
