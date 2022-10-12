# GitHub-Markdown 0.0.3
Markdown for Github documentation
- 깃허브 마크다운 문서 작성용 문법 예시
- - 참조한 것 + 테스트 해본것들 추가중


<br/><br/>

# Github용 마크다운 작성법

<br/><br/>

---
## 1. 헤더 (Headers)

<br/>

### 문법
<pre>
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
</pre>
### 보기
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

<br/>

---
## 2. 문자 표시법

### 문법
<pre>
**강조**
__강조__
*이탤릭*
_이탤릭_
~~취소선~~
***모두 강조 및 이탤릭***
<[!]> 슈퍼스크립트 </[!]> <-- [!] 위치에 sup 작성
<[!]> 서브스크립트 </[!]> <-- [!] 위치에 sub 작성
</pre>

### 보기
**강조** <br/>
__강조__ <br/>
*이탤릭* <br/>
_이탤릭_ <br/>
~~취소선~~ <br/>
***모두 강조 및 이탤릭*** <br/>
<sup> 슈퍼스크립트 </sup> <br/>
<sub> 서브스크립트 </sub> <br/>

<br/>

### 주의사항
문자열과 명령어 사이에 빈칸이 있으면 정상 동작하지 않음
#### 문법
<pre>
__ 강조 __
</pre>
#### 보기
__ 강조 __

## 3. 줄바꿈 (엔터)
- 문서를 작성할 때의 엔터는 결과물에서 적용되지 않는다. 줄바꿈(엔터)에 대한 문법이 추가로 존재한다.

### 문법
<pre>
<[!]/> <- [!] 위치에 br 입력
</pre>

### 미리보기
테스트1
<br/>
테스트2
<br/>


## 4. 수평선

### 문법
<pre>
---
***
___
</pre>

### 미리보기
---
***
___

<br/>

---
## 5. BlockQuote

### 문법
<pre>
> 블록 1
> > 블록 2
> > > 블록 3
> > > > 블록 4
> > > > > 블록 5
</pre>

### 주의사항
> 블록 1
> > 블록 2
> > > 블록 3
> > > > 블록 4
> > > > > 블록 5



## 6. 목록

### 문법
<pre>
*type what grammer is*
</pre>

### 미리보기
- 목록 1
- - 목록 2
- - - 목록 3
<br/>

-   - 목록 4
  - - 목록 5
    - 목록 6
<br/>

-   -   - 목록 7
    -   - 목록 8
    -   -   - 목록 9
<br/>

- 목록 10
    - 목록 11
        - 목록 12

<br/>

### 주의사항
*주의해야 할 사항 개요*
#### 문법
<pre>
*잘못 쓴 코드 문법*
</pre>
#### 미리보기
*잘못 쓴 코드 미리보기*

