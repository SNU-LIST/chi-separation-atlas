# *chi*-separation atlas (*χ*-separation atlas, *x*-separation atlas)

*χ*-separation atlas provides normative paramagntic susceptibility (*χ<sub>para</sub>*) and diamagnetic susceptibility (*χ<sub>dia</sub>*) maps from 106 healthy human brains.
### Features
- __*χ*-separation__ templates, accompanied with __*T*<sub>1</sub>-weighted__ and __hybrid__ templates
- ROI labels and atlas statistics
- NIfTI (`NIfTI/*.nii.gz`) and DICOM (`DICOM/*.zip`) formats available
- Registered to MNI space ([ICBM-2009c](https://nist.mni.mcgill.ca/icbm-152-nonlinear-atlases-2009/) asymmetric *T<sub>1</sub>*-weighted image template)

#### Note that *χ<sub>dia</sub>* is in absolute value.

### Contents

- Templates
  |File name|Description|Unit|
  |---|---|---|
  |`chi_para`|*χ<sub>para</sub>* map|ppb|
  |`chi_dia`|*χ<sub>dia</sub>* map|ppb|
  |`t1w`|*T<sub>1</sub>*-weighted image|a.u. (0–255)|
  |`hybrid`|Hybrid image|a.u. (0–255)|

- Labels [1]

  |File name|Description|Units|
  |---|---|---|
  |`labels`|5 subcortical nuclei and 14 white matter fiber bundles|N/A|
  |`label_names`|Indexes and names of `labels`|N/A|
  |`prior_WM`|Population average of white matter masks|a.u. (0–255)|
  |`prior`|Population average of brain masks|a.u. (0–255)|

- Atlas statistics

  |File name|Description|Unit|
  |---|---|---|
  |`chi_para_rSD`|Relative SD map of *χ<sub>para</sub>*|%|
  |`chi_dia_rSD`|Relative SD map of *χ<sub>dia</sub>*|%|
  |`chi_para_ROI_stats`|Mean and SD of *χ<sub>para</sub>* in ROIs|ppb|
  |`chi_dia_ROI_stats`|Mean and SD of *χ<sub>dia</sub>* in ROIs|ppb|

### Demographics
<table>
  <tr> <td></td> <td>Mean ± SD</td> <td>Quartiles</td> <td>Range</td> </tr>
  <tr> <td>Age</td> <td>60.8 ± 15.8</td> <td>46, 64, 75</td> <td>27–85</td></tr>
  <tr> <td>Sex</td><td align=center colspan="3">34 males and 72 females</td>  </tr>
</table>

#### License
We provide this software and its documentation for academic research purpose only and NOT for commercial or clinical use.

***
[1] Subcortical nuclei and white matter labels are adapted from [MuSus-100](https://doi.org/10.1007/s00429-022-02547-1) and [ICBM-DTI-81](https://doi.org/10.1016/j.neuroimage.2008.07.009)   
For more details, see (upcoming) [preprint](https://list.snu.ac.kr).   
v1.0.0 | Last update: 2023/09/15