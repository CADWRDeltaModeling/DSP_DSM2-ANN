4years - trained on colab runs which go from October 1 to September 30 for 2008, 2010, 2012, and 2014
4years_cal - "calendar years" trained on DSM2 runs which go from January 1 to December 31 for 2008, 2010, 2012, and 2014
4years_cal_hiexplonf2 - 4years_cal periods but with higher exports and lower Northern Flow created with "\\cnrastore-bdo\Delta_mod\Share\dsp_salinity\scripts\generate_boundary_data\franken_ts.R"
4years_DCC - 4years periods with the added colab DCC augmented data
4years_hiexplonf - 4years_cal_hiexplonf2 but with water years instead of calendar years
4years_perturbhist - 4years_cal periods with randomly perturbed boundary data for DCC, Sac River, SJ River, and Exports using "\\cnrastore-bdo\Delta_mod\Share\dsp_salinity\scripts\generate_boundary_data\perturb_historical_ts.R" to generate data in "\\cnrastore-bdo\Delta_mod\Share\dsp_salinity\scripts\generate_boundary_data\data_out\perturbhist"
4years_SacLag - 4years periods with the added colab Lagged Sacramento river flows
4years_SacMag - 4years periods with the added colab altered Sacramento river flow magnitudes
6years - trained on colab runs which go from October 1 to September 30 for 2008, 2009, 2011, 2012, 2014, 2017
6yearsAugmented - 6years periods with the added colab Sacramento and San Joaquin lagged and scaled flows
colab - the colab results as described in the workshop
colab_simple - the colab results but using only the years described in "\\cnrastore-bdo\Delta_mod\Share\dsp_salinity\scripts\ann_test_train_years.xlsx"
colab_simple_wo2015 - colab_simple without the year 2015
colab_wo2015 - colab without 2015
lathypcub_7tide - latinhypercube as described in "latinhypercubetable.png" but with all tide boundaries shifted by 7 days
lathypcub_regtide - latinhypercube as described in "latinhypercubetable.png" but with all tide boundaries in their original historical condition
lathypcub_tideshift - latinhypercube as described in "latinhypercubetable.png" but with all tide boundaries shifted by 100 days
latinhypercube - latinhypercube as described in "latinhypercubetable.png"