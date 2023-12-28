# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 강다은
- 리뷰어 : 이승제


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
      
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 퀘스트 문제 요구조건 등을 지칭
      - 블록함수 구현이 제대로 진행되었으며 구현한 모델의 summary가 예상된 형태로 출력되었다.  
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/c710b10f-276e-4ef7-8701-fe9a5c47c96f)
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/3841a2d8-be1a-4990-80d6-5ebcf4611dc3)

      - tensorflow-datasets에서 제공하는 cats_vs_dogs 데이터셋으로 학습 진행 시 loss가 감소하는 것이 확인되었다.
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/51107e9c-2494-45f8-becc-efabbb7caad4)


     
      - ResNet-34, ResNet-50 각각 plain모델과 residual모델을 동일한 epoch만큼 학습시켰을 때의 validation accuracy 기준으로 Ablation Study 결과표가 작성되었다.  
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/c40952fb-835c-40f3-ada5-693c10e980d5)

    -> 주어진 기준에 모두 만족하는 코드가 제출되었다.


- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**

    ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/2ad11f8f-7b48-451e-8b7e-e14402cbac83)
    
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인  
        -> 블럭과 기능에 무슨 역할을 하는건지 주석이 잘 달려있다.

    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
        -> shortcut에 해당하는 부분에서 어떤 경우에 shortcut을 연결하는지 무엇을 만들어서 연결하는지 알 수 있었다.     

    - 주석을 보고 코드 이해가 잘 되었는지 확인  
        -> 주석을 보고 잘 이해할 수 있었다.

- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 실험이 기록되어 있는지 확인
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/c01d62ac-d59c-4966-b8b9-2a51dc1e7459)
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/5c67ef3d-cbe9-4e70-8aab-26a1e47d6b9f)

        -> 해당 코드를 보면 알 수 있듯이 resnet의 모든 layer를 확인 할 수 있게 만들어 추가적인 시도가 보였다. 그리고 노드에 나오는 것과 다른 파라미터를 사용한 것도 좋았다.
        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해 배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/6e9fb2e6-358c-4a9f-a3c3-547fe4979b06)

         -> 프로젝트를 진행하고 느낀점을 회고에 기록을 잘 해주셨다.

    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/762add22-8c08-47d7-ade8-8695790306fc)

         -> 다른 모델과 비교하는 그래프를 그려주셔서 실험 결과를 한 눈에 이해할 수 있었다.

        
- [x]  **5. 코드가 간결하고 효율적인가요?**
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/5706a29b-47ff-4e89-9529-3a8059a5a261)

    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 하드코딩을 하지않고 함수화, 모듈화가 가능한 부분은 함수를 만들거나 클래스로 짰는지
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화했는지
        -> 스타일 가이드를 준수하였고 모델을 훈련시키는 부분을 함수로 만들어 하나의 함수로 모델을 학습시킬 수 있는 것이 코드 중복을 최소화했다.
