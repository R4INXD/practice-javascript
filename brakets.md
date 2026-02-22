# 괄호 종류

## 둥근괄호 `()`

### 함수 실행시

```js
console.log();
```

### 함수 선언시 인자 선언

```js
const sumeFunction = (a, b) => {
  return a + b;
};
```

## 중괄호 `{}`

### 객체 선언

```js
const obj = {
  name: "홍길동",
  age: 30,
};
```

### 함수 선언

```js
const sumFunction = (a, b) => {
  return a + b;
};
```

### 제어문

```js
if (condition) {
  // 실행할 코드
}

while (condition) {
  // 실행할 코드
}

for (let i = 0; i < 10; i++) {
  // 실행할 코드
}
```

### 템플릿 리터럴

```js
const name = "홍길동";
const greeting = `안녕하세요, ${name}님!`;
```

## 대괄호 `[]`

### 배열 선언

```js
const arr = [1, 2, 3, 4, 5];
```

### 배열 요소 접근

```js
const firstElement = arr[0]; // 1
const secondElement = arr[1]; // 2
```

### 객체의 속성 접근

```js
const obj = {
  name: "홍길동",
  age: 30,
};
const name = obj["name"]; // "홍길동"
```
