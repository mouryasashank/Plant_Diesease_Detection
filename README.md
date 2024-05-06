# Plant_Diesease_Detection

## Introduction
The agricultural industry, comprising more than 570 million farms globally, has historically relied on manual inspections. As an illustration, a study conducted in 2010, required a team of five specialists two weeks to inspect a 50-acre farm. 
In India, where approximately 60% of its 1.3 billion inhabitants are engaged in agriculture, manual inspections can be time-consuming, leading to delays in essential crop management tasks. 
Recent advancements in machine learning and image recognition have significantly enhanced accuracy rates. For example, a study conducted in 2020 demonstrated a 95% accuracy rate in the identification of grape leaf diseases through the use of AI.

## Dataset
In this dataset, around 87,000 RGB images are included, offering a diverse range of healthy and diseased crop leaves. The dataset encompasses 38 different classes representing various plant species and diseases! 

https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

## EDA
EDA was done to learn more about our dataset's characteristics.
This includes:
1. Colour Distribution
2. Image Dimensions
3. Disease Distribution
4. Class Balance

![Capture1](https://github.com/mouryasashank/Plant_Diesease_Detection/assets/53688863/f0eab436-cc35-4f46-8efa-5dcd12cec8c2)

![Capture2](https://github.com/mouryasashank/Plant_Diesease_Detection/assets/53688863/caf38cd1-2207-4ce2-92b4-e5dd47682947)


## Model Architecture
Developed a deep-learning neural network model with 8 layers, unlike the ResNet or VGG model, to train the data very efficiently.

![Capture3](https://github.com/mouryasashank/Plant_Diesease_Detection/assets/53688863/407611fd-8d09-4829-be31-25c3b6756b19)

## Results

As a result, the model is trained very well with the developed model and has a higher accuracy than the usual ones.

![Capture4](https://github.com/mouryasashank/Plant_Diesease_Detection/assets/53688863/08d097ce-df3a-42e9-ab6b-74e02f5d2aeb)
![Capture5](https://github.com/mouryasashank/Plant_Diesease_Detection/assets/53688863/cc2ff956-95ff-4b44-a685-759aae9a264f)
![Capture6](https://github.com/mouryasashank/Plant_Diesease_Detection/assets/53688863/82f663bc-63e6-4e70-8e62-00feb5bdb93c)

## References
[1] Saleem, M. H., Potgieter, J., & Arif, K. M. (2019). Plant disease detection and classification by
deep learning. Plants, 8(11), 468.
[2] Ramanjot, Mittal, U., Wadhawan, A., Singla, J., Jhanjhi, N. Z., Ghoniem, R. M., ... &
Abdelmaboud, A. (2023). Plant disease detection and classification: A systematic literature review.
Sensors, 23(10), 4769.
[3] Lu, J., Tan, L., & Jiang, H. (2021). Review on convolutional neural network (CNN) applied to
plant leaf disease classification. Agriculture, 11(8), 707.
[4] Arsenovic, M. (2024). Deep Learning for Plant Diseases Detection [GitHub repository].
GitHub. https://github.com/MarkoArsenovic/DeepLearning_PlantDiseases/
