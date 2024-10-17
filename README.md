# javascript-calculator-precourse

## 기능 목록

### 입력 및 출력

[] **[1] 입력 안내 메시지 출력**

`“덧셈할 문자열을 입력해 주세요.\n”`

[] **[2] 입력받기**

구분자(`,`, `:`, 커스텀 구분자)와 양수로 구성된 문자열

[] **[3] 사용자가 잘못된 값을 입력할 경우**

`"[ERROR]"`로 시작하는 메시지와 함께 `Error`를 발생시킨 후 애플리케이션 종료

[] **[4] 출력**

```bash
결과 : ${답}
```

### 구분자와 숫자 식별, 숫자 합 구하기

[] **[1] 커스텀 구분자가 정의되어 있다면 등록**

`"//"` 와 `"\n"` 사이에 위치하는 문자

[] **[2] 구분자를 기준으로 숫자 분리**
- [] 쉼표를 포함한 문자열에서 숫자 분리
- [] 쉼표, 콜론을 포함한 문자열에서 숫자 분리
- [] 쉼표, 콜론, 커스텀 구분자를 포함한 문자열에서 숫자 분리

[x] **[3] 숫자의 합 구하기**
