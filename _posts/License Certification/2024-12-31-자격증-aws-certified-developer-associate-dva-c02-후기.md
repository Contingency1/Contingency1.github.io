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

![image](https://github.com/user-attachments/assets/b170ba57-a4ae-4741-8c85-0f1ce4cf6251)

[Examtopics DVA-C02](https://www.examtopics.com/exams/amazon/aws-certified-developer-associate-dva-c02/view/) 이 곳도 도움이 될거라 생각은 하는데, 많이 풀어보지는 않았다. 사실상 Udemy에서 풀어 본것이 다라고 해도 무리가 없다.

### 3. 시험 중 전략

전략이라 하기도 우습다.
생각보다 시간이 남아돌지 않았다.

처음 문제를 다 돌았을 때 65문제 중 확실하게 잡고가는 문제는 25문제 남짓이었고, 조금이라도 애매한 문제가 40문제 정도 였다.
Flag 세우고 나중에 와서 검토를 계속해서 했는데

영어로 봐도 한글로 봐도 모르는 문제가 몇 있었다. 과감하게 찍기는 했는데 운이 좋았던 것 같다.

---

## 알아두면 좋은 정보

### EC2, RDS, S3

가장 기본이 되는 서비스들이다. 이런건 방심하지 않도록 철저하게 알고는 가는게 좋을것이다. 근데 난 하나 틀린듯.

### IAM

정말정말 중요하다.
Identity-Based Policies 사용자, 그룹, 역할에 부여
Resource-Based Policies 특정 리소스(서비스에 부여)
Instance Profile EC2 인스턴스에 부여

IAM 관련 정책 사항은 시험의 한 축을 다룬다. 그 정도로 정말 중요하다.

명시적으로 허용(Policy에 적용)되어 있지 않은 정책은 무조건 Deny 상태이고 만약 서로 같은 서비스에 대한 권한이 충돌되는 상황(ex: 사용자는 EC2 접근 허용, EC2에서는 사용자 접근 거부)이라면

무조건 Deny가 이긴다. 결국 사용자는 접근하지 못하게 된다는 것이다.

### ECS

**EC2 Launch Type**

EC2를 통해 Container를 띄우는 방법

**Fargate Launch Type**

Container 자체만 띄우는 방법 (당연하지만 Serverless)

### DynamoDB

시험볼 때는 WCU, RCU에 대한 값을 공식을 통해 푸는 문제는 나오지는 않았다.
정말 한문제 이상 나올거라고 외워서 가져갔지만 나오지 않아서 아쉬운 부분이었다.

서버리스, 파티션 키, 인덱스 관련(GSI, LSI), data TTL 설정 기능, Strongly Consistent Read, Strongly Consistent Read 등등

여튼 빠삭하게 알고있으면 좋다. 해당 부분 2~3문제 출제됐던것 같다.

### Lambda

람다 같은 경우는 정말 광범위 하게 사용할수 있었다.
여러 서비스에 붙어서 알림 기능이나 이벤트 처리용 등으로 많이 쓰고있는것 같았다. 어떤 상황에서 어떤 Policy를 부여해야만 하는지 적절하게 파악하고 있으면 좋을것같다.

호출 횟수와 실행 시간에 따라 비용 추가, EventSource Mapping, Layers

Lambda의 성능 향상을 위해서는? -> 관련 RAM(Memory) 추가
이런 쉬운 문제가 나오기도 했으니 알면 좋을듯

### Exponential Backoff

이거 나오면 대부분 찍으면 맞다. <- 이건 Stephane도 동의한 부분
한국어로 지수 백오프 전략이라고 하는데
특정 작업에 실패했을 경우 다시 그 작업을 Retry한다.

또 실패하면 조금 있다가 다시 시도하고, 그게 반복되면
조금씩 시간을 늘려가면서 Retry하는 방식을 말한다.

SQS 관련해서 쓰이기도하고 실시간 data관련 Kinesis에서도 쓰였던것 같다.

### X-ray, CloudWatch, CloudTrail

X-ray는 서비스 흐름간 트래픽 흐름 시각적 확인가능 및 분석 가능, 성능문제 확인

CloudWatch는 메트릭을 모니터링하고 log 확인가능, + Lambda를 통해 여러가지로 활용함

CloudTrail은 AWS service API 호출관련 log 확인가능

### Cache

캐쉬 관련 문제가 나왔던 걸로 기억한다.

Write Through - data 캐쉬에 쓰면서 DB에 저장 (data 동기화 중심)
Lazy Loading - 조회 요청시 Cache 쓰면서 전송

### Elastic BeanStalk(ELB)

Service 배포 관련 전략과 연계되어 나왔던것 같다.

All at once, Blue Green, Rolling,Canary 등 배포 전략 빠삭하게 알아야한다.

### CloudFormation

개인적으로 AWS에서 Service 구축의 꽃이라고 할수있을정도로 중요한 Service 인것같다.
해당 Service에서 사용하는 Parameter,Pseudo Parameter, Mappings등 예약어 관련해서는 잘 알아두어야한다.

이런 종류의 형식을 묻는 문제가 1~2문제 나왔던걸로 기억한다.

### SQS

Standard Queue - 최소 1회 이상 전달, 중복가능, 순서보장안됨

FIFO Queue - 정확히 1회 전달, 중복없음, 순서보장

Message Visibility Timeout (메시지 가시성 초과시간), DLQ(DeadLetterQueue, 중요), 사용가능 API (ex: PurgeQueue, CreateQueue ,Delete Queue 등등)

DeleteQue는 큐 자체 삭제, PurgeQueue는 큐 내부 메시지 전부 삭제

등 SQS도 나왔다.

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
