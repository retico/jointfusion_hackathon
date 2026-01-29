# jointfusion_hackathon
Joint fusion DL model to predict ASD from structural and functional connectome brain features extracted form the ABIDE MRI and fMRI datasets.

The DL algorithm developed for the analysis of the ABIDE data (structural and fMRI) published in the paper by Saponaro, S., Lizzi, F., Serra, G., Mainas, F., Oliva, P., Giuliano, A., Calderoni, S., & Retico, A. (2024). Deep learning based joint fusion approach to exploit anatomical and functional brain information in autism spectrum disorders. Brain Informatics, 11(1), 2. https://doi.org/10.1186/s40708-023-00217-4 has been revised to make it available as an exercise for the students of 1st AI-INFN Advanced Hackathon (Nev. 26-28 2024, Padova, Italy) https://fondazione-fair.it/evento/1st-ai-infn-advanced-hackathon/ 

First, have a look at the Ex_sMRI_fMRI_sep.ipynb where the classification problem (ASD vs. controls) to be addressed is explained, and then follow the instructions that are provided for analyzing the MRI and fMRI datasets separately. Once you have completed the first exercise (Ex_sMRI_fMRI_sep.ipynb), check its solution (sMRI_fMRI_sep.ipynb). 
Then, you can move to face the exercise on the joint fusion DL model (Ex_Joint_Fusion.ipynb), whose solution is also provided (Joint_Fusion.ipynb).
A notebook that implements the explainability module based on SHAP, implemented in the paper referenced above is also provided (nestedCV__JointDNN+SHAP_connectoma.ipynb),

The preprocessed and harmonized dataset of brain features analized in that paper are not publicly shared. They are provided to student during teaching events (e.g. the AI hackathons mentioned above). They consists of brain features computed on MRI data made available by the Autism Brain Imaging Data Exchange (ABIDE 1 and ABIDE 2) projects. Brain features are extracted from the T1-weighted structural MRI (sMRI) with the Freesurfer software suite and from the resting-state functional MRI (rs-fMRI or fMRI) with the CPAC processing pipeline. Check the paper for more details.

# Citation
If you find this method and code or useful for your research, please cite our paper:
Saponaro, S., Lizzi, F., Serra, G., Mainas, F., Oliva, P., Giuliano, A., Calderoni, S., & Retico, A. (2024). Deep learning based joint fusion approach to exploit anatomical and functional brain information in autism spectrum disorders. Brain Informatics, 11(1), 2. https://doi.org/10.1186/s40708-023-00217-4

```bibtex
@article{Saponaro2024,
  author = {Saponaro, Sara and Lizzi, Francesca and Serra, Giacomo and Mainas, Francesca and Oliva, Piernicola and Giuliano, Alessia and Calderoni, Sara and Retico, Alessandra},
  title = {{Deep learning based joint fusion approach to exploit anatomical and functional brain information in autism spectrum disorders}},
  journal = {Brain Informatics},
  year = {2024}
  volume = {11},
  number = {1},
  pages = {2},
  doi = {10.1186/s40708-023-00217-4},
  url = {[https://doi.org/10.21203/rs.3.rs-3372317/v1] (https://braininformatics.springeropen.com/articles/10.1186/s40708-023-00217-4)},
  publisher = {Springer Berlin Heidelberg},
}
```

This paper received the annual Best Paper Award of Brain Informatics Springer journal.
