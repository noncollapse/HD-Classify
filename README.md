# HD-Classify
A Survey of Effectiveness of Classification Methods on Heart Disease Data

## Data:
Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [https://archive.ics.uci.edu/ml/datasets/Heart+Disease]. Irvine, CA: University of California, School of Information and Computer Science.

The instances used are found in the `processed.cleveland.data` file.

The names for the variables are found in the `heart-disease.names` files (line 109 onwards)

A condensed documentation for the main features of the dataset is compiled here:<br>

[Detailed Explanation of Data.xlsx](https://github.com/gperez21/HD-Classify/files/10784936/Detailed.Explanation.of.Data.xlsx)

#### **Creating Test and Training Data:**


A randomly sampled 20% of the full Cleveland data is set aside for testing. The remaining 80% is for use in training the models.

**Training Data**
(238 lines)<br>
[Cleveland.data.train.csv](https://github.com/gperez21/HD-Classify/files/10784855/Cleveland.data.train.csv)

**Testing Data**
(65 lines)<br>
[Cleveland.data.test.csv](https://github.com/gperez21/HD-Classify/files/10784854/Cleveland.data.test.csv)

The R Code used to split the data can be found here:

[R code for sample training and testing data](Sample_Training_Data.Rmd)

