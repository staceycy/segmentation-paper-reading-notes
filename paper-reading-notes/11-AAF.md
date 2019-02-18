### The progress of the reading plan: 
11 / 50

## Paper Information
#### Paper Title : 
[Adaptive Affinity Fields for Semantic Segmentation](http://openaccess.thecvf.com/content_ECCV_2018/papers/Jyh-Jing_Hwang_Adaptive_Affinity_Field_ECCV_2018_paper.pdf) 

#### Conference : 
ECCV 2018

#### Authors and Institutions
##### Authors
+ Tsung-Wei Ke
+ Jyh-Jing Hwang
+ Ziwei Liu
+ Stella X. Yu

##### Institutions
UC Berkeley / ICSI

#### Official Codes
[https://github.com/twke18/Adaptive_Affinity_Fields](https://github.com/twke18/Adaptive_Affinity_Fields)

#### Some articles to comprehend this paper
[ECCV18 | UC伯克利提出基于自适应相似场的语义分割](https://mp.weixin.qq.com/s/A6g-WFwuXB-4bX9xg3O9NQ)

#### Network Structure

<div  align="center">    
<img src="https://raw.githubusercontent.com/zhixuanli/segmentation-paper-reading-notes/master/images-folder/11-AAF/01.png" width="80%" height="80%" />
</div>

## Note



### Key Words



## Five questions about this paper:

### 1. [Problem Definition / Motivation] What problem is this paper trying to solve? 
There have been two main lines of efforts at incorporating structural reasoning into semantic segmentation: CRF and GAN.

CRF enforces label consistency between pixels measured by the similiarity in visual appearance, but it's time-consuming and sensitive to visual appearance changes.

GAN makes the predicted label map tested by a discriminator network on whether it resembles ground truth label maps in the training set. But it's very hard to train, particularly proning to model instability and mode collapses.

<div  align="center">    
<img src="https://raw.githubusercontent.com/zhixuanli/segmentation-paper-reading-notes/master/images-folder/11-AAF/02.png" width="80%" height="80%" />
</div>

To solve the problem of sensitive to visual appearance changes and hard to training, AAF is proposed.
### 2. [Contribution / Method] What's new in this paper? / How does this paper solve the above problems?
AAF is proposed to capture and match the semantic relations between neighbouring pixels in the label space.


### 3. Details about the experiment

#### 3.1 Which Datasets are used?



#### 3.2 How is the experiment set up?



#### 3.3 What's the evaluation metric?



#### 3.4 (Optional）How to divide training data and test data？



#### 3.5 (Optional）What is the ranking of the experiment results?



### 4. Advantages (self-summary rather than the author's)



### 5. Disadvantages (self-summary rather than the author's)