# ComputerVision
## **DenseNet:**

Implemented DenseNet architecture in keras. Achieved ~89%
accuracy total 50 epochs.

Used data augmentation & Transfer learning.

Trained model for initial 18 epochs on 16x16 scaled down
image, which help CNN to extract basic features quickly initially. For remaining
32 epochs, trained model on original image 32x32.

(Project was exercise part of my Internship )

 
**RetinaNet:**

Implemented focal loss paper (RetinaNet) in Keras. RetinaNet
is state of art algorithm for object detector. Focal loss resolve class
imbalance problem for one-stage object detector. 

I have trained model only for 4-5 epochs as of now, because each
epoch taking 1.5-2hrs. But as you see in below image, loss is decreasing every
epoch & code functionally correct  

Also I discussed my approach in Approach-RetinaNet.pdf


## **DulicateDetection: **

Develop code which detect duplicate product listed on E-commerce
 website based on image similarity. Code
also used other attributes like brand, sleeveless type to reduce code
complexity(O(N)) from N*N to ~25N. Dataset contain 2M+ products detail. 

I was successfully able to detect duplicated. I have discussed
my results in Approach-DuplicateDetection.pdf

Also I discussed my approach in Approach-DulicateDetection.pdf
