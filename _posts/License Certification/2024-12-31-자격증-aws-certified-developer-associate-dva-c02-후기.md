---
layout: post
title: "[자격증] AWS Certified Developer - Associate (DVA-C02) 후기"
date: 2024-12-31 16:09 +0900
description: AWS 자격증 취득
category: [License / Certification, AWS]
tags: [AWS, DVA-C02, AWS Certified Developer, Certification]
---

![image](https://github.com/user-attachments/assets/509e26c6-1a8c-4617-ba35-14150674666f)

쉽진 않았다.
주어진 시간 160분 중 5분남기고 제출했다.
막바지에 이를땐 식은땀이 났다.

---

## 시험안내

![image](https://github.com/user-attachments/assets/b0a33276-4a78-424e-98f0-73f030540b6c)

라고는 하는데 나같은 개발자(희망) 나부랭이는 동아리에서 기껏해야 EC2, RDS 6개월 정도 깔짝대본게 다이다. (그마저도 인프라 쪽은 잘 다루진 않음..)
딱히 이걸 증명할 방법도 없고 그냥 권장사항인듯 하다.

1000점 만점 중 720점 이상을 얻어야한다.

자세한 안내는 [AWS Certified Developer - Associate(DVA-C02) 시험 안내서](https://d1.awsstatic.com/ko_KR/training-and-certification/docs-dev-associate/AWS-Certified-Developer-Associate_Exam-Guide.pdf) 참조

---

## 준비물 및 준비 기간

카드(가입했을때 사용했던 것.)과 신분증(영어가 있어야함, 여권ok)

필자의 경우 운전면허증 뒷면이 영어라서 그걸 가져갔다.

1달 (연말이라고 좀 논것 같아서 솔직히 3주밖에 못한것 같다.)

---

## 준비 과정 및 전략

### 1. 강의 시청

![image](https://github.com/user-attachments/assets/5c501a77-10f6-4acc-9c9c-a58660a4bc0e)

강의는 [Udemy](https://www.udemy.com/)에서 Stepahne Maarek씨의[【한글자막】 AWS Certified Developer Associate 시험 합격을 위한 모든 것!](https://www.udemy.com/course/best-aws-certified-developer-associate/?couponCode=KEEPLEARNING)을 들었다.
강의가.... 33시간이라 좀 버겁긴한데 그만큼 알차게 들어가 있기는하다.
개념설명 후 바로 실습 들어가는데 실습까지 따라하지는 않았고 보면서 그냥 이런게 있구나 이 정도였긴 하다.
Udemy에서 세일할때 사서 12000원정도 썼다.
혹시라도 살 의향이 있다면 반드시 세일할 때 사는게 지갑건강에 좋을것이다.
애초에 Udemy가 세일을 자주하기도 하니까ㅇㅇ

![image](https://github.com/user-attachments/assets/a7747e4c-bc1b-44d7-b3a8-b0f5dd6f5df8)

필자는 강의를 들으면서 Notion에 따로 페이지를 파서 정리까지 하긴 했는데
이 작업이 생각보다 오래걸렸다. 근데 한번쯤 해두면 좋긴할듯하다. ~~근데 그 마저도 후반부 갈수록 대충하긴했다. 문제푸느라..~~

### 2. Dump 문제 풀기

![image](https://github.com/user-attachments/assets/024f67b6-cdd5-40dc-813d-67688de52a2b)

~~Stephane의 노예~~
Dump 문제도 Udemy에서 제공하는 문제([Practice Exams | AWS Certified Developer Associate 2024](https://www.udemy.com/share/101WNq3@SzHlZT096Hliz-1puWPcWhuO7lpw0LxF6nqMoznw_oZOHgt8laVyzh35Cto3cXrdxw==/))를 샀다. 65문제씩 6 Set로 총 390문제를 풀었는데 강의에 있었던 65문제를 포함하면 455문제를 접했다.

문제는 실제 시험보다 확실히 어렵고 애매하고 한국어가 맞는지 의심이 들정도인 문제도 있다.(번역본으로 봐서 좀더 심한듯) 그래도 전체적으로 봤을때 시험과 비슷한 수준인것 같긴하다.

단 한번도 여기 시험에선 합격하지 못했다.

내가 여기서 **강조**하고 싶은건 문제를 풀고 나서 틀린 것, 애매한 것, 맞은것 다 포함해서 한번씩 개념 체크하고 그중에서 틀린거나 애매한건 GPT한테 물어봐서 **반드시** 일련의 서비스 **흐름**을 알고 가야만 된다는 거다.
시험에서 문제될건 이거다. [Cloud Practitioner 시험, CLF-C02](https://contingency1.github.io/posts/%EC%9E%90%EA%B2%A9%EC%A6%9D-aws-certified-cloud-practitioner-clf-c02-%ED%9B%84%EA%B8%B0/#%EC%86%8C%EA%B0%90)에서 묻는 것 처럼 개념만 알아서는 안된다.

서비스 간 상호작용을 하는데 필용한 IAM Policy 설정, Trouble Shooting 을 위한 Service 등을 파악해야하고, 그러기 위해서는 개념이 밑받침 되어줘야 한다. 개념을 토대로 서비스간 상호작용에 어떤 Solution이 최적의 조건을 하고있는지 파악하는게 가장 중요한 능력이다. 시험은 그걸 원하고 있다. Dump 문제를 접하면 어떤 느낌인지 알것이다.

사실 이 모든게 실무 경험 앞에 대부분 해결될듯 하다. 직접해봤으면 더 멀리 볼수 있으니까.

참고로 DVA-C01 문제도 90문제 정도 풀어봤는데 CLF-C02 수준으로 개념만 알고있으면 통과하는 수준이라 크게 도움이 되지는 않았다. 개념을 탄탄히 하고싶다면 푸는것도 좋을것 같은데 **권장하지는 않는다.** 영양가가 없다.

### 3. 시험 중 전략

전략이라 하기도 우습다.
생각보다 시간이 남아돌지 않았다.
처음 문제를 다 돌았을 때 65문제 중 확실하게 잡고가는 문제는 25문제 남짓이었고, 조금이라도 애매한 문제가 40문제 정도 였다.
Flag 세우고 나중에 와서 검토를 계속해서 했는데
영어로 봐도 한글로 봐도 모르는 문제가 몇 있었다. 과감하게 찍기는 했는데 운이 좋았던 것 같다.

---

## 결과

![image](https://github.com/user-attachments/assets/f33089d9-4c7c-4111-b3a3-f5e8da74d4bc)

746점으로 합격

![image](https://github.com/user-attachments/assets/bfdee2d5-bb09-417b-b7f0-120125944aa9)

섹션 별 역량은 다 충족했다.

## 소감

이젠 AWS가 인증한 개발자다. 아직까지는 개발자(희망)이지만 언젠가는 개발자(진짜)가 될수 있을것이다.

행복한 연말연시면 좋겠지만 우리나라 상황이 안좋다. 슬픈 일이다.

~~719점과 720점은 하늘과 땅차이지만, 720점과 1000점은 어깨동무한다.~~
