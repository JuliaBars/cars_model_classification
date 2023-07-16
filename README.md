## Car models classification

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)  ![Colab](https://img.shields.io/badge/google_colaboratory-F9AB00?style=for-the-badge&logo=google-colab&logoColor=white)

The key issue of this project was light model. So i choose MobileNetV2 with 2,5m parameteres and MobileNetV3(large) with 4,5 m parameteres.

All layers were fine tuned and the last classifier layer was replaced entirely.
___
Model's list is NDA, but you can train this model on Stanford cars dataset or huge 3778 models dataset from Kaggle.

Models were trained on segmented cars, you can segment yours with my script (car_segment_with_yolo_2.ipynb), especially if your model will work with segmented cars.

After checking different augmentations, I've chosen ColorJitter.
___
**MobileNetV2 got 91% accuracy, but 've got more mistakes with real data. While MobileNetV3 've got only 79% accuracy, but also 77% acc with real data.**

Baseline from here: **[haksorus_GitHub](https://github.com/haksorus/mobilenetv2-cars-classification/blob/main/mobilenetv2_training.ipynb)**
