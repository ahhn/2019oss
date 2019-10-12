# 전자기록과 활용소프트웨어
2019년 2학기 한국외국어대학교 정보기록학과 강의자료

#### 강의소개
이 강의는 전자기록을 다룰 때 필요한 소프트웨어의 개념을 익히고 실습을 통해 심화 학습하도록 구성됩니다. 
전체 강의 중 6강은 온라인 퍼블리싱 소프트웨어인 오메카(Omeka)에 배정되어 있습니다. 
수강생들은 한 학기 동안 특정 주제를 아카이빙한 후 자신의 아카이브 사이트로 만들어 봅니다.
그 외에 클라우드 컴퓨팅(AWS), 온라인 카탈로그(AtoM), 장기보존(Archivematica, BagIt), 데이터세트 보존(SIARD), 메타데이터 추출 및 무결성 검증(VeraPDF), 웹 아카이빙(Zotero) 등 대표적인 오픈소스 소프트웨어를 실습해 봅니다.

#### 강의교재
https://ahhn.github.io/2019oss/

#### 참고문헌
- 안대진, 임진희. (2016). 디지털 아카이브 시스템 구축을 위한 공개 소프트웨어 활용방안 연구. 정보관리학회지, 33(3), 345-370.
- 안대진, 임진희. (2017). 기록시스템의 오픈소스화 전략 연구. 기록학연구, 52(3), 119-170.
- 안대진, 임진희. (2017). 제4차 산업혁명 기술의 기록관리 적용 방안. 기록학연구, (54), 211-248.
- 김인택, 안대진, 이해영. (2017). 인공지능을 활용한 지능형 기록관리 방안. 한국기록관리학회지, 17(4), 225-250.


#### 과제 및 평가
##### 과제 : 디지털 아카이브 만들기
1. 디지털 아카이브 사례조사 발표 (20분) : 발표문 제출
2. 아카이빙 계획 발표 (20분) : 아카이빙 계획서 제출
3. 아카이빙 결과 발표 (20분) : 결과보고서 제출

##### 평가요소
발표내용 및 자료제출(90%), 출석(10%)


