# Floral_Circuit_Analysis

### Required R libraries
1. minipack.lm
2. shiny
3. ggplot2
4. DT

### How to use
Use `Rscript -e 'shiny::runApp(".")' ` to start the app and visit the webpage locally.

<img width="1776" height="884" alt="image" src="https://github.com/user-attachments/assets/9ee60cad-aef2-4406-8d2c-fca03b37266b" />

### Fit Summary with Sample data
Sample data is [sample_eis.csv](https://github.com/shinigami-777/Floral_Circuit_Analysis/blob/main/data/sample_eis.csv) and is generated using `make_sample_data.R` script.
```
Converged: TRUE
Iterations: 0
R^2:        0.99357
RMSE [Ohm]: 4266.3
tau_V [s]:  0.004272  (R_V * C_T)
tau_M [s]:  0.0001787  (R_E * C_M)
LM message: Post-vacuole band 1-D refine (RE, CM, RS, RCYT)
```
