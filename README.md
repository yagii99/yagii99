## Hi, I'm Ali 👋

Software engineer based in Marseille, working between **computer vision / AI** and **real-time software** (C#, C++, Unreal, Unity).
Engineering degree in computer science & telecoms (Université Libanaise) and a Master 2 in Mechatronics, Machine Vision & AI (Université Paris-Saclay).

- 📷 Computer vision: OpenCV, YOLO, pose estimation, anomaly detection, ONNX Runtime
- 🥽 XR & 3D: Unreal Engine 5, Unity, OpenXR
- 🛠 Languages: C#, C++, Python
- 📍 Marseille, France. Open to computer vision / industrial vision roles

<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" height="28" /> <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" height="28" /> <img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white" height="28" /> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" height="28" /> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" height="28" /> <img src="https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white" height="28" /> <img src="https://img.shields.io/badge/Unreal_Engine-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white" height="28" /> <img src="https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white" height="28" /> <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" height="28" />

## Projects

### 🔩 [Steel surface inspection](https://github.com/yagii99/inspection-acier-vision): from the camera to the model in production
End-to-end visual inspection pipeline for steel sheets, as a personal project:
- camera acquisition in C# with the Basler pylon SDK (emulator): triggering, producer / consumer queue, automatic reconnection;
- classical image processing with OpenCV (illumination correction, robust thresholding, morphology, FFT), in Python and C#;
- YOLO26n defect detector trained on the public NEU-DET dataset: **mAP@0.5 = 0.74** on the test set, with error analysis;
- ONNX Runtime integration in a C# / WPF operator app, results checked against Python.

<img src="https://raw.githubusercontent.com/yagii99/inspection-acier-vision/main/docs/images/02_inspection_classique_csharp.png" width="600" />

### 🏔 [3D terrain reconstruction](https://github.com/yagii99/terrain-3d-reconstruction)
Estimating the 3D shape of a terrain or an object from a video, using Structure from Motion.

<img src="https://github.com/yagii99/terrain-3d-reconstruction/blob/main/Assets/reconstruction.gif" width="600" />

### 🍲 [Foodbook](https://github.com/yagii99/foodbook)
Flutter app to share recipes and track daily calorie needs.

### 🎮 [GameLounge management system](https://github.com/yagii99/GameLounge-management-system)
C# desktop software with a MySQL database to manage a gaming lounge.

## Experience

- **Azoo Experience**, Marseille: computer vision software (OpenCV, YOLOv8, pose estimation) driving a real-time Unreal Engine 5 application, deployed and validated on site
- **TechViz**: C++ development of a multi-platform virtual reality software used by industrial clients from many sectors
- **Atos**: C# development of VR training simulators for Sanofi
- **Moondev**, Beirut: C++ development with machine learning components

Fun fact: I love cooking, and shawarma is still my favourite dish 🌯
