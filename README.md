# Graduation Design
## Authorname
Jiaxin Liang
## Student ID
22018177
## Supervisor
Jasper Zheng
## Creative Computing Institute
Creative Computing
# Work Record Log
## 6.18
Conduct an online meeting to get a rough idea of what needs to be done for the final project, receive the assignment and start researching machine learning related content and conceptualise what you want to do.
## 6.19-6.21
As a result of the research, machine learning has achieved remarkable results in many areas. Just for example:

1. Amazon SageMaker: this is a platform that makes it easy to build machine learning models and get them ready for training. It provides the links needed to quickly connect to training data. (https://aws.amazon.com/sagemaker/)
2. supervised learning: e.g. logistic regression, which is a method of training models based on input data and corresponding labelled paired output data. Labelling is usually done manually. (https://en.wikipedia.org/wiki/Supervised_learning)
3. Machine Learning Services in RDS MySQL instances: The model training process pulls data from RDS MySQL instances for machine learning model training and prediction. (https://help.aliyun.com/document_detail/146503.html)

## 6.25
Three directions were initially established after research:
1. Related to object recognition, tend to do a certain aspect of the needs of people with disabilities to meet
2. Environment recognition, tend to do ski navigation or extreme sports to observe the site environment in advance.
3. Drawing-related aids
   
## 6.28
Decided to go in an object recognition related direction, but haven't thought about exactly what I'm going to do, probably make a kitchen aid.

## 7.3
Models and related training examples on object recognition were found
1.open source case : target object detection and recognition (openCV self-study record sharing tips)
（https://www.bilibili.com/video/BV1Tb4y1W715/?spm_id_from=333.999.0.0&vd_source=d180e55fe9ecc7e2f2261ffa9ff670ad）
2.Simple Open-Vocabulary Object Detection
with Vision Transformers
（https://arxiv.org/pdf/2205.06230.pdf）
3.Grounded Language-Image Pre-training
（https://arxiv.org/pdf/2112.03857.pdf）

## 7.5-8.2
Make preparations, find the right tools as well as directions for making them, and browse for things of interest.

## 8.3
Trying to use some models for object recognition

![A31BEAC8B42E8095CF7D63CA5C3B8F63](https://github.com/22018177/Final/assets/117812805/b20e4dfe-cff3-441a-9508-e14e9daec479)

There seems to be a problem with the computer configuration environment, dealing with the problem.
## 8.5-8.9
Another attempt at a model using jupyter notebook.

![25925E11A02EF9AD6CF1314ACEEBB723](https://github.com/22018177/Final/assets/117812805/e62d9fcb-20fa-4507-bc7b-723811dbfff2)

![B803282EBD01DA142094EB93D6B11C60](https://github.com/22018177/Final/assets/117812805/8e77fddb-cd44-458b-8308-a06b869d4215)

![D6505A01713BCD4EAF0F254F349A4CF5](https://github.com/22018177/Final/assets/117812805/986bd4bf-5ccc-4f3a-8a2b-59871b7615f1)

Tomatoes and mushrooms were identified, but not very correctly.

## 8.11
Decide to produce work that serves people with disabilities and conduct relevant research.
## 8.12
There are already a number of products that use machine learning to serve the visually impaired, such as speech recognition and speech synthesis, as well as image recognition technology to help visually impaired people identify their surroundings and objects, and the use of machine learning to provide personalised mobile phone interfaces, such as enlarged fonts or whatever, to help make life better for people with impairments.
## 8.13
It was decided to create something that would allow invisible people to "see" the expressions of the people they were talking to, and to let the products of machine learning become their eyes.
## 8.15-8.21
I discussed with relatives and friends what to do, and the general direction was determined to be face recognition and arduino external connection.

## 8.22-8.28
It was decided to use CNN to try to reach face recognition by training the dataset, using the fer-2013 dataset

![O`7VN$@_P~$Y1)VU2YC }2F](https://github.com/22018177/Final/assets/117812805/db41c88b-a863-4b60-83f8-502e6a24b237)

## 9.1
On the initial run, most of the expressions recognised were sad, whether they were shown to be angry or happy or in their usual state, they were all judged to be sad.

![5D1DE46A648769198A8E2B8BCDAE4B19](https://github.com/22018177/Final/assets/117812805/e1dd7f4d-a8dc-4f10-a007-a5cd7c86511a)


![74BEA3900C622B686F93169E7D2DF056](https://github.com/22018177/Final/assets/117812805/8b2745c2-5639-4e3c-a73a-1981a215be05)

![3F7358CECFE48BFBEF6BEEDBF115132B](https://github.com/22018177/Final/assets/117812805/d2efc437-df49-4d7a-b991-50fae96516f5)

## 9.2-9.20
Attempts were made to improve the model accuracy using a variety of approaches, trying to select a suitable architecture for the portrait recognition task, fine-tuning the data, trying to adjust the thresholds to optimise the loss function, etc., and making adjustments and optimisations in many ways.
A lot of problems have arisen, bugs have been created, and tweaks have been made many times during this period.
There's a small improvement in portrait recognition accuracy, with more pairs of images becoming available.

![040E78EB5D6FFC73AFE429E1C7930014](https://github.com/22018177/Final/assets/117812805/9f05b0b2-a4f9-4375-a4df-e6d88081d401)


![BE8CF1A094B8A83C5BA522EF22953E57](https://github.com/22018177/Final/assets/117812805/d47b0fc5-f507-44ac-92bb-48e1bf891c2a)

## 9.21-10.3
Adjusting the dataset, as I suspected that the original dataset had a majority of Western faces within it and was unable to accurately recognise Asian faces, I decided to add sample data to it and train the model again.

![43D4AC35227487070238C342FD1934D5](https://github.com/22018177/Final/assets/117812805/14af73c4-480a-4c03-b560-64258073c43d)


![F82AC8B3AB36AF10540C9A157D7C17B2](https://github.com/22018177/Final/assets/117812805/80c0d5ba-8472-4c8d-9202-abd8297abaec)


![FA6B0CC46F664BDEE6BC891134B3480F](https://github.com/22018177/Final/assets/117812805/3d5461db-dd5b-40ae-b622-3bc9389e3dc4)







