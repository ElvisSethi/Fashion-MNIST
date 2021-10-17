# Fashion_MNIST
<h2>Overview</h2>
<p>
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. We intend Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

Here's an example of how the data looks (each class takes three-rows):

![ml](https://www.researchgate.net/profile/Greeshma-K-V/publication/340299295/figure/fig1/AS:875121904476163@1585656729996/Fashion-MNIST-Dataset-Images-with-Labels-and-Description-II-LITERATURE-REVIEW-In-image.jpg)
</p>
<p>
<b>Project Link Online Deployed on Heroku : <a href="https://fashion-mnist-elvis.herokuapp.com">https://fashion-mnist-elvis.herokuapp.com</a></b>
</p>
<hr>
<h2>Dataset and Libraries</h2>
<p>
<b>Dataset : <a href="https://www.researchgate.net/profile/Greeshma-K-V/publication/340299295/figure/fig1/AS:875121904476163@1585656729996/Fashion-MNIST-Dataset-Images-with-Labels-and-Description-II-LITERATURE-REVIEW-In-image.jpg">https://www.researchgate.net/profile/Greeshma-K-V/publication/340299295/figure/fig1/AS:875121904476163@1585656729996/Fashion-MNIST-Dataset-Images-with-Labels-and-Description-II-LITERATURE-REVIEW-In-image.jpg</a></b><br>
<b>Libraries : </b>Python , Numpy , Pandas, Sklearn , Node.js , Tensorflow.<br>
<b>Frameworks : </b>VScode , jupyter Notebook , Heroku.<br>
</p>
<hr>
<h2>Project Methodology</h2>
<p>
In this project I have developed a machine learning model to predict the fashion item in the image and classify it into different given types . The steps used in developing the machine learning model are of the one that are used in CNN.<br><hr>
<b>Below is brief description of every step and technique used for CNN based Classification:</b><br>
In the training phase, preprocessing, feature exaction and classification with Loss function is performed to make a prediction model. Initially, label the training image set. In the preprocessing image resizing is applied to change size of the image.<br>
I split my entire dataset of 70,000 images of different apparels into training, validation and test set in 80%, 10%, 10% respectively and also I set Load Dataset in Memory to “Full dataset” and then Convolutional Neural Network was created. After tuning the Hyperparameter, I started training my Model and after training my CNN Model the predictions were made with high accuracy.<br>  
</p>
<hr>
<h2>Screenshots of the working Webapp</h2>
<b><p>Initial Page.</p></b>
<img src="img/the1.png">
<b><p>After uploading the MRI scan.</p></b>
<img src="img/the2.png">
<b><p>Getting the required result after classification.</p></b>
<img src="img/the3.png">
<hr>
<h2>Running the Project</h2>
<p><b>1. Accesing the website online </b></p>
  <p> To access the website and check its working you can visit this link <a href="https://fashion-mnist-elvis.herokuapp.com">https://fashion-mnist-elvis.herokuapp.com</a> <br>
 <p><b>2. Copying to local repository </b></p>
  <p> In your terminal run the following commands : <br><br>
     <b>
     git clone https://git.heroku.com/fashion-mnist-elvis.git<br>
     cd fashion-mnist-elvis<br>
     python app.py<br>
     Open https://localhost:3000 <br>
     </b>
  </p>
 <hr>
 <h2>Methodology</h2>
 <img src="img/the4.png">
 <hr>
 <h2>Contributors</h2>
 <p><a href="https://github.com/ElvisSethi">Elvis Sethi</a></p>
 <hr>

