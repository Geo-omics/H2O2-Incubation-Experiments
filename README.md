# H2O2-Incubation-Experiments
R code and input tables that were used to analyze data from H2O2 incubation experiments with western Lake Erie water.

These files include analysis code for data included in a paper in review at L&O (as of 24-Aug-24).

More reader friendly data is available in a BCO-DMO repository at https://demo.bco-dmo.org/project/700767

File description:
H2O2_incubation_experiment.RMD = RMarkdown file that has data analysis code with annotations on what the code is for. There is also a description of each input table inside.

Input tables:
Path_Compare_Table.txt = A table that lists whether photochemical H2O2 production rates and measured net H2O2 production are significantly different. The photochemical production rate was calculated from the CDOM concentration and the bottle pathlength. Several estimates were made with increasing bottle pathlength (to account for uncertain angle of the light path).

Photo_vs_Net.txxt = data used to make a barplot comparing estimated photochemical production rates and the measured net H2O2 production rates in 2019 experiments.

Poor_fit_curves_df.txt = data showing how H2O2 concentrations changed over time in experiments where solver could not calculate PH2O2-unlabeled and Kloss,H2O2.

Prod_Decay_Data.txt = All H2O2 production and decay rate data from outdoor incubations

Prod_Decay_Environ_Data.txt = Environmental data from water used for outdoor incubations

Filtered0.22um_light_dark_prod.txt = Light and dark production of H2O2 in 0.22 um filtered water

Chl_t_test_df.txt = Chlorophyll data from experiments that included whole water and 105 um filtered bottles.

Resp_t_test_df.txt = Respiration rate data from experiments that included whole water and 105 um filtered bottles.

LE_H2O2.shared = OTU abundance data

LE_H202.metadata.txt = Metadata on DNA samples used to find OTU abundances

LE_H2O2.taxonomy = OTU taxonomy data

Outdoor_Indoor_Exp_Compare.txt = dataframe used to compare production and decay rates obtained from experiments with unlabeled and labeled H2O2 spikes

Isotope_Replicate_Data.txt = PH2O2 and Kloss data from every replication bottle in the indoor experiments with 18O2-labeled H2O2 spikes
