=======================================================
An experimental dataset which is presented at 
J. Park et al. High Quality Depth Map Upsampling for 3D-TOF Cameras, ICCV 2011

contact: jspark@rcv.kaist.ac.kr or syncle@gmail.com
=======================================================

Description: 

This dataset is based on Middlebury disparity map.
D. Scharstein and R. Szeliski. A taxonomy and evaluation of dense two-frame stereo correspondence algorithms. IJCV, 47(1/2/3):7?42, 2002.

The ground truth disparity map is downsampled by using MATLAB command 'imresize'

each folder contains the upsampling results from 
bilinear		: Bilinear interpolation
diebel		: J. Diebel and S. Thrun. An application of markov random fields to range sensing. In NIPS, 2005.
kaiming he 	: K. He, J. Sun, and X. Tang. Guided image filtering. In ECCV, 2010.
yang		: Q. Yang, R. Yang, J. Davis, and D. Nist¢¥er. Spatial-depth super resolution for range images. In CVPR, 2007.
ours		: our result for ICCV 2011 paper
Ground truth	: hole filled disparity map





