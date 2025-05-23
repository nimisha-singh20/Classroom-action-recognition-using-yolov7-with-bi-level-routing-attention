In this work, a new student action recognition system with YOLOv7 and Bi-Level Routing Attention (BRA) is introduced to accurately identify different student activities such as hand-raising, reading, writing, discussing, listening, turning head, teaching and standing through attention mechanism-based improved feature extraction. A set of annotated classroom photos is employed to train and test the model with better accuracy and resilience in dense classroom scenes. The experimental results confirm that YOLOv7-BRA performs superior to some traditional models with higher mean average precision (mAP) of 0.92 and superior occluded action detection. The proposed approach presents a trustworthy basis for smart classroom monitoring and automatic educational evaluations.

![image](https://github.com/user-attachments/assets/924ce684-42c9-484c-8702-940645d7bc94)
Dataset having dense environment

![image](https://github.com/user-attachments/assets/d29ef619-9ada-42ef-9676-5ecd95830f7c)
Dataset having same actions

![image](https://github.com/user-attachments/assets/d0106bcc-c4cc-46cd-b533-13cc4d5aa5bc)
Dataset having different actions

![image](https://github.com/user-attachments/assets/12d301e8-ca1c-45ee-aca8-3a3eddbddb8b)
Graph for mean average precision

![image](https://github.com/user-attachments/assets/591f3b9b-6f61-48f7-8576-090bf3a0d8a9)
![image](https://github.com/user-attachments/assets/6402fd92-8cb4-4f64-a74f-0c6e2cf9c095)
Action detected accurately in dense environment


Methodology:
This action recognition system in the classroom is based on an enhanced YOLOv7 model with Bi-Level Routing Attention (BRA) for better detection accuracy in dense and dynamic classroom environments. The dataset is structured into individual folders and a data.yaml file specifies the class names and paths. For supporting the custom attention mechanism, required files such as biformer.py, common.py, and yolo.py are included and modified. Pre-trained YOLOv7 weights are employed and the model is subsequently trained for 15 epochs with a batch size of 16. Once trained, the best-performing model is utilized to identify actions on validation and training images. The results are visualized, and performance metrics like mAP, precision, and recall are gathered to analyze how well the system identifies actions.
