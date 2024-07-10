## Adaptive Sliding Mode Control of a Fuel Cell System
PEMFC system control has to consider problems related to harvesting electrical energy from the PEMFC stack. Fuel cells have a nonlinear voltage–current characteristic, and the power has several local maximum power points in the I–P characteristic under various operating conditions. Therefore, an MPPT algorithm must be established to improve and optimize the PEMFC system efficiency.       

Through this project, we managed to model and draw the characteristic curve of the fuel cell. Moreover, a sliding mode controller for the PEMFC system has been designed, successfully extracting the maximum power of the fuel cell.        
### Operation
To see the characteristic curves of the fuel cell, run the 'fuel_cell_characteristic.slx' file to save the data values, then run the 'characteristic_plot.m' to plot the graph.        
The design and simulation of obtaining the fuel cell's maximum power are shown in 'smc_controller.slx' file.     
