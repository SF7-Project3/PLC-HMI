# 일상의 행복한 변화 : Smart Home 🏡

## 프로젝트 소개
*
## 역할분담
|이름|역할|주요업무|
  |:---:|:---:|:---|
  |김희수|팀장|- PLC : 가스 제어 프로그래밍, HMI : 가스 제어 샘플 구현 <br>- 참고자료 조사, 기능명세서 작성 및 정리, 플로우 차트 작성 및 검토<br>- 일정 관리 및 업무 분담, 발표 자료 제작, 발표|
  |노수현|팀원|- PLC : 조명 제어 프로그래밍, HMI : 메인 화면부터 각 기능별 페이지 작화 구현 총괄<br>- 참고자료 조사, 기능명세서 작성, 회의록 정리, 각 기능별 필요한 그래픽 파일 제작<br>- 발표 자료 제작, 팀 분위기 활성화|
  |한용찬|팀원|- PLC & HMI : 월패드 & 공동현관 엘리베이터 제어, 커튼 제어, 조명 제어(PLC)<br>- 참고자료 조사, 기능명세서, 플로우 차트 작성, PLC 회로 전체 통합, 중복 메모리 할당 수정<br>- PLC & HMI 파일 정리 및 Github 업로드, Readme 작성, 프로그램 시연 보조|
  |황세진|팀원|- PLC : 냉/난방기 및 보일러 프로그래밍, HMI : 냉/난방기 및 보일러 연동<br>- 참고자료 조사, 기능명세서, 플로우 차트 작성, PLC 통합 회로 디버깅 및 최종 검토<br>- 회의록 및 Notion 정리|
   |이안<br>리더님|멘토| 프로젝트 계획서 & 1차 & 2차 검토 및 피드백, 동기 부여|
## 수행 절차 및 방법
|구분|기간|활동|비고|
  |:---|:---|:---|:---:|
  |프로젝트 기획|2.02.12(수)-25.02.13(목)|주제 선정 및 프로젝트 계획서 작성||
  |자료 수집|25.02.14(금)|자료 수집 및 분석, 기능명세서 구체화|계획서 발표|
  |1차 <br>기능 구현|25.02.15(토)-25.02.18(화)|중요도가 높은 기능의 PLC 회로 구현|1차 피드백 검토|
  |2차 <br>기능 구현|25.02.19(수)-25.02.21(금)|1차 기능 HMI 작화 구현 및 2차 기능 추가|2차 피드백 검토|
  |통합 및<br>디버깅|25.02.22(토)-25.02.24(일)|PLC 회로 & HMI 작화 통합, 프로그램 테스트 및 디버깅성||
  |발표준비|25.02.22(토)-25.02.24(월)|발표 자료 완성 및 발표 연습, 프로그램 완성도 향상 및 GIthub 정리||
  |최종 발표|25.02.25(화)|주제 선정 및 프로젝트 계획서 작성||

## 기술스택 및 협업 툴
|카테고리|기술 및 버전|
  |:---:|:---|
  |언어| LD (Ladder Diagram, 그래픽 기반 프로그래밍 언어)|
  |프로그램| PLC : XG5000 (4.78) / HMI : XP-Builder (3.90)|
  |협업 툴| Github(저장소), Notion(업무 공유), MIRO(플로우차트), Discord(비대면 회의), KakaoTalk(연락) |
