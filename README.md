# AMP 92 원우회 홈페이지 시작용 시안

이 프로젝트는 **디자인 확인용 공개 홈페이지 시안**입니다. 로그인, 원우 개인정보 저장, 관리자 기능은 아직 구현되지 않았습니다. 실제 개인정보를 업로드하지 마세요.

## 로컬 실행
1. Node.js LTS 설치
2. 이 폴더에서 `npm install`
3. `npm run dev`
4. 브라우저에서 http://localhost:3000 접속

## Vercel 배포
1. GitHub에 이 폴더를 새 저장소로 업로드
2. vercel.com에서 Add New > Project > GitHub 저장소 선택
3. Framework Preset: Next.js, Deploy

## 다음 개발 단계
- Supabase Auth 로그인 및 회원 승인 상태 테이블
- 원우 명부, 행사, 사진, 공지, 조직도 테이블
- 서버 측 접근 권한 검사와 Row Level Security
- 관리자 권한 검증 및 파일 업로드 제한
- 개인정보 수집 동의, 회원 탈퇴 및 삭제 정책

현재 바로가기 메뉴는 클릭 가능한 실제 기능이 아닌 시안입니다.
