### 기능 구현 목록

1. 야구 게임의 정답을 랜덤 생성하는 기능

```md
- 1~9까지 3자리 자연수(0은 제외)
- 숫자 중복은 허용하지 않음
```

2. 사용자가 입력을 하는 기능

```md
<입력 양식>

- 3자리의 숫자를 입력
- 1~9까지의 숫자만 입력가능(0은 제외)
- 입력 숫자는 중복입력할 수 없음

- 입력 양식과 다른 입력이 들어오면 throw Error처리 후 프로그램 종료
```

3. 사용자 입력에 따라 결과를 보여주는 기능

```md
- 입력을 받은 결과와 정답을 비교하여 낫싱, 3스트라이크 등 결과를 출력함
- 3스트라이크가 나오면 게임이 종료되며 재시작을 할 지 물어봄
- 3스트라이크가 나올 때까지 숫자를 입력받음
```

4. 게임 종료 후 재시작/종료 하는 기능

```md
- 1을 입력하면 재시작, 2를 입력하면 종료
- 그 외 인풋 값이 들어오면 throw Error처리 후 프로그램 종료
```
