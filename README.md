Lv1V1

이 자바 파일은 간단한 자바의 문법을 가지고 계산기를 구현한 버전1 의 계산기 입니다.

이 계산기는 while문(true)을 사용하여 계산 처리 이후 반복 동작을 합니다.

System.out.print를 사용해 첫번째 정수, 연산 기호(+, -, *, /), 두번째 정수를 받습니다.
int num1, char charInp, int num2 라는 변수를 선언해주고 Scanner를 사용하여 input값을 받습니다.


4개의 연산기호 중 한가지의 값을 받았을 때의 계산식을 지정해주기 위해 switch를 사용합니다.
4개의 기호를 각 기호의 case에 지정해 줍니다.

이후 연산기호를 확인 후 case에 저장된 계산식을 result값에 대입후 결과값을 출력합니다.

그후 프로그램을 종료할지 물어보는 출력문이 나오고 exit을 입력하면 brake;를 걸어주는 역할을 하게 됩니다. enter를 입력하면 다시 조건문으로 돌아가 반복하게 됩니다.



Lv1V2

위 방식과 비슷하나
while문을 do while로 대체 하였습니다.

switch문을 if문으로 대체 하였습니다.

break 대신 boolean형 변수 onOff = true 를 선언 하여
exit을 입력했을때 onOff에 false 대입
이후 조건문이 false이기 때문에 코드블럭을 빠져나오게 설계하였습니다.
