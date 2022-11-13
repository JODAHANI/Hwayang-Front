# 화양교회 예배 신청

**현재 vonage 계정 문제로 인증 불가**

(기존 계정이 로그인 불가 라는 메세지가 떠서 vonage 측에 문의 넣은 상태입니다.)

> 화양교회 : 현장 예배를 신청하고 관리하는 웹 서비스 입니다. (모바일, 데스크톱 다 사용 가능합니다.)
> 

[화양교회 예배신청 페이지](http://hwayang.du.r.appspot.com/)

[https://github.com/JODAHANI/Hwayang-worship](https://github.com/JODAHANI/Hwayang-worship)

⛪️ 프로젝트 소개 

- MVC 디자인 패턴을 사용하여 구축.
- vonage API를 사용하여 휴대폰 인증 구현.
- 화양교회 예배 신청은 코로나로 인해 800명의 인원 중 200명의 인원만 예배가 허용되어 만들게 되었습니다.
- 중복 신청 및 페이크 인증을 방지하기 위해 휴대폰 본인 인증을 거친 뒤 예배 신청이 가능하며 신청 결과를 확인할 수 있습니다.
- 관리자가 예배명, 신청시간 등 손 쉽게 수정이 가능하며 관리자가 설정한 시간 이후에 성도들이 예배 신청을 할 수 있도록 만들었습니다.
- 관리자가 예배 신청한 인원들을 간편하게 확인 가능하며 관리 감독 가능합니다.

## 🛠 기술스택

FrontEnd :  `EJS` `CSS` `Javascript`

Server : `Express.js` `Google Cloud Platform`

Database : `MongoDB`

Repository : `Github`

## 🎖  참여 인원

- Design & 기획 : 조다한
- Frontend : 조다한
- Backend : 조다한

---

## 🕹 주요기능

- 예배신청
    - 예배 신청 클릭 → 휴대폰 번호 입력 및 인증 → 이름, 직분, 예배 타임 작성 후 클릭→ 신청완료.
    - (휴대폰 번호를 입력할 때 ex) 010-7767-4478 , 01077674478 다 가능합니다. )
    
    ![ezgif.com-gif-maker.gif](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ecfe6975-2f49-4a30-934b-e6f54f7e12dc/ezgif.com-gif-maker.gif)
    
    ![IMG_0260.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cf78b777-57b1-4289-9f91-1e2f7e596894/IMG_0260.jpg)
    
    - 관리자가 설정한 시간 전에 접속하지 못하도록 구축.
    
    ![대기.gif](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/84326026-597f-41be-b04e-175d798fcca9/%E1%84%83%E1%85%A2%E1%84%80%E1%85%B5.gif)
    
- 신청결과
    - 신청결과 클릭 → 이름과 번호 입력 → 결과확인.
    - ( 번호를 입력할 때 ex) 010-7767-4478, 01077674478  다 가능합니다. )
    
    ![ezgif.com-gif-maker.gif](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a628070b-b206-42e4-8133-3c3806a0458a/ezgif.com-gif-maker.gif)
    
- 관리자
    - 관리자 페이지 로그인 → 참석자 명단 →  타임별 참석자 확인.
    - ( 우측 x 버튼으로 관리자가 예배 취소 가능. )
    
    ![참석명단.gif](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bfe63169-db85-49de-81aa-a0a765a2b448/%E1%84%8E%E1%85%A1%E1%86%B7%E1%84%89%E1%85%A5%E1%86%A8%E1%84%86%E1%85%A7%E1%86%BC%E1%84%83%E1%85%A1%E1%86%AB.gif)
    
    - 다음주 예배 및 일정을 수정하고 싶은 경우  :  수정하기 → 예배명,  신청날짜 및 시간 입력→ 수정 버튼 클릭
    - 예배 신청자를 초기화 하고 싶은 경우 : 초기화 → ok버튼 클릭. → 초기화 완료.
    
    ![2.gif](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7ef05a0d-5feb-4a47-9992-88403e10eabd/2.gif)
    
- 모바일 최적화
    - 미디어 쿼리를 통한 모바일 대응
        
        ![ezgif.com-gif-maker.gif](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/dd35a2d3-7a49-4bdf-b31d-a0018d69072d/ezgif.com-gif-maker.gif)
        
- SEO 적용
    - openGraph 적용
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/39905c8c-0968-49a6-8f08-920337ccbd9e/Untitled.png)
    
    - twitter 적용
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2244f957-3a27-4973-a40f-aecbd0f76a86/Untitled.png)
    
    - 기타 메타 데이터 적용

## 관리자 계정

- ID : master
- PW : 화양1004(화양은 영문으로 타이핑.)

## 앞으로 개발할 기능

- [ ]  다국어 지원 페이지 [ 영어, 중국어 ]
- [ ]  예배 참석한 인원들 체크 및 관리페이지
