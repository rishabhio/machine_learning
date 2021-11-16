### Keras 

```
import tensorflow as tf

# helpers 
import numpy as np
import matplotlib.pyplot as plt

```

### Fashion MNIST 
```
fashion_mnist = tf.keras.datasets.fashion_mnist
(train_images, train_labels), (test_images, test_labels) = fashion_mnist.load_data()
```

- Loading the above dataset returns 4 numpy arrays 
class_names = ['T-shirt/top', 'Trouser', 'Pullover', 'Dress', 'Coat', 'Sandal', 'Shirt', 'Sneaker', 'Bag', 'Ankle boot']


