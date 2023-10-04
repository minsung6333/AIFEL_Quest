# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 정호재
- 리뷰어 : 서민성


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 첨부되었습니다. 
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 코드를 캡쳐해 근거로 첨부
        - 1. 자기만의 카메라앱 기능 구현을 완수하였다.
        - 2. 스티커 이미지를 정확한 원본 위치에 반영하였다
             
      ![스크린샷 2023-10-04 오후 12 10 03](https://github.com/JEONG-HO-JAE/AIFEL_Quest/assets/138687269/1824b19f-3ef2-4b1b-bfdb-fb3dd09cd658)

        - 카메라 스티커앱을 다양한 원본이미지에 적용했을 때의 문제점을 체계적으로 분석하였다.
          
        ![스크린샷 2023-10-04 오후 12 15 44](https://github.com/JEONG-HO-JAE/AIFEL_Quest/assets/138687269/33d1e11d-d6cf-49e2-b7e4-91c07c576328)
        ![스크린샷 2023-10-04 오후 12 14 18](https://github.com/JEONG-HO-JAE/AIFEL_Quest/assets/138687269/c0aa8854-aa09-4e9a-87d5-9f7505546a74)

- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
        - 주석처리된 코드가 없어 아쉬웠습니다. 
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.


        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 해당부분은 확인하기 어려웠습니다.
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
        - 문제를 해결하는 과정간 발견한 문제점과 이를 해결하기 위한 방법에 대한 기록이 잘 되어있습니다.
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
      ![스크린샷 2023-10-04 오후 12 29 32](https://github.com/JEONG-HO-JAE/AIFEL_Quest/assets/138687269/1764dc92-902c-4ba6-91d3-d3a7589b63e3)
        - 실험 결과에 대한 회고
            - I found the model can not detect the tilted face, the face with obscured eyebrows such as the face wearing sunglasses, and the face showing only one side.
        - 카매라 프로그램의 성능 개선을 위한 방안에 대한 회고
            - detector_hog = dlib.get_frontal_face_detector()
        - 이상 탐지에 대한 회고
            - You can see the model detect the 3 faces on the fourth image eventhough it failed to detect my face wearing the ASU hat. Upon closer examination, one of the three detections detected a face that wasn't even visible. 

- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
        - 네 준수했습니다. 
    - 하드코딩을 하지않고 함수화, 모듈화가 가능한 부분은 함수를 만들거나 클래스로 짰는지
        - 하드코딩을 최소화하기 위하여 for 문을 통한 반복실행을 진행하였습니다만 모듈화로 진행되었으면 좋지 않았을까 싶습니다.
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화했는지
      <br><br>
        - ![스크린샷 2023-10-04 오후 12 25 00](https://github.com/JEONG-HO-JAE/AIFEL_Quest/assets/138687269/e7b2e55e-3497-4e0e-af9e-86a023b4de5a)


# 참고 링크 및 코드 개선
```
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```

