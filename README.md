# 즐겨찾기 - API 테스트/문서자동화

# 1단계 - 회원관리 기능

# 회원정보 수정 기능

## 요구 사항

- [x] 회원 정보를 관리하는 기능 구현
- [x] 자신의 정보만 수정 가능하도록 해야하며 **로그인이 선행**되어야 함
- [x] 토큰의 유효성 검사와 본인 여부를 판단하는 로직 추가
- [x] side case에 대한 예외처리
- [x] 인수 테스트와 단위 테스트 작성
- [x] API 문서를 작성하고 문서화를 위한 테스트 작성
- [x] 페이지 연동

## 기능 목록

### 1. 회원 가입
- [x] 이메일 중복 체크
- [x] 이메일 포맷 체크
- [x] 패스워드/확인 일치 여부 체크
- [x] 뷰 페이지 진입시 폼 값 비워주기
- [x] 이메일 값 인터셉터로 지정해주기
- [x] 회원가입 성공시 로그인 뷰로 리다이렉트

### 2. 로그인
- [x] 일치하는 이메일이 있는지 확인
- [x] 비밀번호 일치 여부 확인

### 3. 로그인 후 회원정보 조회/수정/삭제
- [x] 로그인 되어있는지 확인
- [x] 이메일 값으로 패스워드를 제외 한 폼에 필요한 정보 채워주기



# 2단계 - 즐겨찾기 기능

# 즐겨찾기 기능

## 요구사항

- [x] 즐겨찾기 기능을 추가(추가,삭제,조회)
- [x] 자신의 정보만 수정 가능하도록 해야하며 **로그인이 선행**되어야 함
- [x] 토큰의 유효성 검사와 본인 여부를 판단하는 로직 추가(interceptor, argument resolver)
- [ ] side case에 대한 예외처리 필수
- [ ] 인수 테스트와 단위 테스트 작성
- [x] API 문서를 작성하고 문서화를 위한 테스트 작성
- [x] 페이지 연동

## 기능 목록

### 1. 즐겨찾기 추가

- [x] 이미 추가된 경로는 추가하지 않는다.

### 2. 즐겨찾기 목록조회 / 제거

- [x] 없는 즐겨찾기를 지우려고 하는 경우