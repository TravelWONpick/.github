# ✈ 트래블 WON픽 - 우리카드 이용자만을 위한 항공 특가 예매 플랫폼

---
## 👨‍👨‍👧 개발팀원  

| <img src="https://avatars.githubusercontent.com/u/139302518?v=4" width="80"> | <img src="https://avatars.githubusercontent.com/u/127727927?v=4" width="80"> | <img src="https://avatars.githubusercontent.com/u/98442485?v=4" width="80"> | <img src="https://avatars.githubusercontent.com/u/79884688?v=4" width="80"> | <img src="https://avatars.githubusercontent.com/u/79312705?v=4" width="80"> |
|:---:|:---:|:---:|:---:|:---:|
| [곽병찬](https://github.com/gato-46) | [부준혁](https://github.com/BooJunhyuk) | [이연희](https://github.com/LeeYeonhee-00) | [박장우](https://github.com/Lisiant) | [김상민](https://github.com/isshomin) |

---
## ✒ 개요 - 프로젝트 주제

### 트래블 WON픽 - **클라우드 기반 고가용성 클라우드 시스템 구축**

- 우리카드 사용자에 한해서 **항공기 특가를 제공**하여 우리카드 사용자 유입 의도
- **기존 존재하는 "우리WON트래블" 서비스의 개편**을 위함

[우리WON트래블 | 설레는 여행을 똑똑하게](https://won.travel/)

</br>

 <details>
  <summary><h3>📌 프로젝트 개요 (클릭해서 펼쳐보기) </h3></summary>

## 왜 이 주제인가?

연말이 다가오면서 여행 수요가 증가할 것으로 예상됩니다. 비행기 특가, 호텔 예약 같은 서비스에 사용자가 몰릴 것으로 보여 이러한 서비스를 신속하게 배포하고 안정적으로 운영하기 위해 **고가용성 클라우드 시스템** 구축을 목표로 주제를 선정했습니다.

또한, **트래블 상품 개발 방안**의 일환으로 **우리카드 사용자**에게 항공기 특가를 제공하여 사용자 유입을 유도하고 트래픽 증가를 통해 **트래블 사업 강화**를 목표로 합니다.

### 📌 카드사 입장

1. **우리카드의 낮은 실적**  
   - 우리카드는 카드사 매출 실적 하위권에 머무르고 있습니다.  
     [관련 기사](https://ceoscoredaily.com/page/view/2024020715095438041)

2. **트래블 카드의 경쟁력 부족**  
   - 기존 트래블 카드와 비교했을 때 신규 고객을 유입시키는 메리트가 부족합니다.
   - 타 금융지주 계열 카드사의 트래블 카드는 고객 락인 효과를 통해 젊은 세대의 장기고객화를 기대할 수 있지만, 우리카드는 이에 미치지 못합니다.  
     [관련 기사](https://www.fntimes.com/html/view.php?ud=202406121329537588237391cf86_18)

### 📌 사용자 입장

1. **특가 항공권 예매의 어려움**  
   - 정보의 비대칭성과 높은 경쟁률로 인해 사용자들이 혜택을 누리기 어렵습니다.
2. **카드 혜택 비교의 복잡성**  
   - 사용자는 다양한 카드 혜택을 비교하기 어려운 실정입니다.

### 🎯 고객 세그먼트
- **20~30대** 사회 초년생 및 대학생
- 연간 **2~3회 이상 해외여행**을 가는 사용자

### 💡 가치 제안
1. 특가 항공권 정보를 더 쉽게 확인 가능  
2. 우리카드 사용자에게 혜택 제공 (낮은 경쟁률로 특가 혜택 확보 가능)  
3. 카드 혜택 비교를 쉽고 편리하게 제공  

### 🚀 해결책: 트래블 WON 픽
- 우리카드 사용자만을 위한 비행기 특가 서비스 제공  
- 쉽고 빠르게 보기 쉬운 카드 혜택 비교 서비스 제공  

### 💰 수익 흐름
1. 우리은행 및 우리카드 사용자 확보  
2. 카드 사용 실적 증가  
3. 연회비 납부 및 파생 실적 증가  

### 📊 주요 지표
1. 신규 고객 유입 수  
2. 카드 사용 실적  

</details>

</br>

---
## 💪 기술 스택

![skill](https://github.com/user-attachments/assets/c55a6dbc-d94c-44dd-9bd9-9f5ce531d0d2)

### Collaboration tool
![tool](https://github.com/user-attachments/assets/110d675c-f270-4eb7-aa90-13f5c5a8ddda)

---

---
## 🏗️ Architecture

### Infra
![86](https://github.com/user-attachments/assets/bc1de7ee-bd8a-472c-a215-8402f4ad98ff)

</br>

### Service
![image 87](https://github.com/user-attachments/assets/aa78e731-6bcb-4339-8a60-82e51867c429)

---
## ✍ 소스 코드

</br>

⚛️ [Front-end](https://github.com/TravelWONpick/TravelWONpick_client)

🛢 [Back-end](https://github.com/TravelWONpick/TravelWONpick_server)

👷🏼‍♂️ [Infra](https://github.com/TravelWONpick/TravelWONpick_infra)

</br>

---
## 📋 API 명세서 
| 이름                     | HTTP Method | URL                                                                                     | 기능             | 설명                                                                                      |
|--------------------------|-------------|-----------------------------------------------------------------------------------------|------------------|------------------------------------------------------------------------------------------|
| 인증번호전송             | POST        | /auth/verifyuser                                                                        | 관리자, 회원     |                                                                                          |
| 인증번호확인             | POST        | /auth/verifysuccess                                                                     | 관리자, 회원     |                                                                                          |
| 회원가입                 | POST        | /auth/signup                                                                           | 관리자, 회원     |                                                                                          |
| 로그인                   | POST        | /auth/login                                                                            | 관리자, 회원     | AWS Cognito에서 Local DB로 저장되는 API                                                  |
| 로그아웃                 | POST        | /auth/logout                                                                           | 관리자, 회원     | Access Token을 이용해서 Session 만료                                                    |
| 나의 예약조회            | GET         | /my/flight                                                                             | 회원             | 예약 번호, 탑승일, 여정, 좌석, 상태 조회                                                |
| 나의 예약 상세보기       | GET         | /my/flight/{uuid}/flight-detail                                                        | 회원             |                                                                                          |
| 나의 예약 상세보기 탑승객| GET         | /my/flight/{uuid}/passenger-detail                                                     | 회원             |                                                                                          |
| 탑승객 정보조회          | GET         | /my/passenger                                                                          | 회원             | 탑승객 리스트 return                                                                     |
| 탑승객 추가              | POST        | /my/passenger                                                                          | 회원             | 탑승객 추가                                                                               |
| 탑승객 삭제              | DELETE      | /my/passenger/{up_id}                                                                  | 회원             | up_id 기준으로 원하는 탑승객 삭제                                                       |
| 탑승객 수정              | PATCH       | /my/passenger/{up_id}                                                                  | 회원             | up_id 기준으로 원하는 탑승객 수정                                                       |
| 나의 회원정보 조회       | GET         | /my/info                                                                               | 회원             |                                                                                          |
| 회원정보 수정            | PATCH       | /my/info                                                                               | 회원             |                                                                                          |
| 탈퇴하기                 | DELETE      | /my/account                                                                            | 회원             |                                                                                          |
| 전체 특가픽 조회         | GET         | /special                                                                               | 회원             |                                                                                          |
| 특가 항공권 조회          | GET         | /special/{sp_id}?departureDate=2023-12-10&arrivalDate=2023-12-20&depAirportCode=ICN&arrAirportCode=CDG | 회원 | 필터에 맞게 항공권 조회(날짜, 출발/도착지, 좌석수) |
| 결제하기 검증            | POST        | /payments/validate                                                                     | 회원             |                                                                                          |
| 결제하기 승인            | POST        | /payments/confirm                                                                      | 회원             |                                                                                          |
| 항공편 예매하기          | POST        | /special                                                                               | 회원             | 예매 내역에 데이터 추가                                                                  |
| 탑승객 추가              | POST        | /special/passenger                                                                     | 회원             | 탑승객 추가                                                                               |
| 이벤트 페이지            | GET         | /event                                                                                 | 회원             | 이벤트 전체 리스트 조회                                                                  |
| 이벤트 상세 페이지       | GET         | /event/{event_id}                                                                      | 회원             |                                                                                          |
| 이벤트 생성하기          | POST        | /event                                                                                 | 관리자           | 게시글 작성                                                                              |
| 이벤트 삭제하기          | DELETE      | /event/{event_id}                                                                      | 관리자           | 게시글 삭제                                                                              |
| 카드픽 조회하기          | GET         | /cards                                                                                 | 회원             | 모든 카드 조회                                                                           |
| 회원조회                 | GET         | /manager/member                                                                        | 관리자           | 모든 회원 조회                                                                           |
| 회원 탈퇴시키기          | DELETE      | /manager/member                                                                        | 관리자           |                                                                                          |

</br>

---

## 🎞 Service 시연 영상

### 🙎‍♂️ 사용자
[![사용자](https://github.com/user-attachments/assets/6a3d6406-a961-472b-8749-0f9a07619390)](https://youtu.be/0IAAcn4IQXo)

### 👩‍💻 관리자
[![관리자](https://github.com/user-attachments/assets/6a3d6406-a961-472b-8749-0f9a07619390)](https://youtu.be/ejkkZa88FQA)


</br>

---
## 🎞 부하 / 가용성 테스트 시연 영상

### 부하 테스트
[![부하테스트](https://github.com/user-attachments/assets/869ef752-1b8f-4d1e-8224-0a8d04ceed05)](https://youtu.be/mVViaBnOQaI)

### 고가용성 테스트
[![가용성테스트](https://github.com/user-attachments/assets/8df229e6-1ad1-4e93-a220-78ea7cefb2fb)](https://youtu.be/fEHAHB_kEGo)

---

## 🎯 트러블슈팅

</br>

## 🔵 Infra

## 1️⃣) base64 암호화 중 줄넘김 문제

### Springbot-secret.yaml 파일에 base64 형태로 넣은 키, 암호, 경로가 인식인 안되는 문제 발생


```jsx
Error starting ApplicationContext. To display the condition evaluation report re-run your application with 'debug' enabled.
2024-11-20T07:21:44.838Z ERROR 1 --- [           main] o.s.boot.SpringApplication               : Application run failed

org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'paymentController' defined in URL [jar:nested:/app/app.jar/!BOOT-INF/classes/!/wonpick/travel/server/controller/PaymentController.class]: Unsatisfied dependency expressed through constructor parameter 0: Error creating bean with name 'paymentService' defined in URL [jar:nested:/app/app.jar/!BOOT-INF/classes/!/wonpick/travel/server/service/PaymentService.class]: Unsatisfied dependency expressed through constructor parameter 3: Error creating bean with name 'redissonClient' defined in class path resource [wonpick/travel/server/config/RedissonConfig.class]: Failed to instantiate [org.redisson.api.RedissonClient]: Factory method 'redissonClient' threw exception with message: java.net.MalformedURLException: Invalid authority field: [redis:
```
</br>

## ❓원인

디코딩 결과 base64로 암호화 하는 도중 줄넘김이 포함되었다는 사실 발견

</br>

## 🚀 해결 방안

기존 base64 암호화 방식이 잘못되었다는 사실을 인지

### 기존 base64 암호화 방식

```jsx
username@servername:~$ echo '{내용}' | base64
```

### 변경된 base64 암호화 방식

```jsx
username@servername:~$ echo -n '{내용}' | base64
```

`echo -n '{내용}' | base64`  : 기존 명령어에 `-n` 을 추가하여 줄넘김을 방지하여 해결

---

</br>

## 2️⃣) nginx-config api 정규식 문제

![image.png](https://github.com/user-attachments/assets/9547ef63-6d3d-409c-bce6-fa60a7b7936b)

![image.png](https://github.com/user-attachments/assets/ff0af424-a1ef-46af-8e1a-0a1866da3a5e)

### 특정 api만 연동되는 문제

</br>

## ❓원인

/OOO/OOO mapping 형식의 api만 불러오고
/OOO mapping 형식의 api는 불러오지 못함 

</br>

## 🚀 해결 방안

```yaml
#수정 전
location ~ ^/[^.]+/ {
           ...
       }
   
#수정 후
 location ~ ^/[^.]+(/|$) {
           ...
       }
```
위의 정규식 표현 ~ ^/[^.]+/  →   location ~ ^/[^.]+(/|$) 으로 수정

---

</br>

## 3️⃣) Unhealthy nodes 문제

![Image](https://github.com/user-attachments/assets/c4b09db3-796c-4e4c-955e-5b3831e776a0)

![Image](https://github.com/user-attachments/assets/a8c7aca0-0f50-4602-8917-bbbac99380ae)

</br>

## ❓원인

기본 CNI는 AWS CNI로 구성을 하게 되는데 워커 노드에 CNI 정책 룰이 없어 정책으로 인해 실패함

</br>

## 🚀 해결 방안

노드 그룹 생성 시 선택하는 정책에 AmazonEKS_CNI_Policy 룰을 추가


![Image](https://github.com/user-attachments/assets/cca6ebd5-0ff0-492f-9889-7c3c29bb3017)
AmazonEKS_CNI_Policy 권한 추가

</br>

<img width="1211" alt="Image" src="https://github.com/user-attachments/assets/e2877ba4-0af6-4295-90ba-5353a6e1bfef" />
노드 그룹 재생성

---

</br>

## 4️⃣) 노드 그룹 생성 실패

<img width="1142" alt="Image" src="https://github.com/user-attachments/assets/4ab8d59e-4b67-4ebe-b2fc-5b36c5c0da48" />

</br>

<img width="1071" alt="Image" src="https://github.com/user-attachments/assets/c72d5c3d-5bb9-4b41-8faf-d14d938849af" />

### 클러스터 생성 후 nodegroup 생성 실패 발생

</br>

## ❓원인

![Image](https://github.com/user-attachments/assets/7fee7836-513d-4e0d-8e65-9a69683bd257)

VPC를 확인해보니 PivateSubnet의 라우팅 테이블에 NAT-GW가 연결이 되어있지 않았고

(라우팅 테이블에 NAT게이트웨이가 **블랙홀** 상태인 것을 확인)

NAT 게이트웨이를 확인하니 서브넷이 private으로 설정되어 있는 것을 발견

</br>

## 🚀 해결 방안

![Image](https://github.com/user-attachments/assets/e928f9ee-4fd5-4540-bce3-bf385d530bcd)

NAT게이트웨이를 재생성할 때 서브넷을 Public으로 설정

---

</br>

## 5️⃣) React CI pipeline 작성 시 빌드 경로 문제

```yaml
Running in /var/lib/jenkins/workspace/travelwonpick_client
[Pipeline] {
[Pipeline] sh
+ npm run build

> fisa-project@0.0.0 build
> vite build

[36mvite v5.4.10 [32mbuilding for production...[36m[39m
transforming...
[32m✓[39m 2 modules transformed.
[31mx[39m Build failed in 403ms
[31merror during build:
[31m[vite]: Rollup failed to resolve import "\src\index.jsx" from "/var/lib/jenkins/workspace/travelwonpick_client/index.html".
This is most likely unintended because it can break your application at runtime.
If you do want to externalize this module explicitly add it to
`build.rollupOptions.external`[31m
    at viteWarn (file:///var/lib/jenkins/workspace/travelwonpick_client/node_modules/vite/dist/node/chunks/dep-BWSbWtLw.js:65589:17)
    at onwarn (file:///var/lib/jenkins/workspace/travelwonpick_client/node_modules/@vitejs/plugin-react/dist/index.mjs:280:9)
    at onRollupWarning (file:///var/lib/jenkins/workspace/travelwonpick_client/node_modules/vite/dist/node/chunks/dep-BWSbWtLw.js:65619:5)
    at onwarn (file:///var/lib/jenkins/workspace/travelwonpick_client/node_modules/vite/dist/node/chunks/dep-BWSbWtLw.js:65284:7)
    at file:///var/lib/jenkins/workspace/travelwonpick_client/node_modules/rollup/dist/es/shared/node-entry.js:19423:13
    at Object.logger [as onLog] (file:///var/lib/jenkins/workspace/travelwonpick_client/node_modules/rollup/dist/es/shared/node-entry.js:21149:9)
    at ModuleLoader.handleInvalidResolvedId (file:///var/lib/jenkins/workspace/travelwonpick_client/node_modules/rollup/dist/es/shared/node-entry.js:20038:26)
    at file:///var/lib/jenkins/workspace/travelwonpick_client/node_modules/rollup/dist/es/shared/node-entry.js:19996:26[39m
```

### On-Premise(Ubuntu)환경에서 client CI 구성 중 npm run build 중 경로 관련 오류 발생

</br>

## ❓원인

React에서 `index.html` 파일에 있는 경로가 **백슬래시(`\`)**를 포함하고 있는데 리눅스에서는 **슬래시(`/`)**를 사용해야 함

</br>

## 🚀 해결 방안

- index.html 수정

```yaml
<script type="module" src="/src/index.jsx"></script>
```
- vite.config.js에 resolve추가

```yaml
// vite.config.js
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'
import path from 'path'

export default defineConfig({
  plugins: [react()],
  resolve: {
    alias: {
      '@': path.resolve(__dirname, './src'),
    }
  },
  build: {
    outDir: 'build'
  }
})
```

---

</br>


## 🔴 Service


</br>

---
