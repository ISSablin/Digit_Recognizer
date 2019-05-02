##  Digit Recognizer
### Abstract

MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms.

### Goals

- [x] Explore different models for supervised learning
- [x] Find out which one is the best performer on the classic machine learning problem
- [x] Take part in a Kaggle competition

### Dataset

The training set contains 42 000 labeled gray-scale images of hand-drawn digits, from zero through nine. The testing set is 28 000 unlabeled images.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255.

### Models

* K Nearest Neighbors
* Random Forest
* Support Vector Machines
* Combinations of them

### Results on training set  :bar_chart:

* KNN       -   **0.9669**
* RF          -   **0.8900**
* SVM       -   **0.9771**

### Results on testing set (scored by Kaggle)  :bar_chart:

* RF -> RF+KNN              -   **0.97528**
* RF+RF -> RF+KNN       -   **0.97500**
* RF -> SVM                     -   **0.97242**
* RF -> RF+SVM              -   **0.97200**
* SVM                               -   **0.97357**
* RF+SVM                        -   **0.97285**
* RF -> KNN                     -   **0.97328**

### Ideas for Future Research  :rocket:

* Feature engineering
* Neural Networks
* Team work
* Creative thinking

### Inferences and Isights  :clipboard:

* ML is fun
* VM on AWS or Oracle Cloud is recommended
* Reserve more time for research
* Progress indicators are useful
* Hardware to be upgraded
* Never give up!
