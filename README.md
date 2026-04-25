# Geometric-Topological Perception and Motion Prior for Real-Time Satellite Video Object Tracking

Codes comming soon!

## Abstract

Satellite video object tracking (SVOT) remains fundamentally challenging due to texture scarcity, arbitrary rotation, aspect ratio changes, and severe occlusions. While recent state-of-the-art trackers excel in general scenarios, their reliance on rich appearance details or rigid spatial matching mechanisms leads to significant performance degradation in the satellite domain. To bridge this gap, we propose SiamGM, a real-time spatial-temporal unified tracking framework tailored for satellite videos. Instead of conventionally stacking modules, we synergize geometric-topological perception with temporal-kinematic prior, addressing the core limitations of SVOT. Spatially, we closely couple a Topological Attention Module (TAM) with a Geometry-Constrained Label Assignment (GCLA) method during the training phase. This joint paradigm establishes fine-grained structural correspondences and explicitly suppresses surrounding background noise. Temporally, rather than passively relying on visual cues, we propose an Online Motion Model Refinement (OMMR) strategy during the tracking phase. By adopting the Normalized Peak-to-Sidelobe Ratio (nPSR) as a dynamic confidence indicator, we adaptively leverage historical motion information for robust track recovery. Evaluations on two challenging SatSOT and SV248S benchmarks confirm that SiamGM outperforms not only recent Siamese-based satellite trackers but also state-of-the-art Transformer trackers in both precision and success metrics. Notably, this highly unified architecture introduces only minor computational overhead, enabling real-time tracking at 130 frames per second (FPS). Codes and tracking results are available at [https://github.com/wenzx18/SiamGM](https://github.com/wenzx18/SiamGM).

![Overview of the proposed SiamGM](demo/overview.jpg)

## Results

Results can be downloaded from: [Google Drive](https://drive.google.com/drive/folders/1wA-kQ_2gJe4dtK84B_VLtATMBdB7k74U?usp=drive_link)
