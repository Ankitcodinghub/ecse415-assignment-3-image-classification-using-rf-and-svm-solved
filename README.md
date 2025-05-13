# ecse415-assignment-3-image-classification-using-rf-and-svm-solved
**TO GET THIS SOLUTION VISIT:** [ECSE415 Assignment 3-Image Classification using RF and SVM Solved](https://www.ankitcodinghub.com/product/ecse415-assignment-3-image-classification-using-rf-and-svm-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92532&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECSE415 Assignment 3-Image Classification using RF and SVM Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1 Image Classification using RF and SVM

For this task, you are given a dataset of flower images1. The dataset contains images of 9 types of flowers. You can read the images and the corresponding labels as follows.

1The dataset is derived from the 102-Category Flower dataset[1]. 1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
train images = np.load(‘flower subset.npz’)[‘train images’] train labels = np.load(‘flower subset.npz’)[‘train labels’] test images = np.load(‘flower subset.npz’)[‘test images’] test labels = np.load(‘flower subset.npz’)[‘test labels’]

The arrays train images and test images are stacks of 1556 and 90 gray- scale images of size 128×128, respectively.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
<div class="layoutArea">
<div class="column">
•

•

• • •

• • •

</div>
<div class="column">
Resize the train/test images to 64 × 64 and compute HoG features using cells of 8×8 pixels, blocks of 4×4 cells and 4 bins. This should yeild a feature vector of size 1600 per image. (3 points)

(Suggestion: Make a function which takes list of images as arguments and delivers list of HoG features as output. The same function can be used for train and test set.)

Fit a non-linear SVM classifier (use RBF kernel with gamma=‘auto’ and C=1) on the features and the class labels of the training images. (1 points)

Predict labels of the test images by feeding the test features to the trained classifier and calculate classification accuracy. (2 points)

Tune values of hyperparameters ‘gamma’ and ‘C’ to achieve test accuracy greater than 25%. (2 points)

Fit a Random Forest(RF) classifier (set n estimators=10, max depth=5 and criterion=‘entropy’) on the features and the class labels of the training images. (1 points)

Predict labels of the test images by feeding the test features to the trained classifier and calculate classification accuracy. (2 points)

Tune values of hyperparameters ‘n estimators’ and ‘max depth’ to achieve test accuracy greater than 25%. (2 points)

Compare results of SVM and RF classifiers. Which one provides better results? Experiment training both classifiers with a range of random stats and measure classification accuracy of the test set. Which classifier is more stable or robust to the change in random state? (3 points)

Image Classification with Convolution Neural Network (CNN).

</div>
</div>
<div class="layoutArea">
<div class="column">
In this part, you will classify MNIST digits [2] into 10 categories using a CNN. You may chose to run the code on GPU.

1. UsePytorchclasstorchvision.datasets.MNISTto(down)loadthedataset. Use batch size of 32. (3 points)

2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
2. Implement a CNN with the layers mentioned below. (5 points)

<ul>
<li>A convolution layer with 32 kernels of size 3×3.</li>
<li>A ReLU activation.</li>
<li>A convolution layer with 64 kernels of size 3×3.</li>
<li>A ReLU activation.</li>
<li>A maxpool layer with kernels of size 2×2.</li>
<li>A convolution layer with 64 kernels of size 3×3.</li>
<li>A ReLU activation.</li>
<li>A convolution layer with 64 kernels of size 3×3.</li>
<li>A ReLU activation.</li>
<li>A flattening layer. (This layer resizes 2D feature map to a feature vector. The length of this feature vector should be 4096.)</li>
<li>A Linear layer with output size of 10.

(Suggestion: you can start with the code from Tutorial 6 and adapt it forthe current problem.)</li>
</ul>
<ol start="3">
<li>Create an instance of SGD optimizer with learning rate of 0.001. Use the default setting for rest of the hyperparameters. Create an instance of categorical cross entropy criterion. (1 point)</li>
<li>Train the CNN for 10 epochs. (5 points)</li>
<li>Predicts labels of the test images using the above trained CNN. Measureand display classification accuracy. (3 points)</li>
</ol>
References

<ol>
<li>[1] &nbsp;Nilsback, Maria-Elena, and Andrew Zisserman. ”Automated flower classi- fication over a large number of classes.” 2008 Sixth Indian Conference on Computer Vision, Graphics &amp; Image Processing. IEEE, 2008.</li>
<li>[2] &nbsp;Y. LeCun, L. Bottou, Y. Bengio, and P. Haffner. ”Gradient-based learning applied to document recognition.” Proceedings of the IEEE, 86(11):2278- 2324, November 1998.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
