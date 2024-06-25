## Enables depth input for Argus

Currently, depth pipeline has been configured and the scripts for `data_generation` have to be modified to use the ML-Agents Low Level API to send actions and retrieve data from the unity scene. For this, load the folder in Unity and then build the project `File->Build Settings->Build`. We can then use the output executable with `data_generation` script.