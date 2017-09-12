#ground truth files created using generate_ground_truth_place_recognition.cpp in tunnel_localisation in opencv-general-codes by running two instances of the code, hence two separate files where only first column is meaningful and has correspondance between two files for ground truth matches

# final gt file is prepared using ground_truth_interpolation.ipynb in sequenceSLAM/src/ipy


# the *part* files and data
created using a part of original sequence, that is, 13000 to 25000 and 10000 to 20000 indices range from day and night raw data respectively.



.npz :

day/night-imgData.npz has sky blackened images for [:144,:] part of the images and day/night-imgData-2.npz is without sky blackening