# 주별 강의계획
## Week 1. 전자기록 활용소프트웨어 개론
1. 디지털 보존(Digital Preservation) 개요 (OAIS, TRAC, E-Ark 등) : [다운로드](https://github.com/ahhn/2019oss/raw/master/lecture/lecture01_DP.pdf)
2. 전자기록 활용소프트웨어 소개
3. 과제 안내

-----
학기과제 : 디지털 아카이브 만들기
- 아카이빙 계획서 작성방법
  - 개요 : 아카이빙할 주제에 대한 간단한 에세이(배경, 의미 등)
  - 키워드 : 해당 주제와 관련된 키워드 나열(문헌, 연구사례 등을 참고)
  - 범위와 목적 : 해당 주제의 시간/공간/내용적 범위, 아카이빙을 통해 이루고자 하는 목적
  - 컬렉션 구성(영역별 수집대상) : 수집할 컬렉션 영역을 3~5개 정하고 컬렉션별로 대표적 기록을 나열

- 아카이빙 계획서 샘플
  - [대학그룹사운드](https://github.com/ahhn/2018Omeka/raw/master/lecture/plan_sample01_WH.pdf)
  - [슈퍼맨](https://github.com/ahhn/2018Omeka/raw/master/lecture/plan_sample02_Superman.pdf)
  - [봉봉](https://github.com/ahhn/2018Omeka/raw/master/lecture/plan_sample03_vongvong.pdf)
  - [일상의 앰비언스](https://github.com/ahhn/2018Omeka/raw/master/lecture/plan_sample04_Ambience.pdf)

-----
주별과제 : 
- COPTR, POWRR, E-Ark 프로젝트 조사
  - 프로젝트 개요(참여단체, 기간, 펀딩, 목표)
  - 주요과제 및 산출물
  - 시사점
- Omeka 프로젝트 소개
  - 프로젝트 개요(언제, 누가, 왜 만들었는지)
  - 주요 컬렉션
  - 장단점
- Omeka 플러그인 소개
- Archivematica 소개
- BagIt 소개
- SIARD 소개
- VeraPDF 소개
- Zotero 소개

-----

## Week 2. 오픈소스 소프트웨어와 클라우드 컴퓨팅 I
1. 오픈소스 소프트웨어(OSS) 개요 : [다운로드1](https://github.com/ahhn/oss/raw/master/resources/OSS1.pdf)
2. 클라우드 컴퓨팅 개요 : Iaas, PaaaS, SaaS
3. AWS를 이용한 클라우드 서버 구축
- AWS 계정 만들기
- EC2 서버 인스턴스 생성
- Ubuntu Server 설치
4. 과제발표
- 아카이브에 유용한 소프트웨어 소개하기 (COPTR 레지스트리에서 검색)
  - 툴 브라우징한 방법
  - 툴 Description
  - 툴 기능
  - 첫 화면 스크린샷
  - 설치 과정 설명
  - 아카이브 업무 활용방법
- 박해경 : [보고서](https://github.com/ahhn/2019oss/raw/master/lecture/park_coptr.pdf)
  - ImageMagick
  - Metadata Interrogator v1.07
- 이충호 : [보고서](https://github.com/ahhn/2019oss/raw/master/lecture/lee_coptr.pdf)
  - Exif to DC XML Normalizer
  - ExifTool
  - KOST
- 최현균 : [보고서](https://github.com/ahhn/2019oss/raw/master/lecture/choi_coptr.pdf)
  - Disk Image Chef
  - Rescarta

- 토론 (소프트웨어 레지스트리 장단점)
  - 1. 이용자(아키비스트와 일반인 모두 해당)가 이해하기 어려운 수준(설치나 구동환경 등 소프트웨어에 대한 이해가 필요함)
    - 답변 : 설치를 쉽게 하도록 지원해야 함
      - ex1. 데모사이트 제공
      - ex2. Docker 버전 지원
      - ex3. API 제공
      - ex4. 구독 서비스 제공
  - 2. 사용방법 구체적으로 제공하면 좋겠음(스크린샷 등 풍부하게 제공했으면 함. 텍스트 중심 설명)
    - 답변 : 레지스트리는 공동활용, API제공 등을 고려하여 텍스트 중심으로 운영될 수밖에 없음. 자세한 설명은 툴별 홈페이지에서 제공함
  - 3. 분류방법 혼동 : A툴이 여러 분류에 속하거나, 분류기준이 모호한 경우가 많음
    - 답변 : 
      - COPTR/POWRR를 1차 참고도구 정도로 활용해야 함
      - 소프트웨어 정보를 적극적으로 게시해야 함(우리나라에서도)

## Week 3. 오픈소스 소프트웨어와 클라우드 컴퓨팅 II
1. AWS를 이용한 클라우드 서버 구축
- Ubuntu Server 설치
- AMI(Amazon Machine Image)로 어플리케이션 설치(WordPress, Omeka 등) 
  - [Omeka v2.6.1 설치 매뉴얼](https://osasf.net/uploads/FileUpload/5c/770f29d1b1d235ce9b9d938519dfef.pdf)
  - [AWS, Omeka, Filezilla 설치 매뉴얼](https://github.com/ahhn/2019oss/raw/master/lecture/02_AWS_v2.0.pdf)
  - [AWS, Omeka, Filezilla 동영상 강좌](https://www.youtube.com/watch?v=eaw7rN_O6LM&list=PLya-3fVEf50Zj0bfFbkRpxuwO6J9mh4Pf)
2. GitHub 리포지터리 만들기 실습
3. 디지털 아카이브 사례와 아카이빙 주제발표 I
- 최현균 : [광화문 아카이브](https://github.com/ahhn/2019oss/raw/master/lecture/choi_plan.pdf)
- 이충호 : [대진대학교 사학과 사진아카이브](https://github.com/ahhn/2019oss/raw/master/lecture/lee_plan.pdf)
- 박해경 : [출근길 아카이브](https://github.com/ahhn/2019oss/raw/master/lecture/park_plan.pdf)

## Week 4. 오픈소스 소프트웨어와 클라우드 컴퓨팅 III
1. AWS를 이용한 클라우드 서버 구축
- SSH Client(Putty) 설치
- 리눅스 명령어 실습
- FTP 클라이언트(Filezilla) 설치
- 어플리케이션 설치(Omeka) 
2. 디지털 아카이브 사례와 아카이빙 주제발표 II

## Week 5. 온라인 퍼블리싱 소프트웨어 - Omeka 1
1. Omeka 동향과 활용 : [다운로드](https://github.com/ahhn/2018Omeka2/raw/master/lecture/Lecture01_Introduction_to_Omeka.pdf)
2. 아카이브 개요 : [다운로드](https://github.com/ahhn/2018Omeka2/raw/master/lecture/Lecture00_Archives.pdf)
3. Omeka 실습 : 플러그인, 테마, 아이템, 컬렉션, 전시
4. 디지털 아카이브 사례와 아카이빙 주제발표 III
박해경 - OO Archive
- 아카이브 개요(누가, 언제, 왜 만들었나)
- 주요 컬렉션 (대표 컬렉션 목록과 간략소개)
- 특징 (기능, 컬렉션 구성, 서비스 등 여러 측면의 장단점)
이충호 - OO Archive
최현균 - OO Archive

참고 사이트 : 
[Omeka Showcase](https://omeka.org/classic/showcase/)
[Omeka Directory](https://omeka.org/classic/directory/)

## Week 6. 온라인 퍼블리싱 소프트웨어 - Omeka 2
Omeka 실습 : 플러그인 I - CSV Import
- Blog Shortcode
- Bulk Metadata editor - COinS
- Collection Tree
- Commenting
- Connected Carousel - Contribution
- Contributor Contact - Corrections
- CSV Export Format

## Week 7. 온라인 퍼블리싱 소프트웨어 - Omeka 3
Omeka 실습 : 플러그인 II - Derivative Images
- Docs Viewer
- Elasticsearch
- Element Type
- Embed Codes
- Exhibit Image Annotation - Geolocation
- Guest User
- Heist
- Hide Elements
- History Log
- HTML5 Media

## Week 8. 온라인 퍼블리싱 소프트웨어 - Omeka 4
Omeka 실습 : 플러그인 III 
- Item Order
- Item Relations
- Neatline
- Posters
- Reports
- Scripto
- AvantRelationships - Ngram
- Text Analysis

## Week 9. 온라인 카탈로그 소프트웨어 - AtoM 1
1. ICA 국제기술표준 (ISAD(G), ISAAR-CPF, ISDF, ISDIAH) 
2. AtoM 개요
3. AtoM 실습 : ISAD(G)

## Week 10. 온라인 카탈로그 소프트웨어 - AtoM 2
AtoM 실습 : ISAAR-CPF, ISDIAH

## Week 11. 장기보존 소프트웨어 - Archivematica, BagIt
1. Archivematiac 개요
2. 장기보존 패키지 개요 (NEO, NEOx, VEO2, VEO3, BagIt, XIP) 
3. 실습 : Base64 인코딩
4. 실습 : 장기보존패키지(AIP) 만들기

## Week 12. 데이터세트 보존 소프트웨어 - SIARD
1. E-Ark 프로젝트 개요 
2. 실습 : SIARD viewer

## Week 13. 메타데이터 추출 & 무결성 검증 소프트웨어 - NARA File Analyzer & VeraPDF
1. NARA File Analyzer and Metadata Harvester 실습 : 메타데이터 추출, SHA-256 
2. VeraPDF 실습 : PDF 무결성 검증

## Week 14. 웹 아카이빙 소프트웨어 - Zotero, PageCrawler
1. Zotero : 웹 아카이빙 컬렉션 만들기, RDF 추출하기 
2. PageCrawler : 웹페이지 크롤링, WARC 포맷 만들기

## Week 15. 아카이빙 결과 발표 I
디지털 아카이브 구축 결과 발표 I

## Week 16. 아카이빙 결과 발표 II
디지털 아카이브 구축 결과 발표 II
 
    














































# 참고자료

[강의자료1. Omeka 동향과 활용 (다운로드)](https://github.com/ahhn/2018Omeka2/raw/master/lecture/Lecture01_Introduction_to_Omeka.pdf)

[강의자료2. 오픈소스 소프트웨어 개요 (다운로드)](https://github.com/ahhn/oss/raw/master/resources/OSS1.pdf)

[강의자료3. 아카이브 개요 (다운로드)](https://github.com/ahhn/2018Omeka2/raw/master/lecture/Lecture00_Archives.pdf)

[강의자료4. Omeka CSV목록 (다운로드)](https://github.com/ahhn/2018Omeka2/raw/master/lecture/catalog.csv)

[강의자료5. AWS, Omeka, Filezilla 동영상 강좌](https://www.youtube.com/watch?v=eaw7rN_O6LM&list=PLya-3fVEf50Zj0bfFbkRpxuwO6J9mh4Pf)

[강의자료6. AWS, Omeka, Filezilla 매뉴얼](https://github.com/ahhn/2018Omeka2/raw/master/lecture/AWS_v1.9.pdf)

[강의자료7. 더블린 코어(Dublin Core) 설명](https://www.nl.go.kr/standards/dublincore/dublinCoreDcmes.do)

[강의자료8. Omeka CSV목록 - 위치정보추가](https://github.com/ahhn/2019Omeka/raw/master/lecture/catalog2.csv)


## 1.Omeka 소개

**1.1 Omeka 개요**
- 도서관, 박물관, 아카이브의 기록 컬렉션을 쉽게 큐레이션하기 위한 웹 퍼블리싱 소프트웨어

**1.2 개발주체 및 이용자 현황**
- 2008년 미국 조지메이슨대학의 역사뉴미디어센터(RRCHNM, Roy Rosenzweig Center for History and New Media)가 개발
- RRCHNM은 미국 내 역사교육 및 디지털 인문학 분야에서 주도적인 역할을 수행
- 출시 이후 omeka.net은 전 세계 45,000명이 넘는 사용자와 3만 개 이상의 사이트로 성장

**1.3 프로젝트의 배경과 목적**
> “ To preserve and present history online ”
- Omeka 프로젝트는 IT 비전공자인 GLAM기관(Gallery, Library, Archives, Museum)의 직원이 소장물을 쉽게 온라인 콘텐츠로 작성하고 많은 이용자들을 참여시키는 것을 목표로 한다. 따라서 관리자 페이지와 서비스 페이지 모두 아주 직관적인 이용자 인터페이스를 제공하며 어노테이션(annotation) 등 다양한 웹 2.0 기술을 적용하였다. 

![Alt text](https://omeka.org/images/omeka-classic.png)


## 2. Omek로 디지털 아카이브 만들기
### 순서
- 2.1 주제 선정
- 2.2 기록 수집/생산
- 2.3 에세이(Curator’s essay) 작성
- 2.4 omeka 로그인
- 2.5 아이템(Items) 등록
- 2.6 컬렉션(Collections) 등록
- 2.7 전시(Exhibits) 구성
- 2.8 사이트 꾸미기


### 2.1. 주제 선정 ###
- 아카이빙 대상 또는 주제 선택
- 주제 참고: [서울역사박물관 서울역사아카이브](http://www.museum.seoul.kr/archive/NR_index.do)

  - ex. [신림동 청춘 : 고시촌의 일상](http://www.museum.seoul.kr/common/file/NR_download.do?id=e42dcc9e-4d84-4de3-a8fc-848a5bc87d8f)
<img src="http://www.museum.seoul.kr/upload/bbs/2015/10/12/1f25a39d-4f9e-4aab-81e8-f886dfdc7aeb.jpg">
출처: 서울역사박물관
  

### 2.2. 기록 수집/생산 ###
- 수집 : 관련기록을 소장하고 있는 개인/단체/기관로부터 소장기록 수집(기증, 구매, 대여 등)
- 생산 : 사진/영상 촬영, 구술(oral history), 필드레코딩

<img src="http://s3.amazonaws.com/quietus_production/images/articles/11222/Chris_Watson_mic_1359033297_crop_550x385.jpg">
그림. 필드레코딩 중인 Chris Watson
출처: https://thequietus.com/articles/11222-chris-watson-interview-sound-recording-cabaret-voltaire


### 2.3. 에세이(Curator’s essay) 작성 ###
> 헤르만 헤세의 책 제목처럼 청춘은 아름답습니다. 그리고 뜨 겁습니다. 그러나 미래를 준비해야 하기에 고달프고 불안한 시기이기도 합니다. 미래가 불투명할수록 고단함과 불안함 은 더합니다.

> 관악산기슭,도림천옆에자리잡은신림동은그런청춘들 이 머물다 가는 동네입니다. 전국에서 젊은이들의 거주비율 이제일높습니다.집성촌마을들이있던이곳은서울이급 성장을 시작한 1960년대 후반 잇따른 개발 사업으로 도심에 서 쫓겨난 철거민들의 이주정착지가 되었고 1975년 서울대 학교가 옮겨오고 나서는 대학생들의 하숙촌이 되었습니다. 이어서 당국의 강북개발억제책에 따라 고시학원들이 옮겨 오고 고시준비생들도 모여들면서 신림동은 고시촌으로 자 리 잡게 되었습니다.

> 거대도시로 자라난 서울에서 신림동은 한 작은 동네일 뿐입 니다.그러나여기에도서울이겪어온역사의큰흐름이아 로새겨져 있습니다. 서울의 급성장에 따른 강제철거와 이주, 서울대학교의 이전과 권위주의에 대한 저항은 체제 내 입신 을 꿈꾸는 또 다른 열망과 교차되었습니다. 신림동 서점에는 금지된 사회과학서적과 함께 고시서적도 있었고 운동권 학 생들이 기염을 토하던 녹두거리의 주점은 고시생들이 피로 를 푸는 곳이기도 했습니다. 형태는 달라도 신림동은 미래를 향한 열망과 인고의 공간이었던 것입니다.

> 이런 신림동에 새로운 변화의 물결이 닥치고 있습니다. 로스 쿨이 고시를 대체하도록 제도가 바뀌면서 고시촌 신림동이 존폐위기에서게된것입니다.기존의고시원은1인가구의거 주공간으로 바뀌거나 아예 문을 닫은 곳도 늘고 있습니다. 우 리 청춘들에게 다가올 미래가 어떤 것일지 예단하기 어려운 것처럼 신림동의 미래도 알기 어렵습니다.

> ‘신림동 청춘’은 이 특별한 동네의 형성·변천사를 배경으로 고시촌에서의 일상을 조명하고 있습니다. 이를 통하여 젊은 세대의 삶과 한 동네의 성격이 어떻게 시대상황과 만나 적응 하고 변화해 가는지 살펴보려는 것입니다. 서울의 이해에 도 움이 되는 전시이기를 바라 마지않습니다.

출처: 서울역사박물관 기획전 '신림동 청춘(15.9.11~11.8)' 전시도록
http://www.museum.seoul.kr/common/file/NR_download.do?id=e42dcc9e-4d84-4de3-a8fc-848a5bc87d8f



### 2.4. omeka 로그인 ### 
- 실습 사이트 주소 : [http://13.209.4.170](http://13.209.4.170)

1) 상단 로그인 클릭

2) 회원 아이디 : 본인 이메일 앞자리(abc@naver.com의 경우 abc)

3) 패스워드 : ******

4) 상단 관리자모드 클릭


### 2.5. 아이템(Items) 등록 ### 
#### 옵션1. 개별 등록(아이템 1개씩 직접 등록) #### 
1) 좌측 'Items' 클릭

2) Add an Item 클릭

3) Dublin Core(더블린코어) : 15개 메타데이터 작성 (Title, Description, Creator, Date, Identifier, Rights는 필수)
- Rights는 Creative Commons를 적용(http://www.cckorea.org/xe/ccl)
- 하단 우측 'CCL 적용하기' 클릭 > 하단 HTML코드 복사 > Omeka의 Rights 필드에 붙여넣기 > Use HTmL 체크

4) Item Type Metadata : 특별한 유형의 기록을 등록할 경우 아이템 타입(Item Type)을 선택하여 메타데이터 작성

5) Files : 파일 첨부(최대 100MB, 복수등록 가능)

6) Tags : 태그 등록. 쉼표로 구분 (ex. 벽화, 거리)

7) Map : 위치 등록. 지도 상의 특정 위치를 더블클릭하여 포인터 만들기

8) Public : 체크하면 해당 아이템 공개, 체크 안하면 로그인한 사용자에게만 공개

9) Featured : 체크하면 메인화면의 대표 아이템으로 등록 (복수 선택 시 랜덤으로 노출)

10) Owner : 해당 아이템의 소유자 선택

11) Collections : 해당 아이템이 속한 컬렉션 선택 (상위컬렉션이 있을 경우 최하단의 컬렉션 선택)

12) 'Add Item' 클릭


#### 옵션2. 엑셀파일로 등록(복수의 목록과 파일을 한꺼번에 등록) #### 
1) 엑셀 목록 작성 (목록의 files 컬럼에 첨부파일의 URL을 입력하면 목록과 파일을 동시에 업로드)

2) CSV로 저장
- Microsoft 엑셀은 한글이 깨짐. csv 파일을 메모장으로 열어서 한글 인코딩을 UTF-8로 변경 후 다시 csv로 저장
- LibreOffice를 사용하면 한글 깨짐 안생김
  - LibreOffice 다운로드 주소 :  https://ko.libreoffice.org/download/libreoffice-fresh/


3) 첨부파일 업로드

첨부파일을 인터넷 특정 저장소에 미리 업로드한 후 URL을 목록에 연결

- FileZilla 설치 : https://filezilla-project.org/ > Download FileZilla Client > 설치 및 실행
- 사이트 관리자 > 새 사이트 
  - 호스트 : 54.180.85.53
  - 프로토콜 : SFTP
  - 로그온 유형 : Key file
  - 사용자 : root
  - Key file : Browse 클릭 > .ppk 파일 선택(별도 제공)
  - 연결
  - 리모트 사이트 : /var/www/omeka/files/hansung2019/
  - 폴더 만들기 : 우측 하단 빈공간 우클릭 > 디렉토리 만들기 > 본인의 폴더 만들기(영문 소문자나 숫자, ex. djahhn)
  - 파일 업로드 : 파일명을 아이템의 식별자(Identifier)명과 동일하게 미리 변경 후 업로드 (ex. djahhn0001)
  - 파일 URL 따내기 : http://54.180.85.53/files/hansung2019/kim/djahhn0001.jpg

4) Omeka 관리자 페이지 좌측 'CSV Import+' 클릭

5) Import > Upload CSV file* > 파일 선택 > CSV파일 선택

6) Import >  Item type > 특정 유형의 아이템일 경우에만 선택

7) Import > Collection > 해당 아이템들이 포함될 컬렉션 선택(여러 컬렉션에 포함될 경우 선택하지 말 것)

8) Import > Next 클릭

9) Import > 메타데이터 컬럼 매핑 : 좌측 csv파일의 컬럼명과 Omeka의 Element 명칭을 매핑
- Special values : 식별자(Identifier, Files, Tags 등 특수한 메타데이터일 경우에 선택)

10) Import > Import CSV file

11) Status > Completed로 바뀌면 등록 완료된 것임 ('Undo Import'를 클릭하면 방금 등록된 전체 목록이 삭제됨)

12) 좌측 Items 탭을 클릭하여 아이템 등록 


### 2.6. 컬렉션(Collections) 등록 ### 
1) Collections 클릭

2) Add a Collection 클릭

3) Dublin Core 입력
- Title : 컬렉션 제목 
- Description : 컬렉션 소개글 작성

4) Parent Collection 설정 : 상위 컬렉션이 있을 경우에 선택

