<div align="center">
   <h1> Face Recognition LivenessDetection C++ SDK </h1>
   <img src=https://miniai.live/wp-content/uploads/2024/02/logo_name-1-768x426-1.png alt="MiniAiLive Logo"
   width="300">
</div>

## Welcome to the [MiniAiLive](https://www.miniai.live/)!
This repository contains a C++ application that demonstrates face recognition capabilities using computer vision techniques. The demo utilizes OpenCV and dlib libraries for efficient face detection and recognition with 3D passive face liveness detection (face anti-spoofing).

![demo](https://github.com/MiniAiLive/MiniAIFaceSDK/assets/136824647/0859737c-d79e-440f-a400-5aa9097ed818)
### Key Features
 - ### [Face detection](https://demo.miniai.live/): 
    ![face_detect](https://github.com/MiniAiLive/MiniAIFaceSDK/assets/136824647/61f02463-09e9-4efa-b904-6f2f453d95d5)

    The SDK utilizes advanced computer vision techniques to detect faces in images or video frames, enabling a wide range of applications. 
 - ### [Face recognition](https://demo.miniai.live/):
 ![face_compare](https://github.com/MiniAiLive/MiniAIFaceSDK/assets/136824647/29fcd277-f850-4b83-a5da-dc63fb5f0af7)

    It can recognize known faces by comparing them with a pre-defined database of individuals.
 - ### [Age estimation](https://demo.miniai.live/): 
    It can estimate the age of detected faces.
 - ### [Gender detection](https://demo.miniai.live/):
    It can determine the gender of detected faces.
 - ### [Liveness detection](https://demo.miniai.live/): 
    It can detect whether a face is from a live person or a static image.

### Prerequisites
> - C++ compiler with C++11 support  
> - OpenCV (version 4.6.0)

### Installation
Clone the repository:

```
git clone https://github.com/MiniAI/MiniAIFaceSDK.git
```

### Download

- [Download `vcredist_x64.exe` from Microsoft](https://download.microsoft.com/download/2/E/6/2E61CFA4-993B-4DD4-91DA-3737CD5CD6E3/vcredist_x64.exe)
- [Download `vc_redist.x64.exe` from Microsoft](https://download.microsoft.com/download/9/3/F/93FCF1E7-E6A4-478B-96E7-D4B285925B00/vc_redist.x64.exe)
```java
1. Download the `vcredist_x64.exe`, and `vc_redist.x64.exe` files from the provided link.
2. Double-click the downloaded file to start the installation.
3. Follow the on-screen instructions to complete the installation process.
4. Restart your system if prompted.

For more detailed installation instructions, please refer to the [official Microsoft documentation](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redistributable).

```

### Usage
Run the compiled executable:
```java 
./MiniAIFaceDemo.exe
```
We provide free license to test our SDK according to HWID.
You can get the HWID in our SDK application.
Follow the on-screen instructions to perform face detection and recognition.

![HWID](https://github.com/MiniAiLive/MiniAIFaceSDK/assets/136824647/75d935ff-bf2d-4dd2-ac8f-5b356785f91a)
### Customization
> - Face Database: Replace the sample face database with your own set of known faces. Ensure that you provide clear and properly labeled images for accurate recognition.
> - Recognition Algorithm: Adjust the recognition algorithm parameters or explore other algorithms provided by dlib to optimize the recognition performance.


## Face & IDSDK Online Demo, Resources
<div style="display: flex; justify-content: center; align-items: center;"> 
   <table style="text-align: center;">
      <tr>
         <td style="text-align: center; vertical-align: middle;"><a href="https://github.com/MiniAiLive"><img src="https://miniai.live/wp-content/uploads/2024/10/new_git-1-300x67.png" style="height: 60px; margin-right: 5px;" title="GITHUB"/></a></td> 
         <td style="text-align: center; vertical-align: middle;"><a href="https://huggingface.co/MiniAiLive"><img src="https://miniai.live/wp-content/uploads/2024/10/new_hugging-1-300x67.png" style="height: 60px; margin-right: 5px;" title="HuggingFace"/></a></td> 
         <td style="text-align: center; vertical-align: middle;"><a href="https://demo.miniai.live"><img src="https://miniai.live/wp-content/uploads/2024/10/new_gradio-300x67.png" style="height: 60px; margin-right: 5px;" title="Gradio"/></a></td> 
      </tr> 
      <tr>
         <td style="text-align: center; vertical-align: middle;"><a href="https://docs.miniai.live/"><img src="https://miniai.live/wp-content/uploads/2024/10/a-300x70.png" style="height: 60px; margin-right: 5px;" title="Documentation"/></a></td> 
         <td style="text-align: center; vertical-align: middle;"><a href="https://www.youtube.com/@miniailive"><img src="https://miniai.live/wp-content/uploads/2024/10/Untitled-1-300x70.png" style="height: 60px; margin-right: 5px;" title="Youtube"/></a></td> 
         <td style="text-align: center; vertical-align: middle;"><a href="https://play.google.com/store/apps/dev?id=5831076207730531667"><img src="https://miniai.live/wp-content/uploads/2024/10/googleplay-300x62.png" style="height: 60px; margin-right: 5px;" title="Google Play"/></a></td>
      </tr>
   </table>
</div>

## Our Products
| No | Project | Features |
|----|---------|-----------|
| 1  | [FaceRecognition-Docker](https://github.com/MiniAiLive/FaceRecognition-Docker) | 1:1 & 1:N Face Matching |
| 2  | [FaceRecognition-Windows](https://github.com/MiniAiLive/FaceRecognition-Windows) | 1:1 & 1:N Face Matching |
| 3  | [FaceRecognition-Linux](https://github.com/MiniAiLive/FaceRecognition-Linux) | 1:1 & 1:N Face Matching |
| 4  | [FaceRecognition-LivenessDetection-Android](https://github.com/MiniAiLive/FaceRecognition-LivenessDetection-Android) | 1:1 & 1:N Face Matching, 2D & 3D Face Passive Liveness Detection |
| 5  | [FaceRecognition-LivenessDetection-iOS](https://github.com/MiniAiLive/FaceRecognition-LivenessDetection-iOS) | 1:1 & 1:N Face Matching, 2D & 3D Face Passive Liveness Detection |
| 6  | [FaceRecognition-LivenessDetection-CPP](https://github.com/MiniAiLive/FaceRecognition-LivenessDetection-CPP) | 1:1 & 1:N Face Matching, 2D & 3D Face Passive Liveness Detection |
| 7  | [FaceLivenessDetection-Docker](https://github.com/MiniAiLive/FaceLivenessDetection-Docker) | 2D & 3D Face Passive Liveness Detection |
| 8  | [FaceLivenessDetection-Windows](https://github.com/MiniAiLive/FaceLivenessDetection-Windows) | 2D & 3D Face Passive Liveness Detection |
| 9  | [FaceLivenessDetection-Linux](https://github.com/MiniAiLive/FaceLivenessDetection-Linux) | 2D & 3D Face Passive Liveness Detection |
| 10  | [FaceLivenessDetection-Android](https://github.com/MiniAiLive/FaceLivenessDetection-Android) | 2D & 3D Face Passive Liveness Detection |
| 11  | [FaceLivenessDetection-iOS](https://github.com/MiniAiLive/FaceLivenessDetection-iOS) | 2D & 3D Face Passive Liveness Detection |
| 12 | [FaceAttributes-Android](https://github.com/MiniAiLive/FaceAttributes-Android) | Face Attributes, Age & Gender Estimation |
| 13 | [FaceMatching-Android](https://github.com/MiniAiLive/FaceMatching-Android) | 1:1 Face Matching |
| 14 | [FaceMatching-WinApp](https://github.com/MiniAiLive/FaceMatching-WinApp) | 1:1 Face Matching |
| 15 | [ID-DocumentRecognition-Docker](https://github.com/MiniAiLive/ID-DocumentRecognition-Docker) | ID Card, Passport, Driver License, Credit Card, MRZ Recognition |
| 16 | [ID-DocumentRecognition-Windows](https://github.com/MiniAiLive/ID-DocumentRecognition-Windows) | ID Card, Passport, Driver License, Credit Card, MRZ Recognition |
| 17 | [ID-DocumentRecognition-Linux](https://github.com/MiniAiLive/ID-DocumentRecognition-Linux) | ID Card, Passport, Driver License, Credit Card, MRZ Recognition |
| 18 | [ID-DocumentRecognition-Android](https://github.com/MiniAiLive/ID-DocumentRecognition-Android) | ID Card, Passport, Driver License, Credit Card, MRZ Recognition |
| 19 | [ID-DocumentLivenessDetection-Docker](https://github.com/MiniAiLive/ID-DocumentLivenessDetection-Docker) | ID Document Liveness Detection |
| 20 | [ID-DocumentLivenessDetection-Windows](https://github.com/MiniAiLive/ID-DocumentLivenessDetection-Windows) | ID Document Liveness Detection |
| 21 | [ID-DocumentLivenessDetection-Linux](https://github.com/MiniAiLive/ID-DocumentLivenessDetection-Linux) | ID Document Liveness Detection |

## About MiniAiLive
[MiniAiLive](https://www.miniai.live/) is a leading AI solutions company specializing in computer vision and machine learning technologies. We provide cutting-edge solutions for various industries, leveraging the power of AI to drive innovation and efficiency.

## Contact US
For any inquiries or questions, please contact us on [WhatsApp](https://wa.me/+19162702374).

<p align="center">
<a target="_blank" href="https://t.me/Contact_MiniAiLive"><img src="https://img.shields.io/badge/telegram-@MiniAiLive-blue.svg?logo=telegram" alt="www.miniai.live"></a>&emsp;
<a target="_blank" href="https://wa.me/+19162702374"><img src="https://img.shields.io/badge/whatsapp-MiniAiLive-blue.svg?logo=whatsapp" alt="www.miniai.live"></a>&emsp;
</p>
