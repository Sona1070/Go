# 01. HelloWorld

01. Package
- 반복하지 말라는 소프트웨어 공학의 중요한 실천 덕목 중 하나다.
- 모든 언어들이 고품질의 소프트웨어를 만들기 위해서 중복되는 코드를 하나로 관리해서 재사용 할 수 있도록 돕는 매커니즘을 가지고 있다.
- 코드 재사용을 위한 첫 번째 수단은 함수로, 모든 언어에서 기본적으로 제공한다.
- Go 언어는 여기에 더해서 패키지라는 코드 재사용을 위한 매커니즘을 제공한다.
- 위의 hello world 코드를 비롯한 앞으로 다룰 모든 코드들은 import "fmt"와 같은 구문을 포함한다.
- fmt는 형식화와 관련된 여러 함수들을 포함하고 있으며, 개발자는 출력과 관련된 함수를 새로 개발할 필요 없이 fmt 패키지에서 제공하는 함수들을 이용해서 간단하게 출력 기능을 사용 할 수 있다.
- 즉 패키지는 유용한 함수들의 모음이다. C나 C++의 라이브러리, 자바 언어의 package와 비슷하다.
- 특히 java의 package와는 이름뿐만 아니라 하는 일까지도 거의 동일하다.

02. import
- import를 이용해서 패키지를 사용 할 수 있다.
- Go 언어는 유용하게 사용 할 수 있는 표준 패키지와 다른 개발자들이 공유한 수많은 패키지들을 사용 할 수 있다.
- 표준 패키지의 목록은 여기에서 확인 할 수 있다. https://golang.org/pkg/

03. func
- Go에서 함수를 정의 하기 위해서 사용한다.
- 7번째 줄을 보면 func main()이 있는데, go 언어에서 main 함수는 특별하게 취급한다.
- main 함수는 프로그램 실행의 시작 점으로 모든 실행 가능한 go 프로그램은 반드시 하나의 main 함수를 가지고 있어야 한다.

출처
https://www.joinc.co.kr/w/GoLang/example/helloworld
https://gobyexample.com/
