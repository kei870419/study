**MarkDown** 문법 정리
==
---
<br>

# 1. 제목(Header)

# MarkDown(h1)
## MarkDown(h2)
### MarkDown(h3)
#### MarkDown(h4)
##### MarkDown(h5)
###### MarkDown(h6)
<br><br>

# 2. 강조(Emphasis)

* 파일 이름은 숫자 + 질문.md 입니다.
* 이텔릭체는 *별표(asterisks)* 혹은 _언더바(underscore)_ 를 사용합니다.
* 두껍게는 **별표(asterisks)** 혹은 __언더바(underscore)__ 를 사용합니다.
* **_이텔릭체_와 두껍게** 를 같이 사용할 수 있습니다.
* 취소선은 ~~물결표시(tilde)~~를 사용합니다.
* <u>밑줄</u>은 `<u></u>`를 사용합니다.
<br><br>

# 3. 목록(List)
1. 목록 1
    1. 목록 1-1
    2. 목록 1-2
2. 목록 2
- 순서가 필요하지 않은 목록에 사용 가능한 기호
  - 대쉬(hyphen)
  * 별표(asterisks)
  + 더하기(plus sign)
<br><br>

# 4. 링크(Link)
[MyNotion](https://www.notion.so/kei87)

[NAVER](https://naver.com "링크 설명(title)을 작성하세요.")

[상대적 참조](../users/login)

[Dribbble][Dribbble link]

[GitHub][1]

문서 안에서 [참조 링크]를 그대로 사용할 수도 있습니다.

다음과 같이 문서 내 일반 URL이나 꺾쇠 괄호(`< >`, Angle Brackets)안의 URL은 자동으로 링크를 사용합니다.
구글 홈페이지: https://google.com
네이버 홈페이지: <https://naver.com>

[Dribbble link]: https://dribbble.com
[1]: https://github.com
[참조 링크]: https://naver.com "네이버로 이동합니다!"
<br><br>

# 5. 블록(block) 코드 강조
```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$ vim ./~zshrc
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting. 
But let's throw in a tag.
```
<br><br>

# 6. 수평선(Horizontal Rule)
---
(Hyphens)

***
(Asterisks)

___
(Underscores)
<br><br>

# 7. 줄바꿈(Line Breaks)
동해물과 백두산이 마르고 닳도록 
하느님이 보우하사 우리나라 만세   <!--띄어쓰기 2번-->
무궁화 삼천리 화려 강산<br>
대한 사람 대한으로 길이 보전하세