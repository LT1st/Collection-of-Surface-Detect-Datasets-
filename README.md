# Collection-of-Surface-Detect-Datasets


<p align="center">
  <a href="https://example.com/">
    <img src="https://via.placeholder.com/72" alt="Logo" width=72 height=72>
  </a>

  <h3 align="center">Logo</h3>

  <p align="center">
    Summary of Surface Defect Datasets. All links are listed if aviable. 
    <br>
    <a href="https://reponame/issues/new?template=bug.md">Report bug</a>
    ·
    <a href="https://reponame/issues/new?template=feature.md&labels=feature">Request feature</a>
  </p>
</p>

## Summary
In the field of surface defect detection on steel strips, the NEU Surface Defect Database, first proposed by Song in 2013, is the most widely used dataset [1]. NEU-CLS contains six types of defects, each with 300 images. The dataset has characteristics such as large intra-class visual variations, similar inter-class defects, lighting and material variations among different samples. In the 2018 Industrial Big Data Innovation Competition held in Guangdong, Alibaba proposed the Aluminum Profile Surface Defect Recognition Dataset, which consists of 8000 images of 2560x1920 pixels for defects such as cracks, peeling, scratches, corrosion, and bubbles. The training set of 3000 images contains 1351 images without defects, 2281 images with single defects, and 229 images with multiple defects. There is an imbalance in the number of samples among different categories, and the object scales of different categories are also unevenly distributed. In 2019, Severstal Steel Dataset was proposed by Severstal in the Steel Defect Detection competition held by Kaggle [6]. The dataset contains 5506 samples for object detection tasks and four types of defects, sourced from the Russian steel industry data lake. In 2020, He et al. proposed the NEU-DET dataset, which further annotates the data from NEU-CLS and provides bounding-box labels for object detection tasks [2]. In the same year, Song et al. proposed the SD-saliency-900 dataset for image segmentation, which provides pixel-level annotations for three types of defects: inclusions, patches, and scratches [5]. Bao et al. proposed the Surface Defects-4i dataset for surface defect segmentation, which includes common metal surface defects such as aluminum, steel, railway tracks, and ceramic tiles, as well as non-metallic materials such as leather and ceramic tiles as extended data to further prove the model's generalization ability [4]. Niu et al. proposed the RSDDS-113 dataset for surface defect detection on railway tracks, which has high annotation reliability but a small number of data samples [50]. In 2021, Feng et al. proposed the improved X-SDD dataset for defect classification tasks, which contains seven typical hot-rolled steel strip defects with a total of 1360 samples, based on NEU-CLS [3]. Zhang et al. published Rail-5k in the same year, which contains over 5000 high-quality images of the 13 most common types of railway defects, with 1100 images annotated [49]. In 2022, Severstal proposed an improved Severstal Steel Dataset for the AIA Manufacturing Project - Defect Inspection competition [7].

Due to the scarcity of datasets in the field of surface defect detection on steel strips, other datasets with similar backgrounds have also been widely used for training and evaluation of surface defect detection models. The earliest DAGM 2007 [11] is a surface defect image dataset of various textures under various industrial backgrounds, generated using the optical model of defects and manual collaboration. It consists of six datasets, with each containing 1000 texture images without defects and 150 images with a marked defect. The Kolektor Surface-Defect Dataset (KolektorSDD) [8] was constructed based on surface defect images of electronic commutators (metal) collected and annotated by Kolektor Group doo, containing 399 images of size 500x1250 pixels, with annotation accuracy suitable for image classification tasks only. In 2021, this lab further added bounding-box labels to this dataset, making it usable for object detection tasks. In the same year, KolektorSDD2 [9] was proposed by this lab based on KolektorSDD, which contains over 3000 images of various types of defects (scratches, small spots, surface defects, etc.) collected from actual industrial scenes, and can be used for surface defect detection on steel strips. KolektorSDD2 uses pixel-level labels and is suitable for semantic segmentation of defects. BTAD (beanTech Anomaly Detection) dataset proposed by Mishra et al. contains 2830 images of three industrial products collected from real industrial production scenes, with defects occurring on the object body and surface [10].

- [Quick start](#quick-start)



## Quick start

Some text

- Instruction 1


## Details


## Dataloaders


## License
Please note that some of the contents are not published yet, please ref this repo instead. 
```
@misc{lutao_2023,
    author = {Lu Tao},
    title = {Summary of Surface Defect Datasets},
    year = {2023},
    url = {https://github.com/LT1st/Collection-of-Surface-Detect-Datasets-/edit/main/README.md},
    note = {Accessed: Date}
}
```




