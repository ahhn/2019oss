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

- 박해경 : [Living Late Antiquity](https://github.com/ahhn/2019oss/raw/master/lecture/park_case.pdf)
- 이충호 : [CornishMemory.com](https://github.com/ahhn/2019oss/raw/master/lecture/lee_case_cornishmemory.pdf)
- 최현균 : [2015 Boltimore Uprising](https://github.com/ahhn/2019oss/raw/master/lecture/choi_case_2015boltimore-uprising.pdf)

참고 사이트 : 
- Omeka Showcase : [https://omeka.org/classic/showcase/](https://omeka.org/classic/showcase/)
- Omeka Directory : [https://omeka.org/classic/directory/](https://omeka.org/classic/directory/)

## Week 6. 온라인 퍼블리싱 소프트웨어 - Omeka 2
Omeka 실습 : 플러그인 I 
- CSV Import
- Bulk Metadata editor 
- COinS
- Collection Tree : 컬렉션 계층구조 보여주기
- Commenting : 댓글
- Contributor Contact - Corrections
- CSV Export Format
- ItemType : 메타데이터 설정

## Week 7. 온라인 퍼블리싱 소프트웨어 - Omeka 3
Omeka 실습 : 플러그인 II 
- Simple Vocab : 전거통제
- Item Relations : 관계설정
- Record Relation : 관계설정
- Avant Relation : 관계설정
- Avant Common : 관계설정
- Facets : 아이템 브라우징 결과 패싯 정렬
- Default Dublin Core : 메타데이터 설정
- Default Metadata : 메타데이터 설정
- Default Search Options : 기본검색 옵션 설정
- Default Sort : 기본 검색결과 정렬 옵션 설정
- Derivative Images
- Docs Viewer
- Exhibit Image Annotation 
- Geolocation
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
- Ngram : 말뭉치 생성
- Text Analysis : 텍스트 분석

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

[강의자료6. AWS, Omeka, Filezilla 매뉴얼](https://github.com/ahhn/2019oss/raw/master/lecture/02_AWS_v2.0.pdf)

[강의자료7. 더블린 코어(Dublin Core) 설명](https://www.nl.go.kr/standards/dublincore/dublinCoreDcmes.do)

[강의자료8. Omeka CSV목록 - 위치정보추가](https://github.com/ahhn/2019Omeka/raw/master/lecture/catalog2.csv)



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
