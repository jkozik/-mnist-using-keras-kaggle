# MNIST using keras
Downloaded from the [Kaggle](https://kaggle.com) article [MNIST using keras](https://www.kaggle.com/code/adhoppin/mnist-using-keras).

It worked with the MNIST dataset using Keras.  It worked well until line 61.  The visualize function uses the Keras backend learning_phase() function wasn't configured right.  Perhaps it works in TF and not Keras?  Perhaps I need to downgrade to an earlier version of Keras?

# -mnist-using-keras-kaggle
