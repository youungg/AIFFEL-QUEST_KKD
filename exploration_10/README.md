# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 강다은 (네비게이터 : 윤진환)
- 리뷰어 : 이승제


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    1. 아웃포커싱 효과가 적용된 인물모드 사진과 동물 사진, 배경전환 크로마키사진을 각각 1장 이상 성공적으로 제작하였다.  
 

        - 인물 & 크로마키  
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/4a8b0980-4a3c-4e4f-be1f-248ce6a14622)  
        
        
        - 동물 & 크로마키
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/76286812-ca5a-41d6-9f2e-5fc3d9549e1c)  



        **-> 인물과 동물사진의 아웃포커싱 처리가 잘 되었고, 크로마키사진도 완벽하다.**

       
    2. 인물사진에서 발생한 문제점을 정확히 지적한 사진을 제출하였다.  

        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/f4db8061-35cf-46f9-8d42-da1989f3be83)  
        
        
        **-> 인물사진에서 발생한 오브젝트 인식에 관련된 문제를 정확히 지적한 사진을 제출하였다.**

       
    3. semantic segmentation mask의 오류를 보완할 수 있는 좋은 솔루션을 이유와 함께 제시하였다.  
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/9e1e3ec3-c2c0-4d68-96c4-9f3b2eb0e744)  


        **-> 경계 부분에 유사한 픽셀이 있다면 오브젝트 영역을 확장시키거나 특별한 착장에 대한 별도의 학습된 segmentation model을 적용하면 어떨까하는 아이디어를 제시했다.**

<br/>

---

<br/>

- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**

    ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/d7cd713d-4c20-4eab-80ba-35763c628744)  

    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인  
        
        **-> 캡션을 넣는 코드를 작성하고 주석처리가 잘 달려있다.**  


    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.  
        **-> putCaption(img, caption, pos1, pos2)으로 정의가 되어있는데 img: 캡션을 넣을 이미지, caption: 캡션, pos: 넣을 위치로 구성**
    
    
    - 주석을 보고 코드 이해가 잘 되었는지 확인  
     
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/a5be60d3-cda1-4357-ac44-b20b94a85afa)  

        **-> 위의 이미지처럼 동작하는 이유를 주석을 보고 잘 이해할 수 있었다.**

<br/>

---

<br/>
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나”, ”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인  
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/fa1cf5b5-044b-43a6-9be5-aae5b686768d)  

        **-> 문제 원인과 해결을 잘 기록하였다.**


    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 실험이 기록되어 있는지 확인  
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/611887bb-98ba-4d21-a720-0f72a98d39e7)  
        
        **-> 이미지에 캡션을 적용해서 어느 부분이 문제인지 확인이 수월하다.**

<br/>

---

<br/>
        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해 배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인  
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/e1cc3e5b-cc0f-47a6-b235-dfc666509a6f)  

        **-> 프로젝트를 진행하면서 아쉬운 점과 느낀점이 기록이 되어있다.**


    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인  
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/402ff90d-5770-41ef-95c5-1ce236580b64)  

        
        **-> 이미지 처리가 진행되면서 변화하는 과정을 출력하여 이해를 돕고 있다.**

<br/>

---

<br/>
        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인  
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/ad01e160-a11e-4b7a-8862-45f1d414d72f)  
        
        **-> class명은 CamelCase, 함수명은 소문자로 구성하되 필요하면 밑줄로 나눕니다.**


    - 하드코딩을 하지않고 함수화, 모듈화가 가능한 부분은 함수를 만들거나 클래스로 짰는지  
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/ac17e905-e7b6-40f4-a310-fbd73d5773bd)  
  
        **-> segmentImage처럼 자주 사용하는 부분을 함수화 시켰다.**


    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화했는지  
        ![image](https://github.com/happybin2013/AIFFEL-QUEST_DiANA-KANG/assets/85716670/c52c8500-6efb-4f51-8115-33b29823db62)  
  
        **-> mergeObjectBackground와 같이 이미지를 합성하는 함수를 만들어 중복을 최소화 시켰다.**

<br/>

---

<br/>

# 참고 링크 및 코드 개선
```
https://www.gptmagazine.net/gptai/93
2d -> 3d 이미지로 변환할 때 depth map이라는 용어가 자주 나오더라구요! 근데 변환해주는 ai가 있어서 그냥 이런게 있네 하고 첨부합니다!

다은님의 항상 깔끔한 코드 너무 보기 좋습니다~! 최고의 코드..!
```
