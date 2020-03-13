# Laplacian-Re-Decomposition-for-Multimodal-Medical-Image-Fusion (IEEE TIM)

# Installation and operation

* Download and install the Matlab 2019b operating environment.
* Select the "Clone or download" button to download the code and data set.
* Select the LRD_fusion_method.m file to run.

# Schematic Display

    First: The schematic diagram of the Laplacian-Re-Decomposition(LRD).
![image](https://github.com/MDLW/Medical-Image-Fusion-Laplacian-Re-Decomposition-for-Multimodal-Medical-Image-Fusion/blob/master/Schematic_Diagram/Fig1.png)
  
    Second: Schematic diagram of medical image fusion algorithm based on LRD decomposition scheme.
![image](https://github.com/MDLW/Medical-Image-Fusion-Laplacian-Re-Decomposition-for-Multimodal-Medical-Image-Fusion/blob/master/Schematic_Diagram/Fig2.png)

# Abstract

The field of multimodal medical image fusion has made huge progress in the past decade. However, previous methods always suffer from color distortion, blurring and noise. To address these problems, we propose a novel Laplacian re-decomposition framework tailored to multimodal medical image fusion in this paper. The proposed Laplacian re-decomposition has two technical innovations. First, we present a Laplacian decision graph decomposition scheme with image enhancement to obtain complementary information, redundant information, and low-frequency sub-band images. Second, considering the heterogeneous characteristics of redundant and complementary information, we introduce the concept of overlapping domain and non-overlapping domain, where the overlapping domain contributes to fuse redundant information while the non-overlapping domain is responsible to fuse complementary information. Also, an inverse re-decomposition scheme is given by leveraging the global decision graph and local mean to reconstruct high-frequency sub-band fusion images. Finally, inverse Laplacian transform is applied to generate the fusion result. Experimental results demonstrate that the proposal outperforms other current popular fusion methods qualitatively and quantitatively. Index Terms-Multimodal medical image fusion, Laplacian re-decomposition, Overlapping domain, Non-overlapping domain.

# Reference
    @article{li2020laplacian,
        title={Laplacian Re-Decomposition for Multimodal Medical Image Fusion},
        author={Li, Xiaoxiao and Guo, Xiaopeng and Han, Pengfei and Wang, Xiang and Li, Huaguang and Luo, Tao},
        journal={IEEE Transactions on Instrumentation and Measurement},
        year={2020},
        publisher={IEEE}
    }


