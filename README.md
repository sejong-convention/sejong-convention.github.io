# 세종대학교 전시컨벤션산업전공 홈페이지

index.html을 열어 확인할 수 있는 정적 사이트입니다. 별도 설치나 빌드는 필요하지 않습니다.

## 관리하는 폴더
- index.html: 대표 이미지로 각 페이지에 연결하는 메인
- about/index.html: 교육목표·지원혜택·산학 프로젝트 참여기업·교육과정
- faculty/index.html 및 교수별 하위 폴더: 교수진 소개
- admission/index.html: 2027학년도 모집 포스터·원서접수 일정·공식 안내 링크
- archive/index.html: 최근 활동부터 이어지는 전체 아카이브
- archive/활동영문명/index.html: 행사별 소개와 사진
- sns/index.html: 전공 및 KME 계정 QR·바로가기
- assets/css/styles.css: 공통 디자인
- assets/img/: 사진·포스터·로고·QR

## 수정과 업로드
앞으로는 필요한 파일만 직접 수정합니다. 전체 ZIP은 별도로 요청할 때만 만듭니다.
GitHub Pages에는 이 폴더 안의 파일·폴더를 저장소 루트에 올리면 됩니다. 내부 페이지·사진은 상대경로를 사용하고, 인스타그램·학교 모집 안내·전화·메일은 해당 서비스로 직접 연결됩니다.

산학협력 메뉴와 industry/index.html은 제거했습니다. 업무협약과 관련 활동은 아카이브에 포함되어 있습니다. 기존 GitHub 저장소에도 industry/index.html이 있다면 삭제해 주세요.

## 활동 추가
archive/의 기존 행사 폴더를 복사해 실제 소개·사진을 수정하고, archive/index.html의 archive-grid에 카드 하나를 추가합니다. 최근 활동이 앞에 오도록 배치합니다. 모든 카드에 연도 제목·연도 구분을 표시하지 않습니다. 사진은 assets/img/에 저장합니다.

## 홍보 채널
- 전공: https://www.instagram.com/convention.sejong/
- KME 2026: https://www.instagram.com/sejong_conv/
두 QR은 위 주소를 직접 인코딩했습니다. 인스타그램 전용 앱이 없어도 웹 주소로 연결됩니다.

## 자료 확인
CONTENT_SOURCES.md에 게시 자료의 출처와 행사 순서 확인 근거를 정리했습니다.

## 공통 화면 구성
메뉴 순서: 홈 → 전공 소개 → 입학안내 → 아카이브 → 소셜·홍보 → 교수진 소개. 모든 페이지의 상단은 전공명·오른쪽 학교 로고·하단 구분선으로 통일했습니다. 홈에는 상세 내용 미리보기 대신 대표 이미지가 있는 페이지 이동 카드 5개를 배치했습니다.
