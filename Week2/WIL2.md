# AI Study Week 2

Main Category: AIML
Category: Summary
Created Time: September 26, 2023 1:38 PM

### Segmentation

- Semantic Segmentation
    - CNN
    - FCN
        - Fully Connected Layer의 경우 공간적 정보를 무시한 벡터로 표시
        - Convolutional Layer의 경우 Output의 형태가 공간적 정보를 보존하여 upsampling시 input과 같은 크기의 출력을 생성 가능
- Instance Segmentation

### Object Detection

물체(single object)가 아닌 여러 물체(Multiple objects)에 대해 어떤 물체인지 클래스를 분류하는 ***Classification*** 문제와, 그 물체가 어디 있는지 박스를 (Bounding box) 통해 위치 정보를 나타내는 ***Localization*** 문제를 모두 포함

![Untitled](AI%20Study%20Week%202/Untitled.png)

- R-CNN : selective search - region size process - Compute CNN features - Linear SVM로 classify; 물체 위치 찾기 → 물체 분류
    - **설정한 Region**을 **CNN의 feature(입력값)로** 활용하여 **Object Detection**을 수행하는 **신경망**
- SPPNet

![Untitled](AI%20Study%20Week%202/Untitled%201.png)
