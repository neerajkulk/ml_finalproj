# ml_finalproj

This repository contains the code for our final project for CSCI 5622. We primarily used jupyter notebooks and generally each worked in separate files to keep our code organized. The author of the file is noted in the filename. Each of us worked on both a baseline and machine learning approach. The baselines that we used are summarized below:
* Random Selection: This method is fairly self explanatory. As you might imagine, it is not a very good classification method. However, it did show the improvement of other classification methods. The random baseline is shown in `Neil_baseline.ipynb`
* K-Nearest Neighbors (KNN): We tried using a KNN approach within the space of the lightcurves. This model is implemented in `neeraj_baseline.ipynb`.

The machine learning approches that we used were:
* Convolutional Neural Network (CNN): We found this to be the most effective classification method. We used as inputs to the CNN the lightcurves in the 6 different passbands, which were stacked to create image-like objects. The implementation of our CNN is in `Neil_CNN.ipynb`.
* Long Short Term Memory (LSTM): In addition to the CNN we also investigated using an LSTM layer in our network. We found that this did not significantly increase the performance compared to the CNN. This method is implemented in `CNN_LSTM.ipynb`. 
* Support Vector Machine (SVM): Instead of using the lightcurves, we also explored using only the "metadata" which contains information such as location on the sky and distance. This method is implemented in `Abdul_SVM.ipynb`.
