# FRUIT AND VEGETABLE IMAGES CLASSIFICATION WITH CNN MODEL
This project aims to create a 'CNN' model for classificate fruit and vegetable images. At the same time, an interface has been created to visualise the predictions of the given image using 'gradio' library.

## DATASET
The dataset used in this project is available on [Kaggle's Fruit and Vegetable Dataset](https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition).

### DATASET DETAILS
- **Number of classes:** 36
- **Fruits**: Banana, Apple, Pear, Grapes, Orange, Kiwi, Watermelon, Pomegranate, Pineapple, Mango
- **Vegetables**: Cucumber, Carrot, Capsicum, Onion, Potato, Lemon, Tomato, Radish, Beetroot, Cabbage, Lettuce, Spinach, Soybean, Cauliflower, Bell Pepper, Chilli Pepper, Turnip, Corn, Sweetcorn, Sweet Potato, Paprika, Jalapeño, Ginger, Garlic, Peas, Eggplant

The dataset is organized into three main folders:

- **Train**: Contains 100 images per category.
- **Test**: Contains 10 images per category.
- **Validation**: Contains 10 images per category.

## TRAINING THE MODEL
Two separate models were created. The model structure on the left below contains the structure of the model in the first experiment. The training data accuracy of the first model was 0.77 and the validation score was 0.79. With 32 epochs, the deficiencies of the trained model were taken into consideration and since the overfitting problem was suspected, the model was made more complex and the number of epochs was increased to 50. The improved model named 'trained_model2' is given on the right side. While the train score was 0.894, the validation score was 0.888.

![img](Screenshot%202024-07-29%20at%2019.23.55.png)

## GRADIO OUTPUT
The output of the model is visualised using the 'gradio' library. The user can upload an image and the model predicts its label.

![img2](Screenshot%202024-07-29%20at%2021.05.36.png)