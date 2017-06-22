# Arabic Handwritten Characters Dataset

### Astract
Handwritten Arabic character recognition systems face several challenges, including the unlimited variation in human handwriting and large public databases. In this work, we model a deep learning architecture that can be effectively apply to recognizing Arabic handwritten characters. A Convolutional Neural Network (CNN) is a special type of feed-forward multilayer trained in supervised mode. The CNN trained and tested our database that contain 16800 of handwritten Arabic characters. In this paper, the optimization methods implemented to increase the performance of CNN. Common machine learning methods usually apply a combination of feature extractor and trainable classifier. The use of CNN leads to significant improvements across different machine-learning classification algorithms. Our proposed CNN is giving an average 5.1% misclassification error on testing data.

### Context

The motivation of this study is to use cross knowledge learned from multiple works to enhancement the performance of Arabic handwritten character recognition. In recent years, Arabic handwritten characters recognition with different handwriting styles as well, making it important to find and work on a new and advanced solution for handwriting recognition. A deep learning systems needs a huge number of data (images) to be able to make a good decisions.

### Content

The data-set is composed of **16,800** characters written by 60 participants, the age range is between 19 to 40 years, and 90% of participants are right-hand. Each participant wrote each character (from ’alef’ to ’yeh’) ten times on two forms as shown in Fig. 7(a) & 7(b). The forms were scanned at the resolution of 300 dpi. Each block is segmented automatically using Matlab 2016a to determining the coordinates for each block. The database is partitioned into two sets: a training set (13,440 characters to 480 images per class) and a test set (3,360 characters to 120 images per class). Writers of training set and test set are exclusive. Ordering of including writers to test set are randomized to make sure that writers of test set are not from a single institution (to ensure variability of the test set).

In an experimental section we showed that the results were promising with **94.9%** classification accuracy rate on testing images. In future work, we plan to work on improving the performance of handwritten Arabic character recognition.


### Acknowledgements

Ahmed El-Sawy, **Mohamed Loey**, Hazem EL-Bakry, **Arabic Handwritten Characters Recognition using Convolutional Neural Network**, WSEAS, 2017
Our proposed CNN is giving an average **5.1%** misclassification error on testing data.


### Inspiration

Creating the proposed database presents more challenges because it deals with many issues such as style of writing, thickness, dots number and position. Some characters have different shapes while written in the same position. For example the teh character has different shapes in isolated position.
