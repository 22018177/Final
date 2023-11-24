# Graduation Design Log
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

## 10.4-10.12
The code for the face recognition section is also largely complete.Preparation of external arduino related things

![2}QA0%@4CI)2)CKCBKM({G1](https://github.com/22018177/Final/assets/117812805/5ec9f154-6d68-48c4-a56d-b6f1aae74e43)

![ZT G { CA JSLH KMGY$G94](https://github.com/22018177/Final/assets/117812805/581be280-52ef-4266-8ddd-29e1a5dc8115)


![4 A$Q0LSW%W2}(OF3@PE(IV](https://github.com/22018177/Final/assets/117812805/b84188f1-6345-4991-bf2d-bda10fac07c2)


![OF GT${O~%V}O7C0XWE0_@L](https://github.com/22018177/Final/assets/117812805/10fca060-f189-40e3-8180-fdcb77f153f5)


![L%AS5I45BZRI2C46PDB T2E](https://github.com/22018177/Final/assets/117812805/cf05bb4a-35d5-4492-af30-7ec93695c2ac)


## 10.13-10.30
Initially, the decision was made to use the emotions "happy," "natural," "sad," "angry," and "surprise" to create relevant output effects. The goal was to convey the facial expressions of the conversation partner to the user through braille. Among these five expressions, excluding "natural," the braille corresponding to the other four expressions is illustrated in the following image（figure 7）. As depicted, I needed to create twelve active positions to achieve the desired braille output effect.

![5CC01DD0B7AEBB67ECFBBA71E9A34C24](https://github.com/22018177/Final/assets/117812805/5c1af180-d65d-4ced-aaaf-6e9fd172d27a)

![140C0DF581DDE6E6535AFD19EBB67F78](https://github.com/22018177/Final/assets/117812805/230b494f-d4cb-48a0-9605-410238507e8e)


![C31C497443BE86E686A8A7E1FB46038A](https://github.com/22018177/Final/assets/117812805/6b6704fd-1c7a-4e8b-a726-356110afc45f)



Creating an effective tactile interface involves a thoughtful selection of internal components to ensure precision and responsiveness. Here's a detailed breakdown of the key elements:

Tactile Modules - Pull-push Solenoids: The backbone of our tactile interface consists of twelve small cylindrical pull-push solenoids. These modules are strategically chosen for their ability to dynamically move tactile points up and down. They play a pivotal role in converting digital signals into tangible, touch-sensitive feedback.

Control Center - Arduino Nano ATmega328P Controller: At the core of our system is the Arduino Nano ATmega328P. This compact yet powerful controller processes input signals, orchestrating the nuanced movements of the solenoids. Its adaptability makes it the ideal control center for managing the intricacies of the tactile interface.

Power Source - Lithium Battery: Ensuring a consistent power supply, a lithium battery takes center stage. This energy source provides the required voltage to keep the system operational, allowing users to interact seamlessly with the tactile interface.

Precision Drivers - L298N Dual-channel DC Motor Driver Boards: Eight L298N dual-channel DC motor driver boards step into the scene to drive the solenoids with precision. These boards play a crucial role in accurately controlling the movement of the tactile points, ensuring a responsive and finely-tuned user interaction.

Voltage Management - Voltage Regulator Modules: Two voltage regulator modules come into play to harmonize the power dynamics. Their role is to adjust the output voltage from the lithium battery, creating an environment conducive to the optimal operation of all system components.

Fundamental Elements - Basic Electronic Components: The intricate dance of components is facilitated by fundamental electronic elements such as circuit boards and copper wires. These elements form the connective tissue of the system, ensuring a seamless flow of signals and power.

With these carefully selected and orchestrated internal components, the design and construction of the circuit diagram (refer to Figure 8) become the blueprint for an interactive tactile interface. The Arduino Nano, acting as the conductor, orchestrates the tactile symphony, turning digital signals into a tangible and interactive experience for users with visual impairments.







![374634791262594966](https://github.com/22018177/Final/assets/117812805/685fe2c9-f4b9-46fe-bbe5-213fb32f9af0)

And shell-related sketches were made.

![42CC1F8AD9671F32DA0148C40FB5AF8A](https://github.com/22018177/Final/assets/117812805/fa19ceec-9556-4aa3-abef-463c09d89c3e)


## 11.1-11.5
 With the selection of components laid out, the next phase involves the meticulous assembly of these elements to create a cohesive and functional tactile interface. The assembly process is a symphony of precision and care, ensuring each part plays its role seamlessly.

Strategic Placement of Solenoids: The heart of the tactile interface lies in the placement of the pull-push solenoids. These components are strategically positioned to achieve optimal tactile feedback. Precision in their arrangement is key to creating a nuanced and effective touch-sensitive surface.

Arduino Integration: The Arduino Nano ATmega328P takes its place, integrated with the solenoids through the L298N dual-channel DC motor driver boards. This integration forms the nerve center of the system, where digital commands are translated into tangible responses.

Battery Power Integration: Careful attention is given to incorporating the lithium battery into the system. The power source is seamlessly integrated, ensuring a stable and reliable energy supply to sustain the tactile interface's continuous operation.

Fine-tuning with L298N Boards: The eight L298N dual-channel DC motor driver boards are delicately tuned to synchronize with the solenoids. This step is crucial for achieving the desired precision in controlling the movement of the tactile points, providing users with a responsive and accurate interaction experience.

Voltage Regulation Refinement: The voltage regulator modules play a vital role in fine-tuning the power dynamics. Their integration ensures that each component receives the optimal voltage, contributing to the overall efficiency and longevity of the tactile interface.

Circuitry and Wiring Choreography: Basic electronic components, such as circuit boards and copper wires, are intricately woven into the assembly process. The choreography of these elements is meticulously planned to facilitate seamless communication and power distribution among all parts.






![169486156369365297](https://github.com/22018177/Final/assets/117812805/a6421737-0492-41c2-a533-dd7793f66a73)



![229248839143572758](https://github.com/22018177/Final/assets/117812805/8de9d7e7-a734-442d-a159-b5dfbbc097d3)

![564356478279552196](https://github.com/22018177/Final/assets/117812805/fb9043c3-2d76-4eab-98c5-ced9959d9ac4)



## 11.6-11.8
Embarking on the modeling phase using SolidWorks, I translated the conceptual sketch into a tangible 3D model. This digital transformation involved merging the lid and body of the box, concurrently securing the lower portions of the interactive buttons. The SolidWorks model, illustrated in Figure 11，12，13 below, captures the essence of the envisioned enclosure.

![3BZ~J5_54}(QTNE4P`TZOD3](https://github.com/22018177/Final/assets/117812805/a9f9aa6f-b706-41ea-9f27-1e39fe93a93a)

![ZJ2`_L92OC6KR5OR5G0T6VY](https://github.com/22018177/Final/assets/117812805/82730f08-8502-41f4-834e-895e0d6ced32)


![{~_G6$DKC@7307K8SQE0}U7](https://github.com/22018177/Final/assets/117812805/145ca707-0170-4d17-a319-afb8f24cc361)

![~NP~@3` (%ZV8FAGQPMLEYQ](https://github.com/22018177/Final/assets/117812805/0744aeea-63ee-46d8-87f0-58be16e8f994)

![W~~Q $MO4% S@E5H}900JTE](https://github.com/22018177/Final/assets/117812805/a44821b1-287b-4308-9abb-d291ad221981)

With the SolidWorks model finalized, the next pivotal step is the realization of the digital design into a physical form through 3D printing. The chosen material, Polyamide, offers a balance of durability and flexibility, aligning seamlessly with the functional requirements of the envisioned enclosure.The utilization of Polyamide in the 3D printing process brings the meticulously crafted SolidWorks model into the physical realm. Layer by layer, the printer deposits Polyamide material, gradually building the enclosure according to the specifications encoded in the digital design. This additive manufacturing approach ensures precision and accuracy in material deposition.Polyamide, known for its robustness and flexibility, lends itself well to the intended functionality of the enclosure. The material's properties provide the necessary structural integrity to protect the internal components while allowing sufficient flexibility for the interactive buttons' responsive movements.

## 11.9-11.12
Tweak the work and keep writing the pap.

The final implementation involves the listener placing their hand on the white box, while the person being observed opens the camera window. Through the camera, the emotions of the observed individual are recognized. The Python script then sends this data to the Arduino, which activates the tactile buttons on the white box to represent the detected emotion. There are five different scenarios:
When the recognized emotion is happy, the results in the window and the status of the white box's buttons are as shown in Figures：

![Uploading 3ADDCAE0C8AE62D0BA42106DE73D5173.png…]()





