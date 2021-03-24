### 3/23
- 키 값을 github에 올려두지 않으려고 환경변수 파일을 따로 만들어 gitignore함.(API_KEY 등 공개하고 싶지 않을 때)

- 하지만 create-react-app을 통해 환경변수 코드를 실제 값으로 변환시킴. 완전히 숨길 수는 없음

- Authentication 구현 중

### 3/24
- `jsconfig.json`을 만들어 `absolute imports`를 지원해 줄 수 있음.
[참고](https://create-react-app.dev/docs/importing-a-component/)
- `form`을 이용하여 login form 을 만듦.
- `input`을 입력했을 때 `onChange`이벤트를 받아서 email과 password를 변경함. 상태값은 `useState` hooks 를 사용하여 변경하였음.

### 3/25
