# CSSY

CSSY는 LESS-Styler를 변형하여<br>
LESS와 SASS를 동일한 방식으로 믹스인화한<br>
CSS 전처리기 라이브러리(CSS Preprocessor Library) 입니다.

<a align="center" href="http://kaldilab.com/cssy"><img width="100%" src="http://iiago.cdn2.cafe24.com/images/cssy.jpg" alt="Kaldi Lab - CSSY"></a>

> LESS & SASS Mixin Library `v1.0.0`

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

- [CSSY](http://kaldilab.com/cssy/)