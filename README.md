# *chi*-separation atlas (*χ*-separation atlas, *x*-separation atlas)

![chi_pn_100](https://github.com/SNU-LIST/chi-separation-atlas/assets/49898081/b08189cf-7ade-4b5c-8b28-d480389b420e)

The *χ*-separation atlas provides normative maps of paramagnetic susceptibility (*χ<sub>para</sub>*) and diamagnetic susceptibility (*χ<sub>dia</sub>*) derived from 106 healthy human brains. For more details, refer to [Min et al., NMR Biomed., 2024](https://doi.org/10.1002/nbm.5226).
### Features
- __*χ*-separation__ templates
  - Accompanied by __*T*<sub>1</sub>-weighted__ and __hybrid__ templates
- ROI labels
  - With associated *χ*-separation statistics
- MNI space registration
  - All templates are registered to the [MNI ICBM-2009c](https://nist.mni.mcgill.ca/icbm-152-nonlinear-atlases-2009/) asymmetric *T<sub>1</sub>*-weighted image template

> **Note:** The *χ<sub>dia</sub>* atlas is provided in absolute values.

### Contents

- Templates
  |File name|Description|Unit|
  |:---|:---|:---|
  |`chi_para`|*χ<sub>para</sub>* map|ppm|
  |`chi_dia`|*χ<sub>dia</sub>* map|ppm|
  |`chi`|QSM map|ppm|
  |`t1w`|*T<sub>1</sub>*-weighted image|a.u. (0–1)|
  |`hybrid`|Hybrid image|a.u. (0–1)|

- Labels

  |File name|Description|Unit|
  |:---|:---|:---|
  |`labels`|8 subcortical nuclei, 3 thalamic nuclei, and 13 white matter |N/A|
  |`label_names`|Indexes and names of `labels`|N/A|
  |`prior_WM`|Population average of white matter masks|a.u. (0–1)|
  |`prior`|Population average of brain masks|a.u. (0–1)|

- Atlas statistics

  |File name|Description|Unit|
  |:---|:---|:---|
  |`chi_para_rSD`|Relative SD map of *χ<sub>para</sub>*|N/A|
  |`chi_dia_rSD`|Relative SD map of *χ<sub>dia</sub>*|N/A|
  |`chi_para_ROI_stats`|Mean and SD of *χ<sub>para</sub>* in ROIs|ppb|
  |`chi_dia_ROI_stats`|Mean and SD of *χ<sub>dia</sub>* in ROIs|ppb|

### Demographics
<table>
  <tr> <td></td> <td>Mean ± SD</td> <td>Quartiles</td> <td>Range</td> </tr>
  <tr> <td>Age</td> <td>62.1 ± 15.8</td> <td>47.5, 65, 76.5</td> <td>27–85</td></tr>
  <tr> <td>Sex</td><td align=center colspan="3">37 males and 79 females</td>  </tr>
</table>

## License

This software and its documentation are provided **for academic research purposes only**. They are **not intended for commercial or clinical use**.

---

**Acknowledgments**

Subcortical nuclei, thalamic nuclei, and white matter labels are adapted from [MuSus-100](https://doi.org/10.1007/s00429-022-02547-1) and [ICBM-DTI-81](https://doi.org/10.1016/j.neuroimage.2008.07.009).

**Version:** v1.2.0  
**Last Updated:** 2024/10/31

---
