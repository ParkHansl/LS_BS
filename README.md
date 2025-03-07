# LS_BS

# title 1 (h1)

프리뷰 단축키 : cmd + shift + k

**강조는 star 2개 쌓기**

*italic 체는 star 1개 감싸기*

~~취소선은~~ 로


## title 2 (h2)

글 중간에 목록을 삽입하고 싶은 경우

- item 1
    - subitem 1
- item 2
    - subitem 2
- item 3


순서가 있는 목록을 삽입 할 수도 있음.

1. item 1
    1. subitem 1
    1. subitem 3
    1. subitem 2
1. item 2
    1. subitem 1
    1. subitem 2
    1. subitem 3
1. item 3

option 화살표로 위아래 이동 가능

### title 3 (h3)

문의사항은 [슬기로운 통계생활](https://www.naver.com)로 문의주세요!


#### title 4 (h4)

이미지 삽입 방법

![image](https://lab.statisticsplaybook.com/wp-content/uploads/2025/02/lab-main2.png)



##### title 5 (h5)

표를 넣고 싶은 경우

| header 1 | header 2 | header 3 |
| --- | --- | --- |
| row 1 | row 2 | row 3 |


###### title 6 (h6)

문장 안에 들어가는 수식은 달러 기호 한개를 사용.

$E = mc^2$

만약, 수식만 따로 문단을 만들어서 보여주고 싶은 경우는 $$ 사용

$$
E = mc^2
$$

$$
\begin{aligned}
    a&= b+ c \\
     &= d+ e + f
\end{aligned}
$$

* `\\`는 줄바꿈을 의미!
* `&` 기호는 정렬 기준을 의미
* ``로 기호 출력 가능

단축키 : cmd + shitf + i

```{tex}
## quarto의 존재 이유

파이썬 코드 청크를 첨부 가능
```

```{python}
import numpy as np
```