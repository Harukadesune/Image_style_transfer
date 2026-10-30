007. Images Style Transfer
Area of Research: Computer Vision (CV)
Problem Statement: Image style transfer applies the artistic style of a reference image to a target image while preserving
its content. Traditional CNN-based methods struggle to capture global image dependencies due to their local receptive
fields, leading to biased content representations and reduced transfer quality. Recent advances in Generative AI (GenAI) and
GANs offer promising alternatives, provided the models can integrate both local details and global information, supported by
scale-invariant positional encoding suited to image-based tasks. This project explores GenAI- and GAN-based approaches to
improve content preservation and style quality, evaluated qualitatively and quantitatively against state-of-the-art techniques.
Task: Develop an automatic image style transfer method using GenAI or GANs that achieves high accuracy and robustness
in transferring artistic styles while preserving original content, enhancing applicability in art, design, and media production.
Dataset:
Figure 7: COCO examples: style images (first column), content images (second column), and style transfer results (last
column).
The MS COCO dataset [1] is a large-scale benchmark (164,000 images) widely used for object detection, segmentation,
key-point detection, and captioning.
Style Images: WikiArt | Content Dataset: COCO 2014 (Kaggle)
Relevant Papers
[1]. Deng, Y., et al. (2022). StyTr2
: Image style transfer with transformers. CVPR (pp. 11326–11336). [PDF]
[2]. Xu, W., et al. (2021). DRB-GAN: A dynamic ResBlock generative adversarial network for artistic style transfer. ICCV
(pp. 6383–6392). [PDF]
[3]. Chen, X., et al. (2018). Gated-GAN: Adversarial gated networks for multi-collection style transfer. IEEE TIP, 28(2),
546–560. [Link]
[4]. Liu, H., et al. (2018). Artsy-GAN: A style transfer system with improved quality, diversity and performance. ICPR (pp.
79–84). [Link]
[5]. Xu, W., et al. (2023). Learning dynamic style kernels for artistic style transfer. CVPR (pp. 10083–10092). [PDF]