5) Public(공개여부), Featured(메인페이지 노출여부) 체크

6) Owner 선택 : 컬렉션의 소유자 선택


### 2.7. 전시(Exhibits) 구성 ### 
- [전시 구성하기 매뉴얼_영문](https://info.omeka.net/build-a-website/manage-plugins/exhibit-builder-3/)

1) 전시(Exhibit) 개요
- Omeka 전시는 등록된 기록 아이템들 중 핵심기록을 선별하여 글과 함께 보여주는 온라인 전시 콘텐츠이다.
- Omeka의 각 전시는 하위에 여러 계층의 페이지(Page)를 둘 수 있고, 각 페이지는 복수의 콘텐츠 블록(content block)으로 구성된다.
- 콘텐츠 블록은 기록, 텍스트, 기록+텍스트, 지도 등의 콘텐츠에 적합한 여러 레이아웃을 선택 및 배열하여 구성한다.

<img src="https://s3.amazonaws.com/libapps/accounts/17288/images/ExhibitBuilder3structure.png">
이미지 출처: https://libguides.whitman.edu/omeka/docs


2) 전시(Exhibit) 생성
- 좌측 Exhibits 클릭
- Add an Exhibit
- 전시정보 작성
  - Title : 전시 제목
  - Slug : 전시 URL의 뒷자리(영문소문자, 숫자 등. ex. exhibit01)
  - Credits : 크레딧 정보 (안써도 됨)
  - Description : 전시 소개문 작성
  - Tags : 태그 작성(콤마로 구분)
  - Theme : 전시 웹페이지에 사용될 디자인 테마 (전시마다 다르게 설정 가능)
  - Cover Image : 전시 커버 이미지 등록(등록 안해도 됨. 안하면 전시에 쓰인 첫번째 이미지를 사용)
