# resolution4ST-paired-HE

## Spot size used for micron/pixel estimation
Q: Why using 65um to estimate instead of 55um?

10x team: You are correct that on average the actual spot size is 55 microns. However, in the software the spot diameter is hard coded as 65 microns. In short you should rely on the 65 micron spot size. 


## Resolutation, micron/pixel (mpp), for 10x ST paired H&E and IF images
|Human cancer type  |File ID     | H&E (mpp)    | H&E-estimated (mpp)|  IF (mpp)| Tissue source|
|:-----------------:|:-----------:|:------------:|:------------:|:------------:|:------------:|
|Breast             |Xenium_V1_FFPE_Human_Breast_IDC_Big_1_he_image.ome.tif|0.2125| NA |0.2125|
|Breast             |Xenium_V1_FFPE_Human_Breast_IDC_Big_2_he_image.ome.tif|0.2125| NA |0.2125|
|Breast             |Xenium_V1_FFPE_Human_Breast_IDC_With_Addon_he_image.ome.tif|0.2125| NA |0.2125|
|Breast             |Xenium_V1_FFPE_Human_Breast_ILC_With_Addon_he_image.ome.tif|0.2125| NA |0.2125|
|Breast             |Xenium_V1_FFPE_Human_Breast_IDC_he_image.ome.tif|0.2125| NA |0.2125|
|Breast             |Xenium_V1_FFPE_Human_Breast_ILC_he_image.ome.tif|0.2125| NA |0.2125|
|Breast             |Xenium_V1_FFPE_Human_Breast_IDC_With_Addon_he_image.ome.tif|0.2125 | NA|0.2125|
|Breast NC          |Xenium_FFPE_Human_Breast_Cancer_Rep1_he_image.ome.tif|0.3638|NA|NA|
|Breast NC          |Xenium_FFPE_Human_Breast_Cancer_Rep1_if_image.tif | NA | NA|0.2125|
|Breast NC          |Xenium_FFPE_Human_Breast_Cancer_Rep2_he_image.ome.tif|0.3638|NA|NA|
|Breast NC          |morphology.ome.tif (Rep2) | NA | NA | 0.2125|
|Breast NC          |Xenium_V1_FFPE_Preview_Human_Breast_Cancer_Sample_2_he_image.ome.tif|0.2740|NA|NA|
|Breast NC          |morphology.ome (sample2) |NA|NA | 0.2125|
|Breast NC          |CytAssist_FFPE_Human_Breast_Cancer_tissue_image.tif| 0.5476| TBD | NA|
|Cervical           |Visium_FFPE_Human_Cervical_Cancer_image.jpg | NA | 0.6925 | NA|
|Colorectal         |CytAssist_11mm_FFPE_Human_Colorectal_Cancer_tissue_image.tif | 0.2510 | 0.2510 | NA |
|Colorectal         |Visium_HD_Human_Colon_Cancer_tissue_image.btf | 0.2738 | TBD |NA|
|Intestine          |Visium_FFPE_Human_Intestinal_Cancer_image.jpg | NA | 0.6928| NA|
|Kidney             |CytAssist_11mm_FFPE_Human_Kidney_tissue_image.tif |0.2738 | 0.2966 | NA |
|Lung(5k-3.0)       |Xenium_Prime_Human_Lung_Cancer_FFPE_he_image.ome.tif |0.2738 | NA | NA| 
|Lung(5k-3.0)       |morphology.ome.tif |NA|NA|0.2125|
|Lung(v1-2.0)       |Xenium_V1_humanLung_Cancer_FFPE_he_image.ome.tif | 0.2738 | NA | NA| BioIVT|
|Lung(v1-2.0)       |morphology.ome | NA| NA | 0.2125| BioIVT|
|Lung(v1-1.3)       |Xenium Human Lung Preview Data no HnE-cancer| NA| NA|NA|Avaden Biosciences|
|Lung(v1-1.3)       |morphology.ome.tif-cancer| NA| NA|0.2125|Avaden Biosciences|
|Lung(v1-1.3)       |Xenium Human Lung Preview Data no HnE-lung| NA| NA|NA|Avaden Biosciences|
|Lung(v1-1.3)       |morphology.ome.tif-lung| NA| NA|0.2125|Avaden Biosciences|
|Lung               |CytAssist_FFPE_Human_Lung_Squamous_Cell_Carcinoma_tissue_image.tif | 0.2740 | 0.2538 | NA|
|Lung               |CytAssist_11mm_FFPE_Human_Lung_Cancer_tissue_image.tif | 0.2738 | 0.2965 | NA|
|Ovarian            |Visium_FFPE_Human_Ovarian_Cancer_image.jpg | NA | 0.6926 | NA |
|Overian            |CytAssist_11mm_FFPE_Human_Ovarian_Carcinoma_tissue_image.tif | 0.2740 | 0.2967 | NA|
|Prostate           |Visium_FFPE_Human_Prostate_Acinar_Cell_Carcinoma_image.tif | TBD | 0.3445 | NA|
|Lymph node         |Xenium5K_Prime_Human_Lymph_Node_Reactive_FFPE_he_image.ome.tif | 0.2738 | NA | NA|
|Lymph node         |Xenium5K_morphology.ome.tif | NA | NA | 0.2125|
