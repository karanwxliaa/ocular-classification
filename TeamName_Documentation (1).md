

**DOCUMENTATION ON QUALITY WEEK – ML/DL CONTEST ON IMAGE CLASSIFICATION**

Team name: Team Name

Team members: Jaskaran Singh Walia (21BCE1089) Jesher Joshua (21BAI1925)

**Introduction:**

The ML/DL image classification competition was a challenge to identify four classes of eye

diseases from the dataset provided - cataract, diabetic\_retinopathy, glaucoma, and normal. The

aim of the competition was to develop a deep learning model that could accurately classify the

images and achieve high accuracy.

Fig 1. Dataset’s class representation

**Methodology:**

We implemented deep learning methodologies to tabulate the results, and several models

were tried before selecting the final one. The models tested were VGG19, MobileNet,

GoogLeNet, Alexnet, and ElasticNet. The final model selected was Resnet50, which was fine-

tuned and optimized for the dataset. The model was trained with the SGD loss function after

trying out the Adam and LazyAdam optimizers.

Other hyperparameters used after extensive re-iteration and testing were

Batch size 64

Img size 32x32

Epochs 11





Optimizer SGD

Weights = imagenet (gave the best results)

**Model Performance:**

The Resnet50 model was fine-tuned and achieved an accuracy of 95% on the train dataset and

92% on the test dataset. This was achieved after hyperparameter tuning, including learning rate

adjustments and batch size adjustments. The model was trained for a total of 11 epochs.

**Model**

**Final Score**

VGG19

82%

68%

73%

62%

84%

92%

MobileNet

GoogLeNet

Alexnet

ElasticNet

Resnet50

Results obtained by other transfer learning models.

**Evaluation metrics:**

**Total Train-Test split was 60% - 40% which concluded the images to be**

**Train = 2532**

**Test = 1685**

**Confusion Matrix:**





**Accuracy & Loss:**

**Precision, Recall, F1-Score, Support:**





**ROC Curve:**

**Sensitivity:**

**Kappa score:**

**Visualizing results:**





Conclusion:

The ML/DL image classification competition was a challenging task that required us to develop

deep learning models capable of accurately classifying eye diseases. The Resnet50 model

proved to be the most effective, achieving a high accuracy of 95% on the train dataset and 92%

on the test dataset after performing hyperparameter tuning. The competition demonstrated

the power of deep learning methodologies and the importance of fine-tuning and optimizing

models to achieve the best results all of which are mentioned above.

