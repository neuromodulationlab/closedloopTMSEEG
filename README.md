# Real-time phase detection for closed-loop EEG-TMS
Matlab Codes for resting-state EEG recording and 3 methods of real-time EEG phase estimation for closed-loop EEG-TMS: 
1) Autoregression-based prediction (AR),
2) FFT-based prediction (FFT), and
3) Educated Temporal Prediction (ETP).

The ETP method was orignially developed at the Alex Opitz lab, University of Minnesota.

Real-time EEG data acquisition is done using LSL (https://github.com/sccn/labstreaminglayer). 
Triggers to the TMS machine are delivered from the parallel port on the PC using InpOutx64 DLL (http://www.highrez.co.uk/downloads/inpout32/).
The code runs in MATLAB (MathWorks) 2014b+ and requires the FieldTrip toolbox (https://github.com/fieldtrip/fieldtrip).

For more information, refer to:
Shirinpour, Alekseichuk, Mantell, Opitz (2020). Experimental Evaluation of Methods for Real-Time EEG Phase-Specific Transcranial Magnetic Stimulation. Journal of Neural Engineering, doi: https://doi.org/10.1088/1741-2552/ab9dba
