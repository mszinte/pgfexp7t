# pMFexp
By :      Martin SZINTE<br/>
Projet :  pGFexp7T<br/>
With :    Matthias NAU, Jan Patrick STELLMANN & Tomas KNAPEN
Version:  1.0<br/>

## Version description
Determine gain field maps using an equivalent to pRF scanning design but with gaze changes over a large visual portion of the visual field in total darkness.<br/>

### Tasks:

1. Calib: Calibration with 9 extreme eye directions, fixating 13 sec each<br/>
   order: center, up, down, left, right, left-up, right-up, left-down, right-down<br/>

2. GazeLines: 97 eye directions (5 by 5 grid in lines zigzag), 2TR each<br/>

3. GazeColumns: 97 eye directions (5 by 5 grid in columns zigzag), 2TR each <br/>

### Run sequence
- Run  1 : task-Calib_run-01: 90TRs - 1 min 57 sec
- Run  2 : task-GazeLines_run-01 : 194TRs - 4 min 12.2 sec
- Run  3 : task-GazeColumns_run-01 : 194TRs - 4 min 12.2 sec
- Run  4 : task-GazeLines_run-02 : 194TRs - 4 min 12.2 sec
- Run  5 : task-GazeColumns_run-02 : 194TRs - 4 min 12.2 sec
- Run  6 : task-GazeLines_run-03 : 194TRs - 4 min 12.2 sec
- Run  7 : task-GazeColumns_run-03 : 194TRs - 4 min 12.2 sec
- Run  8 : task-GazeLines_run-04 : 194TRs - 4 min 12.2 sec
- Run  9 : task-GazeColumns_run-04 : 194TRs - 4 min 12.2 sec
- Run 10 : task-GazeLines_run-05 : 194TRs - 4 min 12.2 sec
- Run 11 : task-GazeColumns_run-05 : 194TRs - 4 min 12.2 sec

## Acquisition sequences

3D-EPI<br/>
1.3 sec TR (aquisition time)<br/>

## Experiment runner
* run the experiment using main/expLauncher.m


