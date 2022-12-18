# Dog Breed classification kaggle problem

In this project we're going to be using machine learning to help us identify different breeds of dogs.

To do this, we'll be using data from the [Kaggle dog breed identification competition](https://www.kaggle.com/competitions/dog-breed-identification/overview)
It consists of a collection of 10,000+ labelled images of 120 different dog breeds.

This kind of problem is called multi-class image classification. It's multi-class because we're trying to classify mutliple different breeds of dog. If we were only trying to classify dogs versus cats, it would be called binary classification (one thing versus another).

Multi-class image classification is an important problem because it's the same kind of technology Tesla uses in their self-driving cars or Airbnb uses in atuomatically adding information to their listings.

## Workflow
Since the most important step in a deep learng problem is getting the data ready (turning it into numbers), that's what we're going to start with.

We're going to go through the following TensorFlow/Deep Learning workflow:

* Get data ready (download from Kaggle, store, import).
* Prepare the data
* Choose and fit/train a model (TensorFlow Hub, tf.keras.applications, TensorBoard, EarlyStopping).
* Evaluating a model (making predictions, comparing them with the ground truth labels).
* Improve the model through experimentation (start with 1000 images, make sure it works, increase the number of images).
* Save, sharing and reloading your model and are available in the `Dog Vison/models`


