# SalinityMLWorkshop_DMS_UCD<BR>
This repository contains Machine Learning scripts, data, and documents for the workshop.<BR><BR>

docs/Acronyms.pdf: List of acronyms used in the presentations and documents<BR>
docs/Agenda_AdditionalInfo.pdf: Workshop agenda, directions, and parking information<BR>
docs/JWRPMpaper_CalSim3ANN_enhance_2021.pdf: ASCE paper: "Enhanced Artificial Neural Networks for Salinity Estimation and Forecasting in the Sacramento-San Joaquin Delta of California"<BR>
doc/Module0_Welcome.pdf: Workshop slides: Welcome <BR>
docs/Module1_Overview.pdf: Workshop slides: workshop overview<BR>
docs/Module2_Dashboard.pdf: Worshop slides: ANN Dashboard<BR>
docs/Module3_ANNs.pdf: Workshop slides: ANN tutorial and demo<BR>
docs/Module4_PINNs.pdf: Workshop slides: Physics Informed Neural Networks<BR>
docs/PINN_Survey_Paper.pdf: Journal of Scientific Computing article: "Scientific Machine Learning Through Physics-Informed Neural Networks: Where we are and What's Next"<BR>
docs/PreWorkshopSetup_Colab.pdf: PDF document describing the process for setting up Google Colab to run the ANN notebooks. <BR>
docs/PreWorkshopSetup_Local.pdf: PDF document describing the process for setting up your laptop or desktop to run the ANN notebooks locally. <BR>
docs/water-14-02030-Multi_Location_Emulation.pdf: MDPI Water article: Multi-Location Emulation of a Process-Based Salinity Model Using Machine Learning <BR>
docs/water-14-03628-Novel_Salinity_Modeling_Deep_Learning.pdf: MDPI Water article: "Novel Salinity Modeling Using Deep Learning for the Sacramento-San Joaquin Delta of California"<BR>
docs/Workshop_Q-A_20230130.pdf: "Questions and Answers from Delta Flow-Salinity Modeling Using Machine Learning Workshop"<BR>
Colab_Train_ANN_on_Augmented_Dataset.ipynb: A jupyter notebook for use with Google Colab, which runs the ML code to train the ANN on augmented observed data using input files from this folder.<BR>
Colab_Train_ANN_on_Observed_Data-Chronological-Test_on_Augmented_Data.ipynb: A jupyter notebook for use with Google Colab, which runs the ML code to train the ANN on observed data using input files from this folder. <BR>
Colab_Transfer_Learning_from_Augmented_to_Observed_Chronological.ipynb: A jupyter notebook for use with Google Colab, which runs the ML code to transfer learning to observed data using input files from this folder. <BR>
Local_Train_ANN_on_Augmented_Dataset.ipynb: A jupyter notebook for use locally on a personal computer, which runs the ML code to train the ANN on augmented observed data using input files from this folder.<BR>
Local_Train_ANN_on_Observed_Data-Chronological-Test_on_Augmented_Data.ipynb: A jupyter notebook for use locally on a personal computer, which runs the ML code to train the ANN on observed data using input files from this folder. <BR>
Local_Transfer_Learning_from_Augmented_to_Observed_Chronological.ipynb: A jupyter notebook for use locally on a personal computer, which runs the ML code to transfer learning to observed data using input files from this folder. <BR>
Salinity_DWR.yml: A YAML file used when creating a conda environment to run the jupyter notebooks locally. <BR>
annutils.py: A python module containing ANN code which is used by all ANN scripts and notebooks.<BR>
dsm2_ann_inputs_base.xlsx: An Excel file containing historical ANN inputs. <BR>
dsm2_ann_inputs_dcc0.xlsx: An Excel file containing historical ANN inputs, with Delta Cross-Channel gates always closed. <BR>
dsm2_ann_inputs_dcc1.xlsx: An Excel file containing historical ANN inputs, with Delta Cross-Channel gates always open. <BR>
dsm2_ann_inputs_rsacminus15day.xlsx: An Excel file containing historical ANN inputs, with Sacramento River inflows shifted forward by 15 days.<BR>
dsm2_ann_inputs_rsacminus20pct.xlsx: An Excel file containing historical ANN inputs, with Sacramento River inflows scaled down by 20%.<BR>
dsm2_ann_inputs_rsacplus15day.xlsx: An Excel file containing historical ANN inputs, with Sacramento River inflows shifted backward by 15 days.<BR>
dsm2_ann_inputs_rsacplus20pct.xlsx: An Excel file containing historical ANN inputs, with Sacramento River inflows scaled up by 20%.<BR>
dsm2_ann_inputs_rsanminus15day.xlsx: An Excel file containing historical ANN inputs, with San Joaquin River inflows shifted forward by 15 days.<BR>
dsm2_ann_inputs_rsanminus20pct.xlsx: An Excel file containing historical ANN inputs, with San Joaquin River inflows scaled down by 20%.<BR>
dsm2_ann_inputs_rsanplus15day.xlsx: An Excel file containing historical ANN inputs, withSan Joaquin River inflows shifted backward by 15 days. <BR>
dsm2_ann_inputs_rsanplus20pct.xlsx: An Excel file containing historical ANN inputs, withSan Joaquin River inflows scaled up by 20%.<BR>
dsm2_ann_inputs_smscg0.xlsx: An Excel file containing historical ANN inputs, with the Suisun Marsh Salinity Control gates always closed. <BR>
dsm2_ann_inputs_smscg1.xlsx: An Excel file containing historical ANN inputs, with the Suisun Marsh Salinity Control gates always open.<BR>
observed_data_daily.xlsx: An Excel file containing observed data, used to train ANNs. Testing addition<BR>