## 기능 명세서
![Image](https://github.com/user-attachments/assets/056881e1-414b-4508-b271-02a892e8e601)
## 

## 주요기능 & 플로우차트
### 1. 월패드 호출 밑 공동현관 자동호출
|HMI|플로우차트|
  |:---:|:---:|
  |![Image](https://github.com/user-attachments/assets/5e2e0e40-8e51-41b5-a9df-172bcfbe4a4e)|플로우차트|
### 2. 커튼 제어
|HMI|플로우차트|
  |:---:|:---:|
  |![Image](https://github.com/user-attachments/assets/5394c489-4029-4005-aace-dd2ba9ce28f1)|플로우차트|
### 3. 조명 제어
|HMI|플로우차트|
  |:---:|:---:|
  |![Image](https://github.com/user-attachments/assets/7c3829e5-06f9-4665-ba49-d9610b4bb2d4)|플로우차트|
### 4. 가스 밸브 제어
|HMI|플로우차트|
  |:---:|:---:|
  |![Image](https://github.com/user-attachments/assets/90f4ed60-ad4e-42e7-b922-c4104ad6c279)|플로우차트|
### 5. 냉/난방기 제어
|HMI|플로우차트|
  |:---:|:---:|
  |![Image](https://github.com/user-attachments/assets/3a3c2445-b948-4206-b3e0-32a0bd0920e5)|플로우차트|
### 6. 보일러 제어
|HMI|플로우차트|
  |:---:|:---:|
  |![Image](https://github.com/user-attachments/assets/baaa9c08-0a88-485b-b37c-d80c052eb95d)|플로우차트|


## 기대효과 및 활용 방안

## 참고자료
* SKT(NUGU) : https://www.sktsmarthome.com/ 

* LG(ThinQ) : https://www.lge.co.kr/lg-thinq/app?utm_medium=cpc&utm_source=google&utm_campaign=241008_smart_thinq_sa_bc&utm_term=lg%EC%8A%A4%EB%A7%88%ED%8A%B8%ED%99%88&utm_content=%ED%99%95%EC%9E%A5&gad_source=1&gclid=CjwKCAiAzba9BhBhEiwA7glbasR6tlKrdB53NbHUU0r64sRzP0Rjj1wNt5HTyehMRRY4XJz1NbROzRoCHAAQAvD_BwE

* 삼성(SmartThings) : https://www.samsung.com/sec/smartthings/#samsung-devices

* 스마트 가전 제품 추천 리스트 : https://everyday-holiday3.tistory.com/entry/1%EC%9D%B8-%EA%B0%80%EA%B5%AC-%EC%83%9D%ED%99%9C-%EC%A0%95%EB%B3%B4-%ED%95%84%EC%88%98-%EA%B0%80%EC%A0%84%EC%A0%9C%ED%92%88-%EC%8A%A4%EB%A7%88%ED%8A%B8-%EA%B0%80%EC%A0%84%EC%A0%9C%ED%92%88-%EC%B6%94%EC%B2%9C-%EB%A6%AC%EC%8A%A4%ED%8A%B8

* 스마트 팩토리 참고 : https://www.youtube.com/watch?v=mj8UdZYYthc

* 애플 홈킷 예시 : https://brunch.co.kr/@forchoon/418

* 엘리베이터 자동 호출 :
  1. 유엘루트 https://blog.naver.com/lifesmart-kr/223664670289
  2. 코맥스 https://m.blog.naver.com/commax0401/221376348512

* 에어컨 원격제어 : https://smartstore.naver.com/airdeep/products/8638447772?n_media=27758&n_query=에어컨자동제어&n_rank=2&n_ad_group=grp-a001-01-000000035337903&n_ad=nad-a001-01-000000303664220&n_keyword_id=nkw-a001-01-000005459099493&n_keyword=에어컨자동제어&n_campaign_type=1&n_ad_group_type=1&n_match=1&NaPm=ct%3Dm748z1i0|ci%3D0zG0001BKoTBTCn3yLkh|tr%3Dsa|hk%3Deacb63a56f67a44dbbe75123516556641581a60f|nacn%3DdgegDABgginlB

* 가전제품 제어 방법 LG ThinQ : https://www.lge.co.kr/support/software-SW20231218351001 

* PLC이용 엘리베이터 제어 예시 : https://blog.naver.com/kj98te07/222806108610

* XGK사용방법 : https://sol.ls-electric.com/uploads/document/16572866006190/XGK%20%EC%B4%88%EA%B8%89_V21_.pdf

* 스마트팜 실습 예제(LS ELECTRIC) : https://www.youtube.com/watch?v=F3aCeGqTpV0

* 하수처리시설_ 모터교번운전 실습예제(LS ELECTRIC) : https://www.youtube.com/watch?v=F-b6qiiZ3BI

