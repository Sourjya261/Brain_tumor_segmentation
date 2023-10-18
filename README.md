# Brain_tumor_segmentation

Brain cancer’s severity necessitates precise brain tumor segmentation via 3D MRI, crucial for diagnosis, monitoring, and effective treatment planning. Manual identification,
burdened by high costs, labor, and error risks, highlights
the need for automated methods. In this study, we introduce
the Global Context-aware Squeeze and Excite Residual UNet
(GCSER-UNet), integrating the innovative Global Context-aware
Squeeze and Excite (GCSE) mechanism. GCSE facilitates a
fusion of spatial and channel-wise attention, enhancing the
model’s capacity to capture intricate spatial dependencies and
contextual information. GCSER-UNet efficiently extracts tumor
segments from multimodal MRI slices, delivering exceptional
performance. Evaluations on benchmark databases exhibit its
superiority, achieving a notable 94% dice score on the TCGA
LGG dataset, surpassing the state-of-the-art dice score of 91.8%.
In the BraTS 2020 dataset, the proposed GCSER-UNet ensemble
approach yielded dice scores of 95%, 92%, and 90% for the tumor
regions—Whole Tumor (W), Tumor Core (T), and Enhancing Tumor (E), respectively. By comparison, the current state-of-the-art
dice scores were 94%, 93%, and 88%. These compelling outcomes
highlight the efficacy of GCSER-UNet in precise brain tumor
segmentation, promising enhanced efficiency and precision, thus
advancing brain cancer management and treatment planning.

**Architecture:**

(a) Schematic of Res-Block, (b) Schematic of the proposed GCSE mechanism, (c) Structural overview of the proposed
GCSER-UNet
![image](https://github.com/Sourjya261/Brain_tumor_segmentation/assets/89221563/d5515a1c-0b2a-4cac-bdd6-215c52eb6511)

**Results:**
![image](https://github.com/Sourjya261/Brain_tumor_segmentation/assets/89221563/807c4dfc-dca5-449a-a493-958357a54611)
![image](https://github.com/Sourjya261/Brain_tumor_segmentation/assets/89221563/db763b2a-77e8-4195-ab02-19490573a17e)
![image](https://github.com/Sourjya261/Brain_tumor_segmentation/assets/89221563/1641c354-586c-4765-ae9f-b371044ec65a)
![image](https://github.com/Sourjya261/Brain_tumor_segmentation/assets/89221563/775c7502-a04c-4b1f-a44e-4542007020f2)





**Ablation study segmentation output comparison TCGA:**
![ablation_TCGA](https://user-images.githubusercontent.com/89221563/229312497-173e5c87-e67c-4665-a6d3-58081b15369b.jpg)
**Ablation study segmentation output comparison BraTS 2020:**
![BraTS_ablation](https://user-images.githubusercontent.com/89221563/229312512-ddc3a5e5-76b6-4ec9-819d-1a1967be1fc0.png)



