# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 강다은 (네비게이터 : 윤진환)
- 리뷰어 : 이승제


# PRT(Peer Review Template)
- [o]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    1. 다양한 방법으로 Text Classification 태스크를 성공적으로 구현하였다.	3가지 이상의 모델이 성공적으로 시도됨
- RNN  
![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/397d135e-faf5-497a-8e0c-e164ea1f52e5)  

- CNN  
![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/70ab2374-0ba3-4efb-b57b-8989fa02b419)  

- POOL  
  ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/138e135a-f9db-4b11-98e4-1e85275bdbdb)  

**-> RNN, CNN, POOL로 구분하여 3가지 이상 성공적으로 시도된 것을 확인할 수 있다.**

       
    2. gensim을 활용하여 자체학습된 혹은 사전학습된 임베딩 레이어를 분석하였다.	gensim의 유사단어 찾기를 활용하여 자체학습한 임베딩과 사전학습 임베딩을 비교 분석함

- 자체학습  
![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/1ce1ca42-3b18-4ee5-8843-b19f90c573cf)  

- 사전학습  
![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/a47930cd-dcce-4618-b8ab-6e0505159711)  

**-> 자체학습한 데이터와 임베딩한 데이터가 차이가 나는 것을 볼 수 있다.**

       
    3. 한국어 Word2Vec을 활용하여 가시적인 성능향상을 달성했다.	네이버 영화리뷰 데이터 감성분석 정확도를 85% 이상 달성함
![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/3747a867-7042-4443-aead-377988f9c642)

**-> 정확도가 85.4%의 값으로 85% 이상을 달성하였다.**

---
    
- [o]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
 ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/1801a4c7-15fd-43cd-81dc-0625e07714f5)

**-> 주석이 3줄로 잘 달려있는 것을 확인할 수 있다.**


    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
 
**-> embedding_matrix 을 먼저 numpy를 사용해서 구조를 만든 후에 w2v_ko에 잂치하는 단어가 있다면 그 단어로 대체한다.**


    - 주석을 보고 코드 이해가 잘 되었는지 확인
 **-> 주석을 보고 임베딩 매트릭스와 일치하는 단어가 대체되는 것을 쉽게 알 수 있었다.**

---
        
- [o]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/c097ada5-7da2-4351-8be1-d850ebed703b)



    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/acd9426c-e696-4493-a313-3f98510fe991)

**->LSTM(64)으로 LSTM값을 변화시켜 추가적인 실험이 진행된 것을 볼 수 있다.**

---
        
- [o]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/e0e2e662-90aa-4732-855f-2553b07575c8)

**->느낀점을 잘 기록하였다.**


    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/dc96e42a-a84d-4317-815e-d9b8c4f80f1b)

**-> 코드가 진행되면서 나타난 결과값을 그래프로 표현해 이해를 돕는다.**

---
        
- [o]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/64d389d2-fc1b-4c1b-b718-e04d40698166)

**->class명은 CamelCase, 함수명은 소문자로 구성하되 필요하면 밑줄로 나눕니다.**


    - 하드코딩을 하지않고 함수화, 모듈화가 가능한 부분은 함수를 만들거나 클래스로 짰는지
![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/9255757c-b08b-4ef7-95c3-945ca0d5cd51)

**->encodeSentence, decodeSentences등 자주 사용하는 코드를 함수화하여 사용한다.**


    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화했는지
 ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/8059c0c2-ad34-4821-a1a4-60e11974954a)

 **->모델을 생성하는 함수를 만들어 모델을 효율적으로 사용했다.**

---

# 참고 링크 및 코드 개선
```
https://ultrakain.gitbooks.io/python/content/chapter1/coding-style-pep8.html - pep8
함수명은 def encodeSentence(): -> def encode_sentence(): 으로 pep8 코딩 스타일에 나와있네요!
저도 코딩 스타일을 다시 보고 정리를 해야겠네요.. 하하
```
