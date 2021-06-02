# CS229_project

This repository shows the codes necessary to implement three regression models over the NGA West database to predict the difference in angular directionality between two given sites.

main.py runs all three regression models and generates the plots presented in the report.

Input files

- azimuth_diffs.csv: File containing updated seismic data base
- filter_data.csv: Seismic database preliminaly filteres
- filter_data_indices.csv: Indices characterizing data.

Input codes

generate_x_y.py: Auxiliary code to read csv inouts
geometry.py

Models code

benchmark_model.py: Regression that uses distance in a linear function
Neural_network_model.py: Regression with all features in a neural network.
Ridge_model.py: Ridge regression over selected variables