- Public(공개여부), Featured(메인페이지 노출여부) 체크

3) 페이지(Page) 생성
- Add Page 클릭
- 페이지 정보 작성
  - Page Title : 페이지 제목
  - Page Slug : 페이지 URL 뒷자리 (ex. p01)
- Add Page 반복 및 페이지 계층구조 설정(페이지 내에 하위페이지가 있을 경우 페이지 박스를 상하좌우로 드래그하여 계층 조정)

4) 블록(block) 생성
- Edit Page > New Block > Select layout > 원하는 레이아웃 선택
- Add new content block 클릭 > 반복

5) 저장
- Save Changes

6) 전시 구성
- Exhibits > 원하는 전시명 하단 'Edit' 클릭
- Page명 클릭 > 콘텐츠 블록에 글을 작성하고 기록을 삽입하여 전시 콘텐츠 구성


#### 전시 샘플 ####
**Page1. 신림동 입장**
> 신림동하면 떠오르는 단어는 ‘고시촌’이다. 로스쿨 도입 전까지 이곳은 각종 고시를 준비하는 많은 청 년들이 모여들어 ‘신림동=고시촌’이라는 장소적 특성을 가졌다. 비록 서울 남부에 위치한 작은 동네 지만 전국에서 몰려온 낯선 이들의 삶으로 채워진 이곳은, ‘고시촌’이라는 명성에 걸맞게 꿈을 이루기 위한 기회의 땅으로 충실한 역할을 해왔다. 고시원, 고시학원, 고시서점, 고시식당 등 신림동 골목마다 찾아볼 수 있는 ‘고시’의 흔적들은, 꿈을 위해 잠시 젊음의 화려함을 유예해 둔 우리 시대 청춘의 삶을 증명한다.
> 그러나 신림동의 지난 세월에는 고시합격을 위해 매 진해 온 이들의 팍팍한 인생만 있는 것은 아니다. 짧 지 않은 시간 동안 신림동 사람들은 각자 그들의 방 식으로 신림동에 머물렀으며, 시대와 조응하며 신 림동의 역사를 입체적으로 형성해 왔다. 해방 후 신 림동으로 강제 이주된 철거민들은 이곳을 또 다른 고향으로 삼기 위해 노력했으며, 80년대 민주화를 갈망하던 대학생들은 이곳을 기반으로 세상과 맞서 싸웠다. 그리고 고시생이 떠난 뒤 ‘1인가구’라 불리 며 그 빈자리를 메우고 있는 현 청년들은 ‘오포세대’ 라는 자조 섞인 세상의 부름을 떠안으며 오늘도 고 군분투하고 있다. 여전히 청춘들의 인생은 신림동 에서 진행 중이다.

