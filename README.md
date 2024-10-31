This project aims to investigate the effects of psychedelic substances, such as LSD, on the BOLD (blood-oxygen-level-dependent) signal observed in fMRI data. Psychedelics have shown promise in treating mental health conditions like treatment-resistant depression. However, the observed changes in BOLD activation induced by these substances remain difficult to interpret, as they may be caused by neuronal or hemodynamic changes. In this project, I aim to disentangle these effects by building and applying biophysical models, specifically spectral Dynamic Causal Modelling (DCM), to neuroimaging data.

The primary goals of this project are:
1.	Modelling: Develop and implement a linearized P-DCM model to simulate neuronal and hemodynamic contributions to the BOLD signal under the influence of psychedelics, with a focus on LSD.
2.	Parameter Fitting: Fit the parameters in the linearized used to describe the power-law decay of the endogenous fluctuations driving the neuronal states.
3.	Compute Predicted CSD using parameters from (Stephan et al., 2007) 
4.	Compute Empirical CSD.
5.	Comparison with Real Data: Compare the model’s predicted cross-spectral density (CSD) with real fMRI data to evaluate how well the model captures the psychedelic-induced alterations in brain activity using statistical measures such as MSE.
6.	Optimize the Parameters: Optimize the model’s parameters such as mean transit time (MTT) using gradient descent.
