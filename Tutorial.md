Tutorial MarkDown 작성법
===============
# 1. 마크다운에 관하여
## 1.1. Github란?
Github란 다른 사람들과 협업할 때, 편하게 하려고 만들어진 버젼관리를 위한 소프트웨어 프로그램입니다. But 저희는 이 Github를 블로그처럼 글을 쓰고,저장하는
Community로 사용하려고 합니다.! 

## 1.2. 마크다운이란?
마크다운은 .md(MarkDown) 확장자를 가진 파일을 말합니다. HTML로 변환이 가능하다고 얘기하는데, 우리는 .md파일을 이용해서 슬기짜기 Github에서 우리들이 동아리활동한 내용들을 기록하고자 합니다. 기본적인 사용법은 매우 쉽고 단순하므로, 누구나 할 수 있습니다.! 그럼 시작하겠습니다.

# 2. Git 사용법
  




# 3. 마크다운 사용법 
우리가 자주 사용하는 문법들을 위주로 작성하겠습니다. 
시작하기 전 제가 만들어놓은 회색박스는 마크다운에서 주석에 해당됩니다. 
다음과 같습니다.  
\`\`\`  
내용  
\`\`\`  
* 위 내용을 Ctrl+c -> Ctrl+v를 해보면 다음과 같습니다.

```
내용
```  
한 줄 주석은 
\`을 사용하면 됩니다.  
` 내용


## 2.1. 헤더Headers
* 큰제목과 작은제목 : 각 문서(md)는 하나의 큰 제목(문서 제목)과 하나의 작은 제목(문서 부제목)을 가질 수 있습니다.
```
큰 제목
======================    

작은 제목
----------------------
```

* 실제로 위의 Line을 위 회색박스의 내용을 그대로 Ctrl+c -> Ctrl+v를 해보면 다음과 같습니다.

큰 제목
======================    

작은 제목
----------------------

* 글머리 : 글머리는 총 1~6까지 있습니다. 
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
```
* 실제로 위의 Line을 위 회색박스의 내용을 그대로 Ctrl+c -> Ctrl+v를 해보면 다음과 같습니다.

# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6

## 2.2. BlockQuote
이메일에서 사용하는 ```>``` 블럭인용문자를 이용합니다.
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.
```
* 실제로 위의 Line을 위 회색박스의 내용을 그대로 Ctrl+c -> Ctrl+v를 해보면 다음과 같습니다.(다음 부터는 이 주석을 달지 않지만 동일합니다!)
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.

이 안에서는 다른 마크다운 요소를 포함할 수 있습니다.
> ### This is a H3
> * List
>	```
>	code
>	```

## 2.3. 목록
### ● 순서있는 목록(번호)
순서있는 목록은 숫자와 점을 사용한다.
```
1. 첫번째
2. 두번째
3. 세번째
```
1. 첫번째
2. 두번째
3. 세번째


## 2.4. 코드
4개의 공백 또는 하나의 탭으로 들여쓰기를 만나면 변환되기 시작하여 들여쓰지 않은 행을 만날때까지 변환이 계속된다.

### 2.4.1. 들여쓰기
```
This is a normal paragraph:

    This is a code block.
    
end code block.
```

실제로 적용해보면,

적용예:

*****
This is a normal paragraph:

    This is a code block.

end code block.
*****

> 한줄 띄어쓰지 않으면 인식이 제대로 안되는 문제가 발생합니다.

```
This is a normal paragraph:
    This is a code block.
end code block.
```

적용예:

*****
This is a normal paragraph:
    This is a code block.
end code block.
*****







