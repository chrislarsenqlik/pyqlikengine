# PyQlikEngine

PyQlikEngine is a python module used to communicate with the Qlik Sense Engine API. It works on Qlik Sense Enterprise, Qlik Sense Desktop, and/or Qlik Core.

## Setup
1. Clone the repository
2. Push into jupyter, cdsw, or other notebook environment
3. Open and run DR_Qlik_Demo.py.. 

## What is Happening

This is a fully [currently] working demo which uses a live Qlik Sense Enterprise environment, pulls data out into a dataframe, runs the data against a pre-built model in Datarobot using their python API. 

The data is from a rental prices data set, loaded into a Qlik Sense app.

The same rental price data has been loaded into Datarobot and a **price optimization** analysis/model has been implemented.

The visualizations are standard matplotlib visualizations

## What is Possible / Next Steps

The PyQlikEngine module has methods to edit a loadscript and do a reload and do a save operation, therefore it is completely possible to push results back into Qlik. This use case does not support that integration example however.
