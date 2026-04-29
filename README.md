# MiDVMD

# Video Mirror Detection with the Motion-in-Depth Cue - AAAI-2026 (Oral)

[Alex Warren](https://alex-warren.co.uk), [Ke Xu](https://kkbless.github.io), [Xin Tian](https://scholar.google.com/citations?user=Ru6BvE4AAAAJ&hl=en), [Gary K.L. Tam](https://sites.google.com/site/csgarykl/home), [Benjamin W. Wah](https://benjaminwah.github.io), [Rynson W.H Lau](https://www.cs.cityu.edu.hk/~rynson/).

Swansea University, City University of Hong Kong, Huawei Technologies, Chinese University of Hong Kong

### Code and Weights Download & Paper Links
[[Code and Weights]](https://swanseauniversity-my.sharepoint.com/:u:/g/personal/851864_swansea_ac_uk/IQDqO3mkOL3tRJSPvdc8-DC_AfAgv6SOotfBcgh1sbFBhXs?e=OeRKIy) [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/download/38023/41985)
[[Swansea University Confra](https://cronfa.swan.ac.uk/Record/cronfa70923/Details)]

## Setup
To run inference using **Motion-in-Depth**, you will need to install both a **Depth Estimation** and a **Scene Flow Estimation** method. 
Follow the steps below to set up `raft3d` (SF) and `raft_stereo` (Depth Estimation)

### Project Structure
```
networks/
├── raft3d/
└── raft_stereo/
```
RAFT-3D
https://github.com/princeton-vl/RAFT-3D networks/raft3d

RAFT-Stereo
https://github.com/princeton-vl/RAFT-Stereo networks/raft_stereo

### Dependancies
pip install -r requirements.txt

### Notes
Inference can be found in train.py

### BibTeX
```bibtex
@article{Warren_Xu_Tian_Tam_Wah_Lau_2026, title={Video Mirror Detection with the Motion-in-Depth Cue}, volume={40}, url={https://ojs.aaai.org/index.php/AAAI/article/view/38023}, DOI={10.1609/aaai.v40i13.38023}, year={2026}, month={Mar.}, pages={10512-10520} }
```
