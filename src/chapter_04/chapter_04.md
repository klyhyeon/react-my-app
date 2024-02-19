### Elements의 정의와 생김새

- 가장 작은 단위
- DOM Elements: 화면에 나타나는 내용을 기술하는 스크립트 객체
- Virtual DOM != Browser DOM
- Elements는 화면에서 보이는 것을 기술

```
javascript
React.createElement(
    type,
    [props],
    [...children]
)
```

- React elements are immutable
- Elements 생성 후에는 children이나 attributes를 바꿀 수 없다.