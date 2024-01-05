# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 강다은
- 리뷰어 : 이재영


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 코드를 캡쳐해 근거로 첨부

<br/>
![image](https://github.com/youungg/AIFFEL-QUEST_KKD/assets/149548911/e108c799-d35d-46e6-8e58-9b89c666cf16)


![image](https://github.com/youungg/AIFFEL-QUEST_KKD/assets/149548911/b9af2c3b-a93b-48b2-88c7-7fe6761901bd)


![image](https://github.com/youungg/AIFFEL-QUEST_KKD/assets/149548911/9496c264-4f19-4d70-bef6-f946485d99c0)

<br/>

작성된 코드를 보았을 때, 데이터셋 전처리를 정상적으로 진행했을 뿐더러,

바운딩 박스가 명확히 시각화 되어있고 테스트 결과도 100%가 나왔음을 알 수 있다.

이는 주어진 루브릭을 완벽히 수행함을 알 수 있다.

<br/>
<br/>
    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
<br/>

![image](https://github.com/youungg/AIFFEL-QUEST_KKD/assets/149548911/0929599f-760c-46d5-9cbf-6a30def6168e)

![image](https://github.com/youungg/AIFFEL-QUEST_KKD/assets/149548911/8b1c1572-0c83-4e2a-804a-e9444fdaa87f)

![image](https://github.com/youungg/AIFFEL-QUEST_KKD/assets/149548911/4c52d4d3-2a96-4251-ad8d-1d362961dd0e)

<br/>

위 내용들을 보아, 어려운 내용 및 이해가 쉽지않은 코드에 대해 주석 처리가 되어있어,

코드의 작동 메커니즘을 알 수 있게 작성되었다.

<br/>
<br/>
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.

<br/>

![image](https://github.com/youungg/AIFFEL-QUEST_KKD/assets/149548911/f7669fe4-04dc-4e3f-a774-c6f3968afc91)

![image](https://github.com/youungg/AIFFEL-QUEST_KKD/assets/149548911/8b19111d-e069-44eb-8273-1fc0ab3227e3)

![image](https://github.com/youungg/AIFFEL-QUEST_KKD/assets/149548911/c4575f8e-a916-455e-9677-6b5ffef70cfb)

<br/>

validation이 추가되었고, train history를 그려 loss 값을 확인하였을 뿐만 아니라, self_drive_assist 역시 매우 잘 작성 되어 동작하였다.

이를 통하여 새로운 시도 및 추가 실험을 진행한 것을 알 수 있다.

<br/>
<br/>
        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.

<br/>

![image](https://github.com/youungg/AIFFEL-QUEST_KKD/assets/149548911/cf5d232a-b665-4d41-9713-b1f250819c32)

<br/>

위 사진을 보아 회고에 아쉬운 점, 느낀점이 매우 잘 작성되어 있음을 알 수 있다.

<br/>
<br/>

- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 하드코딩을 하지않고 함수화, 모듈화가 가능한 부분은 함수를 만들거나 클래스로 짰는지
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화했는지
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.

<br/>

![image](https://github.com/youungg/AIFFEL-QUEST_KKD/assets/149548911/3e180aeb-0b28-430a-addd-ff4b1720adab)

![image](https://github.com/youungg/AIFFEL-QUEST_KKD/assets/149548911/474f630d-5d27-4325-958f-ce84c16f754a)

![image](https://github.com/youungg/AIFFEL-QUEST_KKD/assets/149548911/9fb17102-d3dc-4ef2-b78d-c60f44b83fdd)

<br/>

코드내 거의 모든 부분이 함수 혹은 클래스로 정의되어 있음을 확인할 수 있다.

이를 통하여 코드가 간결하고 효율적임을 알 수 있다.

<br/>
<br/>

# 참고 링크 및 코드 개선
```
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
