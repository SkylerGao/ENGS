# ENGS (CVPR2026 Oral)
Official implementation of Energy-GS: Image Energy-guided Pose Alignment Gaussian Splatting with Redesigned Pose Gradient Flow

**Paper Link:** [Here](https://pan.baidu.com/s/1mfpRFNH5F0VT7e5ue6ArHg?pwd=cvpr)

## Abstract

High-quality 3D scene representation in radiance fields relies on accurate camera poses which are often difficult to acquire in real-world scenarios. An effective solution is to use RGB images for the joint optimization of radiance fields and camera poses, an approach that has been well explored in NeRF series methods. However, unlike NeRF, joint optimization in 3D Gaussian Splatting (3DGS) often requires additional regularization or prior spatial knowledge to reach comparable performance. To eliminate these dependencies, we introduce Energy-GS, a pose-aware Gaussian splatting framework that jointly optimizes scene representation and camera poses using only RGB images. We observe that pose gradients in joint optimization are unstable due to the point-based rendering mechanism. Furthermore, unlike NeRF’s spatial sampling framework that enables coarse-to-fine pose alignment, rasterization-based 3DGS lacks controllable sampling and thus cannot support progressive pose refinement. To address these challenges, we redesign the optimization strategy of Gaussian primitives and introduce an image-energy-guided constraint that encourages progressive alignment of camera poses. Experiments on both synthetic and real-world datasets show that Energy-GS can effectively optimize the scene reconstruction and resolve camera pose misalignment at the same time. Benefiting from reliance on only RGB images, we believe this work provides promising insights for visual localization and dense mapping applications such as SLAM.

## Coming Soon !


**The code will be publicly released after the CVPR 2026 conference concludes. Thank you for your attention!**