>> ***Block1. 벼슬산 및 신림동 고시촌의 형성***
>> ‘벼슬산’이라 불리던 관악산에는 예부터 산속 절 방한칸을얻어공부에매진하던고시수험생들이 있었다. 특히 1970년대부터 ‘돼지막’이라 불리던 무허가 건물들이 들어섰는데, 일렬로 늘어선 5~6개의 1평짜리 방에 책걸상, 침구만 놓인 단순한 형태로 어려운 공부에 집중하기엔 최적의 장소로 여겨져 고시준비생들 사이에서 이미 이름 나 있었다.
>> 1975년 서울대학교가 근처로 이전해 오자 이 일대는 하숙생을 비롯해 고시 준비생들이 더욱 많아졌으며, 1980년대 현재와 같은 고시원 형태의 건물이 50여 곳 들어서게 되어 본격적으로 ‘고시촌’을 형성했다.
>> 또한 2000년대에 들어 사법고시 응시제한연령이 폐지되고 선발인원이 1,000명에 육박하게 되면서 점점 더 많은 사람들이 이곳 고시촌으로 몰려오게 되어 그 명성이 확고해졌다.

>> ***Block2. 개천에서 용 난다 : 고시 열풍***
>> 해방 후 ‘고등고시 사법과’는 고정된 합격자 수가 있지 않아 평균 60점 이상을 획득해야 합격할 수 있는 절대점수제로 시행되었다. 그러다 1970년대가 되면 ‘사법시험’이라는 명칭 변경과 함께 법조 인력을 확대하기 위한 정원제가 실시되었다. 이후 1990년대까지 법조인 선발 수는 꾸준히 증가했고, 2000년대가 되면 선발인원이 1,000명에 육박했으며 더불어 40세였던 응시연령 제한이 폐지되면서 더욱 많은 사람들이 사법시험에 도전하게 되었다. 2002년 44회 사법시험 당시 접수자는 3만여명(최종합격자 수 998명)에 달했다. 또한 해마다 시험제도와 출제 경향이 바뀌기 때문에 독학으로 공부하는 것보다 학원과 스터디를 통해 정보를 얻고 분석하는 것이 훨씬 더 유용했다. 고시를 준비하는 이라면 으레 신림동 고시촌을 찾았고, 고시 열풍이 뜨거워질수록 신림동 고시촌의 명성도 자자해졌다.

