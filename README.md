## Example script for using kornia and pycolmap for 3D reconstruction

For the classical local feature pipeline - check [KeyNetAffNetHardNet pipeline](keynetaffnet-adalam-pycolmap-3dreconstruction.ipynb) and [DISK pipeline](DISK-adalam-pycolmap-3dreconstruction.ipynb)

For the LoFTR (a bit hacky) pipeline - check [LoFTR](loftr-pycolmap-3dreconstruction.ipynb)

### LoFTR 640px reconstruction

![LoFTR-reconstruction](assets/loftr_wooden_lady.png)


### DISK-2k reconstruction

![DISK-reconstruction](assets/disk_wooden_lady.png)


### KeyNetAffNetHardNet-2k reconstruction

![KeyNetAffNetHardNet-reconstruction](assets/keynet_affnet_wooden_lady.png)


### Apple Object Capture mesh


![Apple Object Capture](assets/aoc_wooden_lady.png)


The mesh, reconstructed by [Apple Object Capture](https://developer.apple.com/augmented-reality/object-capture/) app. Unfortunately, there is no way of exporting camera poses from ti

The repo is based on [kornia-adalam](https://kornia-tutorials.readthedocs.io/en/latest/image_matching_adalam.html) tutorial, with help of DISK [h5py-to-colmap](https://github.com/cvlab-epfl/disk/tree/master/colmap) scripts.



