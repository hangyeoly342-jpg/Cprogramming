실습과제 1번

| 수식   | 결과값 | 결과값의 자료형 |
| ---- | --- | -------- |
| &ch  | 100 | char*    |
| &in  | 101 | int*     |
| &db  | 105 | double*  |
| *&ch | 'A' | char     |
| *&in | 10  | int      |
| *&db | 3.4 | double   |


실습과제 2번

실행결과
<img width="969" height="159" alt="02-2" src="https://github.com/user-attachments/assets/eef2d82c-3cb2-426e-ab2d-800bf9deec59" />


실습과제 3번

```
#include<stdio.h>

int main(void)
{
int* ptr= (int*)125; // ①
*ptr= 10;
printf("%d\n", *ptr);
return0;
}
```

* ①에서 ptr은 int* 타입의 포인터 변수이고, 125는 int 타입의 정수이므로 타입이 일치하지 않는다. 따라서 (int*) 강제 형변환을 사용하여 125를 int* 타입으로 변환한 후 ptr에 저장한다.

* 이 코드에서 오류가 나오는 이유는 *ptr = 10을 실행하여 125번지에 값을 저장하려고 하는데, ①에서 ptr를 초기화해주지 않아 쓰레기값이 저장되어 있을 수 있어서 오류가 발생할 수 있다.

&nbsp;


실습과제 4번

실행결과
<img width="972" height="124" alt="02-04" src="https://github.com/user-attachments/assets/ccd1978f-cce2-4cf6-b9b5-3cc04b393842" />

실습과제 5번

문제

정수형 변수 num1과 num2를 선언하여 각각 35와 60으로 초기화하고, 포인터 변수 ptr1과 ptr2가 각각 num1과 num2를 가리키도록 하시오.
두 포인터가 가리키는 값을 비교하여, 더 작은 값에는 10을 더하고 더 큰 값에는 10을 빼시오.
그 후 두 포인터가 가리키는 값을 서로 교환한 뒤 변경된 num1과 num2의 값을 각각 출력하는 프로그램을 작성하시오.


실행결과
<img width="985" height="166" alt="02-05" src="https://github.com/user-attachments/assets/8293a616-26a8-45af-8a88-36aef8b70236" />