>> ***Block3. 윗동네 아랫동네 : 고시촌의 분화***
>> 현재 신림9동을 거닐다 보면 고시촌의 과거와 현재를 비교해 볼 수 있다. 관악산을 향한 가파른 언덕길 근처의 윗동네는 1980년대 고시촌이 형성되던 초기의 중심 장소로, 과거 고시촌의 모습을짐작해볼수있다.그러나이제이곳의 고시원은 낙후된 시설과 고시생 감소로 문을 닫거나, ‘고시낭인’이라 불리는 장수생 및 기초생활 수급자, 불안정 노동자, 외국인 유학생 등이 살고 있다. 반면, 도림천과 신림로 부근 상권이 밀집되어 있는 아랫동네의 고시촌에서는 변화된 현재의
모습을 볼 수 있다. 2000년대 이후 고시생들이 점점 방음이 잘되고 깔끔하며 개인 시설을 갖춘 원룸을 선호하기 시작하면서, 1평짜리 방을 트거나 넓혀 풀옵션으로 개조한 원룸들이 들어선 것이다. 불편을 감내하며 공용 생활공간에서 공부하는 ‘배고픈 고시생’보다는, 보다 쾌적한 환경에서 공부에만 집중하길 원하는 고시생들이 많아진 것이다.



**Page2. 안녕 고시촌**
> 도림천 건너편 산등성이를 빽빽한 건물로 가득 메 운 신림9동(현 대학동)에는 ‘신림동 고시촌’이 자리하고 있다. 고시촌이 번성하던 90년대엔 주민 의 과반수가 전국 각지에서 몰려든 고시 준비생들 이었고, 주민 상당수는 이들을 대상으로 고시 관 련 시설과 각종 상권에 종사하며 신림동을 ‘고시 촌’이라는 특성화된 공간으로 만들었다.
이 일대는 전국에서 청년(25~34세) 거주비율이 두 번째로 높은 곳이지만, 그 비율이 무색하리만치 단조롭고 정체되어 보인다. 그러나 고시학원, 고시 서점, 고시뷔페 등 고시 준비를 위해 최적화된 이곳 에서 고시생들은 합격이라는 한 가지 목표를 위해 고시촌 골목 골목을 분주한 마음으로 오간다. 2000 년대 초반까지 전국의 고시생이 몰려들며 최전성기 를 누렸던 신림동 고시촌의 기억은 여전히 생생하게 동네 구석구석에 살아 있다.

