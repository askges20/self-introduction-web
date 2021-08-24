## 2021 여름 부트캠프 : 자기소개 웹페이지 제작 및 배포
성남산업진흥원 주관 ICT 기업 인턴 교육 프로그램 과제 수행

### 프로젝트 개요
- 본인의 기술 스택, 연도별 공부 내역, 프로젝트를 정리한 포트폴리오 페이지 제작
- 웹페이지 기획부터 설계, UX 파악, 개발, 배포의 과정을 거침
- HTML, CSS, JS를 이용한 반응형 웹 구현
- AWS EC2를 이용하여 Apache 웹서버 구축, 배포

### 서버 구축 및 배포 방법
1. AWS VPC, 퍼블릭 서브넷 생성
2. 인터넷 게이트웨이 생성 후 라우팅 테이블에서 VPC와 연결
3. EC2 보안그룹 설정 (22포트 내 IP, 80포트 인터넷망) 후 EC2 인스턴스에 적용
4. PuTTY에서 EC2 접속 후 Apache 웹서버 설치
5. 개발한 웹페이지 파일 FileZilla 이용하여 EC2 폴더에 넣기
6. 퍼블릭 IP로 접속하여 웹페이지 배포 확인

### 배포 링크
- [About Yewon](https://quirky-kalam-5e2cf7.netlify.app/) (AWS EC2는 비용 발생으로 인해 현재 호스팅 중지 상태, Netlify로 대체)

### 웹페이지 화면
<div align="center">
<img src="https://user-images.githubusercontent.com/75527311/130611343-38113ff5-6ead-4abe-8f0c-1ed43c69d214.png">
<p>웹페이지 좌측에는 프로필 이미지 및 컨택, 우측에 본문 내용</p>
<br>
<img src="https://user-images.githubusercontent.com/75527311/130611382-3a838bb2-d241-4533-8d5a-c342ff09ac0d.png">
<p>지금까지 공부한 전공 과목, 참여한 프로젝트, 대외활동 등을 연도별로 나타냄</p>
<br>
<img src="https://user-images.githubusercontent.com/75527311/130611430-9bcac75a-1632-4752-bcc0-b6265cef91e7.png">
<p>Github Repository에 업로드 된 프로젝트 목록, 클릭 시 Repository로 이동</p>
</div>
