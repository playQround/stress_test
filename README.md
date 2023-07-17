# 로드 테스트
아틸러리 사용

# 설치
npm i -D artillery

# 로드테스트 진행
npx artillery run --insecure -o report.json loadtest.yml
npx artillery run --insecure -o <리포트파일이름.형식> <테스트파일yml or json>
--insecure -> 인증서 무시 옵션

# html로 변경
npx artillery report report.json
npx artillery report <리포트로 만들고 싶은 파일>

# 파일 설명
0. 테스트 데이터셋
1. 로드테스트 초기버전 .json 포멧
2. 로드 테스트 (소켓) .yml
3. 로드 테스트 (소켓) 성능 테스트용
4. 회원가입 시나리오 테스트
5. 로그인 -> 유저 정보 조회 테스트