>> ***Block1. 고시촌 구석구석***

>> ***Block2. 고시생 24시***

>> ***Block3. 남거나 떠나거나***


**Page3. 고시촌 너머 신림동**
> 신림동의 역사는 시대의 흐름을 연속적으로 반영 하며, 개인의 삶에 영향을 미쳐왔다. 1960~70년 대 도시개발에 밀려 쫓겨나듯 정착한 철거민의 삶 과 80년대 희뿌연 화염 속에서 민주화를 갈망하던 젊은이들의 패기, 90년대 1평짜리 작은 방에서 꿈 을 향해 숨죽이던 고시생들의 유예된 청춘, 그리고 2000년대 방황하는 1인세대의 긴 한숨까지 신림동 의 역사와 함께한 삶의 모습들이다. 미래에 대한 불 확실성을 스스로에 대한 성찰과 성실로 답한 수많은 이들과, 오늘과 다른 내일을 꿈꾸는 이들에게 신림 동은 과연 어떤 의미일까?

>> ***Block1. 집성촌에서 철거민의 마을로***

>> ***Block2. 관악캠퍼스와 신림동***


**Page4. 지금 신림동**
> 2013년 행정명 변경으로 ‘신림9동’이 아닌 ‘대학 동’으로 불리는 이곳은 고시촌으로서의 명성을 점 점 잃어가는 중이다. 2000년대 중반 사법시험 영 어대체제 도입, 2008년 로스쿨제도 도입, 2017 년 사법시험 폐지 등은 많은 고시생들이 이곳을 떠 나는 이유가 되었다. 이로 인해 고시생들을 기반 으로 한 다양한 시설들이 폐업을 하거나 규모를 축 소하고 있어 침체되어 가는 동네를 우려하는 주민 들이 많다.
현재 고시촌은 ‘1인세대’로 대표되는 이들이 새롭 게 모여들고 있다. 기존의 고시촌이 고시생들만을 위한 공간이었다면, 지금 이곳은 다양한 사람들에 게 저렴한 가격에 주거부터 일상생활까지 한 번에 해결할수있는공간으로인식되면서또다른삶 의터전이되고있다.이로써우리는최근이곳에 서 진행되고 있는 공간적 변화와 구성원 유입을 통 해, 한국 사회에서 점차 늘어나는 ‘1인가구’가 모 인 지역의 시대적 단면을 살펴볼 수 있다.

