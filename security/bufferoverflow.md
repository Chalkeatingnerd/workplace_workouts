# buffer overflow

## 개념

buffer(메모리 저장 공간) + overflow(넘치다)

buffer overrun이라고도 하며, 메모리를 다루는 데에 오류가 발생해 잘못된 동작을 일으키는 프로그램의 취약점이다.

## 결과

버퍼가 흘러넘쳐 발생, 데이터를 메모리에 저장할 때, 프로그래머가 지정한 메모리 바깥쪽에 저장됨

이렇게 벗어난 데이터는 가까운 메모리를 덮어쓰게 되는데, 해당 메모리에 다른 데이터가 포함돼 있을 가능성이 있다.

이로인해 손상받을 수 있는 데이터에 프로그램 변수와 흐름 제어 데이터 또한 포함되며, 이로 인해 프로그램 종료·시스템 보안 누설 등이 발생할 수 있다.

## 발생 원인

데이터를 메모리에 저장하는 과정에서 메모리 위치가 유효한지를 검사하지 않아 발생한다. 버퍼 영역에서 다음에 오는 복귀 주소를 조작해서 악성코드가 실행되게 만들 수 있으므로, 이는 많은 소프트웨어의 취약점이 되며, 악의적으로 이용될 수 있다.
