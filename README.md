# GitHub-Markdown 0.1.0
Markdown for Github documentation
- 깃허브 마크다운 문서 작성용 문법 예시
- 참조한 것 + 테스트 해본것들 추가중


<br/>

# Github용 마크다운 작성법

<br/>

---
<details>
<summary><font size="5"> 1. 헤더 </font></summary>

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
</details>

---
<details>
<summary><font size="5"> 2. 문자 표시법 </summary>

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
#### 미리보기
__ 강조 __
</details>

---
<details>
<summary><font size="5"> 3. 줄바꿈(엔터) </font></summary>

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
</details>

---
<details>
<summary><font size="5"> 4. 수평선 </font></summary>

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
</details>

---
<details>
<summary><font size="5"> 5. 인용구 (Blockquote) </font></summary>

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
</details>


---
<details>
<summary><font size="5"> 6. 목록</font></summary>

### 문법
<pre>
- 목록 1
- - 목록 2
- - - 목록 3

-   - 목록 4
  - - 목록 5
    - 목록 6

-   -   - 목록 7
    -   - 목록 8
    -   -   - 목록 9

- 목록 10
    - 목록 11
        - 목록 12
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
목록 생성은 바(-)로 수행한다.
하위 목록 생성시 - 사이에 공백 또는 탭 문자를 넣어서 하위 목록을 생성 가능하다.
특징으로 상위 목록 표시와 하위 목록 표시를 동시에 할 수 있다.
</details>

---
<details>
<summary><font size="5"> 7. 코드 블록 </font></summary>

### 문법
<pre>
```
print('hello world!)
```

```python
print('hello world!)
```
</pre>

### 미리보기
```
print('hello world!')
```

```python
print('hello world!')
```

<br/>

### 주의사항
<pre>
문법 강조 (syntax highliting)
첫 ```의 뒤에 코드 블록 안에 작성한 코드의 사용 언어를 입력하면 코드에 색이 입혀진다.
</pre>
</details>

---
<details>
<summary> <font size="5"> 8. 섹션 </font></summary>

### 문법
<pre>
<[!]> <- [!]에 detail 작성
<[?]> 문서 접기 </[?]> <- [?]에 summary 작성
    문서 내용
</[!]> <- [!]에 detail 작성
</pre>


### 미리보기
<details>
<summary> 섹션 </summary>
문서 내용
</details>

<br/>

### 주의사항
summary 항목은 작성하지 않아도 동작함
- 이 경우 접은 문단의 제목은 기본값 '세부정보' 적용되는듯
</details>

</details>

visit https://github.com

---
<details>
<summary> TODO List</summary>

- 테이블 (tables) (기본)
- 링크 (link) (기본)
- 파일 업로드 (기본, 테스트 필요)
- 다이어그램 (diagram) (응용)
- 수학표현식 (Mathematical expressions) (응용)
- 자동 링크 url (Autolinked references and URLs) (응용)

</details>

The background color should be `#ffffff` for light mode and `#0d1117` for dark mode. 
`rgb(9, 105, 218)` aaa bbb