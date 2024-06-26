

## 중요한 형식과 코딩 규칙
* Go는 실수를 방지하도록 엄격한 코딩 규칙을 적용합니다.
* Go가 제공하는 표준 도구(gofmt)를 제공해 형식은 자동으로 조정할 수 있습니다.
### 코딩 규칙
* 패키지를 임포트 하면 해당 패키지 기능을 사용해야 합니다.
* 변수를 선언했다면 반드시 사용해야 합니다..
* 중괄호를 사용하는 형식은 1가지 방법 밖에 없습니다.
```go
package main

import(
    "fmt"
)

// 컴파일 오류가 발생합니다.
func main()
{
    fmt.Println("Go has strict rules for curly braces!")
}
```
* 코드가 한문장이거나 아예 존재하지 않더라도 코드 블록은 중괄호로 감싸야 합니다.
* 함수는 여러 개의 값을 반환할 수 있습니다.
* 같은 종류의 데이터일지라도 다른 데이터 타입으로 자동 변환되지 않습니다. (정수를 부동소수점으로 자동변환하지 않습니다.)








## 정리
* 웹 애플리케이션을 구현하기 위한 Go 언어의 기본 기능을 살펴 보았습니다. 물론 Go 언어에 대해 모두 배운것은 아닙니다,
* Go 언어를 이용해서 프로젝트를 생성/실행 하는 과정을 살펴 보았습니다.
* 여러가지 타입을 정의 하고, 타입의 변수를 만드는 작업을 확인 하였습니다.
* 오류처리와 포인터에 대한 기본적인 지식을 알게 되었습니다.