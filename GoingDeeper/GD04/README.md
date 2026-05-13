# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 최수정.
- 리뷰어 : 정수연.


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - 
        - lr 이 달라짐에따라 loss가 모델별로 어떻게 변화하는지 알아본 결과를 확인할 수 있었습니다
        - loss 결과를 보면 simple baseline 모델이 더 좋은 성능을 보일 것 같았지만 실제 이미지로 확인해 보았을 때,
        - hourglass 가 더 잘 예측하고 있는 모습을 확인할 수 있었습니다
        - 
        - <img width="600" height="196" alt="image" src="https://github.com/user-attachments/assets/e83ec3b9-b11d-45a9-af98-ce6ddc3ab9e1" />
        - <img width="608" height="314" alt="image" src="https://github.com/user-attachments/assets/4682a9e8-e0ad-45ae-ba65-881bee8bf110" />
        - <img width="637" height="298" alt="image" src="https://github.com/user-attachments/assets/35cfdf2c-d078-4f2a-957c-f887b9c89ba4" />



    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 
        - 이번에 가장 중요했던 점은 hourglass 모델을 이해하고 실험을 수행하는 것이라고 생각하여 hourglass 구조 만드는 코드를 선택하게 되었습니다
        - 더불어 비교모델인 simplebaseline 모델을 구축하는 것도 중요하다고 생각해 두가지를 캡쳐해서 가져왔습니다
        - <img width="605" height="499" alt="image" src="https://github.com/user-attachments/assets/f9f2c83b-593f-49a1-955d-927f2af68938" />
        - <img width="609" height="420" alt="image" src="https://github.com/user-attachments/assets/471eb60d-fc50-4e81-b8a6-dd770bb3fef0" />


        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 
        - 팀원들과 추가적으로 backbone 수정, 비디오 결과로 판단하기 등등 다양하게 수행한 것을 확인 할 수 있었습니다
        - <img width="616" height="437" alt="image" src="https://github.com/user-attachments/assets/6855a853-6a1f-4ab6-ae2d-36ca0850eb80" />
        - <img width="635" height="489" alt="image" src="https://github.com/user-attachments/assets/9093b900-9535-463e-9f20-616ee9212dfa" />


        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 전체적으로 어떤 결과를 수행했는 지 확인 할 수 있었습니다.
        - <img width="628" height="299" alt="image" src="https://github.com/user-attachments/assets/61696b11-b5e7-43ae-a6c9-5bf43c135784" />

        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 
        - 코드가 시작되기 전 주석으로 항상 깔끔하게 잘 처리하시는 것 같습니다
        - <img width="583" height="409" alt="image" src="https://github.com/user-attachments/assets/b5df2409-f1ae-4aa9-8606-c016e7081269" />



# 회고(참고 링크 및 코드 개선)

조원들끼리 실험을 분리해서 수행해서 다양한 결과를 확인할 수 있었고, 항상 결과를 깔끔하게 정리하시는 것 같아 동기부여가 되는 코드였습니다.
