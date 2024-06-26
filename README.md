# Satellite-Change-Detection

We proposed an unsupervised LCD method by exploiting the vision foundation model SAM. The process commences with image acquisition, where a sequence of two images is captured. Since these images are for different dates, they have different resolutions and contrast; therefore, pre-processing steps to eliminate Gaussian noises and atmospheric interferences are essential.

We used two public datasets: 

- LEVIR-CD is a large-scale remote sensing building change detection dataset. It contains very high-resolution (VHR, 0.5m/pixel) GEE image patch pairs with a size of 1024 × 1024 pixels.
- DSIFN-CD consists of high-resolution (2m) satellite images from six major cities in China. It covers changes in various land cover types, including roads, buildings, croplands, and water bodies.

  and (case study) this study used optical imagery from Sentinel-2 sensors acquired from GEE to detect illegal constructions in the protected area surrounding Gerˆes Park, Portugal.


and some of the results for two public datasets and one case study from the north of Portugal are:

![img_result](https://github.com/NarjesDavari/Satellite-Change-Detection/blob/main/img_result.png)

![img_result2](https://github.com/NarjesDavari/Satellite-Change-Detection/blob/main/img_result2.png)


![case study](https://github.com/NarjesDavari/Satellite-Change-Detection/blob/main/case_study.png)
