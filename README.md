# HAE

#### How About Exercise?(Back-end)
#### This is a project from 2020.07 ~ 2020.08

Web, REST(CRUD) 등 관련 개념이 없었을 당시 개발했었던 Back-end 서버(Django 활용)

### [포스트](https://github.com/KimUJin3359/HAE_back_end/blob/master/HAE_%ED%8F%AC%EC%8A%A4%ED%84%B0.pdf)

### 프로젝트 개요
![SW경진대회_작품설명서_HAE (1)_page-0003](https://user-images.githubusercontent.com/50474972/109842392-6021e880-7c8d-11eb-849d-fa9466f064e7.jpg)

### 작품 구성
![SW경진대회_작품설명서_HAE (1)_page-0004](https://user-images.githubusercontent.com/50474972/109842471-73cd4f00-7c8d-11eb-8640-7ad16526691f.jpg)
![SW경진대회_작품설명서_HAE (1)_page-0005](https://user-images.githubusercontent.com/50474972/109842485-75971280-7c8d-11eb-951f-f7ba86b2772c.jpg)

### 결과물
![SW경진대회_작품설명서_HAE (1)_page-0007](https://user-images.githubusercontent.com/50474972/109842623-995a5880-7c8d-11eb-9a76-6e6bf4cf421f.jpg)

#### [영상 링크](https://www.youtube.com/watch?v=NVYHjHHro0A&feature=youtu.be)

### 관련 코드
- [DB_model](https://github.com/KimUJin3359/HAE_back_end/blob/master/HAE_DB/models.py)
  - 데이터베이스 모델 설정
  - 관련 기능 설정
- [DB_serializer](https://github.com/KimUJin3359/HAE_back_end/blob/master/HAE_DB/serializers.py)
  - data를 받아오기 위한 설정
- [DB_views](https://github.com/KimUJin3359/HAE_back_end/blob/master/HAE_DB/views.py)
  - 각 기능에 맞춰 작업을 수행(조회, 생성, 수정, 삭제)
  - 후에 알게된 것이지만 데이터를 일괄 업데이트 할 때는 PUT, 개별로 업데이트 할 때는 PATCH 사용
- 서버 작동 : nginx 사용
