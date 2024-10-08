# Fall Detection System using LLaVa

## Overview

Falls represent a significant health concern, particularly for elderly individuals. Rapid and accurate fall detection is crucial for minimizing fall-related injuries. This project explores a comprehensive framework that utilizes deep learning and gradient boosting techniques to enhance fall detection accuracy.

## Objectives

- To develop a multi-faceted fall detection system that analyzes both image and sensor data.
- To leverage advanced models, including the Large Language and Vision Assistant (LLaVa), Extreme Gradient Boosting (XGBoost), and Light Gradient Boosting Machine (LGBM), for improved classification accuracy.
- To evaluate and compare the effectiveness of these models on the UP-Fall dataset.

## Methodology

1. **Data Sources:**
   - We utilized the UP-Fall dataset for our experiments, which includes both image data and sensor data relevant to fall detection.

2. **Model Framework:**
   - **Image Data Analysis:** Implemented the fine-tuned LLaVa model to recognize human falls from images, achieving an accuracy of **96.3%**.
   - **Sensor Data Analysis:** Employed XGBoost and LGBM to classify falls based on sensor data, with XGBoost achieving an accuracy of **99.3%** and LGBM achieving **99.1%**.

3. **Comparative Analysis:**
   - Evaluated the effectiveness of sensor-based versus image-based classification methods.
   - Results indicated that sensor data outperforms image data in this specific context, highlighting the importance of informative features captured by sensors.

## Results

- **Sensor-Based Model Accuracy:**
  - XGBoost: **99.3%**
  - LGBM: **99.1%**

- **Image-Based Model Accuracy:**
  - Fine-tuned LLaVa: **96.3%**

## Discussion

The study revealed a significant performance gap between sensor-based and image-based models. Despite the advantages of sensor data in accuracy, practical challenges related to user convenience remain. Further investigation is needed to explore:

- The types of sensors and features they capture.
- Enhancements to the LLaVa model through hyperparameter tuning, data augmentation, or integration of additional sensor data.

A promising future direction involves creating a multimodal learning framework that combines both sensor and image data, aiming for even greater classification accuracy and improved real-world application efficacy.

## Conclusion

This project demonstrates the potential of combining deep learning and gradient boosting techniques for effective fall detection. The results underscore the value of sensor data while also indicating the need for advancements in image-based detection methods. Future work will focus on refining these approaches and exploring multimodal frameworks.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments

Thank you to the contributors, researchers, and institutions involved in the UP-Fall dataset and the development of the models used in this study. Your efforts have been invaluable in advancing fall detection technology.
