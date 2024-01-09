# Geophysics-Visualization
Web based visualization data of geophysics (gravity and magnetic)

This repository contains a Python script for visualizing geophysics data using Streamlit, Matplotlib, and other libraries. The script provides an interactive web application for visualizing magnetic and gravity data, performing various analyses such as interpolation, upward continuation, derivative calculation, cutoff wavelength filtering, and reduction to the pole (RTP).

# Getting Started
Prerequisites
Make sure you have Python installed on your machine. You can download it from python.org.

# Installation
Clone the repository:
git clone https://github.com/ByNicelava/Geophysics-Visualization.git
cd Geophysics-Visualization

Install the required packages:
pip install -r requirements.txt

# Usage
Run the script using the following command:
streamlit run app.py
This will launch a Streamlit web application, and you can interact with it through your web browser.

# Features
Data Input: Upload CSV or TXT files containing geophysics data (magnetic or gravity).
Interpolation: Perform kriging interpolation on the uploaded data.
Upward Continuation: Visualize the data after upward continuation.
Derivative Calculation: Calculate and visualize first, second, or third-order derivatives.
Cutoff Wavelength Filtering: Apply low-pass and high-pass filtering based on a specified wavelength.
Reduction to the Pole (RTP): Perform reduction to the pole on the data.

Visualization Output
The script generates visualization outputs in the form of images for each analysis, such as interpolated maps, upward continuation plots, derivative maps, low-pass, and high-pass maps, and RTP maps. These images are saved as PNG files.

Overlay on Map
You can generate interactive maps with the visualized data overlaid using Folium. The maps are saved as HTML files and can be found in the repository.
