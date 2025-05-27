# STEP-Mover: Stratified and Tiered Elimination Process for Efficient LiDAR Dynamic Removal

STEP-Mover is a dynamic object removal framework designed to efficiently filter dynamic points from LiDAR point cloud maps, preserving high-fidelity static structures for precise localization and navigation. The method employs a **coarse-to-fine-to-refine** strategy with voxel-based multi-scale descriptors and integrates static point retrieval to handle blind spots.

## 🎥 Video

<p align="center">
  <img src="web/resources/video.gif" alt="STEP-Mover Demo" width="800"/>
</p>

## 🚫 Open Source Disclaimer

Due to third-party agreements and proprietary dependencies, this project is **not open-sourced at this time**.  
We appreciate your interest and are actively exploring future possibilities for community sharing.

👉 For algorithm details, demos, or collaboration inquiries, please visit: [Our Website](https://yaepiii.github.io/STEP-Mover/)  
Or contact: **yaepiii@126.com**

## 🌟 Highlights

![Framework](web/resources/figure2.png)

- **Multi-scale Voxel Descriptors**: Combine height, occupancy, and statistical distributions to identify dynamic regions.
- **Coarse-to-Fine Filtering Strategy**: Eliminates ghost trails while enabling static point recovery.
- **Robust Across Sensors and Scenarios**: Evaluated on SemanticKITTI, HeLiMOS, and M2UD datasets.
- **CPU-friendly & Real-Time Ready**: Suitable for embedded deployment without GPU dependency.

## 📷 Visual Results

<img src="web/resources/table2.png" width="100%"/>
<img src="web/resources/figure7.png" width="100%"/>
<img src="web/resources/figure8.png" width="100%"/>
<img src="web/resources/table6.png" width="100%"/>

---

# Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
