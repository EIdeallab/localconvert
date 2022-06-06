# 2022-05-27

LocalConvert

- 메인 사이트 도메인 변경 및 인증서 추가
  localconvert.net -> www.localconvert.net

비디오변환기

- 0.1.0 버전 배포
- 메인 도메인 변경
  videcode.netlify.app -> videcode.localconvert.net

PDF변환기

- 0.1.0 버전 배포
- 메인 도메인 변경
  pidecode.netlify.app -> pidecode.localconvert.net

# 2022-05-28

PDF변환기

- PDF 파일 포맷 분석
- Nameobject 오류 발생하는 PDF 파일 선별

# 2022-05-29

LocalConvert

- 메인 사이트 로고 디자인
- fabicon 수정

PDF변환기

- Nameobject에서 string 처리 방식 변경(비표준 pdf 대응)

# 2022-05-30

비디오변환기

- 0.1.1 버전 배포
- 툴바 로고 url이 기존 localconvert.net으로 연결되던 문제 수정
- 로고 디자인과 fabicon 변경
- 메인 텍스트가 옵션 선택시 옵션에 따라 변경되도록 수정

PDF변환기

- 0.1.1 버전 배포
- 툴바 로고 url이 기존 localconvert.net으로 연결되던 문제 수정
- 로고 디자인과 fabicon 변경
- 메인 텍스트가 옵션 선택시 옵션에 따라 변경되도록 수정

# 2022-05-31

비디오변환기

- 유저 커맨드 옵션이 정상적으로 작동되지 않는 문제 수정
- gif -> other 변환이 정상적으로 작동되지 않아 임시로 막음

PDF변환기

- Module Lazy load 하도록 수정 중

# 2022-06-01

PDF변환기

- Module Lazy load 관련 프로젝트 구조 변경 작업 진행

# 2022-06-03

PDF변환기

- 파일 변환 시 새로운 페이지로 Routing 하도록 수정
- 일부 페이지 Lazy loading 하도록 수정
- 이미지 변환 프로그레스 표시 오류 수정
- 페이지 로딩 개선 중

# 2022-06-04

PDF변환기

- 각 옵션마다 Routing하도록 수정
- PDF변환 모듈 Lazy loading 완료
- Angular universal 적용 중

# 2022-06-06

PDF변환기

- Angular universal custom webpack 설정
