# tf.data Deep Learning Workflow
The project's goal was exploiting TensorFlow's data manipulation features for the creation of a DL Pipeline focused on digit recognition. It began with the raw data importing and its proper partition in training, validation and testing sets in .tfrecord's files.

Following the protobuf's reading and parsing, two Neural Networks were fit on the training data and evaluated. They were a LeNet-5 and a Fully Connected model, the latter with 5 hidden layers using ELU that were trained with the Dropout technique.

In the end, we conducted a Hypothesis Test in order to statistically compare the algorithms' accuracies. Although no discrepancy was found out, LeNet-5 still proved to be more suitable for deployment matters for having way less parameters than the FCNN.
