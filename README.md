![BiaPy logo](https://raw.githubusercontent.com/BiaPyX/BiaPy/master/img/biapy_logo.png)

# BiaPy: Bioimage analysis pipelines in Python

<p align="left">
    <a href="https://www.python.org/">
      <img src="https://img.shields.io/badge/Python-3.10-yellow.svg" /></a>
    <a href= "https://pytorch.org/">
      <img src="https://img.shields.io/badge/PyTorch-2.4-orange.svg" /></a>
    <a href= "https://pypi.org/project/biapy/">
      <img src="https://img.shields.io/pypi/v/biapy.svg?color=green" /></a>
    <a href= "https://github.com/BiaPyX/BiaPy/blob/master/LICENSE">
      <img src="https://img.shields.io/badge/License-MIT-blue.svg" /></a>
    <a href= "https://biapy.readthedocs.io/en/latest/">
      <img src="https://img.shields.io/badge/Doc-Latest-2BAF2B.svg" /></a>
    <a href= "https://www.biorxiv.org/content/10.1101/2024.02.03.576026v1">
      <img src="https://img.shields.io/badge/bioRxiv-Paper-bd2635.svg" /></a>
    <a href= "https://ieeexplore.ieee.org/abstract/document/10230593">
      <img src="https://img.shields.io/badge/IEEE-Paper-00629B.svg" /></a>
</p>

🔥**NEWS**🔥: We have a new **preprint**! Check it out at bioRxiv: https://www.biorxiv.org/content/10.1101/2024.02.03.576026v1

[BiaPy](https://biapyx.github.io) is an open source ready-to-use all-in-one library that provides deep-learning workflows for a large variety of bioimage analysis tasks, including 2D and 3D [semantic segmentation](https://biapy.readthedocs.io/en/latest/workflows/semantic_segmentation.html), [instance segmentation](https://biapy.readthedocs.io/en/latest/workflows/instance_segmentation.html), [object detection](https://biapy.readthedocs.io/en/latest/workflows/detection.html), [image denoising](https://biapy.readthedocs.io/en/latest/workflows/denoising.html), [single image super-resolution](https://biapy.readthedocs.io/en/latest/workflows/super_resolution.html), [self-supervised learning](https://biapy.readthedocs.io/en/latest/workflows/self_supervision.html), [image classification](https://biapy.readthedocs.io/en/latest/workflows/classification.html) and [image to image translation](https://biapy.readthedocs.io/en/latest/workflows/image_to_image.html). 
                        
BiaPy is a versatile platform designed to accommodate both proficient computer scientists and users less experienced in programming. It offers diverse and user-friendly access points to our workflows.

This repository is actively under development by the Biomedical Computer Vision group at the [University of the Basque Country](https://www.ehu.eus/en/en-home) and the [Donostia International Physics Center](http://dipc.ehu.es/).       

![BiaPy workflows](https://raw.githubusercontent.com/BiaPyX/BiaPy/master/img/BiaPy-workflow-readme.svg)

## Description video
Find a comprehensive overview of BiaPy and its functionality in the following videos:

| [![BiaPy history and GUI demo](./img/BiaPy_presentation_and_demo_at_RTmfm.jpg)](https://www.youtube.com/watch?v=Gnm-VsZQ6Cc "BiaPy: a ready-to-use library for Bioimage Analysis Pipelines") <br> <span style="font-weight:normal">BiaPy history and GUI demo at [RTmfm](https://rtmfm.cnrs.fr/en/) by Ignacio Arganda-Carreras and Daniel Franco-Barranco.</span> |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [![BiaPy presentation](./img/BiaPy-Euro-BioImaging-youtube.png)](https://youtu.be/6eYtX-ySpc0 "BiaPy: a ready-to-use library for Bioimage Analysis Pipelines") <br> BiaPy presentation at [Virtual Pub of Euro-BioImaging](https://www.eurobioimaging.eu/) by Ignacio Arganda-Carreras.                                                                      |                          |                          |                              |                           |

## User interface

You can also use BiaPy through our graphical user interface (GUI).

![BiaPy GUI](https://raw.githubusercontent.com/BiaPyX/BiaPy/master/img/BiaPy_GUI_main_page.png)

## Download BiaPy GUI for you OS

- [Windows 64-bit](https://drive.google.com/uc?export=download&id=1iV0wzdFhpCpBCBgsameGyT3iFyQ6av5o) 
- [Linux 64-bit](https://drive.google.com/uc?export=download&id=13jllkLTR6S3yVZLRdMwhWUu7lq3HyJsD) 
- [macOS 64-bit](https://drive.google.com/uc?export=download&id=1fIpj9A8SWIN1fABEUAS--DNhOHzqSL7f) 

Project's page: [[BiaPy GUI](https://github.com/BiaPyX/BiaPy-GUI)]

## Applications using BiaPy

|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                                                                                                                                                             |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------:|
| ```López-Cano, Daniel, et al. "Characterizing Structure Formation through Instance Segmentation" (2023).``` <br><br> This study presents a machine-learning framework to predict the formation of dark matter haloes from early universe density perturbations. Utilizing two neural networks, it distinguishes particles comprising haloes and groups them by membership. The framework accurately predicts halo masses and shapes, and compares favorably with N-body simulations. The open-source model could enhance analytical methods of structure formation by analyzing initial condition variations. ```BiaPy``` is used in the creation of the watershed approach. <br><br> [[Documentation (not yet)](https://biapy.readthedocs.io/en/latest)] [[Paper](https://arxiv.org/abs/2311.12110)] |                                                  ![](https://raw.githubusercontent.com/BiaPyX/BiaPy/master/img/halo_instances.png)                                                |
| ```Franco-Barranco, Daniel, et al. "Current Progress and Challenges in Large-scale 3D Mitochondria Instance Segmentation." (2023).``` <br><br> This paper reports the results of the MitoEM challenge on 3D instance segmentation of mitochondria in electron microscopy images, held in conjunction with IEEE-ISBI 2021. The paper discusses the top-performing methods, addresses ground truth errors, and proposes a new scoring system to improve segmentation evaluation. Despite progress, challenges remain in segmenting mitochondria with complex shapes, keeping the competition open for further submissions. ```BiaPy``` is used in the creation of the MitoEM challenge baseline (U2D-BC). <br><br> [[Documentation](https://biapy.readthedocs.io/en/latest/tutorials/mitoem.html)] [[Paper](https://ieeexplore.ieee.org/document/10266382)] [[Toolbox](https://github.com/BiaPyX/TIMISE)] |                                                  ![](https://raw.githubusercontent.com/BiaPyX/BiaPy/master/img/complex_MOAS.png)                                                |
| ```Backová, Lenka, et al. "Modeling Wound Healing Using Vector Quantized Variational Autoencoders and Transformers." 2023 IEEE 20th International Symposium on Biomedical Imaging (ISBI). IEEE, 2023.``` <br><br> This study focuses on time-lapse sequences of Drosophila embryos healing from laser-incised wounds. The researchers employ a two-stage approach involving a vector quantized variational autoencoder and an autoregressive transformer to model wound healing as a video prediction task. ```BiaPy``` is used in the creation of the wound segmentation masks. <br><br> [[Documentation](https://lenkaback.github.io/wound-healing-modeling/)] [[Paper](https://ieeexplore.ieee.org/document/10230571)] | ![](https://raw.githubusercontent.com/BiaPyX/BiaPy/master/img/wound_diagram_VQVAE.png) |
| ```Andrés-San Román, Jesús A., et al. "CartoCell, a high-content pipeline for 3D image analysis, unveils cell morphology patterns in epithelia." Cell Reports Methods (2023)``` <br><br> Combining deep learning and 3D imaging is crucial for high-content analysis. CartoCell is introduced, a method that accurately labels 3D epithelial cysts, enabling quantification of cellular features and mapping their distribution. It's adaptable to other epithelial tissues. CartoCell method is created using ```BiaPy```. <br><br> [[Documentation](https://biapy.readthedocs.io/en/latest/tutorials/cartocell.html)] [[Paper](https://www.cell.com/cell-reports-methods/pdf/S2667-2375(23)00249-7.pdf)]                                                                                                                                                                                                                                                                  | <table>   <tr>     <td>![](https://raw.githubusercontent.com/BiaPyX/BiaPy/master/img/cyst_sample.gif) </td>     <td>![](https://raw.githubusercontent.com/BiaPyX/BiaPy/master/img/cyst_instance_prediction.gif) </td>   </tr> </table> |
| ```Franco-Barranco, Daniel, et al. "Deep learning based domain adaptation for mitochondria segmentation on EM volumes."  Computer Methods and Programs in Biomedicine 222 (2022): 106949.``` <br><br> This study addresses mitochondria segmentation across different datasets using three unsupervised domain adaptation approaches, including style transfer, self-supervised learning, and multi-task neural networks. To ensure robust generalization, a new training stopping criterion based on source domain morphological priors is proposed. ```BiaPy``` is used for the implementation of the Attention U-Net. <br><br> [[Documentation](https://github.com/danifranco/EM_domain_adaptation)] [[Paper](https://www.sciencedirect.com/science/article/pii/S0169260722003315)]                                                                                                                  |                                                           ![](https://raw.githubusercontent.com/BiaPyX/BiaPy/master/img/domain_EM.jpg)                                                         |
| ```Franco-Barranco, Daniel, et al. "Stable deep neural network  architectures for mitochondria segmentation on electron microscopy volumes." Neuroinformatics 20.2 (2022): 437-450.``` <br><br> Recent deep learning models have shown impressive performance in mitochondria segmentation, but often lack code and training details, affecting reproducibility. This study follows best practices, comprehensively comparing state-of-the-art architectures and variations of U-Net models for mitochondria segmentation, revealing their impact and stability. The research consistently achieves state-of-the-art results on various datasets, including EPFL Hippocampus, Lucchi++, and Kasthuri++. ```BiaPy``` is used for the implementation of the methods compared in the study. <br><br> [[Documentation](https://biapy.readthedocs.io/en/latest/tutorials/stable.html)] [[Paper](https://link.springer.com/article/10.1007/s12021-021-09556-1)]                                                                                                 |                                                       ![](https://raw.githubusercontent.com/BiaPyX/BiaPy/master/img/unet_attn_stable.png)                                                     |
| ```Wei, Donglai, et al. "Mitoem dataset: Large-scale 3d mitochondria instance segmentation from em images." International Conference on Medical Image Computing and Computer-Assisted Intervention. Cham: Springer International Publishing, 2020.``` <br><br> Existing mitochondria segmentation datasets are small, raising questions about method robustness. The MitoEM dataset introduces larger 3D volumes with diverse mitochondria, challenging existing instance segmentation methods, highlighting the need for improved techniques. ```BiaPy``` is used in the creation of the MitoEM challenge baseline (U2D-BC). <br><br> [[Documentation](https://biapy.readthedocs.io/en/latest/tutorials/mitoem.html)] [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-59722-1_7)] [[Challenge](https://mitoem.grand-challenge.org/)]                                                                                                                                                                             |                                               ![](https://raw.githubusercontent.com/BiaPyX/BiaPy/master/img/MitoEM_teaser_cable_length_split.png)                                                |

## Authors

| Name                                                                               | Role                                     | Affiliations                                                                                                                                                                                                                                                        |
|------------------------------------------------------------------------------------|------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Daniel Franco-Barranco](https://BiaPyX.github.io/)                            | Creator, Implementation, Software design | <ul> <li> Dept. of Computer Science and Artificial Intelligence, University of the Basque Country (UPV/EHU)  </li> <li>  Donostia International Physics Center (DIPC) </li> </ul>                                                                                   |
| [Lenka Backová](https://www.biofisika.org/en/about/people/lenka-backova)                     | Implementation                              | <ul> <li> Biofisika Institute </li> </ul>        |
| [Aitor Gonzalez-Marfil](https://dipc.ehu.eus/es/dipc/personas/investigadores-en-formacion/aitor-gonzalez-marfil)                     | Implementation                              | <ul> <li> Dept. of Computer Science and Artificial Intelligence, University of the Basque Country (UPV/EHU) </li> <li> Donostia International Physics Center (DIPC) </li> </ul>        |
| [Ignacio Arganda-Carreras](https://www.ikerbasque.net/es/ignacio-arganda-carreras) | Supervision, Implementation              | <ul> <li> Dept. of Computer Science and Artificial Intelligence, University of the Basque Country (UPV/EHU) </li> <li> Donostia International Physics Center (DIPC)  </li> <li> IKERBASQUE, Basque Foundation for Science </li> <li>Biofisika Institute </li> </ul> |
| [Arrate Muñoz-Barrutia](https://image.hggm.es/es/arrate-munoz)                     | Supervision                              | <ul> <li> Dept. de Bioingenieria, Universidad Carlos III de Madrid </li> </ul>  |


## External collaborators

| Name                                                                                               | Role                        | Affiliations                                                                                                                                                                                                                                                                                                                                                     |
|----------------------------------------------------------------------------------------------------|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Jesús Ángel Andrés-San Román](https://scholar.google.es/citations?user=OfDu4q4AAAAJ&hl=en&oi=sra) | Implementation              | <ul> <li>Instituto de Biomedicina de Sevilla (IBiS), Hospital Universitario Virgen del Rocío/CSIC/Universidad de Sevilla and Dept. de Biología Celular, Facultad de Biología, Universidad de Sevilla </li> <li> Biomedical Network Research Centre on Neurodegenerative Diseases (CIBERNED) </li> </ul>                                                    |
| [Pedro Javier Gómez Gálvez](https://scholar.google.es/citations?user=aWeyQGUAAAAJ&hl=en&oi=sra)    | Supervision, Implementation | <ul> <li>Instituto de Biomedicina de Sevilla (IBiS), Hospital Universitario Virgen del Rocío/CSIC/Universidad de Sevilla and Dept. de Biología Celular, Facultad de Biología, Universidad de Sevilla </li> <li> MRC Laboratory of Molecular Biology </li> <li> Department of Physiology, Development and Neuroscience, University of Cambridge </li> </ul> |
| [Luis M. Escudero](http://www.scutoids.es/)                                                        | Supervision                 | <ul> <li>Instituto de Biomedicina de Sevilla (IBiS), Hospital Universitario Virgen del Rocío/CSIC/Universidad de Sevilla and Dept. de Biología Celular, Facultad de Biología, Universidad de Sevilla </li> <li> Biomedical Network Research Centre on Neurodegenerative Diseases (CIBERNED) </li> </ul>                                                    |
| [Iván Hidalgo Cenalmor](https://henriqueslab.github.io/team/2023-03-16-IH/)                        | Implementation              | <ul> <li> Optical cell biology group, Instituto Gulbenkian de Ciência, Oerias, Portugal </li> </lu>                                                                                                                                                                                                                                                              |
| [Donglai Wei](https://donglaiw.github.io/)                                                        | Supervision                 | <ul> <li>Boston College</li> </ul>  |
| [Clément Caporal](https://scholar.google.com/citations?hl=en&user=R0fXJGUAAAAJ)                                                        | Implementation                 | <ul> <li>Laboratoire d’Optique et Biosciences, CNRS, Inserm, Ecole Polytechnique</li> </ul>  |
| [Anatole Chessel](https://scholar.google.com/citations?hl=en&user=GC8aiVsAAAAJ)                                                        | Supervision                 | <ul> <li>Laboratoire d’Optique et Biosciences, CNRS, Inserm, Ecole Polytechnique</li> </ul>  |

## Citation
```
Franco-Barranco, Daniel, et al. "BiaPy: a ready-to-use library for Bioimage Analysis Pipelines." 
2023 IEEE 20th International Symposium on Biomedical Imaging (ISBI). IEEE, 2023.
``` 
