실습과제 1
문제

아래 변수들이 메모리에 할당될 때 다음 식의 결과값과 결과값의 자료형을 작성하시오.

char ch = 'A';
int in = 10;
double db = 3.4;
풀이

메모리 주소는 그림에 나온 것처럼 다음과 같이 할당되어 있다고 생각할 수 있다.

변수	시작 주소	자료형	크기
ch	100	char	1바이트
in	101	int	4바이트
db	105	double	8바이트

각 식을 살펴보면,

수식	결과값	결과값의 자료형
&ch	100	char *
&in	101	int *
&db	105	double *
*&ch	'A'	char
*&in	10	int
*&db	3.4	double
