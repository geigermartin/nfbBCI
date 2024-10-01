# **Neurofeedback**

## Folder Structure 
```
│projectdir          <- Project's main folder
│
├── examples         <- Example scripts
│   ├── brainflow    <- Brainflow is a library to obtain and analyse EEG data, often recommended for OpenBCI,
│   │                   but I didn't use it yet
│   ├── pylsl        <- Python interface to the LabStreamingLayer(LSL)
│
├── desktopShortcuts <- Since everyone has to log into the laptop with their own account, I summarized
│   │                   shortcuts for the commonly used software so you can simply drag these onto your 
│   │                   desktop to use them.
│
├── software         <- All the nfb-related software I installed on the laptop
│
├── src              <- Source code for this project
│   ├── arduino      <- Script 'nanoWifiMotor.ino' to setup the Arduino Nano as a server to communicate with 
│   │                   a Wifi hotspot on the laptop to use the wristband for haptic feedback
│   ├── conda        <- Conda environment 'nfb.yml' in which all the python scripts can be run
│   ├── python       <- Python scripts for timing tests, beta ERD simulation, simpleRT experiment,
│   │                   neurofeedback real-time processing, ...
│
├── README.md        <- Top-level README
```