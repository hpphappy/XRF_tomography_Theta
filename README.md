# XRF_tomography_Theta
computing time test on Theta

Use python to run ```jXRFT_recon_test_gpu_updating.py```
The program will start calculating the P array if the it is not existed. A ```P_array``` folder will be created to save the P_array.
The reconstruction begins after the P array calculation is done. A folder ```sample8_size_64_recon``` will be created to store the reconstructed results.
To check the computing time spent on each epoch, please check the file ```per_epoch_time_mb_size_64.csv```. The unit of time is second.
