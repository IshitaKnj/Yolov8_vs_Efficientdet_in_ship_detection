# Introduction
Autonomous vehicles are becoming more common in various industries, but the use of autonomous maritime vehicles is still being studied. This is because controlling these vehicles requires making important decisions about design, propulsion, payload management, and communication systems, which can lead to errors and collisions. One major challenge is detecting other ships and objects in real-time to avoid collisions. Recently, deep learning techniques based on convolutional neural networks (CNNs) have been developed to help with this, such as YOLOv8 and EfficientDet. This paper examines how these methods can be used to detect ships. We trained and tested these two models on a large maritime dataset. On examining the performance of the two models we have compared the working of both.

# Motivation
- AMVs revolutionize waterway technology with AI, sensors, and autonomy.

- Growing demand for offshore exploration and surveillance fuels AMV usage.

- AMVs offer safety, cost, and efficiency advantages over traditional vessels.

- Applications of AMVs include research, monitoring, security, and more.

- Object detection remains a challenge for AMVs, especially in maritime settings.

- Deep learning techniques like CNNs improve object detection accuracy and speed.

- YOLOv8 and EfficientDet offer enhanced accuracy, reduced complexity, scalability, robustness, and generalization for ship detection.

# Literature Review:
Research on AMVs is ongoing and focuses on enabling autonomous vessels to operate in different marine environments, perform various tasks, and serve different applications.

Recent studies have explored AMV applications in oceanographic research, environmental monitoring, marine transportation, and defense. 

The current research aims to improve reliability, safety, and energy efficiency of AMVs, while developing new sensor technologies and data processing methods to enhance performance and functionality.

# Research Gaps:
- Improved accuracy in challenging maritime environments.
- Real-time operation on autonomous vehicles.
- Generalizability to different object types.
- Robustness to changes in lighting and background.
- Integration of sensor fusion techniques.
- Enhanced detection of small and distant objects.
- Evaluation of algorithms in real-world maritime scenarios.
- Consideration of regulatory and ethical aspects.

  # Objectives:
- To evaluate the performance of two state-of-the-art deep learning algorithms, YOLOv8 and EfficientDet, for object detection in autonomous maritime vehicles
-  To compare the performance of these algorithms on a real-world dataset of maritime objects and evaluate their accuracy, computational efficiency, and generalizability

  # Results:
A Python script specifying the thresholds, network paths and images to recognize wass used to test the new model. 
Our trained model correctly recognises the item (ship) in images and videos
The model was able to recognise the item not only in photos, but also in real time/inputted videos.

## Ship Detection in Video
https://github.com/IshitaKnj/Yolov8_ship_detection/assets/71023544/2e8bf966-a47b-4eaa-a974-f9e5ea7ed42c

## Ship Detection in Images

<img src="https://github.com/IshitaKnj/Yolov8_ship_detection/assets/71023544/d3c2b0c2-1f94-415c-934e-6a925b49c796" height = "500" width="500">
<img src="https://github.com/IshitaKnj/Yolov8_ship_detection/assets/71023544/a68eb43c-f391-4809-b046-e57bde65f705" height = "500" width="500">

## Final Result of our research:

![image](https://github.com/IshitaKnj/Yolov8_vs_Efficientdet_in_ship_detection/assets/70091050/c121d269-8517-4631-a031-50fdd8773557)
### Datasets used :
- Singapore Maritime Dataset for Testing the model
- Roboflow Ship2 Image Dataset for Training the model
  
# References:
[1] Prasad, D.K., Rajan, D., Rachmawati, L., Rajabally, E. and Quek, C., 2017. Video processing from electro-optical sensors for object detection and tracking in a maritime environment: A survey. IEEE Transactions on Intelligent Transportation Sys- tems, 18(8), pp.1993-2016.

[2] Kim, T.E., Perera, L.P., Sollid, M.P., Batalden, B.M. and Sydnes, A.K., 2022. Safety challenges related to autonomous ships in mixed navigational environments. WMU Journal of Maritime Affairs, 21(2), pp.141-159.

[3] Shao, Z., Lyu, H., Yin, Y., Cheng, T., Gao, X., Zhang, W., Jing, Q., Zhao, Y. and Zhang, L., 2022. Multi-Scale Object Detection Model for Autonomous Ship Navigation in Maritime Environment. Journal of Marine Science and Engineering, 10(11), p.1783.

[4] Chang, Y.L., Anagaw, A., Chang, L., Wang, Y.C., Hsiao, C.Y. and Lee, W.H., 2019. Ship detection based on YOLOv2 for SAR imagery. Remote Sensing, 11(7), p.786.

[5] Munteanu, D., Moina, D., Zamfir, C.G., Petrea, S, M., Cristea, D.S. and Munteanu, N., 2022. Sea Mine Detection Framework Using YOLO, SSD and EfficientDet Deep Learning Models. Sensors, 22(23), p.9536.

[6] Redmon, J., Divvala, S., Girshick, R. and Farhadi, A., 2016. You only look once: Unified, real-time object detection. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 779-788).

[7] smart helmet, Ship2 Dataset


