# MindWave

‘삶의 덫에서 벗어나 새로운 나를 열기’ 책을 기반으로 ‘마음의 덫’ 을 테스트하고 심리를 분석하여 성찰 일기를 작성하는 웹 서비스

## Contributors

FE : 숙명여자대학교  김지은, 이연진, 최현서

BE : 숙명여자대학교 우정은, 한지수

DL: 숙명여자대학교 황영서, 강정인 

## 주요 기능

 1. 마음의 덫 test 

![mw1](https://github.com/Mindwave-solux-web6/data_analysis/assets/100707876/20d66d3c-3f18-42eb-8603-0cac6cb8ba8e)

![mw2](https://github.com/Mindwave-solux-web6/data_analysis/assets/100707876/cf41e340-d2b0-4e37-a0bd-4d63f62a33bf)

2. 마음일지 

![mw3](https://github.com/Mindwave-solux-web6/data_analysis/assets/100707876/6249a406-b816-48da-bc0e-f6bbeb620c15)

3. 감정 분석

![mw4](https://github.com/Mindwave-solux-web6/data_analysis/assets/100707876/2a512e48-7d80-4f6c-9c87-f82b55a9d9eb)


### 일기 사용자의 감정 분류를 위한 다중 분류 모델 구현

1) **AI-HUB 의 ‘ 감성 대화 말뭉치’ 데이터셋을 이용& 전처리**

    [train dataset](https://drive.google.com/file/d/19pFp8QrjKAJ9zonQ_LQk5wEeZ7oRnD6e/view?usp=drive_link)

    [test dataset](https://drive.google.com/file/d/19P7VdCow6-KwYS0Ds8g0m9tigWb84Y9x/view?usp=drive_link)

    → 6개의 감정 ( 분노, 기쁨, 불안, 당황 , 슬픔, 상처 ) 으로 분류할 수 있도록 데이터 전처리

2) **KoBert (’SKT Brain’ 공개) 모델 적용**
   
3) **Token화 하고 KoBert  모델 parameter를 조정시켜 train 시켜줌**

   → test datast 에 대해서는 accuracy : 0.71 를 보여줌 
_________
[SOLUX_23_1_Web6_MindWave](https://solux.tistory.com/1070) 에서 시연 영상과 자세한 설명을 볼 수 있습니다
