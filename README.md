# K_means
Consider the problem of classification of Shouted and Normal Speech. A common approach is to extract the MFCC features from the speech signal. These features are extracted from overlapping frames of tagged speech intervals. The two MFCC feature data files MFCC_N_2500.npy and MFCC_S_2500.npy respectively store 2500 MFCC features of normal and shouted speech. 
1. Load the two datasets MFCC_N_2500.npy and MFCC_S_2500.npy into arrays N and S respectively using np.load( filename ). 
2. Append these two arrays to form the Dataset D=[N,S] 
3. Subject D to K-Means clustering with K = 100 
4. Let P S [j] and P N [j] (P S [j] + P N [j]=1) be the respective proportions of shouted and normal feature points in each cluster j (j=1,...K). Report the plots of P S [j] and P N [j] against j=1,...K in two different colors (say, Red and Blue). NOTE: This is an example usage of Training Data Distribution Analysis using Unsupervised Methods.
