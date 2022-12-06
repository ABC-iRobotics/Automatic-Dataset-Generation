# Automatic-Dataset-Generation
Supplementary material for our proposal: "Increasing the Robustness of Deep Learning Models for Robotic Manipulation: Mixing Automatically Annotated Real and Synthetic Data"

Code for the real-data annotation pipeline can be found in the [real_image_labeling](real_image_labeling) submodule.

The scenes and code for generating the OE dataset (FTRG included) can be found in the [OE_Logo_BAT](OE_Logo_BAT) submodule. For generating the annotations the Blender Annotation Tool (BAT) from [blender_annotation_tool](blender_annotation_tool) can be used.

The [OE dataset](https://drive.google.com/drive/folders/1aRME9R4BX2yHghh7Y29VcDbV_CYCuSXb?usp=sharing) contains our rendered and real images for the OE logos and bolts as well as the FTRG dataset. It also contains our trained Mask-RCNN models. (We used the Mask-RCNN implementation provided [here](https://github.com/matterport/Mask_RCNN))

From [SynLORIS data, scenes and benchmark results](https://drive.google.com/drive/folders/16h6LfcJMMu1plYdFcDDNhrp2svE0jpgX?usp=sharing) the Blender scene for generating the SynLORIS dataset, the SynLORIS dataset itself and our benchmark results on the OpenLORIS-Object benchmark. (We used the OpenLoris-Object benchmark from [here](https://github.com/lifelong-robotic-vision/OpenLORIS-Object))