# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0] 2018-11-08 beta

#### Added

- New version with gastby. For this version our team change storybook enviroment for developers and introduce our own enviroment based on gatsby.
- Functional CSS. Now each component of our library allow functional css.

## [1.4.0] Unreleased

#### Added

- [#](https://github.com/front10/landing-page-book/pull/151) Added props `alignHeader` to Section component, by [@jlfalcon3589]
- [#151](https://github.com/front10/landing-page-book/pull/151) Props `circle`, `rounded`, `active`, `size`, `color`, `style` to component Button, by [@rootlinux2](https://github.com/rootlinux2)
- [#151](https://github.com/front10/landing-page-book/pull/151) Props `btnRounded`, `btnDisabled` to component GithubButton, by [@rootlinux2](https://github.com/rootlinux2)
- [#151](https://github.com/front10/landing-page-book/pull/151) CSS variable --GithubDetail_speech-rounded to component GithubButton, by [@rootlinux2](https://github.com/rootlinux2)
- [#](https://github.com/front10/landing-page-book/pull/#) Added aligment `center` in the Header component , by [@jlfalcon3589](https://github.com/jlfalcon3589)

#### Change

- [#151](https://github.com/front10/landing-page-book/pull/151) All components API to work with Button, by [@rootlinux2](https://github.com/rootlinux2)
- [#](https://github.com/front10/landing-page-book/pull/#) Added paragraphs component, by [@jlfalcon](https://github.com/jlfalcon)
- [#](https://github.com/front10/landing-page-book/pull/#) Fixed `isCentered` props in the Hero component, by [@jlfalcon3589](https://github.com/jlfalcon3589)

## [1.3.1] 2018-10-20

#### Change

- Feature component removed required ID.

## [1.3.0] 2018-10-19

#### Added

- [#152](https://github.com/front10/landing-page-book/pull/152) Theming variables `--Team__Image-width`, `--Team__Image-height`, by [@ycgarrido](https://github.com/ycgarrido)
- [#152](https://github.com/front10/landing-page-book/pull/152) Props `shadow`, `imageShadow`, `topColor` to Team, by [@ycgarrido](https://github.com/ycgarrido)

#### Change

- [#153](https://github.com/front10/landing-page-book/pull/153) Theming variables `--CodeMirror__Footer-backgroundColor`, `--CodeMirror__Footer-color`, by [@jlfalcon3589](https://github.com/jlfalcon)

## [1.2.1] 2018-10-19

#### Change

- [#151](https://github.com/front10/landing-page-book/pull/151) homepage to `https://front10.com/landing-page-book` in `package.json`, by [@rootlinux2](https://github.com/rootlinux2)

## [1.2.0] 2018-10-19

#### Added

- [#151](https://github.com/front10/landing-page-book/pull/149) Theming variable `--Label-color`, `--Input-height:`, by [@jlfalcon3589](https://github.com/jlfalcon3589)
- [#151](https://github.com/front10/landing-page-book/pull/149) Prop `imgFilter` to Image, by [@jlfalcon3589](https://github.com/jlfalcon3589)
- [#151](https://github.com/front10/landing-page-book/pull/151) Prop `outline` to Button, `imageShadow`, `shadow`, `showFooter`, `outlineButton` to Features, by [@ycgarrido](https://github.com/ycgarrido)
- [#149](https://github.com/front10/landing-page-book/pull/149) Prop `shadow` to Image, `imageShadow`, `summaryJustified`, `shadow` to Card, by [@ycgarrido](https://github.com/ycgarrido)
- [#149](https://github.com/front10/landing-page-book/pull/149) Theming variable `--Image-boxShadow`, `--Card-boxShadow`, by [@ycgarrido](https://github.com/ycgarrido)

#### Remove

- [#151](https://github.com/front10/landing-page-book/pull/151) Prop `showBorder` to Features, by [@ycgarrido](https://github.com/ycgarrido)

## [1.1.0] 2018-10-18

#### Added

- [#146](https://github.com/front10/landing-page-book/pull/146) Props `collapsed`, `showDeleteButton`, `showCopyButton`, `children`, `collapsible` to Code, by [@ycgarrido](https://github.com/ycgarrido)
- [#146](https://github.com/front10/landing-page-book/pull/146) Theming variables `--CodeMirror__Container-border`, `--CodeMirror__Footer-color`, `--CodeMirror-borderRadius`, `--CodeMirror-fontSize`, by [@ycgarrido](https://github.com/ycgarrido)

#### Change

- [#146](https://github.com/front10/landing-page-book/pull/146) Theming variable name from `--CodeMirror__footer_backgroundColor` to `--CodeMirror__Footer-backgroundColor`, by [@ycgarrido](https://github.com/ycgarrido)
- [#146](https://github.com/front10/landing-page-book/pull/146) Code height from `250px` to `auto`, by [@ycgarrido](https://github.com/ycgarrido)
- [#146](https://github.com/front10/landing-page-book/pull/146) Code default theme from `oceanic-next` to `monokai`, by [@ycgarrido](https://github.com/ycgarrido)

#### Remove

- [#146](https://github.com/front10/landing-page-book/pull/146) Theming variables `--CodeMirror__footer_with`, `--CodeMirror__footer_height`, `--CodeMirror__header_copybtn_margin`, `--CodeMirror__header_deletebtn_margin`, by [@ycgarrido](https://github.com/ycgarrido)
- [#146](https://github.com/front10/landing-page-book/pull/146) Prop `showfooter` from Code, by [@ycgarrido](https://github.com/ycgarrido)
- [#142](https://github.com/front10/landing-page-book/pull/142) Tag `<title>` from svg image if `tooltip` prop is null, by [@ycgarrido](https://github.com/ycgarrido)

## [1.0.1] 2018-10-17

#### Added

- [#139](https://github.com/front10/landing-page-book/pull/139) Field `id` in array of items in Features component for map key, by [@ycgarrido](https://github.com/ycgarrido)
- [#137](https://github.com/front10/landing-page-book/pull/137) Improved responsive design compatibility in the Navbar for resolutions less than 768 px, by [@jlfalcon3589](https://github.com/jlfalcon3589)
- [#135](https://github.com/front10/landing-page-book/pull/135) New variables for GithubButton theming, by [@ycgarrido](https://github.com/ycgarrido)

#### Change

- [#139](https://github.com/front10/landing-page-book/pull/139) Put svg `<title>` in image component into `<g>`, by [@ycgarrido](https://github.com/ycgarrido)
- [#138](https://github.com/front10/landing-page-book/pull/138) Change subHeader from `h1` to `h2` in Hero, by [@ycgarrido](https://github.com/ycgarrido)
- [#135](https://github.com/front10/landing-page-book/pull/135) Default value of prop `selectedLanguage` from `US` to `""`, by [@ycgarrido](https://github.com/ycgarrido)

#### Remove

- [#137](https://github.com/front10/landing-page-book/pull/137) Removing letter-spacing in the Minecraft Theme, by [@jlfalcon3589](https://github.com/jlfalcon3589)

## [1.0.0] 2018-10-16

#### Added

- Initial Release.

## [0.1.24] 2018-10-15

#### Added

- More than 40 ReactJS components for landing page [StoryBook](https://front10.com/landing-page-book).
- Bootstrap theming [Theming](https://github.com/front10/landing-page-book/blob/master/theming.md).
- Zero config, Online playground, Lots of examples. [Easy & Fast](https://front10.com/get-landing-page-book).
- Proven and painless integration with Create React App, GatsbyJS and NextJS. [Integration](https://front10.com/get-landing-page-book).
