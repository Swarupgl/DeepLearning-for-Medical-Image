# Brain MRI Tumor Segmentation

## Methods

* Otsu Global Thresholding
* Sauvola Adaptive Thresholding

## Metrics

* Dice Score
* Jaccard Index (IoU)

## Results

Otsu Dice: 0.0754
Sauvola Dice: 0.0537
Otsu Jaccard: 0.0406
Sauvola Jaccard: 0.0282

## Observations

* Otsu thresholding performed better than Sauvola on this dataset.
* Both methods achieved relatively low segmentation accuracy.
* Increasing window size in Sauvola made it behave closer to global thresholding.
* Intensity-based thresholding struggles due to complex MRI intensity distribution and low tumor contrast.

## Conclusion

Otsu performed slightly better than Sauvola; however, both thresholding methods showed limited performance for MRI tumor segmentation. This highlights the need for more advanced approaches such as region-based techniques or deep learning models for accurate medical image analysis.

## Dataset

BRISC 2025 Brain MRI Segmentation Dataset (Kaggle)