>> ***Block1. 텅빈 고시촌***

>> ***Block2. 또다른 청년들***

>> ***Block3. 청춘 고시원***

>> ***Block4. 대학동 살리기 프로젝트***


[출처: 서울역사박물관 기획전 '신림동 청춘(15.9.11~11.8)' 전시도록]
(http://www.museum.seoul.kr/common/file/NR_download.do?id=e42dcc9e-4d84-4de3-a8fc-848a5bc87d8f)



### 2.8. 사이트 꾸미기 ###
아카이브 사이트의 소개문, 로고, 디자인, 문의 이메일 정보 등을 제공해야 한다.
- [보여주기 설정](https://info.omeka.net/build-a-website/manage-appearance-settings/)
- [테마 선택](https://info.omeka.net/build-a-website/manage-themes/) 
- [메뉴 만들기](https://info.omeka.net/build-a-website/change-site-navigation/)



## 3. [부록] Omeka.net 활용방법
- [이용자 매뉴얼](https://info.omeka.net/manage-an-account/)

### 3.1 가입
- www.omeka.net 접속 > Learn which plan is right for you 클릭

![Alt text](/image/image_01.png)

- Start your free Omeka trial 클릭 (유료 계정을 만들면 더 많은 기능과 디자인 사용 가능)

![Alt text](/image/image_02.png)


- 계정 정보 작성 후 'Sign Up' 클릭

![Alt text](/image/image_03.png)


- 로그인 : MY ACCOUNT > Log In > Manage Site(관리 사이트) or View Site(서비스 사이트) 접속

![Alt text](/image/image_04.png)




### 3.2 둘러보기

- 관리자 대시보드

  - 1. 상단메뉴
    - Plugins : 플러그인 설치/설정
    - Appearance : 테마, 메뉴구성, 페이지설정
    - Users : 사용자 관리
    - Settings : 사이트 이름, 검색옵션, 메타데이터요소, 아이템유형, API설정

  - 2. 좌측메뉴
    - Dashboard : 등록 현황
    - Items : 아이템 등록/관리
    - Collections : 컬렉션 등록/관리
    - Item Types : 아이템 유형 등록/관리
    - Tags : 태그 등록/관리

![Alt text](/image/image_05.png)



- View Site (서비스 사이트)
  - 등록된 아이템, 컬렉션, 전시를 일반 이용자들에게 보여주는 사이트

![Alt text](/image/image_06.png)







### 3.3 컬렉션 등록
- [컬렉션 등록 매뉴얼](https://info.omeka.net/build-a-website/manage-collections/)



### 3.4 아이템 등록
- [아이템 등록 매뉴얼](https://info.omeka.net/build-a-website/add-items/)


### 3.5 전시 만들기
- [플러그인 설치](https://info.omeka.net/build-a-website/manage-plugins/)
- [전시 만들기](https://info.omeka.net/build-a-website/manage-plugins/exhibit-builder-3/)


### 3.6 사이트 꾸미기
- [보여주기 설정](https://info.omeka.net/build-a-website/manage-appearance-settings/)
- [테마 선택](https://info.omeka.net/build-a-website/manage-themes/) 
- [메뉴 만들기](https://info.omeka.net/build-a-website/change-site-navigation/)



## 4. 참고 사이트
- 강의 깃허브 : [https://github.com/ahhn/2019Omeka2/](https://github.com/ahhn/2019Omeka2/)
- Omeka.net (가입형) : [https://omeka.net](https://omeka.net)
- Omeka Classic (설치형) : [https://omeka.org](https://omeka.org)
- Omeka Classic 설치방법 동영상 : [https://www.youtube.com/watch?v=qfhjxUGkR0g&index=2&list=PLya-3fVEf50Zj0bfFbkRpxuwO6J9mh4Pf](https://www.youtube.com/watch?v=qfhjxUGkR0g&index=2&list=PLya-3fVEf50Zj0bfFbkRpxuwO6J9mh4Pf)
- Omeka 사이트 모음 : [https://omeka.org/classic/directory/](https://omeka.org/classic/directory/)
- 오픈소스 기록관리 소프트웨어 포럼(OSASF) : [https://osasf.net/](https://osasf.net/)



## Instructor information
 
[Daejin Ahn](https://www.instagram.com/djahhn/) is an artist and enterpreneur based in Seoul. Ahn founded the [archivelab](http://archivelab.co.kr) in 2016, where he continues to experiment and explore open source software based digital archives.
 
email : djahhn@gmail.com
