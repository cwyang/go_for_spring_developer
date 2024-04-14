## 반복문
* Go는 반복문으로 for 키워드만 제공합니다. (while 이 없습니다.)
### 구구단의 2단 (E5)
```go
package main

import "fmt"

func main() {
	for i := 1; i < 10; i++ {
		fmt.Printf("%d X %d = %d \n", 2, i, 2*i)
	}
}
```

## Workshop(e5/w1)
* 2단 부터 9단까지 표시하는 구구단 프로그램을 작성하세요.
* 예상 결과
```
2 x 1 = 2 
2 x 2 = 4 
2 x 3 = 6 
2 x 4 = 8 
2 x 5 = 10 
2 x 6 = 12 
2 x 7 = 14 
2 x 8 = 16 
2 x 9 = 18 
3 x 1 = 3 
// 중간생략....
8 x 9 = 72 
9 x 1 = 9 
9 x 2 = 18 
9 x 3 = 27 
9 x 4 = 36 
9 x 5 = 45 
9 x 6 = 54 
9 x 7 = 63 
9 x 8 = 72 
9 x 9 = 81 
```


