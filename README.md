# 🏃 모두의 헬스 케어 비서 - MOBI 
> Notion: https://www.notion.so/MOBI-041d60cbe6864780a47d9ba9e671b8f8

## ✍️ 주요 기능

* **식이 관리**

  * 영양 성분표 기반으로 탄수화물, 지방, 단백질 등의 함유량을 계산 및 몸 상태에 맞는 수치 업데이트

* **몸 상태 & 관리 루틴 제시**

  * BMI 지수, 근육량, 체지방량 기록 후 수치 예측 및 목표 수치 제시


* **몸 상태 비교**

  * 눈바디 사진첩 생성 후 몸의 변화 관찰


* **운동 도우미**

  * 사용자의 음성 인식 기반으로 횟수 기록

<br/>

## 👩‍👩‍👧‍👧 About Project

> 숭실대학교 소프트웨어학부 2020-1 소프트웨어 프로젝트
<br/>

## 💁 팀 구성
  * **김승지: Project Manager & Design Administrator**

    * ` UI `, ` Firebase ML KIT Manager `, ` OpenCV `

  * **박재희: Design Administrator**

    * ` UI `, ` Firebase Database Manager `

  * **허예은: firebase Connect Manager**

    * ` Firebase ML KIT Connect Manager `, ` OpenCV ` , `Schedule Manager`

  * **박정아: Server Manager & Database Administrator**

    * ` Firebase Database Manager `, ` Schedule Manager `

<br/>

## ⏰   프로젝트 일정
> 추후 업로드 예정

<br/>


## 👩🏻‍💻  개발 환경 (추후 변동 가능)
* Android Studio

* Firebase Database

* Firebase Authentication (oauth)

* Firebase ML KIT - Text Recognition


<br/>

## ✏️  브랜치 전략
> Git Branch 전략

  * ` master `

    * 서버 연동 브랜치
    * 회의록 업로드 브랜치

  * ` dev `

    * new content 업로드 브랜치. pull request를 생성 후 통과된 폴더 및 파일만 'master'에 merge

 *  ` 팀원명 `

    * 새로운 기능을 추가할 때 생성하는 브랜치. 기능이 완성되면 'dev' 브랜치에 merge

<br/>

> Commit Chart
>  > 프로젝트 완성 후 업로드 예정

<br/>

## ⚒   Project Architecture

> Service Architecture

![image](https://user-images.githubusercontent.com/43927910/77143955-0221e280-6ac8-11ea-8338-da5ff079bb4c.png)

> DB Architecture

![Database Shcema-4 (1)](https://user-images.githubusercontent.com/28800101/82138942-4ed33100-985f-11ea-837e-d806b386469d.png)

* **User**
  * 사용자의 아이디와 비밀번호, 해당 사용자 데이터가 가지고 있는 하위 정보
* **RecDailyIntake**
  * 사용자의 정보를 바탕으로 사용자가 섭취해야 하는 영양성분의 총량
* **DailyIntake**
  * 스캔한 영양 성분표에 기재된 정보, 섭취한 성분의 숫자 데이터 값
* **TotalDailyIntake**
  * 스캔한 영양 성분표를 기준으로 한 사용자가 실제 섭취한 영양 성분의 총량

<br/>

- Firebase Authentication
  - ` User Info `

- Firebase Cloud
  - ` ML Kit Module `

<br/>

 ## 🗞  Reference Lists
  - **개발 환경**
    - [Firebase Documentation](https://firebase.google.com/docs/ )
    - [Firebase ML kit - Text Recognition (Android Version)](https://firebase.google.com/docs/ml-kit/android/recognize-text)
    - [Firebase Database Read and Write](https://firebase.google.com/docs/database/android/read-and-write?hl=ko )
    - [Firebase Authentification](https://firebase.google.com/docs/auth/android/firebaseui )
    - [Firebase Text Recognition Test Github - yeeun]( https://github.com/yeahsilver/hText-Recognition-Test)
    - [Google Cloud STT Test version Github - seungji]( https://github.com/seungjikim/Speech_to_text )
    - [스캔 이미지 처리](https://www.opentutorials.org/module/3811/25283)
    - [Tess two를 이용한 ocr 앱 만들기 문자 인식](https://hjiee.tistory.com/entry/Android-TessTwo를-이용한-OCR-앱-만들기문자인식)
    - [Tenserflow를 이용한 object recognition](https://cloud.google.com/solutions/creating-object-detection-application-tensorflow?hl=ko)
    - [Tesseract 개발환경 만들기](https://junyoung-jamong.github.io/computer/vision/2019/02/07/Android-Tesseract-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0.html)
    - [Camera X](https://developer.android.com/training/camerax)
    
  - **오픈소스**
    - [Android Chart](https://github.com/PhilJay/MPAndroidChart)



<br/>  

## 📑  회의록
- [2020년 3월 15일 월요일 회의록](./meeting-record/20200315.md )
- [2020년 3월 22일 일요일 회의록](./meeting-record/20200322.md)
- [2020년 3월 30일 화요일 회의록](./meeting-record/20200331.md )
- [2020년 4월 6일 월요일 회의록](./meeting-record/20200408.md)
- [2020년 4월 27일 월요일 회의록](./meeting-record/20200427.md)
- [2020년 5월 4일 월요일 회의록](./meeting-record/20200504.md)
- [2020년 5월 13일 월요일 회의록](./meeting-record/20200513.md)
- [2020년 5월 18일 월요일 회의록](./meeting-record/20200518.md)
- [2020년 5월 25일 월요일 회의록](./meeting-record/20200525.md)
