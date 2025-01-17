# Markdown 문법 정리

## 1. 헤더(Header)
`#`을 사용하여 제목 크기 지정 (1~6단계 지원)

```markdown
# H1 제목
## H2 제목
### H3 제목
#### H4 제목
##### H5 제목
###### H6 제목
```

---

## 2. 목록(List)
### 순서 있는 목록
숫자와 점(`.`)으로 생성:
```markdown
1. 첫 번째
2. 두 번째
   1. 두 번째의 하위
   2. 또 다른 하위
```

### 순서 없는 목록
`*`, `-`, `+`를 사용:
```markdown
- 리스트 1
- 리스트 2
  - 서브 리스트 1
  - 서브 리스트 2
```

---

## 3. 텍스트 스타일
### **굵게**
```markdown
**굵은 텍스트**
```

### *기울임*
```markdown
*기울임 텍스트*
```

### ~~취소선~~
```markdown
~~취소선~~
```

---

## 4. 링크
### 텍스트와 URL 링크
```markdown
[링크 텍스트](https://example.com)
```

### 참조 스타일 링크
```markdown
[링크 텍스트][링크ID]

[링크ID]: https://example.com
```

---

## 5. 이미지
```markdown
![이미지 설명](이미지 URL)
```
예:
```markdown
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

---

## 6. 인라인 코드와 코드 블록
### 인라인 코드
```markdown
`코드 내용`
```

### 코드 블록
```markdown
```언어
코드 내용
```
```

예:
```markdown
```javascript
console.log('Hello, World!');
```
```

---

## 7. 인용문(Blockquote)
`>`로 생성:
```markdown
> 인용 내용
>> 중첩 인용
```

---

## 8. 수평선(Horizontal Line)
```markdown
---
```

---

## 9. 테이블(Table)
```markdown
| 제목 1 | 제목 2 | 제목 3 |
|--------|--------|--------|
| 데이터1 | 데이터2 | 데이터3 |
| 데이터4 | 데이터5 | 데이터6 |
```

---

## 10. 체크박스
```markdown
- [x] 완료
- [ ] 미완료
```

---

## 11. 이스케이프 문자
특수 문자 앞에 `\`를 추가:
```markdown
\*, \#, \(, \)
```

---

## 12. HTML 태그 사용
HTML을 직접 사용할 수도 있습니다:
```html
<a href="https://example.com">HTML 링크</a>
```

---
