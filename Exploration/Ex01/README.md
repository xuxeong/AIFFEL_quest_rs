# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 최수정
- 리뷰어 : 리뷰어의 이름을 작성하세요.


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
    <img src="<img width="556" height="374" alt="image" src="https://github.com/user-attachments/assets/997480d8-059c-4dbc-803f-587d11bc7e63" />" width="32%">
    <img src="<img width="555" height="411" alt="image" src="https://github.com/user-attachments/assets/1c7e7564-f726-4752-9fb9-d43ead7547f7" />" width="32%">
    <img src="<img width="561" height="377" alt="image" src="https://github.com/user-attachments/assets/f9217756-2cc8-4fb8-a2c7-1fb586fc97f7" />" width="32%">

- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 모델을 입력을 준비하는 전처리 단계부터, 특정 가중치를 적용한 모델 선정, 추론 후 결과를 시각화하는 과정까지 전체 파이프라인이 포함된 핵심 로직
        - 이 모델과 가중치를 왜 선택했는지 이유가 명확히 전달됨
      <img width="761" height="348" alt="image" src="https://github.com/user-attachments/assets/a77088d2-8c7d-4db5-81ce-5b36a257d4b3" />

        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 배경 이미지의 blur가 약한 문제를 잡고 blur 파라미터 튜닝하면서 성능을 높인 과정을 주석으로 기록해놓음. 또한 프로젝트 평가 기준에 더해 추가적으로 수행할 솔루션을 잘 기록함.
    <img width="1005" height="94" alt="image" src="https://github.com/user-attachments/assets/46f2ad8f-5adf-4472-bc16-939bfda184af" />
    <img width="929" height="479" alt="image" src="https://github.com/user-attachments/assets/6fb05897-6078-4a7a-9ac1-9bc0fca78bfe" />

- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 프로젝트 결과물에 그치지 않고, 인물 사진의 경계선 처리(머리카락, 손가락) 및 동물 털과 같은 미세 구조에서 발생하는 세그멘테이션의 한계를 분석함.
    <img width="874" height="256" alt="image" src="https://github.com/user-attachments/assets/d7c1bb38-480f-483f-9e21-0985a987572f" />

- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - T.Compose를 통해 전처리 과정을 하나의 파이프라인으로 묶어 코드 중복을 최소화했습니다.
    <img width="384" height="127" alt="image" src="https://github.com/user-attachments/assets/0ec14580-9bc9-46a7-98a8-933f26f1d08b" />


# 회고(참고 링크 및 코드 개선)
이번 프로젝트에서 수정 님은 단순한 코드 구현을 넘어, 모델이 특정 객체(dog -> sheep)를 오분류하는 원인을 분석하고 가중치 변경을 통해 해결하려는 시도가 인상 깊었습니다. 또한 마지막 회고 부분에서 머리카락이나 동물의 털 같은 미세 구조의 세그멘테이션 한계를 정확히 짚어내고, 'Smooth Blur' 같은 구체적인 개선 방향을 제시한 점이 좋았습니다.
