# Advanced-Memristor-Modeling
A memristor library containing several commonly used existing standard models and several modified models. The proposed models are for simulations of memristor circuits in LTSpise in time domain. They could be adapted for operation in PSpice or other SPICE environments.
# Modeling of memristors in LTSpise environment
To test the proposed models and to make and analyze memristor circuits you must use LTSpice software. You can download and install it from the following link:
https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html#
# General Information
After downloading the .zip file, unzip it and keep the obtained folder. All the proposed models are in this folder.
# LTSpice code and creating library models
Open the unzipped folder and the model that you want to apply. Then right click on the file, select "Open with LTSpice". Then select by the mouse the abbreviation of the model in the opened file, for example A1, then right click and select "Create part". The created symbol appears with its three electrodes. The electrode Y could be connected to additional high-valued resistor (for example 1GOhm) and the next terminal of the resistor - to the ground. The others two terminals have to be connected to the respective nodes in the created circuit.
# Application in memristor circuits
# Description of the models
# Citation
When you use a given memristor model from the respective library, please cite the given sources in the end of the code.
