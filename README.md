# CSSY

LESS나 SCSS는 변수(Variable)나 중첩 규칙(Nested Rules) 등을 사용해 CSS 작성의 효율성을 높이는 CSS 전처리기(CSS Preprocessor)이다. CSSY는 LESS와 SCSS를 활용하여 CSS의 모든 속성을 '극단적으로' 믹스인화한 LESS & SCSS 믹스인 라이브러리(Mixin Library)이다.

<a align="center" href="http://kaldilab.com/cssy"><img width="100%" src="http://iiago.cdn2.cafe24.com/images/cssy.jpg" alt="Kaldi Lab - CSSY"></a>

## Usage

**① Project (Folder)**

```sh
Your Project/
├── mixins/
│   ├── _mixins.less(_mixins.scss)
│   └── ...
├── (img)
├── (css)
└── (less)
```

**② Import(*.less)**

```css
@import "(..)/mixins/_mixins.less";
```

**② Import(*.scss)**

```css
@import "(..)/mixins/_mixins.scss";
```

① 다운로드 받은 파일들 중 'mixins' 폴더를 통째로 사용자의 프로젝트에 붙여넣기 합니다.<br>② 'mixins' 폴더 내의 '_mixins.less' 파일 또는 '_mixins.scss' 파일을 사용자의 스타일 less 또는 scss 파일 첫머리에 첨부(@import)합니다. 끝.

## Kaldi Lab

[Kaldi Lab](http://kaldilab.com/)의 CSSY Website의 설명을 참고하세요.

- [CSSY](http://kaldilab.com/wp/cssy/)