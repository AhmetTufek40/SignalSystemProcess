# SignalSystemProcess

# Homemade Electrical Stethoscope's Matlab code that shows orginal,filtered, fourier transformed graphs
   
   This project implements a homemade electrical stethoscope using MATLAB. The stethoscope connects to an Arduino to read voltage signals from a sensor, applies a customizable digital filter to the signal, and visualizes the original and filtered signals along with their FourFeaturesier transforms.

#Features
1)Real-time Signal Processing: Capture and process electrical signals in real-time.
2)Filtering Options: Apply various digital filters with customizable parameters.
3)Arduino Integration: Connects to an Arduino for voltage signal input.
4)Graphical Visualization: Visualize the original and filtered signals, as well as their Fourier transforms.
#Installation
1)Clone or download the repository.
#Usage:
1)Open the MATLAB app by running "SignalFilter.mlapp"
2)Connect your Arduino board and select the appropriate port in the UI.
3)Configure the filter settings such as type, order, and frequency parameters.
4)Click the "Start" switch to begin real-time signal processing.It will turn to green light .
#Configuration
1)Filter Settings: Adjust the filter type, order, and frequency parameters using the UI dropdowns and numeric fields.
2)Arduino Connection: Select the correct Arduino port from the dropdown menu.
#Filter settings section's photo

![Uygulama Ekran Görüntüsü](https://github.com/AhmetTufek40/SignalSystemProcess/blob/c02b29354280dd9c70aecb9ff71efb6e45e9ca7c/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-01-21%20202928.png)

##Known issues 
1)Matlab can work the code in quite time sometimes , so try to rewrite or change the values of filter order and the other values and start again.
