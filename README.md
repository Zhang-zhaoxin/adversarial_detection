# adversarial_detection
TensorFlow provides implementations of object detection algorithms and pre-trained models. We used this framework to implement the adversarial example detection method for the Faster R-CNN object detection network.

First, synchronize the TensorFlow model repository by running the following command:

```bash
git clone https://github.com/tensorflow/models.git
```

Next, copy the adversarial example generation and detection method code `object_detection_adversarial_detection` to the `models/research/object_detection` directory and run it from there.
