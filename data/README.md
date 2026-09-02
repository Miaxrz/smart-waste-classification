# Dataset

## Dataset Name

Real-World Waste Classification Dataset (5 Class)

## Source

The dataset is available through Kaggle:

Real-World Waste Classification Dataset (5 Class)

## Purpose

The dataset is used to develop and evaluate a computer vision system capable of classifying waste materials into predefined categories.

## Classes

The dataset contains five waste categories:

| Class   | Description                                                |
| ------- | ---------------------------------------------------------- |
| Metal   | Metal cans, containers, foil and similar materials         |
| Plastic | Plastic bottles, bags, packaging and similar materials     |
| Paper   | Paper, cardboard and paper-based materials                 |
| Glass   | Glass bottles, jars and similar materials                  |
| Organic | Food waste, fruit peels, leaves and other organic material |

## Dataset Size

The dataset contains 1,647 images distributed across five classes.

## Data Distribution

* Metal: 375 images
* Plastic: 335 images
* Paper: 323 images
* Glass: 314 images
* Organic: 300 images

## Data Usage

The dataset will not be committed directly to this GitHub repository. Users should download the dataset from its original source and place the images in the local project data directory.

## License

The dataset is listed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.

## Preprocessing

Images will be loaded using OpenCV and processed before model training. The preprocessing pipeline will include resizing, colour-space conversion where required, normalization, and preparation of labels.

## Important Note

The dataset will be split into training, validation, and testing subsets before model development. Data augmentation will only be applied to the training data to reduce the risk of data leakage.
