
**Abaut MNİST Dataset:**

SD-1 contains 58,527 digit images written by 500 different writers. In contrast to SD-3, where blocks of data from each writer appeared in sequence, the data in SD-1 is scrambled. Writer identities for SD-1 is available and we used 
this information to unscramble the writers. We then split SD-1 in two: characters written by the first 250 writers went into our new training set. The remaining 250 writers were placed in our test set. Thus we had two sets with nearly 30,000
examples each. The new training set was completed with enough examples from SD-3, starting at pattern # 0, to make a full set of 60,000 training patterns. Similarly, the new test set was completed with SD-3 examples starting 
at pattern # 35,000 to make a full set with 60,000 test patterns. Only a subset of 10,000 test images (5,000 from SD-1 and 5,000 from SD-3) is available on this site. The full 60,000 sample training set is available.



**GOAL:**

The project aims to leverage deep learning techniques to recognize and classify handwritten digits, specifically those from 0 to 9. By training a convolutional neural network (CNN) on the MNIST dataset, which contains thousands of labeled images,
the model learns to identify patterns in the handwritten forms. This enables it to accurately predict digits in new images, showcasing the power of artificial intelligence in image recognition tasks


**ALGORİTHM:**

Convolutional Neural Network (CNN)
A Convolutional Neural Network (CNN) is a specialized type of deep learning model designed primarily for processing structured grid data, such as images. CNNs utilize convolutional layers to automatically detect patterns and features in the data,
enabling them to perform tasks like image classification and object detection effectively.

Epoch 1/10
1875/1875 ━━━━━━━━━━━━━━━━━━━━ 8s 4ms/step - accuracy: 0.9132 - loss: 0.2849 - val_accuracy: 0.9852 - val_loss: 0.0456
Epoch 2/10
1875/1875 ━━━━━━━━━━━━━━━━━━━━ 7s 4ms/step - accuracy: 0.9853 - loss: 0.0461 - val_accuracy: 0.9901 - val_loss: 0.0323
Epoch 3/10
1875/1875 ━━━━━━━━━━━━━━━━━━━━ 7s 4ms/step - accuracy: 0.9915 - loss: 0.0276 - val_accuracy: 0.9877 - val_loss: 0.0358
Epoch 4/10
1875/1875 ━━━━━━━━━━━━━━━━━━━━ 8s 4ms/step - accuracy: 0.9938 - loss: 0.0197 - val_accuracy: 0.9903 - val_loss: 0.0293
Epoch 5/10
1875/1875 ━━━━━━━━━━━━━━━━━━━━ 9s 5ms/step - accuracy: 0.9952 - loss: 0.0153 - val_accuracy: 0.9884 - val_loss: 0.0404
Epoch 6/10
1875/1875 ━━━━━━━━━━━━━━━━━━━━ 9s 5ms/step - accuracy: 0.9967 - loss: 0.0116 - val_accuracy: 0.9881 - val_loss: 0.0377
Epoch 7/10
1875/1875 ━━━━━━━━━━━━━━━━━━━━ 9s 5ms/step - accuracy: 0.9971 - loss: 0.0086 - val_accuracy: 0.9877 - val_loss: 0.0460
Epoch 8/10
1875/1875 ━━━━━━━━━━━━━━━━━━━━ 8s 4ms/step - accuracy: 0.9979 - loss: 0.0071 - val_accuracy: 0.9906 - val_loss: 0.0367
Epoch 9/10
1875/1875 ━━━━━━━━━━━━━━━━━━━━ 8s 4ms/step - accuracy: 0.9987 - loss: 0.0047 - val_accuracy: 0.9902 - val_loss: 0.0356
Epoch 10/10
1875/1875 ━━━━━━━━━━━━━━━━━━━━ 7s 4ms/step - accuracy: 0.9987 - loss: 0.0043 - val_accuracy: 0.9905 - val_loss: 0.0408

![Handwritten Digit Recognition](https://github.com/user-attachments/assets/e1c734b0-0425-4388-aa7c-039a75851b7c)


**WHY WE USED CNN IN THIS PROJECT!!!!**

Image Data Handling: CNNs are specifically designed to handle image data efficiently. They can capture spatial hierarchies by learning patterns at different scales, making them ideal for recognizing handwritten digits.

Feature Extraction: The convolutional layers automatically extract relevant features from images, such as edges, shapes, and textures, without requiring manual feature engineering. This leads to improved accuracy in classification tasks.

Translation Invariance: CNNs can recognize digits regardless of their position in the image. This property, known as translation invariance, is crucial for handwritten digit recognition, where variations in writing styles can affect the digit's location.

Parameter Sharing: CNNs reduce the number of parameters through weight sharing in convolutional layers, making the model more efficient and less prone to overfitting, particularly beneficial when working with limited datasets like MNIST.

Proven Success: CNNs have consistently achieved state-of-the-art performance in image classification tasks, including handwritten digit recognition. Their success in similar applications provides a strong foundation for achieving high accuracy in this project.

By utilizing CNNs, we can leverage these advantages to build a robust model for accurately recognizing and classifying handwritten digits from the MNIST dataset.
