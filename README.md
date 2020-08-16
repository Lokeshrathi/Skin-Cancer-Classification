# Skin-Cancer-Classification

## Data:
- Collected from [Kaggle](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000)
- Dataset was divided among various csv files.
- Data size was 10015 rows and 7 columns.
- There were 7 labels present.

![](/Images/skin.png)

---

## From the Author:
- Training of neural networks for automated diagnosis of pigmented skin lesions is hampered by the small size and lack of diversity of available dataset of dermatoscopic images. We tackle this problem by releasing the HAM10000 ("Human Against Machine with 10000 training images") dataset.
- Cases include a representative collection of all important diagnostic categories in the realm of pigmented lesions: Actinic keratoses and intraepithelial carcinoma / Bowen's disease (akiec), basal cell carcinoma (bcc), benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratoses, bkl), dermatofibroma (df), melanoma (mel), melanocytic nevi (nv) and vascular lesions (angiomas, angiokeratomas, pyogenic granulomas and hemorrhage, vasc).

---

## Model Training:
- Used 3 Convolutional Neural Network layers and 2 Dense Layer.
- Used Data Augmentation to expand the Training Data.
- number of epochs used: 50, Batch_size: 90.
- Final Validation score: **Validation Accuracy: 0.7363** and **Recall: 0.6766**

![](/Images/plotloss.png)

![](/Images/final.png)

You can find my Kaggle Notebook here: [Link](https://www.kaggle.com/lokeshrth4617/skin-cancer-classification).
