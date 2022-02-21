# Mortality-constraint

This repository is generated for the projected ‘Field-based tree mortality constraint reduces estimates of model-projected forest carbon sinks’. 

The files include: 1) Data of LOSS aggregated at 0.25 degree used to spatially estimate LOSS at continent scales by a machine learning approach. The raw inventory data are available upon reasonable request from the corresponding author. 

The codes of machine learning used to generate LOSS maps were adapted from https://github.com/KailiangYu/Biogeography-of-soil-microbes.git.

2) The final observational LOSS maps (mean and standard deviation, ‘ML_LOSS_mean_50degree_constrain.tif’ and ‘ML_LOSS_SD_50degree_constrain.tif’), the historical climate (‘Pre_his_con_05.tif’ and ‘Tem_his_con_05.tif’), and model products of projected NPP (‘NPP_Grid_SEIB_con_05_sum_final.tif’) and historical LOSS (‘SEIB_biomassloss_con_05.tif’) by model SEIB-DGVM  at 0.5 degree used in our ML constraint approach. 

Code of the machine learning approach is ‘sum_future_npp_constrain_biomassloss_climate_new.ipyn’. The code can be adapted to constrain the projected heterotrophic respiration. 

For more questions and comments, please contact Kailiang Yu kai86liang@gmail.com 
