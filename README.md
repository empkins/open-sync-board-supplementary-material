# Supplementary Material - OSB Quality Control Data

This Repository is part of the [Open Sync Board](https://github.com/empkins/open-sync-board) project.
In this repository, the measurement data recorded for quality control is provided. 
For this purpose, we recorded data to quantify possible inaccuracies caused by the OSB hard- and firmware and asses their impact on the synchronization performance. Three different sources of delays were identified: 
- Delay caused by the transmission of the synchronization trigger signal to the MD outputs (Trigger Delay)
- Delay caused by the transmission of the M-sequence signal to the MD outputs (M-Sequence Delay)
- Delay caused by external start source (Input Delay)

The repeated measurement data recorded with a digital oscilloscope for each of those cases is uploaded in the respective folders. 
Each of the ".csv" data files contains data from one measurement, with one column for the voltage on every output.
The *Input Delay* data is recorded with a sampling rate of 1 562 500 Hz, whereas the *Trigger Delay* and *M-Sequence Delay* data was acquired with a sampling rate of 781 250 Hz. Here, the *M-Sequence Delay* was downsampled to 78 125 Hz for storage space efficiency.
