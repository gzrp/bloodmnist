# About dataset

The BloodMNIST , as a sub set of MedMNIST, is based on a dataset of individual normal cells, captured from individuals without infection, hematologic or oncologic disease and free of any pharmacologic treatment at the moment of blood collection. It contains a total of 17,092 images and is organized into 8 classes. it is split with a ratio of 7:1:2 into training, validation and test set. The source images with resolution 3×360×363 pixels are center-cropped into 3×200×200, and then resized into 3×28×28.

8 classes of the dataset:

```
"0": "basophil",
"1": "eosinophil",
"2": "erythroblast",
"3": "ig (immature granulocytes)",
"4": "lymphocyte",
"5": "monocyte",
"6": "neutrophil",
"7": "platelet"
```