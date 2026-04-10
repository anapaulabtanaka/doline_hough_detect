# doline_hough_detect
Detecting dolines alignments. This repository is associated with my PhD research, abstracts and EGU presentation. 

<br>
<img src="./cover/dolines.png" alt="dolines">

<br/>


## References
Tanaka, A. P. B., Trunz, C., Trottet, M., Racine, T., & Renard, P. (2025). Detecting fracture networks and karst features alignments similarities in the aquifer system of Tsanfleuron, Swiss Alps (No. EGU25-11154). Copernicus Meetings.

https://doi.org/10.5194/egusphere-egu25-11154

Tanaka, A. P. B., Trunz, C., Trottet, M., Racine, T., & Renard, P. (2025). Linking fracture and conduit orientations in the lapiaz of Tsanfleuron, Swiss Alps. 19th International Congress of Speleology.

<br/>

## Data description

### Files

In the "data" folder, you will find:

- The circular/elipsoidal geometries for doline analyses
  - Filename: `flooded_scalgo.shp`
  - Filename: `depression_scalgo.shp`
    Exported from Scalgo (https://scalgo.com/): rain=10mm, area=0m^2, volume=0m^3)

- Fracture lineaments azimuths
  - Filename: `frac_azimuths.csv`

- Conduit lineaments azimuths
  - Filename: `karst_azimuths.csv`
 
## Dependencies

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the following packages.

```bash
pip install numpy matplotlib pandas scipy geopandas shapely jupyter-notebook plotly cv2
```
                
## Examples

Jupyter notebook examples to characterize the networks, analyze, and export:

- Ex01_Dolines_alignment_karst_fracture.ipynb

