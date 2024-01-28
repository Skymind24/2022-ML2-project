# <p align="center">Eye Disease Diagnosis Program <br/> Using Semi-Supervised Learning</p>

## :pushpin: Abstract
We built an artificial intelligence program that can diagnose eye diseases using human eye data that can be observed with the naked eye. To compensate for the limitation of the absolute lack of data specifying the presence or absence of a disease or its name, we conducted semi-supervised learning using a large number of unlabeled data (UD). And we analyzed the performance difference with a supervised learning model using existing labeled data to observe the effectiveness of using the technique.

<br/>

## :pushpin: Models
Semi-Supervised Learning Algorithms
* Pseudo labeling
* Noisy student

<br/>

## :ballot_box_with_check: Installation
```
%pip install torchmetrics
%pip install torchvision
%pip install tensorflow==2.3
%pip install seaborn
%pip install scikit-plot
```

<br/>

## :ballot_box_with_check: How to run
Use Google Colab

```   Run main.ipynb   ```

<br/>

## :ballot_box_with_check: Folder Structure
```
.
├── augmentation.py
├── augmentation_upgrade.py
├── baseline.py
├── checkpoints
│   ├── augmentation.pth
│   ├── augmentation_save_model.pth
│   ├── augmentation_upgrade.pth
│   ├── augmentation_upgrade_save_model.pth
│   ├── baseline.pth
│   ├── baseline_save_model.pth
│   ├── noisy-student_0_save_model.pth
│   ├── noisy-student_1.pth
│   ├── noisy-student_1_save_model.pth
│   ├── noisy-student_2.pth
│   ├── noisy-student_2_save_model.pth
│   ├── noisy-student_3.pth
│   ├── noisy-student_3_save_model.pth
│   ├── noisy-student_4.pth
│   ├── noisy-student_4_save_model.pth
│   ├── noisy-student_5.pth
│   ├── noisy-student_5_save_model.pth
│   ├── noisy-student_6.pth
│   ├── noisy-student_6_save_model.pth
│   └── pseudo-label.pth
├── data
│   ├── crop_data_labeled_class6
│   │   ├── train
│   │   │   ├── cataracts
│   │   │   ├── conjunctivitis
│   │   │   ├── exophthalmos
│   │   │   ├── glaucoma
│   │   │   ├── normal
│   │   │   └── uveitis
│   │   └── val
│   └── crop_data_unlabeled
│       └── unlabeled
├── data_preprocessing
│   ├── Crawling_naver.ipynb
│   ├── eye_detect.ipynb
│   └── face_cropped_test.ipynb
├── main.ipynb
├── noisy_student.py
├── pseudo_labeling.py
├── savefig
└── src
    ├── __init__.py
    ├── datasets.py
    ├── engines.py
    ├── models.py
    └── utils.py
```
