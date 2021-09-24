# Frontend 지식
## HTML
- html 5부터는
  - ```<script>``` Default로 javascript
  - ```<style>``` Default로 css

### Tags
```HTML
<a href = "URL">
```
: 링크된 페이지의 URL을 명시함.


## JavaScript
### 변수 선언 방식
- `var`: 같은 이름의 변수를 한 번 더 선언하더라도 에러없이 다른 값 출력됨.
- `let`: 변수 재선언은 불가능하지만 (에러 뜸) 재할당은 가능하다. (선언없이 바로 덮어쓰기)
- `const`: 변수 재선언, 재할당 모두 불가능.
- 결론:  
  > 1. 재할당이 필요한 경우에 한정해 `let`을 사용한다. 이때, 변수의 스코프는 최대한 좁게 만든다.
  > 2. 재할당이 필요 없는 상수와 객체에는 `const`를 사용한다.


### 변수 가져오기
`.val()` 메소드를 사용하면 입력받은 value값을 가져오거나 원하는 value값으로 set이 가능합니다.

### `$`의 의미
> jquary 객체라는 뜻.
jQuery는 한 개의 JavaScript 파일로 존재한다.  
공통의 DOM, 이벤트, 특수 효과, Ajax 함수를 포함한다.  
다음 코드를 쓰면, 웹 페이지로 포함시킬 수 있다:  

```javascript
<script type="text/javascript" src="path/to/jQuery.js"></script>
```


