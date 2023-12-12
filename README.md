Two distinct modes of hemodynamic responses in the human brain
===============

[#Preprint](https://www.biorxiv.org/content/10.1101/2023.12.08.570806)

This dataset consists of 40 healthy, right-handed participants (see participants.tsv file) with the following data:

1. quantitative mri
    raw
    - multi-echo spin-echo T2 (MESE)
    - multi-echo, gradient-echo T2* (MEGRE, saved under derivatives)- 
    - dynamic suceptibility contrast (DSC, saved under derivatives)
    - pseudo-continuous arterial spin labelinng (asl)
    preprocessed, saved under derivatives/SUB/qmri
    - T2 (from MESE)
    - T2s (from MEGRE)
    - cbv (from dsc)
    - cbf (from asl)
    - R2 (1/T2)
    - R2s (1/T2s)
    - R2prime (R2s-R2)
    - oef (R2prime/x*cbv)
    - cmro2 (cbf* oef *CaO2)

2. qualitative bold-fmri
    raw
    - task-all_bold: 4 conditions for p019-p055, 2 conditions (CALC and CTRL) for p058-p068
    preprocessed (with fmriprep, derivatives/SUB/func)
    - _filtered_func.nii.gz

3. anat
    - T1w
    - FLAIR

