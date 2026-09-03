# 소스코드 설명

```
#include <stdio.h>
```

* printf 등 라이브러리 객체의 선언을 포함하고 있는 헤더 파일 stdio.h를 포함합니다.

```
int main(void)
```

* 메인 함수 시작입니다.

```
char a = 'A';
```

* char형 변수 a에 'A'라는 문자 대입합니다

```
int b = 36;
```

* int형 변수 b에 36 대입합니다

```
double c = 3.141592;
```

* double형 변수 c에 3.141592 대입합니다

```
printf("char형 변수 a의 주소: %p \n", (void *)&a);
printf("int형 변수 b의 주소: %p \n", (void *)&b);
printf("double형 변수 c의 주소: %p \n", (void *)&c);
```

* printf 함수를 이용하여 변수 a, b, c의 주소를 출력한다. %p는 주소를 출력하는 서식 문자이고, &\(앰퍼샌드\)는 변수의 주소를 구하는 연산자이다.

```
return 0;
```

* 0을 반환하고 메인 함수를 정상 종료한다.

# 실행 결과
<img width="970" height="183" alt="image" src="https://github.com/user-attachments/assets/42692cb3-8899-4ecc-bf00-9e4dc1e3ea10" />
