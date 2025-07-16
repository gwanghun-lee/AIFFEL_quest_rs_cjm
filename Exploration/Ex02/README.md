# AIFFEL Campus Online Code Peer Review Template

- **코더(Code 작성자)** : 최정민
- **리뷰어(Reviewer)** : 세냐

## PRT (Peer Review Template)

1. [x] **주어진 문제를 해결하는 완성된 코드가 제출되었나요?**  
   - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인  
   - 중요! 해당 조건을 만족하는 부분을 캡처해 근거로 첨부  
   ![Снимок экрана 2025-07-16 10:40:25](https://raw.githubusercontent.com/averksuu/AIFFEL_quest_rs2/main/Exploration/Ex02/pictures/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-07-16%20104025.png)  
   ![Снимок экрана 2025-07-16 10:40:57](https://raw.githubusercontent.com/averksuu/AIFFEL_quest_rs2/main/Exploration/Ex02/pictures/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-07-16%20104057.png)

2. [x] **전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**  
   - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인  
   - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인  
   - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인  
   - 주석을 보고 코드 이해가 잘 되었는지 확인  
   - 중요! 잘 작성되었다고 생각되는 부분을 캡처해 근거로 첨부  
   ![Снимок экрана 2025-07-16 10:41:20](https://raw.githubusercontent.com/averksuu/AIFFEL_quest_rs2/main/Exploration/Ex02/pictures/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-07-16%20104120.png)  
   ![Снимок экрана 2025-07-16 10:41:36](https://raw.githubusercontent.com/averksuu/AIFFEL_quest_rs2/main/Exploration/Ex02/pictures/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-07-16%20104136.png)

3. [x] **에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나 새로운 시도 또는 추가 실험을 수행해봤나요?**  
   - 문제 원인 및 해결 과정을 잘 기록하였는지 확인  
   - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 실험이 기록되어 있는지 확인  
   - 중요! 잘 작성되었다고 생각되는 부분을 캡처해 근거로 첨부  
   ![Снимок экрана 2025-07-16 10:41:55](https://raw.githubusercontent.com/averksuu/AIFFEL_quest_rs2/main/Exploration/Ex02/pictures/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-07-16%20104155.png)

4. [x] **회고를 잘 작성했나요?**  
   - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해 배운 점과 아쉬운 점, 느낀 점 등이 기록되어 있는지 확인  
   - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인 
   - 중요! 잘 작성되었다고 생각되는 부분을 캡처해 근거로 첨부
     
  
     변수들의 분포를 이해하는 데 도움이 되는 그래프들이 제시되었습니다.  

5. [x] **코드가 간결하고 효율적인가요?**  
   - 파이썬 스타일 가이드(PEP8)를 준수하였는지 확인  
   - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인  
   - 중요! 잘 작성되었다고 생각되는 부분을 캡처해 근거로 첨부
     
     
       코드는 문법적으로 올바르게 작성되었으며 함수로 잘 분리되었습니다.

---

## 회고 (참고 링크 및 코드 개선)

- 특징 공학(feature engineering)이 적용되어 새로운 특성이 생성되었으며,  
  클러스터링을 통해 우편번호(zip code)가 동일한 위치로 그룹화되어 큰 장점을 제공합니다.  
- 여러 모델의 예측을 결합(blending)하여 단일 모델이 아닌 다수 모델의 예측을 활용했습니다.


