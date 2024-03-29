# OralEpitheliumDB

The OralEpitheliumDB immage set is composed of 456 microscopic images of Oral Epithelial Dysplasia (OED) collected from 30 mice tongues. It is divided in 114 healthy tissue and 342 OED samples (40x magnification, 450x250 pixels, 3-channel RGB, 8-bit color depth, TIFF format). This dataset was built in collaboration with the School of Dentistry and the Department of Histology and Morphology from Federal University of Uberlândia, Brazil.

The database images were classified in the groups of healthy tissues, mild, moderate and severe OED by a pathologist. Each class contains 114 tissue images.
The cell nuclei were manually marked by a specialist and the resulting labels were evaluated and validated by the pathologist, defining gold-standard annotations.
The dataset images were normalized with the combination of four stain normalization methods and three reference images, totalling 12 normalized sets. The normalized images were stored in the JPG format. A total of 5,472 color normalized images were generated from this operation.

**OralEpitheliumDB** is structured as follows:
| Image | Channels | Color depth | File Format | Total of images |
| --- | --- | --- | --- | --- |
| Original images | 3 | 8-bit | TIFF | 456 |
| Gold standard masks | 3 | 8-bit | PNG | 456 |
| Normalized images | 3 | 8-bit | JPG | 5472 |

### Dataset Access
The dataset can be downloaded [here](https://ufubr-my.sharepoint.com/:f:/g/personal/adriano_barbosa_ufu_br/Erdu9z-S9txJjG5AAcuOgL4BrKAjqRYPCyDWmAqohIpqCg?e=1scP08)
