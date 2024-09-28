- 밀크T Genia.: 천재교육의 42년 교육 전문 노하우와 기술력이 만들어낸 인공지능 AI기술 집약체
- 특징
    - 학생 한명 한명의 실력을 진단하고 점검하여 1:1 맞춤학습을 추천
    - 진단, 맞춤학습 제공, 점검의 프로세스.

- 개발 활용
    - 

- AI맞춤학습 프로세스

    ![alt text](image.png)

    - 학습, 평가, 보강의 과정을 반복하여 학습을 마무리하면 종합 측정을 통해 회원의 성취 기준을 다시 측정하여 필요한 학습을 진행하는 일련의 과정을 반복


- Knowledge Tracing > 특정 학생의 지난 교육 기록을 활용해 아직 풀지 않은 문제에 대한 정오답을 예측하는 task
    - 학생(user)의 풀이 이력을 활용하여 학생이 미래에 각 문제에 대해 잘 풀어낼 확률을 도출하는 것으로 이를 활용하여 학생의 지식 상태를 추적. 숙련도로 이를 나타내는 척도로 사용
    - BKT, DKT 등의 모델이 사용.[참고링크](https://medium.com/riiid-teamblog-kr/%EA%B5%90%EC%9C%A1ai%EC%9D%98-%EA%B8%B0%EB%B3%B8%EC%9D%B4%EC%9E%90-%EC%8B%9C%EC%9E%91-deep-knowledge-tracing-dkt-8bc132eda9ec)

    - DKT는 RNN(Recurrent Neural Networks) 모델의 형태를 가지고 있습니다. RNN은 시간 순차적 데이터를 학습하는 데 특화된 순환적 구조를 갖는 것이 특징입니다. DKT는 RNN의 일종인 LSTM(Long Short-Term Memory models)
        ![RNN](![alt text](image-1.png))
    - 현재 KT 에서 사용하는 모델(최신화)

- ICP
    - AI 기반 개인화 추천 기술은 학습자가 학습한 이력을 바탕으로 학습 정도를 추정하고, 학습자에게 적합한 내용과 방법을 추천하는 기술
    - 알고리즘
        - CBF, CF, MF
        - 정오답 확률을 예측할 수 있는 알고리즘은 MF. 하지만 부가정보를 활용할 수 없기에 FM도 많이 사용

- IRT
    
