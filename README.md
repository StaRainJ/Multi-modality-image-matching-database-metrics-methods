# Multi-modality-image-matching-database-metrics-methods 
![Error show](https://github.com/StaRainJ/Multi-modality-image-matching-database-metrics-methods/blob/master/Multimodal_Image_Matching_Datasets/OverviewImagePairs.png)
# This database comes from our survey paper, 'A review of multimodal image matching: Methods and applications' which is still under review.  
The provided database  contains 18 common types of data with ground truth annotation.

  From these collected raw image pairs, we manually label 15 to 20 matched landmarks (i.e., point locations) for each one, which could be used to evaluate the registration accuracy based on the distance of these matched landmarks. We also provide the affine transformation matrix for some image pairs (those intrinsically undergoing linear transformation) so that they can be well registered without any visible misalignment by using these given affine matrices. On the basis of the transformation matrix for each image pair, we can know which two points are matched in the fixed and moving images, and judge whether the matched points created by the feature descriptor are correct or not.
