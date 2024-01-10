# Melanoma-Detection-Assignment
You are required to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents


- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)


## Conclusions
- Developed a CNN model, which can accurately detect 9 classes present in the dataset.
- Adam optimise is chosen.
- There is clear evidence of model overfitting-Training accuracy is 0.84 after 20 epochs but validation accuracy is 0.52 (difference of 0.32).Training loss is going down after every epoch but validation loss is parabolic. In fact validation loss is going up.


-Which class has the least number of samples?
->seborrheic keratosis
- Which classes dominate the data in terms proportionate number of samples?
->pigmented benign keratosis

- Augmentor is used to rectify the class imbalance
- Got rid of underfitting. Now training and validation accuracies are higher than previous model (0.82, 0.79)

## Technologies Used

- numpy - version 1.23.5
- pandas - version 1.5.3
- matplotlib - version 3.7
- seaborn - version 0.12.2
- tensor flow -version 2.15.0

## Acknowledgements


## Contact

