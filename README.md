# MagicFingerSnap

- 오른 손으로 **핑거 스냅**을 하면 **불**이 나옵니다.
- 손 모양을 감지할 수 있는 **Vision 의 기능 (VNDetectHumanHandPoseRequest)** 을 사용합니다.

![modify](https://github.com/sujinnaljin/MagicFingerSnap/blob/master/GIF/modified.GIF)

## Overview
- 원래 프로젝트의 이름은 Detecting Hand Poses with Vision로, WWDC20 [10653: Detect Body and Hand Pose with Vision](https://developer.apple.com/videos/play/wwdc2020/10653/) 세션과 관련이 있음. 아래와 같이 엄지, 검지를 모으면 글씨가 써짐 (Create a virtual drawing app by using Vision's capability to detect hand poses.)

  ![origin](https://github.com/sujinnaljin/MagicFingerSnap/blob/master/GIF/original.GIF)

- 이를 응용해 아래와 같이 변형

  1. 엄지, 검지를 모았다가 
  2. 검지가 엄지보다 왼쪽으로 가면 
  3. 불 나옴

## Develop Environment

- Language : **Swift 5**
- iOS Depolyment Target : **14.0**
- XCode: **12.4**
