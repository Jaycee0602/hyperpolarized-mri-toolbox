# Sample In Vivo Hyperpolarized MRI Data

The in vivo hyperpolarized MRI data contained in the folders here comes from animal and human studies, and was acquired with different methods that are described below.

## Rat Kidneys Dynamic MRS

This dataset contains slab-selective dynamic MR spectroscopy, acquired in normal rat kidneys.  There are repeated injections ("shots") for each animal (originally to look for stability or changes in metabolism across injections).

Further details and analysis can be found in:
Hu, Simon, Peder E Z Larson, Mark Vancriekinge, Andrew M Leach, Ilwoo Park, Christine Leon, Jenny Zhou, et al. “Rapid Sequential Injections of Hyperpolarized [1-¹³C]Pyruvate in Vivo Using a Sub-Kelvin, Multi-Sample DNP Polarizer.” Magn Reson Imaging 31, no. 4 (May 2013): 490–96. https://doi.org/10.1016/j.mri.2012.09.002.  https://www.ncbi.nlm.nih.gov/pubmed/23107275

## Rat Kidneys EPI

This dataset contains pyruvate and lactate dynamic imaging using metabolite-specific imaging with EPI in normal rat kidneys.  Experiment 1 used a variable flip angle scheme (`exp1_vfa`) while experiment 2 used a constant-in-time flip angle scheme (`exp2_const`).  The `.mat` files contain the flip angles used at each time point.

The metabolite-specific imaging with EPI is described in:
Gordon, Jeremy W, Daniel B Vigneron, and Peder E Z Larson. “Development of a Symmetric Echo Planar Imaging Framework for Clinical Translation of Rapid Dynamic Hyperpolarized (13) C Imaging.” Magn Reson Med, February 2016. https://doi.org/10.1002/mrm.26123. https://www.ncbi.nlm.nih.gov/pubmed/26898849

## TRAMP Mouse Multi-slice EPI

This dataset contains pyruvate and lactate dynamic imaging using metabolite-specific imaging with EPI in a transgenic adenocarcinoma of mouse prostate (TRAMP) mouse model of prostate cancer.  The `.mat` file contains the flip angles used at each time point.

The metabolite-specific imaging with EPI is described in:
Gordon, Jeremy W, Daniel B Vigneron, and Peder E Z Larson. “Development of a Symmetric Echo Planar Imaging Framework for Clinical Translation of Rapid Dynamic Hyperpolarized (13) C Imaging.” Magn Reson Med, February 2016. https://doi.org/10.1002/mrm.26123. https://www.ncbi.nlm.nih.gov/pubmed/26898849

## Non-human Primate Brain Dynamic MRS

This dataset contains dynamic slab MR spectroscopy (`primate_brain_slab_dynamic.mat`) and dynamic MR spectroscopic imaging/chemical shift imaging (`primate_brain_csi_variableflip_dynamic.mat`), the latter using a variable flip angle strategy.  The files contain metabolite amplitudes, extracted from the spectra, as well as the excitation flip angles for each TR.

Further details and analysis can be found in:
Park, Ilwoo, Peder E Z Larson, James L Tropp, Lucas Carvajal, Galen Reed, Robert Bok, Fraser Robb, et al. “Dynamic Hyperpolarized Carbon-13 MR Metabolic Imaging of Nonhuman Primate Brain.” Magn Reson Med 71, no. 1 (January 2014): 19–25. https://doi.org/10.1002/mrm.25003. https://www.ncbi.nlm.nih.gov/pubmed/24346964

## Human Prostate Dynamic MRSI

This dataset contains dynamic MR spectroscopic imaging in 3 human subjects with prostate cancer.  The `spectra` are the full spectral and spatial data, while the `extracted_data` are the peak heights of pyruvate and lactate, extracted from the spectra.  The files also contain excitation flip angles for each TR.

Further details and analysis can be found in:
Nelson, Sarah J, John Kurhanewicz, Daniel B Vigneron, Peder E Z Larson, Andrea L Harzstark, Marcus Ferrone, Mark van Criekinge, et al. “Metabolic Imaging of Patients with Prostate Cancer Using Hyperpolarized [1-13C]Pyruvate.” Sci Transl Med 5, no. 198 (August 2013): 198ra108. https://doi.org/10.1126/scitranslmed.3006070. https://www.ncbi.nlm.nih.gov/pubmed/23946197
