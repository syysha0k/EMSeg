# Lightweight Road Image Segmentation Algorithm Based on Multi-scale Feature Fusion

Image segmentation is a crucial technology for environmental perception, widely used in various scenarios such as autonomous driving and virtual reality. With the rapid development of technology, the computer vision-based blind guide system is gaining popularity, and it outperforms traditional solutions in terms of accuracy and stability. The semantic segmentation of the road is an essential component of the visual guide system. By analyzing the output of the sensors, the guide system can understand the current environment and help blind people navigate safely, which helps them avoid obstacles and move efficiently. The visual guide system is often used in complex environments, which requires high model efficiency and segmentation accuracy. However, the commonly used high-precision semantic segmentation algorithms are unsuitable for the blind guiding system due to their slow inference speed and large model parameters. To solve this problem, this paper proposed an efficient road image segmentation algorithm based on multi-scale features. Unlike the existing methods, the introduced model contains two feature extraction branches, namely the Detail Branch and the Semantic Branch. The Detail Branch extracts low-level detail information from the image, while the Semantic Branch extracts high-level semantic information. Then, these extracted multi-scale features from each branch are also fused, which can further improve the model's performance. In addition, we designed a simple and efficient feature fusion module to enhance the model's ability to encode contextual information by fusing multi-scale features. We collected and labeled a large amount of road segmentation data suitable for blind-guiding scenarios and made a corresponding data set. We conduct extensive experiments on the proposed dataset. The experimental results show that the mIoU of the proposed method is 96.5%, which is better than the existing complex models. Our method can achieve 201FPS on Nvidia GTX 3090Ti faster than the existing lightweight segmentation approaches. The model can be deployed on the Nvidia AGX Xavier to obtain 53FPS, which can meet the needs of the visual guide system.
