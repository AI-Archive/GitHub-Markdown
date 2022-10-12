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
### 미리보기
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

### 미리보기
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



---
## 3. BlockQuote

<pre>
> 블록 1
> > 블록 2
> > > 블록 3
> > > > 블록 4
> > > > > 블록 5
</pre>

> 블록 1
> > 블록 2
> > > 블록 3
> > > > 블록 4
> > > > > 블록 5

+ this text is highlighted in green

``` diff
+ this text is highlighted in green
- this text is highlighted in red
```

