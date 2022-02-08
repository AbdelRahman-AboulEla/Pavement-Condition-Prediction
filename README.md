# Pavement-Condition-Prediction

This is my final project in Infrastructure Asset Management (a master degree course).

### Description
- This project is about predicting the pavement condition through building a deterioration model.
- The data used in the model is the pavement of Montana.
- The data used to validate the model is the pavement of IOWA 
- By comparing the predicted pavement condition index (PCI) to the standard PCI rating scale, we can determine when the worst condition of the pavement will occur. 
- So, by knowing the duration when the condition of road reaches the dangers zoon, they can schedule when they can apply maintenance.
- Also, they can estimate the cost of the maintenance after determining the damage amount from the PCI Scale and preserve some budget for this event.

### Usage
- Import the excel number 1 in each of index model.
- The model will be saved in .h5 file.
- Using the .h5 file along with the other excel files in the future and validation model.
- An excel file will be exported from each model that contain the actual vs the predicted PCI.

### Used libraries 
keras, pandas and matplotlib, were used in this model.
