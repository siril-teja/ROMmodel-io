# ROMmodel-io
Repository containing the Rigid-Flexible Body Dynamic MATLAB model of the spine, referenced in Dukkipati & Driscoll 2025 


[![Schematic of the RFBD Input-Output model. Click for video.](schematic.png)](ROMvideo.mp4)



## Model inputs:

1. Case-wise models (C0-5), and scripts to benchmark these models are made available in this repository.
2. To change model inputs, go to Modeling tab -> Design -> Model Workspace
2. All the parameters are listed in the model workspace.
3. Some parameters can not be changed as they are directly referenced in the simulink blocks inside the "Main_Cx" model. Please refer to the Appendix document for the description of these parameters.

## Model outputs

1. All possible model outputs are made available in the Model_Outputs subsystem
2. To view any output, simupy open the corresponding scope. You can also export the data outside MATLAB using "To Workspace" blocks

## More info

Contact the authors directly for an editable copy of the model.