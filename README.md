# SAM3D-VPCC
The SAM3D-VPCC project utilizes [Meta's Segment Anything Model (SAM)](https://github.com/facebookresearch/segment-anything) to generate 2D projections of 3D point clouds, which can be used by [VPCC](https://github.com/MPEGGroup/mpeg-pcc-tmc2) during point cloud compression. 

In doing so, we can [hide visual artifacts](https://docs.google.com/presentation/d/1gIdTFOMO5lgHIY2Pe7HvBGoenh18Etk9ccfSdaaZrio/edit#slide=id.g2ce2202ea0e_0_292) created during compression by having them appear in more natural boundaries between segments in the point cloud.

# Getting Started
To run the example notebook, `sam3d`, you will need to  install `segment_anything` alongside its dependencies in your local environment, following the[ official installation instructions](https://github.com/facebookresearch/segment-anything?tab=readme-ov-file#installation) in SAM.

# Models for SAM
The models used by SAM can be downloaded from [the official SAM repository](https://github.com/facebookresearch/segment-anything?tab=readme-ov-file#model-checkpoints) and placed in the `models` directory.

# Point Cloud Data
The point cloud data used, `longdress`, is provided by [8i Labs at the JPEG Pleno Database](https://plenodb.jpeg.org/pc/8ilabs).
