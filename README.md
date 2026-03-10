# Image-Teaching-feature
Patchification: Images (224x224) are split into 196 non-overlapping patches of 16x16 pixels.  Random Masking: The model masks 75% of the image patches (147 out of 196). Only the remaining visible patches are processed by the encoder, significantly reducing computation.  Reconstruction: The decoder takes the encoded visible patches 
