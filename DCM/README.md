This folder describes a toy example of dynamic causal modeling processing using ERP EEG data  This code refers to the [workshop](https://github.com/AshleyTyrer/DCM_for_ERPs) which Ashley Tyrer held within the [Computational Psychiatry Course](https://www.translationalneuromodeling.org/cpcourse/) in 2023. Here, we've only learnt how to use DCM in the SPM GUI

Ashley's [work](https://academic.oup.com/braincomms/article/2/2/fcaa212/6029493) explored changes in the brain connectivity during visual recognition and implicit priming tasks between control and Parkinson's disease patients. Based on the source reconstruction, Ashley with colleagues created the model with four sources, which are used further in the DCM experiment. 
At the seminar, she explored how to conduct DCM and how to analyze the obtained data in the SPM, taking as an example the preprocessed EEG sample of one patient (mfaeffspmeeg_example_proc_data.dat and mfaeffspmeeg_example_proc_data.mat). 

After loading the data to the SPM DCM window, we specified the ERP NDMA model, defined a time window between 0 and 450 milliseconds, and wrote down between trial effects. Detrend, subsample, and mode options were left unchanged. We chose the IMG electromagnetic model and specified source priors. MNI_coords.mat contains all coordinates for these sources. Next, we defined connections, input, and the modulatory matrix.

![SPM DCM screen](./DCM%20SPM%20screen.jpg)

The example of result is that the strenght of the reccurent connection of the right right occipital pole is decreased between effects. 

![Result](./Result.jpg)
