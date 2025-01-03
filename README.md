Signal Processing 
Assignment 2 
1. Generate two random signals with low frequency content (less than 1rad/sec) and call 
them 𝑥1 and 𝑥2 in Python by using numpy library. Plot them. (Take your time array from 
−50 𝑡𝑜 50 with 0.01 increments). 
2. Modulate 𝑥1 with cos (10𝑡) and 𝑥2 with cos (20𝑡). Plot the modulated signals 
(𝑥1𝑚 and 𝑥2𝑚). 
3. Add two modulated signals and store it as 𝑥. Plot 𝑥. 
4. Now Bandpass filter 𝑥 to extract 𝑥1𝑚. Store it as 𝑥1𝑚−𝑒𝑥𝑡𝑟𝑎𝑐𝑡𝑒𝑑. Then repeat to get 
�
�2𝑚_𝑒𝑥𝑡𝑟𝑎𝑐𝑡𝑒𝑑. (Note: for convolution you can use np.convolve(x, y) from numpy library) 
5. Now to reconstruct the original signals 𝑥1 and 𝑥2, multiply 𝑥1𝑚_𝑒𝑥𝑡𝑟𝑎𝑐𝑡𝑒𝑑 with cos (10𝑡) 
and low-pass filter to get 𝑥1_𝑟𝑒𝑐𝑜𝑛𝑠𝑡𝑟𝑢𝑐𝑡𝑒𝑑. Then repeat steps to get 𝑥2_𝑟𝑒𝑐𝑜𝑛𝑠𝑡𝑟𝑢𝑐𝑡𝑒𝑑.  
6. Plot on one same figure 𝑥1 and 𝑥1_𝑟𝑒𝑐𝑜𝑛𝑠𝑡𝑟𝑢𝑐𝑡𝑒𝑑. Then plot on one same figure 𝑥2 and 
�
�2_𝑟𝑒𝑐𝑜𝑛𝑠𝑡𝑟𝑢𝑐𝑡𝑒𝑑.  
Include all the plots with their name, original functions 𝒙𝟏 and 𝒙𝟐, and your full 
Python code in the submission.
