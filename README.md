# ETD3D
>
> 📎 *This repository is directly related to the manuscript currently under submission to* **The Visual Computer**.  
> Please cite this paper if you use this code in your research.
##  Overview  
A pytorch implementation of "**Enhanced Text-Driven 3D Stylization: Local Consistency and Hierarchical Encoding**"

[![DOI](https://zenodo.org/badge/1078083958.svg)](https://doi.org/10.5281/zenodo.17379663)

This is a framework for **text-driven 3D mesh stylization**, which enhances **structure robustness**, **stylization fidelity**, and **semantic alignment** in text-guided 3D content generation.

<p align="center">
  <img src="images/framework.png" width="700">
</p>




### System Requirements  

- Python 3.9 
- CUDA 11
- Nvidia GPU with 8 GB ram at least
- the package of clip (https://github.com/openai/CLIP)
- the package of kaolin (https://github.com/NVIDIAGameWorks/kaolin)
  
##  Installation  
Install dependencies via:

```bash
pip install -r requirements.txt
```
## Run examples
>Call the below shell scripts to generate example styles.
```bash
# Cactus vase 
./demo/run_cactus_vase.sh
# Colorful Lamp
./demo/run_colorful_lamp.sh
...
```
>The outputs will be saved to results/demo, with the stylized .obj files, colored and uncolored render views, and screenshots during training.
>
## Result
<p align="center">
  <img src="images/result.png" height="700">
</p>

## 📚 Citation
If you find this work useful, please cite our related manuscript:
```bibtex
@article{LHE3D_2025,
  title     = {Enhanced Text-Driven 3D Stylization: Local Consistency and Hierarchical Encoding},
  author    = {Jiayi Bu, Huihuang Zhao, Yichun Wu, Jiajia Hu},
  year      = {2025},
  note      = {Manuscript submitted to The Visual Computer (under review)},
  url       = {[https://github.com/yourusername/LHE3D](https://github.com/Coraaaaal/Enhanced-Text-Driven-3D-Stylization)},
}
