# 처음 시작하는 HTML과 CSS 
## 개발 환경 설정
> 모던 웹브라우저 설치 (크롬, 파이어폭스)  
> 확장 프로그램 설치
>> Web Developer  
>> Headingmap
>> Open Wax 
> Visual Studio Code 설치
> 확장 프로그램 설치  
>> Live Server  
>> Auto Close Tag
>> Auto Rename Tag

## CLI 명령어
* mkdir(디렉토리 생성)  
* cd (디렉토리 이동)
* rmdir (디렉토리 삭제)
* touch (빈문서 생성)
* echo (파일 생성과 내용입력)
* cp (파일복사)
* mv (파일이동 및 이름변경)

## Git의 활용
**git init : 저장소 초기화**  
**git status : 상태확인**  
**git add : 인덱스로 이동**  
**git commit -m : 커밋 및 메세지 입력**  
**git push : 원격 저장소로 이동**  

## 웹표준과 웹접근성
1. 웹표준  
* HTML(구조)  
* CSS(디자인)
* Javascript(동작)
2. 웹접근성
> 장애와 비장애 모두를 만족시키기 위한 노력

## HTML 기본 문법
```HTML
<!DOCTYPE html>
<html lang="ko-KR">

<head>
    <meta charset="UTF-8">
    <title>기본 구조</title>
    <link rel="stylesheet" href="css/style.css">
</head>

<body>
    <h1>커피</h1>
    <p>커피는 마시면 기운이 솟아나요... ^^*</p>
</body>

</html>
```

---
``` CSS
@charset "utf-8";
h1 {
    background-color: yellow;
}

p {
    background-color: pink;
}
```
