# public Repository

## 목적
* 자기주도학습을 위한 가이드 제공

## 구성
* GitPitch 슬라이드 문서
  - **PITCHME.md**: Git의 소개와 GitHub, GitPitch 사용 안내를 담은 markdown 문서. GitPitch로 접근하면 슬라이드쇼로 볼 수 있음(https://gitpitch.com/사용자명/Repository명/Branch명)
  - **PITCHME.yaml**: GitPitch 프레젠테이션을 위한 환경설정 파일(없으면 기본설정값을 가지므로, 꼭 생성해야 하는 것은 아님)
  - **css**: html, md 등에 사용할 수 있는 스타일을 정의한 CSS(Cascading Style Sheets) 파일 디렉토리
    - **PITCHME.css**: GitPitch 슬라이드 문서에 적용할 스타일을 정의한 파일

* Jekyll 테마 블로그
  - **\_config.yml**: Jekyll 테마에 대한 설정 파일(현재 설정은 원격 Repository의 리소스를 사용하게 되어 있으므로, 본 Repository 안에 테마 관련 파일이 없음)
  - **index.html**: GitHub Page(블로그) 초기 화면
  - **\_data**: Page에 관한 데이터가 들어가는 디렉토리
    - **navigation.yml**: 상단(header) 영역에 링크(메뉴)를 구성
  - **\_pages**: 개별 페이지 파일이 들어가는 디렉토리
    - **md-table.md**: Markdown 문법 안내 페이지
    - **gp-table.md**: GitPitch 문법 안내 페이지
    - **topic1.md**: 오늘의 미션 과제1 페이지
    - **topic2.md**: 오늘의 미션 과제2 페이지
  - **\_posts**: 블로그에 포스팅할 글이 들어가는 디렉토리(YYYY-MM-DD-title.md 형식을 지켜야 하며, Jekyll 테마에서 자동으로 읽어 표시해 줌)
  
