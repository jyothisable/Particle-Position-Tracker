# Particle Position Tracker
From the given list of .csv files in input directory, this program will generate a .csv file containing the particle position at which it was removed. Particle ID is used as unique ID for comparison. Additionally we can filer particles by thier potition.

## Installation instructions
1. Install all dependencies (see below)
2. Clone this repository to your local machine or download the zip file from github
3. Place the .csv files in the input directory (file name should start with timestamp because files are read in accending order of timestamps also it should be of same format as the example .csv files in input directory)
4. Run app.ipynb file in the root directory and output should be generated in the output directory

## Dependencies
1. python v3.6 or above
2. pandas v1.3.5 or above
3. numpy v1.18 or above
4. natsort v7.0.0 or above
Once python is installed type this in terminal to install all other dependencies `pip install pandas numpy natsort`