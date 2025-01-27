# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

<a name="4.2.0"></a>
# [4.2.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@4.1.0...@progress/kendo-theme-bootstrap@4.2.0) (2019-09-02)


### Bug Fixes

* **card:** update subtitle color to match design ([dbea6f6](https://github.com/telerik/kendo-themes/commit/dbea6f6))


### Features

* **card:** add callout and update styles based on the design ([bf3bc1c](https://github.com/telerik/kendo-themes/commit/bf3bc1c))
* **filter:** widget styles ([2334e35](https://github.com/telerik/kendo-themes/commit/2334e35))
* **pdf-viewer:** add search dialog styles ([4e4742e](https://github.com/telerik/kendo-themes/commit/4e4742e))
* **pdf-viewer:** add text layer sass styles ([bcf3a3a](https://github.com/telerik/kendo-themes/commit/bcf3a3a))
* **timeline:** widget styles ([dbee03c](https://github.com/telerik/kendo-themes/commit/dbee03c))




<a name="4.1.0"></a>
# [4.1.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@4.0.0...@progress/kendo-theme-bootstrap@4.1.0) (2019-07-26)


### Features

* rating styles ([1104050](https://github.com/telerik/kendo-themes/commit/1104050))




<a name="4.0.0"></a>
# [4.0.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@3.4.2...@progress/kendo-theme-bootstrap@4.0.0) (2019-07-08)


### Bug Fixes

* add !default flag to more variables ([5372039](https://github.com/telerik/kendo-themes/commit/5372039))
* **multiselect:** placeholder color ([aba2611](https://github.com/telerik/kendo-themes/commit/aba2611))
* remove usages of add-two and add-three ([604a730](https://github.com/telerik/kendo-themes/commit/604a730))


### Features

* fit frozen group header text in one row ([17382fe](https://github.com/telerik/kendo-themes/commit/17382fe))
* modify themes for dart-sass ([d3e1c27](https://github.com/telerik/kendo-themes/commit/d3e1c27))
* **grid:** add styles for search bar within grid toolbar ([0460702](https://github.com/telerik/kendo-themes/commit/0460702))


### BREAKING CHANGES

* remove add-two and add-three functions due to dart-sass compatibility issues
* Refactor themes so they can be compiled with dart-sass:

* create `.k-button-flat` selector for `@extend` use
* create `.k-button-overlay` selector for `@extend` use
* replace `@extend` usages of composite selectors `.k-button.k-flat` and `.k-button::before` with said selectors




<a name="3.4.2"></a>
## 3.4.2 (2019-06-12)


### Bug Fixes

* use gulp tasks in themes instead of lerna ([f5d5c0c](https://github.com/telerik/kendo-themes/commit/f5d5c0c))
* **drawer:** fix includes in bootstrap theme ([ed4364d](https://github.com/telerik/kendo-themes/commit/ed4364d))
* **grid:** adaptive renedering checkbox focused state ([12c2dbe](https://github.com/telerik/kendo-themes/commit/12c2dbe))
* **grid:** add no records template styles ([0c64ab0](https://github.com/telerik/kendo-themes/commit/0c64ab0))
* **notification:** improve alignment of text and icons in notification ([e629688](https://github.com/telerik/kendo-themes/commit/e629688))




<a name="3.4.1"></a>
## [3.4.1](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@3.4.0...@progress/kendo-theme-bootstrap@3.4.1) (2019-05-15)




**Note:** Version bump only for package @progress/kendo-theme-bootstrap

<a name="3.4.0"></a>
# 3.4.0 (2019-05-13)


### Bug Fixes

* **colorpicker:** alpha slider bgr using embed assets script ([a300c78](https://github.com/telerik/kendo-themes/commit/a300c78))
* drawer overlay closed layout ([9b09fa1](https://github.com/telerik/kendo-themes/commit/9b09fa1))
* **colorpicker:** bootstrap and material themes icon hover styles ([d451132](https://github.com/telerik/kendo-themes/commit/d451132))
* **colorpicker:** flex layout glitches when hiding dynamically content ([9711ef9](https://github.com/telerik/kendo-themes/commit/9711ef9))


### Features

* drawer styles ([76c7ea3](https://github.com/telerik/kendo-themes/commit/76c7ea3))
* **spreadsheet:** add images sass styles ([b369217](https://github.com/telerik/kendo-themes/commit/b369217))




<a name="3.3.1"></a>
## [3.3.1](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@3.3.0...@progress/kendo-theme-bootstrap@3.3.1) (2019-04-09)




**Note:** Version bump only for package @progress/kendo-theme-bootstrap

<a name="3.3.0"></a>
# [3.3.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@3.2.3...@progress/kendo-theme-bootstrap@3.3.0) (2019-04-08)


### Bug Fixes

* **buttons:** disabled focused buttons styles in mozilla ([961f592](https://github.com/telerik/kendo-themes/commit/961f592))
* **textbox:** placeholder color in IE ([cfd732a](https://github.com/telerik/kendo-themes/commit/cfd732a))


### Features

* **calendar:** add styles for Blazor calendar ([8987d65](https://github.com/telerik/kendo-themes/commit/8987d65))
* **pager:** rendering changes and styles ([0a5642b](https://github.com/telerik/kendo-themes/commit/0a5642b))




<a name="3.2.3"></a>
## 3.2.3 (2019-03-14)


### Bug Fixes

* upgrade theme dependency to bootstrap 4.3.1 ([eedd116](https://github.com/telerik/kendo-themes/commit/eedd116))
* **buttons:** use correct color for .k-button.k-flat:hover.k-state-active ([eebad66](https://github.com/telerik/kendo-themes/commit/eebad66))
* **colorpicker:** wrapper hover styles not applied ([0f5ea5e](https://github.com/telerik/kendo-themes/commit/0f5ea5e))
* **dropdowns:** remove list items transform transitions ([71f3982](https://github.com/telerik/kendo-themes/commit/71f3982))
* **grid:** added active styles for grid column menu ([dfd1bc6](https://github.com/telerik/kendo-themes/commit/dfd1bc6))
* **grid:** grouping header text overflows with frozen columns ([779a216](https://github.com/telerik/kendo-themes/commit/779a216))
* **scheduler:** decreasing bootstrap padding in angular ([8ad054c](https://github.com/telerik/kendo-themes/commit/8ad054c))
* **scheduler:** month view style improvements ([e3dc082](https://github.com/telerik/kendo-themes/commit/e3dc082))
* **toolbar:** added min-height ([452f4c0](https://github.com/telerik/kendo-themes/commit/452f4c0))




<a name="3.2.2"></a>
## [3.2.2](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@3.2.1...@progress/kendo-theme-bootstrap@3.2.2) (2019-02-19)


### Bug Fixes

* **gantt:** improve focused toolbar item styles ([1c2d77f](https://github.com/telerik/kendo-themes/commit/1c2d77f))
* **scheduler:** improve scheduler event styles ([a37e948](https://github.com/telerik/kendo-themes/commit/a37e948))




<a name="3.2.1"></a>
## 3.2.1 (2019-02-14)


### Bug Fixes

* **editor:** selected table cells styles ([3e9bc58](https://github.com/telerik/kendo-themes/commit/3e9bc58))
* **grid:** improve styles for column settings menu ([6f5ba27](https://github.com/telerik/kendo-themes/commit/6f5ba27))
* **input:** edge specific style for inputs in flex container ([2e80be3](https://github.com/telerik/kendo-themes/commit/2e80be3))
* **pivotgrid:** bottom border on collapsed items ([23e00f5](https://github.com/telerik/kendo-themes/commit/23e00f5))
* **scheduler:** columns layout in material theme ([20b31c9](https://github.com/telerik/kendo-themes/commit/20b31c9))
* **scheduler:** header items focus state styles ([7516d9c](https://github.com/telerik/kendo-themes/commit/7516d9c))
* **scheduler:** incorrect inverse color for event title [#168](https://github.com/telerik/kendo-themes/issues/168) ([b2b2a81](https://github.com/telerik/kendo-themes/commit/b2b2a81))
* **scheduler:** navigation focus state ([9e5b372](https://github.com/telerik/kendo-themes/commit/9e5b372))
* **spreadsheet:** filter menu sort icons ([f9d09ab](https://github.com/telerik/kendo-themes/commit/f9d09ab))




<a name="3.2.0"></a>
# [3.2.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@3.1.0...@progress/kendo-theme-bootstrap@3.2.0) (2019-01-15)


### Bug Fixes

* **popup:** group header styles ([7032efe](https://github.com/telerik/kendo-themes/commit/7032efe))


### Features

* **datetimepicker:** add styles for kendo-react ([1aea521](https://github.com/telerik/kendo-themes/commit/1aea521))




<a name="3.1.0"></a>
# [3.1.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@3.0.0...@progress/kendo-theme-bootstrap@3.1.0) (2019-01-14)


### Bug Fixes

* **pager:** hover bg color ([bda7b56](https://github.com/telerik/kendo-themes/commit/bda7b56))


### Features

* add prebuilt swatches to npm package ([5962540](https://github.com/telerik/kendo-themes/commit/5962540)), closes [#36](https://github.com/telerik/kendo-themes/issues/36)




<a name="3.0.0"></a>
# [3.0.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.18.0...@progress/kendo-theme-bootstrap@3.0.0) (2019-01-08)


### Features

* **switch:** improvements based on the latest design ([2a1dcec](https://github.com/telerik/kendo-themes/commit/2a1dcec))


### BREAKING CHANGES

* **switch:** Improve switch rendering and remove javascript animations




<a name="2.18.0"></a>
# 2.18.0 (2019-01-07)


### Bug Fixes

* improve clear icon position in dropdowns and pickers ([f83db0f](https://github.com/telerik/kendo-themes/commit/f83db0f))
* **calendar:** remove material header buttons shadow ([1396eec](https://github.com/telerik/kendo-themes/commit/1396eec))
* **dialog:** improve button layouts ([37c988d](https://github.com/telerik/kendo-themes/commit/37c988d))
* **grid:** drag clue styles improvements [#252](https://github.com/telerik/kendo-themes/issues/252) ([780ff12](https://github.com/telerik/kendo-themes/commit/780ff12))
* **grid:** filter menu buttons margin and borders ([471c5b2](https://github.com/telerik/kendo-themes/commit/471c5b2))
* **scrollview:** trigger build ([a209ce2](https://github.com/telerik/kendo-themes/commit/a209ce2))
* **window:** window actions are not properly aligned in IE ([c2f6f6b](https://github.com/telerik/kendo-themes/commit/c2f6f6b))


### Features

* add predefined widths for Window and Dialog ([18cab9c](https://github.com/telerik/kendo-themes/commit/18cab9c))
* responsive pager jQuery ([9baeefc](https://github.com/telerik/kendo-themes/commit/9baeefc))




<a name="2.17.1"></a>
## [2.17.1](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.17.0...@progress/kendo-theme-bootstrap@2.17.1) (2018-12-07)


### Bug Fixes

* **material:** improve window appearance in dark themes ([ad56d1e](https://github.com/telerik/kendo-themes/commit/ad56d1e))
* **pager:** expose and use pager variables ([a09f6f4](https://github.com/telerik/kendo-themes/commit/a09f6f4))
* **scrollview:** revert regression rendering changes ([398412c](https://github.com/telerik/kendo-themes/commit/398412c))




<a name="2.17.0"></a>
# [2.17.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.16.0...@progress/kendo-theme-bootstrap@2.17.0) (2018-11-22)


### Bug Fixes

* **grid:** non-scrollable grid command buttons margins ([43e18ba](https://github.com/telerik/kendo-themes/commit/43e18ba)), closes [#426](https://github.com/telerik/kendo-themes/issues/426)


### Features

* **grid:** add hover + selected rows styles ([7dde502](https://github.com/telerik/kendo-themes/commit/7dde502))




<a name="2.16.0"></a>
# [2.16.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.15.0...@progress/kendo-theme-bootstrap@2.16.0) (2018-11-09)


### Bug Fixes

* **scheduler:** adaptive view switcher background ([41bdb94](https://github.com/telerik/kendo-themes/commit/41bdb94))
* **scheduler:** use :hover for buttons ([e296270](https://github.com/telerik/kendo-themes/commit/e296270))


### Features

* add kendo-theme-tasks ([61bda89](https://github.com/telerik/kendo-themes/commit/61bda89))




<a name="2.15.0"></a>
# [2.15.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.14.3...@progress/kendo-theme-bootstrap@2.15.0) (2018-10-31)


### Features

* **multiviewcalendar:** add multiviewcalendar for kendo-jquery ([9761e30](https://github.com/telerik/kendo-themes/commit/9761e30))




<a name="2.14.3"></a>
## [2.14.3](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.14.2...@progress/kendo-theme-bootstrap@2.14.3) (2018-10-29)




**Note:** Version bump only for package @progress/kendo-theme-bootstrap

<a name="2.14.2"></a>
## 2.14.2 (2018-10-16)


### Bug Fixes

* **inputs:** apply invalid state only trough class name instead of pseudo class ([4e0c8a2](https://github.com/telerik/kendo-themes/commit/4e0c8a2))
* **pager:** font-size and alignment corrections ([d44c8dd](https://github.com/telerik/kendo-themes/commit/d44c8dd))
* **pager:** use correct border radius in first / last links when in rtl ([ec3d97d](https://github.com/telerik/kendo-themes/commit/ec3d97d))
* **tabstrip:** extract tabstrip variables and use correct values ([699be9c](https://github.com/telerik/kendo-themes/commit/699be9c))




<a name="2.14.1"></a>
## [2.14.1](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.14.0...@progress/kendo-theme-bootstrap@2.14.1) (2018-10-01)


### Bug Fixes

* correct a typo in variable name ([0b1938c](https://github.com/telerik/kendo-themes/commit/0b1938c))




<a name="2.14.0"></a>
# 2.14.0 (2018-09-11)


### Bug Fixes

* **combobox:** incorrect styling when importing styles separately ([16da3d5](https://github.com/telerik/kendo-themes/commit/16da3d5))
* **multiselect:** incorrect styling when importing styles separately ([e5ea1ed](https://github.com/telerik/kendo-themes/commit/e5ea1ed))
* **tooltip:** incorrect styling when importing styles separately ([#304](https://github.com/telerik/kendo-themes/issues/304)) ([f78ff85](https://github.com/telerik/kendo-themes/commit/f78ff85))
* improve form variables in accordance to material design ([dcb5a44](https://github.com/telerik/kendo-themes/commit/dcb5a44))


### Features

* add themes for dropdowngrid ([d4171f0](https://github.com/telerik/kendo-themes/commit/d4171f0))
* **spreadsheet:** add Material theme ([#275](https://github.com/telerik/kendo-themes/issues/275)) ([043d7ed](https://github.com/telerik/kendo-themes/commit/043d7ed))




<a name="2.13.8"></a>
## 2.13.8 (2018-08-22)


### Bug Fixes

* **buttons:** remove box-shadow of active outline buttons ([#238](https://github.com/telerik/kendo-themes/issues/238)) ([ff5708f](https://github.com/telerik/kendo-themes/commit/ff5708f)), closes [telerik/kendo-themes#237](https://github.com/telerik/kendo-themes/issues/237)
* relax Bootstrap framework version requirement ([08a15b3](https://github.com/telerik/kendo-themes/commit/08a15b3))
* **progressbar:** use repeating gradient for indeterminate state ([d16368c](https://github.com/telerik/kendo-themes/commit/d16368c))




<a name="2.13.7"></a>
## [2.13.7](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.13.6...@progress/kendo-theme-bootstrap@2.13.7) (2018-07-24)




**Note:** Version bump only for package @progress/kendo-theme-bootstrap

<a name="2.13.6"></a>
## [2.13.6](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.13.5...@progress/kendo-theme-bootstrap@2.13.6) (2018-06-18)


### Bug Fixes

* **calendar:** error when compiling standalone calendar ([67aa44a](https://github.com/telerik/kendo-themes/commit/67aa44a))
* **tooltip:** align closable tooltip icon button ([69f2d09](https://github.com/telerik/kendo-themes/commit/69f2d09))




<a name="2.13.5"></a>
## [2.13.5](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.13.4...@progress/kendo-theme-bootstrap@2.13.5) (2018-05-23)


### Bug Fixes

* **notification:** add Material styles, improve close icon positioning ([5340230](https://github.com/telerik/kendo-themes/commit/5340230))




<a name="2.13.4"></a>
## [2.13.4](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.13.3...@progress/kendo-theme-bootstrap@2.13.4) (2018-05-16)




**Note:** Version bump only for package @progress/kendo-theme-bootstrap

<a name="2.13.3"></a>
## [2.13.3](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.13.2...@progress/kendo-theme-bootstrap@2.13.3) (2018-05-15)




**Note:** Version bump only for package @progress/kendo-theme-bootstrap

<a name="2.13.2"></a>
## [2.13.2](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.13.1...@progress/kendo-theme-bootstrap@2.13.2) (2018-05-10)




**Note:** Version bump only for package @progress/kendo-theme-bootstrap

<a name="2.13.1"></a>
## [2.13.1](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.13.0...@progress/kendo-theme-bootstrap@2.13.1) (2018-05-09)




**Note:** Version bump only for package @progress/kendo-theme-bootstrap

<a name="2.13.0"></a>
# 2.13.0 (2018-05-07)


### Features

* add TabStrip styling ([a93d7cc](https://github.com/telerik/kendo-themes/commit/a93d7cc))
* **grid:** add Angular column menu styling ([38d9486](https://github.com/telerik/kendo-themes/commit/38d9486))




<a name="2.12.1"></a>
## [2.12.1](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.12.0...@progress/kendo-theme-bootstrap@2.12.1) (2018-04-30)


### Bug Fixes

* **chat:** resolve missing file error when building from source ([#148](https://github.com/telerik/kendo-themes/issues/148)) ([d72af65](https://github.com/telerik/kendo-themes/commit/d72af65))




<a name="2.12.0"></a>
# 2.12.0 (2018-04-27)


### Bug Fixes

* **grid:** improve grouping header layout in Angular ([1df42eb](https://github.com/telerik/kendo-themes/commit/1df42eb))
* **textarea:** use input appearance ([af44caf](https://github.com/telerik/kendo-themes/commit/af44caf))


### Features

* add styles for chat widget ([#146](https://github.com/telerik/kendo-themes/issues/146)) ([5729aec](https://github.com/telerik/kendo-themes/commit/5729aec))
* add styles for Material Upload ([0a183f4](https://github.com/telerik/kendo-themes/commit/0a183f4))




<a name="2.11.11"></a>
## 2.11.11 (2018-04-11)


### Bug Fixes

* **dateinput:** improve spinner layout to match numeric ([d8d0842](https://github.com/telerik/kendo-themes/commit/d8d0842))
* **listview:** Improve focused and selected state appearance of listview in accordance with design ([4225503](https://github.com/telerik/kendo-themes/commit/4225503))




<a name="2.11.10"></a>
## [2.11.10](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.11.9...@progress/kendo-theme-bootstrap@2.11.10) (2018-03-26)


### Bug Fixes

* **button:** improve styles for flat and bare look ([e2e8b7a](https://github.com/telerik/kendo-themes/commit/e2e8b7a))




<a name="2.11.9"></a>
## [2.11.9](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.11.8...@progress/kendo-theme-bootstrap@2.11.9) (2018-03-12)


### Bug Fixes

* **input:** show angular invalid state on touch/dirty ([a7dbc4d](https://github.com/telerik/kendo-themes/commit/a7dbc4d)), closes [telerik/kendo-theme-bootstrap#369](https://github.com/telerik/kendo-theme-bootstrap/issues/369)




<a name="2.11.8"></a>
## [2.11.8](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.11.7...@progress/kendo-theme-bootstrap@2.11.8) (2018-02-20)




**Note:** Version bump only for package @progress/kendo-theme-bootstrap

<a name="2.11.7"></a>
## [2.11.7](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-bootstrap@2.11.6...@progress/kendo-theme-bootstrap@2.11.7) (2018-02-16)


### Bug Fixes

* **editor:** add styles for editor table telerik/kendo[#8213](https://github.com/telerik/kendo-themes/issues/8213) ([5cec16a](https://github.com/telerik/kendo-themes/commit/5cec16a))




<a name="2.11.6"></a>
## [2.11.6](https://github.com/telerik/kendo-theme-bootstrap/compare/@progress/kendo-theme-bootstrap@2.11.5...@progress/kendo-theme-bootstrap@2.11.6) (2018-02-13)




**Note:** Version bump only for package @progress/kendo-theme-bootstrap

<a name="2.11.5"></a>
## [2.11.5](https://github.com/telerik/kendo-theme-bootstrap/compare/@progress/kendo-theme-bootstrap@2.11.4...@progress/kendo-theme-bootstrap@2.11.5) (2018-02-06)




**Note:** Version bump only for package @progress/kendo-theme-bootstrap

<a name="2.11.4"></a>
## [2.11.4](https://github.com/telerik/kendo-theme-bootstrap/compare/@progress/kendo-theme-bootstrap@2.11.3...@progress/kendo-theme-bootstrap@2.11.4) (2018-02-06)


### Bug Fixes

* **package:** reduce npm package size for derived themes ([d4a2ad9](https://github.com/telerik/kendo-theme-bootstrap/commit/d4a2ad9))




<a name="2.11.3"></a>
## [2.11.3](https://github.com/telerik/kendo-theme-bootstrap/compare/@progress/kendo-theme-bootstrap@2.11.2...@progress/kendo-theme-bootstrap@2.11.3) (2018-02-06)




**Note:** Version bump only for package @progress/kendo-theme-bootstrap

<a name="3.0.0"></a>
# 3.0.0 (2018-01-30)


### Bug Fixes

* add bootstrap overrides and update variables ([0a81bc0](https://github.com/telerik/kendo-theme-bootstrap/commit/0a81bc0))
* add dependencies to bootstrap variables to all components ([912e821](https://github.com/telerik/kendo-theme-bootstrap/commit/912e821))
* add dirty collapse / expand icons. unifiy icon pseudo elements ([dd8fa00](https://github.com/telerik/kendo-theme-bootstrap/commit/dd8fa00))
* add global options variables for rounded corners, shadows, gradients and transitions ([7fbd9b1](https://github.com/telerik/kendo-theme-bootstrap/commit/7fbd9b1))
* add styles for missing chart components ([e07ec09](https://github.com/telerik/kendo-theme-bootstrap/commit/e07ec09))
* add styles for selected tabstrip pane ([32143f0](https://github.com/telerik/kendo-theme-bootstrap/commit/32143f0))
* allow package to work outside of webpack ([f330d67](https://github.com/telerik/kendo-theme-bootstrap/commit/f330d67))
* border and text decorations ([2c45e1f](https://github.com/telerik/kendo-theme-bootstrap/commit/2c45e1f))
* consolidate picker form controls ([3a01dc4](https://github.com/telerik/kendo-theme-bootstrap/commit/3a01dc4))
* correct classnames for seek icons ([0ce684a](https://github.com/telerik/kendo-theme-bootstrap/commit/0ce684a))
* correct main file name in NPM package ([c6feade](https://github.com/telerik/kendo-theme-bootstrap/commit/c6feade))
* correct path for editor import ([bb8954c](https://github.com/telerik/kendo-theme-bootstrap/commit/bb8954c))
* define all inherited variables when importing component files ([3e1e3a2](https://github.com/telerik/kendo-theme-bootstrap/commit/3e1e3a2))
* duplicate selectors in switch widget styles so kendo-ng-* can use them ([42b4f96](https://github.com/telerik/kendo-theme-bootstrap/commit/42b4f96))
* grid alt and selected state ([7052156](https://github.com/telerik/kendo-theme-bootstrap/commit/7052156))
* improve styles for days ([778f9ec](https://github.com/telerik/kendo-theme-bootstrap/commit/778f9ec))
* improve styles in switch for angular ([409fb25](https://github.com/telerik/kendo-theme-bootstrap/commit/409fb25))
* improve volume slider styles ([8a30252](https://github.com/telerik/kendo-theme-bootstrap/commit/8a30252))
* include color functions in the variables file ([07975f2](https://github.com/telerik/kendo-theme-bootstrap/commit/07975f2))
* inline Editor border width and select state ([aea000b](https://github.com/telerik/kendo-theme-bootstrap/commit/aea000b))
* make theme work with kendo-theme-default@2.x ([44e2ee5](https://github.com/telerik/kendo-theme-bootstrap/commit/44e2ee5))
* missing handle icon and background of splitbar in normal state ([6878f70](https://github.com/telerik/kendo-theme-bootstrap/commit/6878f70))
* **MaskedTextbox:** Fix invalid state border ([9d559cb](https://github.com/telerik/kendo-theme-bootstrap/commit/9d559cb))
* pager and dropdownlist appearance ([a33c910](https://github.com/telerik/kendo-theme-bootstrap/commit/a33c910))
* reduce toolbar padding ([56b4e30](https://github.com/telerik/kendo-theme-bootstrap/commit/56b4e30))
* remove extra borders of button groups and fix border color of selected button ([8930df8](https://github.com/telerik/kendo-theme-bootstrap/commit/8930df8))
* remove focus box-shadow from editors ([56386c4](https://github.com/telerik/kendo-theme-bootstrap/commit/56386c4))
* specify transition properties ([3224751](https://github.com/telerik/kendo-theme-bootstrap/commit/3224751)), closes [#198](https://github.com/telerik/kendo-theme-bootstrap/issues/198)
* splitter does not apply styles for hover state ([ccd3303](https://github.com/telerik/kendo-theme-bootstrap/commit/ccd3303))
* stop using css modules via common-tasks 2.0 ([04ef5ee](https://github.com/telerik/kendo-theme-bootstrap/commit/04ef5ee))
* **button:** improve outline button appearance ([a634d3e](https://github.com/telerik/kendo-theme-bootstrap/commit/a634d3e))
* **button:** use correct colors for primary button ([89d803d](https://github.com/telerik/kendo-theme-bootstrap/commit/89d803d))
* **buttonGroup:** fix no applying focus state to disabled button in button group telerik/kendo[#7846](https://github.com/telerik/kendo-theme-bootstrap/issues/7846) ([c64cbd7](https://github.com/telerik/kendo-theme-bootstrap/commit/c64cbd7))
* **calendar:** add styles for infinite calendar ([abee18c](https://github.com/telerik/kendo-theme-bootstrap/commit/abee18c))
* **calendar:** update calendar appearance in accordance to Bootstrap v4 beta-1 ([5779cd9](https://github.com/telerik/kendo-theme-bootstrap/commit/5779cd9))
* **chart:** grid lines colors ([#102](https://github.com/telerik/kendo-theme-bootstrap/issues/102)) ([7e2361d](https://github.com/telerik/kendo-theme-bootstrap/commit/7e2361d))
* **combobox:** rtl appearance ([9970562](https://github.com/telerik/kendo-theme-bootstrap/commit/9970562))
* **combobox:** wrong border colors of focused combobox ([3774304](https://github.com/telerik/kendo-theme-bootstrap/commit/3774304))
* **common:** improve header variables ([b0b54e6](https://github.com/telerik/kendo-theme-bootstrap/commit/b0b54e6))
* **common:** update dependency to Bootstrap v4 beta-2 ([0c50b53](https://github.com/telerik/kendo-theme-bootstrap/commit/0c50b53))
* **contextmenu:** update contextmenu appearance ([a416da7](https://github.com/telerik/kendo-theme-bootstrap/commit/a416da7))
* **dateinput:** border, hover and focus state ([08b753c](https://github.com/telerik/kendo-theme-bootstrap/commit/08b753c))
* **dateinputs:** apply consistent header styles ([c2b7d5f](https://github.com/telerik/kendo-theme-bootstrap/commit/c2b7d5f))
* **datetimepicker:** wrong focus state borders colors ([687c955](https://github.com/telerik/kendo-theme-bootstrap/commit/687c955))
* **dropdown:** add focus state to dropdown and popup ([9ce99ab](https://github.com/telerik/kendo-theme-bootstrap/commit/9ce99ab))
* **dropdownlist:** apply color to option label border ([ececc25](https://github.com/telerik/kendo-theme-bootstrap/commit/ececc25))
* **editors:** common layout glitches ([5b588d2](https://github.com/telerik/kendo-theme-bootstrap/commit/5b588d2))
* **forms:** align forms in dialog labels. ([61c881d](https://github.com/telerik/kendo-theme-bootstrap/commit/61c881d))
* **gantt:** improve milestone appearance ([df7c9a1](https://github.com/telerik/kendo-theme-bootstrap/commit/df7c9a1))
* **gantt:** make task resize handler wider and transparent ([af62568](https://github.com/telerik/kendo-theme-bootstrap/commit/af62568))
* **gantt:** reduce padding of toolbar-like elements in gantt ([fd945e2](https://github.com/telerik/kendo-theme-bootstrap/commit/fd945e2))
* **gantt:** view switcher is missing selected state ([2c19585](https://github.com/telerik/kendo-theme-bootstrap/commit/2c19585))
* **grid:** Add dirty cell indicator styling ([e75eca0](https://github.com/telerik/kendo-theme-bootstrap/commit/e75eca0))
* **grid:** Add missing locked footer border color ([e5caf33](https://github.com/telerik/kendo-theme-bootstrap/commit/e5caf33))
* **grid:** Add RTL styles for dirty cells ([266ebc7](https://github.com/telerik/kendo-theme-bootstrap/commit/266ebc7))
* **grid:** border color ([1923fff](https://github.com/telerik/kendo-theme-bootstrap/commit/1923fff))
* **grid:** Fix edit textbox width variable ([598e451](https://github.com/telerik/kendo-theme-bootstrap/commit/598e451))
* **grid:** improve grid row selected state ([1150dad](https://github.com/telerik/kendo-theme-bootstrap/commit/1150dad))
* **grid:** reduce padding of toolbar-like elements in grid ([cf25e3c](https://github.com/telerik/kendo-theme-bootstrap/commit/cf25e3c))
* **grid:** remove focus on header links ([96637a2](https://github.com/telerik/kendo-theme-bootstrap/commit/96637a2))
* **grid:** Remove selection column checkbox margin in RTL ([c671f29](https://github.com/telerik/kendo-theme-bootstrap/commit/c671f29))
* **grid:** scope selcted styles ([be070f9](https://github.com/telerik/kendo-theme-bootstrap/commit/be070f9))
* **grid:** Set fixed font-size of col sorting index to achieve alignment ([e8aef0b](https://github.com/telerik/kendo-theme-bootstrap/commit/e8aef0b))
* **grid:** Tweak multiple column sorting index position ([787d70e](https://github.com/telerik/kendo-theme-bootstrap/commit/787d70e))
* **grid:** use scoped grid variables ([7c12b76](https://github.com/telerik/kendo-theme-bootstrap/commit/7c12b76))
* **Grid:** Add cell focused state styles ([0c3fd96](https://github.com/telerik/kendo-theme-bootstrap/commit/0c3fd96))
* **Grid:** Add styles for verification tooltip ([c2b1f8a](https://github.com/telerik/kendo-theme-bootstrap/commit/c2b1f8a))
* **input:** Add styles for placeholder text ([9ea8b70](https://github.com/telerik/kendo-theme-bootstrap/commit/9ea8b70))
* **inputs:** wrong border color for invalid inputs ([c62ea18](https://github.com/telerik/kendo-theme-bootstrap/commit/c62ea18)), closes [telerik/kendo-theme-bootstrap#289](https://github.com/telerik/kendo-theme-bootstrap/issues/289)
* **listbox:** use correct variables for listbox ([f863af3](https://github.com/telerik/kendo-theme-bootstrap/commit/f863af3))
* **ListBox:** Improve button margins temporarily ([005ce87](https://github.com/telerik/kendo-theme-bootstrap/commit/005ce87))
* **listview:** add focused state ([b5d0c07](https://github.com/telerik/kendo-theme-bootstrap/commit/b5d0c07))
* **map:** Add marker color ([c958ace](https://github.com/telerik/kendo-theme-bootstrap/commit/c958ace))
* **map:** directions navigator is not properly customized in themebuilder ([502028d](https://github.com/telerik/kendo-theme-bootstrap/commit/502028d))
* **MaskedTextbox:** Add missing invalid state border ([2b9a72b](https://github.com/telerik/kendo-theme-bootstrap/commit/2b9a72b))
* **mediaplayer:** add opacity to toolbar ([d0aa7bc](https://github.com/telerik/kendo-theme-bootstrap/commit/d0aa7bc))
* **menu:** add styles for scrolling ([aa4a878](https://github.com/telerik/kendo-theme-bootstrap/commit/aa4a878))
* **multiselect:** border color ([d620f57](https://github.com/telerik/kendo-theme-bootstrap/commit/d620f57))
* **multiselect:** improve height of token with empty string telerik/kendo-ui-core[#372](https://github.com/telerik/kendo-theme-bootstrap/issues/372) ([a050374](https://github.com/telerik/kendo-theme-bootstrap/commit/a050374))
* **multiselect:** wrong items height ([a5c6116](https://github.com/telerik/kendo-theme-bootstrap/commit/a5c6116))
* **notification:** use panel styles for default type ([91ca341](https://github.com/telerik/kendo-theme-bootstrap/commit/91ca341))
* **notification:** use scoped variables for notification ([96b2c2c](https://github.com/telerik/kendo-theme-bootstrap/commit/96b2c2c))
* **numerictextbox:** spinners misalignment ([d89d006](https://github.com/telerik/kendo-theme-bootstrap/commit/d89d006))
* **pager:** add focus outline for pager buttons ([316ff9b](https://github.com/telerik/kendo-theme-bootstrap/commit/316ff9b))
* **pager:** focused state text decoration ([82fa821](https://github.com/telerik/kendo-theme-bootstrap/commit/82fa821))
* **pager:** improve disabled state of pager items ([18922d1](https://github.com/telerik/kendo-theme-bootstrap/commit/18922d1))
* **pager:** improve selected styles ([86b5726](https://github.com/telerik/kendo-theme-bootstrap/commit/86b5726))
* **pager:** use consistent header appearance ([a6ae6cd](https://github.com/telerik/kendo-theme-bootstrap/commit/a6ae6cd))
* **pager:** use relative units for button metrics ([#267](https://github.com/telerik/kendo-theme-bootstrap/issues/267)) ([bc5d7d3](https://github.com/telerik/kendo-theme-bootstrap/commit/bc5d7d3))
* **panelbar:** improve focus state ([54497f8](https://github.com/telerik/kendo-theme-bootstrap/commit/54497f8))
* **panelbar:** use correct border color for root items ([7dd7582](https://github.com/telerik/kendo-theme-bootstrap/commit/7dd7582))
* **pivotgrid:** apply header-bg to pivotgrid configurator ([381406a](https://github.com/telerik/kendo-theme-bootstrap/commit/381406a))
* **pivotgrid:** reduce padding of toolbar-like elements in pivotgrid ([8af6287](https://github.com/telerik/kendo-theme-bootstrap/commit/8af6287))
* **pivotgrid:** use correct color for pivotgrid toolbar border ([9f0fb06](https://github.com/telerik/kendo-theme-bootstrap/commit/9f0fb06))
* **Popup:** Remove the top and bottom padding of Popup when used as a column menu ([5b0ed95](https://github.com/telerik/kendo-theme-bootstrap/commit/5b0ed95))
* **progressbar:** add styles for indetermined progressbar ([e13a6c4](https://github.com/telerik/kendo-theme-bootstrap/commit/e13a6c4))
* **progressbar:** use correct variables for progressbar ([7bcdc0c](https://github.com/telerik/kendo-theme-bootstrap/commit/7bcdc0c))
* **ripple:** add default ripple styles ([19d1c09](https://github.com/telerik/kendo-theme-bootstrap/commit/19d1c09))
* **scheduler:** add bacground to event with no resources ([5fa6a29](https://github.com/telerik/kendo-theme-bootstrap/commit/5fa6a29))
* **scheduler:** view switcher is missing selected state ([9abcf35](https://github.com/telerik/kendo-theme-bootstrap/commit/9abcf35))
* **scrollview:** add styles for scrollview pager ([e79ecb8](https://github.com/telerik/kendo-theme-bootstrap/commit/e79ecb8))
* **slider:** add focus state to drag handle ([8208d0a](https://github.com/telerik/kendo-theme-bootstrap/commit/8208d0a))
* **slider:** add tick images ([80ed313](https://github.com/telerik/kendo-theme-bootstrap/commit/80ed313))
* **slider:** link slider variables to progressbar variables ([0ede195](https://github.com/telerik/kendo-theme-bootstrap/commit/0ede195))
* **slider:** remove browser outline on focus ([dc7fd03](https://github.com/telerik/kendo-theme-bootstrap/commit/dc7fd03))
* **splitter:** use correct colors for splitter ([2ff9472](https://github.com/telerik/kendo-theme-bootstrap/commit/2ff9472))
* **spreadsheet:** add styles for filter menu and filter button ([05ea173](https://github.com/telerik/kendo-theme-bootstrap/commit/05ea173))
* **spreadsheet:** improve spreadsheet active cell border by frozen cells telerik/kendo-ui-core[#3254](https://github.com/telerik/kendo-theme-bootstrap/issues/3254) ([0d838c3](https://github.com/telerik/kendo-theme-bootstrap/commit/0d838c3))
* **spreadsheet:** make drag handle to be visible in all cases telerik/kendo-ui-core[#3254](https://github.com/telerik/kendo-theme-bootstrap/issues/3254) ([4fdeafc](https://github.com/telerik/kendo-theme-bootstrap/commit/4fdeafc))
* **spreadsheet:** missing indicators for spreadsheet ([18ff11d](https://github.com/telerik/kendo-theme-bootstrap/commit/18ff11d))
* **spreadsheet:** styles for spreadsheet toolbar ([7e51ad7](https://github.com/telerik/kendo-theme-bootstrap/commit/7e51ad7))
* **switch:** border-color of switch is too dark ([1659185](https://github.com/telerik/kendo-theme-bootstrap/commit/1659185))
* wrong border color of input in scheduler advanced form ([eaf5e48](https://github.com/telerik/kendo-theme-bootstrap/commit/eaf5e48))
* **switch:** use correct border-radius for switch wrapper ([11f697e](https://github.com/telerik/kendo-theme-bootstrap/commit/11f697e))
* **tabstrip:** update variables to reflect changes in bootstrap ([fc60359](https://github.com/telerik/kendo-theme-bootstrap/commit/fc60359))
* **tabstrip:** use correct border-color when hovering / selecting tabs ([66709a7](https://github.com/telerik/kendo-theme-bootstrap/commit/66709a7))
* **timepicker:** improve popup appearance ([#348](https://github.com/telerik/kendo-theme-bootstrap/issues/348)) ([19e3965](https://github.com/telerik/kendo-theme-bootstrap/commit/19e3965))
* **tooltip:** tooltip cannot be customized in theme builder ([8e220c7](https://github.com/telerik/kendo-theme-bootstrap/commit/8e220c7))
* **tooltip:** use $font-size-sm ([c40001f](https://github.com/telerik/kendo-theme-bootstrap/commit/c40001f))
* **tooltip:** use alert-padding for close button ([2b130c7](https://github.com/telerik/kendo-theme-bootstrap/commit/2b130c7))
* **tooltip:** use contrast function to determine text color based on background ([6bc6c12](https://github.com/telerik/kendo-theme-bootstrap/commit/6bc6c12))
* **tooltip:** use correct padding for collapsible tooltip ([20ec0ad](https://github.com/telerik/kendo-theme-bootstrap/commit/20ec0ad))
* **tooltip:** use tooltip font-size variable ([53b2864](https://github.com/telerik/kendo-theme-bootstrap/commit/53b2864))
* **treeview:** add additional spacing around nodes so box shadow dont overlap ([260a216](https://github.com/telerik/kendo-theme-bootstrap/commit/260a216))
* **treeview:** add border radius to nodes ([184301c](https://github.com/telerik/kendo-theme-bootstrap/commit/184301c))
* **treeview:** focused and selected-focused state are clipped ([56e9445](https://github.com/telerik/kendo-theme-bootstrap/commit/56e9445))
* **treeview:** improve node colors ([9885066](https://github.com/telerik/kendo-theme-bootstrap/commit/9885066))
* **treeview:** reduce spacing between checkbox and item text ([b6426fc](https://github.com/telerik/kendo-theme-bootstrap/commit/b6426fc))
* **upload:** import theme styles from the default theme ([6e330aa](https://github.com/telerik/kendo-theme-bootstrap/commit/6e330aa))
* **window:** add spacing between buttons ([cbd9223](https://github.com/telerik/kendo-theme-bootstrap/commit/cbd9223))
* **window:** fix content bleeding outside of window boundaries ([932c9a7](https://github.com/telerik/kendo-theme-bootstrap/commit/932c9a7))
* **window:** increase window actions padding ([0709998](https://github.com/telerik/kendo-theme-bootstrap/commit/0709998))
* **window:** reduce window action size ([e450346](https://github.com/telerik/kendo-theme-bootstrap/commit/e450346))
* use Listing D:\WORK\kendo-ui\kendo-theme-bootstrap\ New files added to this directory will not be compressed. ([ca44855](https://github.com/telerik/kendo-theme-bootstrap/commit/ca44855))
* **window:** remove box shadow ([2331805](https://github.com/telerik/kendo-theme-bootstrap/commit/2331805))
* switch appearance ([24bb58e](https://github.com/telerik/kendo-theme-bootstrap/commit/24bb58e))
* switch label alignment ([0233b20](https://github.com/telerik/kendo-theme-bootstrap/commit/0233b20))
* Switch to a variable from pixels for font-size of col sorting index text ([55d1140](https://github.com/telerik/kendo-theme-bootstrap/commit/55d1140))
* Switch to separate vars for alert vertical / horizontal padding ([8976522](https://github.com/telerik/kendo-theme-bootstrap/commit/8976522))
* unify design of dialog buttons and action buttons ([a8b8f21](https://github.com/telerik/kendo-theme-bootstrap/commit/a8b8f21))
* unify theme entrypoint name ([1e11ce0](https://github.com/telerik/kendo-theme-bootstrap/commit/1e11ce0))
* update dependencies on build ([c2f835f](https://github.com/telerik/kendo-theme-bootstrap/commit/c2f835f))
* update license ([#277](https://github.com/telerik/kendo-theme-bootstrap/issues/277)) ([f8a0fab](https://github.com/telerik/kendo-theme-bootstrap/commit/f8a0fab))
* update spacer-x / y variables ([9987287](https://github.com/telerik/kendo-theme-bootstrap/commit/9987287))
* update variables for themebuilder ([a7cafcc](https://github.com/telerik/kendo-theme-bootstrap/commit/a7cafcc))
* use ~ paths to reference node_modules ([7bfa24d](https://github.com/telerik/kendo-theme-bootstrap/commit/7bfa24d))
* use bootstrap component-* variables for theme base variables ([130b46f](https://github.com/telerik/kendo-theme-bootstrap/commit/130b46f))
* use box sizing for autocomplete ([0ccb3e8](https://github.com/telerik/kendo-theme-bootstrap/commit/0ccb3e8))
* use correct import path for media player ([fc7ef6f](https://github.com/telerik/kendo-theme-bootstrap/commit/fc7ef6f))
* use correct selectors for focused state ([fec9aae](https://github.com/telerik/kendo-theme-bootstrap/commit/fec9aae))
* use correct values for grid-padding and toolbar-padding ([3b1656a](https://github.com/telerik/kendo-theme-bootstrap/commit/3b1656a))
* use new contrast function ([6df8a35](https://github.com/telerik/kendo-theme-bootstrap/commit/6df8a35))
* use new contrast function ([c8936af](https://github.com/telerik/kendo-theme-bootstrap/commit/c8936af))
* use the correct box sizing for pager ([b939a69](https://github.com/telerik/kendo-theme-bootstrap/commit/b939a69))
* **window:** use correct border color for window ([23f90ff](https://github.com/telerik/kendo-theme-bootstrap/commit/23f90ff))
* use the correct box-sizing for colorpicker ([13233f1](https://github.com/telerik/kendo-theme-bootstrap/commit/13233f1))
* use the correct box-sizing for slider ([e572252](https://github.com/telerik/kendo-theme-bootstrap/commit/e572252))
* **window:** use opacity for window action buttons ([edc9733](https://github.com/telerik/kendo-theme-bootstrap/commit/edc9733))
* **window:** use scoped variables for window ([d56f591](https://github.com/telerik/kendo-theme-bootstrap/commit/d56f591))
* varibles are not properly set ([b3257c9](https://github.com/telerik/kendo-theme-bootstrap/commit/b3257c9))
* various editor fixes ([f16bfbe](https://github.com/telerik/kendo-theme-bootstrap/commit/f16bfbe))
* various fixes in navigation control ([f8ad8f7](https://github.com/telerik/kendo-theme-bootstrap/commit/f8ad8f7))


### Features

* add fill and outline utility mixins ([0e003c7](https://github.com/telerik/kendo-theme-bootstrap/commit/0e003c7))
* Add ListBox styles ([f372ac9](https://github.com/telerik/kendo-theme-bootstrap/commit/f372ac9))
* add media player ([f68e2f5](https://github.com/telerik/kendo-theme-bootstrap/commit/f68e2f5))
* add pivotgrid styles ([e777abf](https://github.com/telerik/kendo-theme-bootstrap/commit/e777abf))
* **button:** add styles for outline button ([b87efdc](https://github.com/telerik/kendo-theme-bootstrap/commit/b87efdc))
* add styles for dialog component ([9401341](https://github.com/telerik/kendo-theme-bootstrap/commit/9401341))
* add styles for gantt ([d463033](https://github.com/telerik/kendo-theme-bootstrap/commit/d463033))
* Add styles for inline Editor ([33f4422](https://github.com/telerik/kendo-theme-bootstrap/commit/33f4422))
* add styles for map ([f7ee367](https://github.com/telerik/kendo-theme-bootstrap/commit/f7ee367))
* add styles for spreadsheet closes [#47](https://github.com/telerik/kendo-theme-bootstrap/issues/47) ([8555777](https://github.com/telerik/kendo-theme-bootstrap/commit/8555777))
* add styling for forms ([#268](https://github.com/telerik/kendo-theme-bootstrap/issues/268)) ([5f65bfe](https://github.com/telerik/kendo-theme-bootstrap/commit/5f65bfe))
* add support for ng-chart colors ([1645717](https://github.com/telerik/kendo-theme-bootstrap/commit/1645717))
* embed dependencies during publish ([2b77ef9](https://github.com/telerik/kendo-theme-bootstrap/commit/2b77ef9))
* enable development channel ([0543ec3](https://github.com/telerik/kendo-theme-bootstrap/commit/0543ec3))
* extract dropdown wrap ([c51f240](https://github.com/telerik/kendo-theme-bootstrap/commit/c51f240))
* publish package with [@progress](https://github.com/progress) prefix ([5c7a061](https://github.com/telerik/kendo-theme-bootstrap/commit/5c7a061))
* remove 'base' mixin folder ([f230f4e](https://github.com/telerik/kendo-theme-bootstrap/commit/f230f4e))
* remove box-sizing override to better comply with 3rd party frameworks ([540e8d1](https://github.com/telerik/kendo-theme-bootstrap/commit/540e8d1))
* standartize folder structure ([e193234](https://github.com/telerik/kendo-theme-bootstrap/commit/e193234))
* styles for barcode and qrcode ([c852789](https://github.com/telerik/kendo-theme-bootstrap/commit/c852789))
* styles for scheduler ([a67afec](https://github.com/telerik/kendo-theme-bootstrap/commit/a67afec))
* styles for scrollview ([fdd5738](https://github.com/telerik/kendo-theme-bootstrap/commit/fdd5738))
* styles for table alignment and media player ([8d65e31](https://github.com/telerik/kendo-theme-bootstrap/commit/8d65e31))
* tie bootstrap dep to a specific commit (latest as of 2017/03/06) ([fd7c42e](https://github.com/telerik/kendo-theme-bootstrap/commit/fd7c42e))
* update bootstrap dependency to 4.0.0-beta ([#299](https://github.com/telerik/kendo-theme-bootstrap/issues/299)) ([2a99728](https://github.com/telerik/kendo-theme-bootstrap/commit/2a99728))
* **grid:** style grid filter button states ([543bbe9](https://github.com/telerik/kendo-theme-bootstrap/commit/543bbe9))
* update bootstrap dependency to v4.0.0 ([3f739c8](https://github.com/telerik/kendo-theme-bootstrap/commit/3f739c8))
* **badge:** add styles for badge telerik/kendo[#7846](https://github.com/telerik/kendo-theme-bootstrap/issues/7846) ([7cd13d2](https://github.com/telerik/kendo-theme-bootstrap/commit/7cd13d2))
* **button:** add styles for bare button ([ca29995](https://github.com/telerik/kendo-theme-bootstrap/commit/ca29995))
* **button:** add styles for flat button ([2b299b7](https://github.com/telerik/kendo-theme-bootstrap/commit/2b299b7))
* **button:** add styles for outline button ([ed1f492](https://github.com/telerik/kendo-theme-bootstrap/commit/ed1f492))
* **calendar:** implement design for kendo-angular ([73268ec](https://github.com/telerik/kendo-theme-bootstrap/commit/73268ec))
* **checkbox:** improve styles for checkboxes ([0afbdde](https://github.com/telerik/kendo-theme-bootstrap/commit/0afbdde))
* **DateInput:** Add invalid state styles ([627057c](https://github.com/telerik/kendo-theme-bootstrap/commit/627057c))
* **DatePicker:** Add DateInput invalid state ([81d3727](https://github.com/telerik/kendo-theme-bootstrap/commit/81d3727))
* **datetimepicker:** Add invalid state styles ([1a14bfa](https://github.com/telerik/kendo-theme-bootstrap/commit/1a14bfa))
* **edit-form:** add styles for edit form ([16a157c](https://github.com/telerik/kendo-theme-bootstrap/commit/16a157c))
* **grid:** Add styles for column sorting ([55abc0e](https://github.com/telerik/kendo-theme-bootstrap/commit/55abc0e))
* **Grid:** Add styles for Grid column sorting order ([85cdfb9](https://github.com/telerik/kendo-theme-bootstrap/commit/85cdfb9))
* **MaskedTextbox:** Add separate styles for MTB, invalid state (telerik/kendo[#6825](https://github.com/telerik/kendo-theme-bootstrap/issues/6825)) ([d1067b0](https://github.com/telerik/kendo-theme-bootstrap/commit/d1067b0))
* **numerictextbox:** add pressed state to increase/decrease arrows; align spinner icons ([47fa757](https://github.com/telerik/kendo-theme-bootstrap/commit/47fa757))
* **radiobutton:** improve styles for radio button ([1a6db60](https://github.com/telerik/kendo-theme-bootstrap/commit/1a6db60))
* **timepicker:** Add invalid state styles ([e22dd7f](https://github.com/telerik/kendo-theme-bootstrap/commit/e22dd7f))
* use mixins from [@telerik](https://github.com/telerik)/kendo-theme-default ([ed4c3d9](https://github.com/telerik/kendo-theme-bootstrap/commit/ed4c3d9))
* use pickerwrap for combo and dropdown ([85ed82d](https://github.com/telerik/kendo-theme-bootstrap/commit/85ed82d))


### BREAKING CHANGES

* Publish with @progress prefix




<a name="2.12.0-dev.c7ddd20b"></a>
# 2.12.0-dev.c7ddd20b (2018-01-30)


### Bug Fixes

* add bootstrap overrides and update variables ([0a81bc0](https://github.com/telerik/kendo-theme-bootstrap/commit/0a81bc0))
* add dependencies to bootstrap variables to all components ([912e821](https://github.com/telerik/kendo-theme-bootstrap/commit/912e821))
* add dirty collapse / expand icons. unifiy icon pseudo elements ([dd8fa00](https://github.com/telerik/kendo-theme-bootstrap/commit/dd8fa00))
* add global options variables for rounded corners, shadows, gradients and transitions ([7fbd9b1](https://github.com/telerik/kendo-theme-bootstrap/commit/7fbd9b1))
* add styles for missing chart components ([e07ec09](https://github.com/telerik/kendo-theme-bootstrap/commit/e07ec09))
* add styles for selected tabstrip pane ([32143f0](https://github.com/telerik/kendo-theme-bootstrap/commit/32143f0))
* allow package to work outside of webpack ([f330d67](https://github.com/telerik/kendo-theme-bootstrap/commit/f330d67))
* border and text decorations ([2c45e1f](https://github.com/telerik/kendo-theme-bootstrap/commit/2c45e1f))
* consolidate picker form controls ([3a01dc4](https://github.com/telerik/kendo-theme-bootstrap/commit/3a01dc4))
* correct classnames for seek icons ([0ce684a](https://github.com/telerik/kendo-theme-bootstrap/commit/0ce684a))
* correct main file name in NPM package ([c6feade](https://github.com/telerik/kendo-theme-bootstrap/commit/c6feade))
* correct path for editor import ([bb8954c](https://github.com/telerik/kendo-theme-bootstrap/commit/bb8954c))
* define all inherited variables when importing component files ([3e1e3a2](https://github.com/telerik/kendo-theme-bootstrap/commit/3e1e3a2))
* duplicate selectors in switch widget styles so kendo-ng-* can use them ([42b4f96](https://github.com/telerik/kendo-theme-bootstrap/commit/42b4f96))
* grid alt and selected state ([7052156](https://github.com/telerik/kendo-theme-bootstrap/commit/7052156))
* improve styles for days ([778f9ec](https://github.com/telerik/kendo-theme-bootstrap/commit/778f9ec))
* improve styles in switch for angular ([409fb25](https://github.com/telerik/kendo-theme-bootstrap/commit/409fb25))
* improve volume slider styles ([8a30252](https://github.com/telerik/kendo-theme-bootstrap/commit/8a30252))
* include color functions in the variables file ([07975f2](https://github.com/telerik/kendo-theme-bootstrap/commit/07975f2))
* inline Editor border width and select state ([aea000b](https://github.com/telerik/kendo-theme-bootstrap/commit/aea000b))
* make theme work with kendo-theme-default@2.x ([44e2ee5](https://github.com/telerik/kendo-theme-bootstrap/commit/44e2ee5))
* missing handle icon and background of splitbar in normal state ([6878f70](https://github.com/telerik/kendo-theme-bootstrap/commit/6878f70))
* **MaskedTextbox:** Fix invalid state border ([9d559cb](https://github.com/telerik/kendo-theme-bootstrap/commit/9d559cb))
* pager and dropdownlist appearance ([a33c910](https://github.com/telerik/kendo-theme-bootstrap/commit/a33c910))
* reduce toolbar padding ([56b4e30](https://github.com/telerik/kendo-theme-bootstrap/commit/56b4e30))
* remove extra borders of button groups and fix border color of selected button ([8930df8](https://github.com/telerik/kendo-theme-bootstrap/commit/8930df8))
* remove focus box-shadow from editors ([56386c4](https://github.com/telerik/kendo-theme-bootstrap/commit/56386c4))
* specify transition properties ([3224751](https://github.com/telerik/kendo-theme-bootstrap/commit/3224751)), closes [#198](https://github.com/telerik/kendo-theme-bootstrap/issues/198)
* splitter does not apply styles for hover state ([ccd3303](https://github.com/telerik/kendo-theme-bootstrap/commit/ccd3303))
* stop using css modules via common-tasks 2.0 ([04ef5ee](https://github.com/telerik/kendo-theme-bootstrap/commit/04ef5ee))
* **button:** improve outline button appearance ([a634d3e](https://github.com/telerik/kendo-theme-bootstrap/commit/a634d3e))
* **button:** use correct colors for primary button ([89d803d](https://github.com/telerik/kendo-theme-bootstrap/commit/89d803d))
* **buttonGroup:** fix no applying focus state to disabled button in button group telerik/kendo[#7846](https://github.com/telerik/kendo-theme-bootstrap/issues/7846) ([c64cbd7](https://github.com/telerik/kendo-theme-bootstrap/commit/c64cbd7))
* **calendar:** add styles for infinite calendar ([abee18c](https://github.com/telerik/kendo-theme-bootstrap/commit/abee18c))
* **calendar:** update calendar appearance in accordance to Bootstrap v4 beta-1 ([5779cd9](https://github.com/telerik/kendo-theme-bootstrap/commit/5779cd9))
* **chart:** grid lines colors ([#102](https://github.com/telerik/kendo-theme-bootstrap/issues/102)) ([7e2361d](https://github.com/telerik/kendo-theme-bootstrap/commit/7e2361d))
* **combobox:** rtl appearance ([9970562](https://github.com/telerik/kendo-theme-bootstrap/commit/9970562))
* **combobox:** wrong border colors of focused combobox ([3774304](https://github.com/telerik/kendo-theme-bootstrap/commit/3774304))
* **common:** improve header variables ([b0b54e6](https://github.com/telerik/kendo-theme-bootstrap/commit/b0b54e6))
* **common:** update dependency to Bootstrap v4 beta-2 ([0c50b53](https://github.com/telerik/kendo-theme-bootstrap/commit/0c50b53))
* **contextmenu:** update contextmenu appearance ([a416da7](https://github.com/telerik/kendo-theme-bootstrap/commit/a416da7))
* **dateinput:** border, hover and focus state ([08b753c](https://github.com/telerik/kendo-theme-bootstrap/commit/08b753c))
* **dateinputs:** apply consistent header styles ([c2b7d5f](https://github.com/telerik/kendo-theme-bootstrap/commit/c2b7d5f))
* **datetimepicker:** wrong focus state borders colors ([687c955](https://github.com/telerik/kendo-theme-bootstrap/commit/687c955))
* **dropdown:** add focus state to dropdown and popup ([9ce99ab](https://github.com/telerik/kendo-theme-bootstrap/commit/9ce99ab))
* **dropdownlist:** apply color to option label border ([ececc25](https://github.com/telerik/kendo-theme-bootstrap/commit/ececc25))
* **editors:** common layout glitches ([5b588d2](https://github.com/telerik/kendo-theme-bootstrap/commit/5b588d2))
* **forms:** align forms in dialog labels. ([61c881d](https://github.com/telerik/kendo-theme-bootstrap/commit/61c881d))
* **gantt:** improve milestone appearance ([df7c9a1](https://github.com/telerik/kendo-theme-bootstrap/commit/df7c9a1))
* **gantt:** make task resize handler wider and transparent ([af62568](https://github.com/telerik/kendo-theme-bootstrap/commit/af62568))
* **gantt:** reduce padding of toolbar-like elements in gantt ([fd945e2](https://github.com/telerik/kendo-theme-bootstrap/commit/fd945e2))
* **gantt:** view switcher is missing selected state ([2c19585](https://github.com/telerik/kendo-theme-bootstrap/commit/2c19585))
* **grid:** Add dirty cell indicator styling ([e75eca0](https://github.com/telerik/kendo-theme-bootstrap/commit/e75eca0))
* **grid:** Add missing locked footer border color ([e5caf33](https://github.com/telerik/kendo-theme-bootstrap/commit/e5caf33))
* **grid:** Add RTL styles for dirty cells ([266ebc7](https://github.com/telerik/kendo-theme-bootstrap/commit/266ebc7))
* **grid:** border color ([1923fff](https://github.com/telerik/kendo-theme-bootstrap/commit/1923fff))
* **grid:** Fix edit textbox width variable ([598e451](https://github.com/telerik/kendo-theme-bootstrap/commit/598e451))
* **grid:** improve grid row selected state ([1150dad](https://github.com/telerik/kendo-theme-bootstrap/commit/1150dad))
* **grid:** reduce padding of toolbar-like elements in grid ([cf25e3c](https://github.com/telerik/kendo-theme-bootstrap/commit/cf25e3c))
* **grid:** remove focus on header links ([96637a2](https://github.com/telerik/kendo-theme-bootstrap/commit/96637a2))
* **grid:** Remove selection column checkbox margin in RTL ([c671f29](https://github.com/telerik/kendo-theme-bootstrap/commit/c671f29))
* **grid:** scope selcted styles ([be070f9](https://github.com/telerik/kendo-theme-bootstrap/commit/be070f9))
* **grid:** Set fixed font-size of col sorting index to achieve alignment ([e8aef0b](https://github.com/telerik/kendo-theme-bootstrap/commit/e8aef0b))
* **grid:** Tweak multiple column sorting index position ([787d70e](https://github.com/telerik/kendo-theme-bootstrap/commit/787d70e))
* **grid:** use scoped grid variables ([7c12b76](https://github.com/telerik/kendo-theme-bootstrap/commit/7c12b76))
* **Grid:** Add cell focused state styles ([0c3fd96](https://github.com/telerik/kendo-theme-bootstrap/commit/0c3fd96))
* **Grid:** Add styles for verification tooltip ([c2b1f8a](https://github.com/telerik/kendo-theme-bootstrap/commit/c2b1f8a))
* **input:** Add styles for placeholder text ([9ea8b70](https://github.com/telerik/kendo-theme-bootstrap/commit/9ea8b70))
* **inputs:** wrong border color for invalid inputs ([c62ea18](https://github.com/telerik/kendo-theme-bootstrap/commit/c62ea18)), closes [telerik/kendo-theme-bootstrap#289](https://github.com/telerik/kendo-theme-bootstrap/issues/289)
* **listbox:** use correct variables for listbox ([f863af3](https://github.com/telerik/kendo-theme-bootstrap/commit/f863af3))
* **ListBox:** Improve button margins temporarily ([005ce87](https://github.com/telerik/kendo-theme-bootstrap/commit/005ce87))
* **listview:** add focused state ([b5d0c07](https://github.com/telerik/kendo-theme-bootstrap/commit/b5d0c07))
* **map:** Add marker color ([c958ace](https://github.com/telerik/kendo-theme-bootstrap/commit/c958ace))
* **map:** directions navigator is not properly customized in themebuilder ([502028d](https://github.com/telerik/kendo-theme-bootstrap/commit/502028d))
* **MaskedTextbox:** Add missing invalid state border ([2b9a72b](https://github.com/telerik/kendo-theme-bootstrap/commit/2b9a72b))
* **mediaplayer:** add opacity to toolbar ([d0aa7bc](https://github.com/telerik/kendo-theme-bootstrap/commit/d0aa7bc))
* **menu:** add styles for scrolling ([aa4a878](https://github.com/telerik/kendo-theme-bootstrap/commit/aa4a878))
* **multiselect:** border color ([d620f57](https://github.com/telerik/kendo-theme-bootstrap/commit/d620f57))
* **multiselect:** improve height of token with empty string telerik/kendo-ui-core[#372](https://github.com/telerik/kendo-theme-bootstrap/issues/372) ([a050374](https://github.com/telerik/kendo-theme-bootstrap/commit/a050374))
* **multiselect:** wrong items height ([a5c6116](https://github.com/telerik/kendo-theme-bootstrap/commit/a5c6116))
* **notification:** use panel styles for default type ([91ca341](https://github.com/telerik/kendo-theme-bootstrap/commit/91ca341))
* **notification:** use scoped variables for notification ([96b2c2c](https://github.com/telerik/kendo-theme-bootstrap/commit/96b2c2c))
* **numerictextbox:** spinners misalignment ([d89d006](https://github.com/telerik/kendo-theme-bootstrap/commit/d89d006))
* **pager:** add focus outline for pager buttons ([316ff9b](https://github.com/telerik/kendo-theme-bootstrap/commit/316ff9b))
* **pager:** focused state text decoration ([82fa821](https://github.com/telerik/kendo-theme-bootstrap/commit/82fa821))
* **pager:** improve disabled state of pager items ([18922d1](https://github.com/telerik/kendo-theme-bootstrap/commit/18922d1))
* **pager:** improve selected styles ([86b5726](https://github.com/telerik/kendo-theme-bootstrap/commit/86b5726))
* **pager:** use consistent header appearance ([a6ae6cd](https://github.com/telerik/kendo-theme-bootstrap/commit/a6ae6cd))
* **pager:** use relative units for button metrics ([#267](https://github.com/telerik/kendo-theme-bootstrap/issues/267)) ([bc5d7d3](https://github.com/telerik/kendo-theme-bootstrap/commit/bc5d7d3))
* **panelbar:** improve focus state ([54497f8](https://github.com/telerik/kendo-theme-bootstrap/commit/54497f8))
* **panelbar:** use correct border color for root items ([7dd7582](https://github.com/telerik/kendo-theme-bootstrap/commit/7dd7582))
* **pivotgrid:** apply header-bg to pivotgrid configurator ([381406a](https://github.com/telerik/kendo-theme-bootstrap/commit/381406a))
* **pivotgrid:** reduce padding of toolbar-like elements in pivotgrid ([8af6287](https://github.com/telerik/kendo-theme-bootstrap/commit/8af6287))
* **pivotgrid:** use correct color for pivotgrid toolbar border ([9f0fb06](https://github.com/telerik/kendo-theme-bootstrap/commit/9f0fb06))
* **Popup:** Remove the top and bottom padding of Popup when used as a column menu ([5b0ed95](https://github.com/telerik/kendo-theme-bootstrap/commit/5b0ed95))
* **progressbar:** add styles for indetermined progressbar ([e13a6c4](https://github.com/telerik/kendo-theme-bootstrap/commit/e13a6c4))
* **progressbar:** use correct variables for progressbar ([7bcdc0c](https://github.com/telerik/kendo-theme-bootstrap/commit/7bcdc0c))
* **ripple:** add default ripple styles ([19d1c09](https://github.com/telerik/kendo-theme-bootstrap/commit/19d1c09))
* **scheduler:** add bacground to event with no resources ([5fa6a29](https://github.com/telerik/kendo-theme-bootstrap/commit/5fa6a29))
* **scheduler:** view switcher is missing selected state ([9abcf35](https://github.com/telerik/kendo-theme-bootstrap/commit/9abcf35))
* **scrollview:** add styles for scrollview pager ([e79ecb8](https://github.com/telerik/kendo-theme-bootstrap/commit/e79ecb8))
* **slider:** add focus state to drag handle ([8208d0a](https://github.com/telerik/kendo-theme-bootstrap/commit/8208d0a))
* **slider:** add tick images ([80ed313](https://github.com/telerik/kendo-theme-bootstrap/commit/80ed313))
* **slider:** link slider variables to progressbar variables ([0ede195](https://github.com/telerik/kendo-theme-bootstrap/commit/0ede195))
* **slider:** remove browser outline on focus ([dc7fd03](https://github.com/telerik/kendo-theme-bootstrap/commit/dc7fd03))
* **splitter:** use correct colors for splitter ([2ff9472](https://github.com/telerik/kendo-theme-bootstrap/commit/2ff9472))
* **spreadsheet:** add styles for filter menu and filter button ([05ea173](https://github.com/telerik/kendo-theme-bootstrap/commit/05ea173))
* **spreadsheet:** improve spreadsheet active cell border by frozen cells telerik/kendo-ui-core[#3254](https://github.com/telerik/kendo-theme-bootstrap/issues/3254) ([0d838c3](https://github.com/telerik/kendo-theme-bootstrap/commit/0d838c3))
* **spreadsheet:** make drag handle to be visible in all cases telerik/kendo-ui-core[#3254](https://github.com/telerik/kendo-theme-bootstrap/issues/3254) ([4fdeafc](https://github.com/telerik/kendo-theme-bootstrap/commit/4fdeafc))
* **spreadsheet:** missing indicators for spreadsheet ([18ff11d](https://github.com/telerik/kendo-theme-bootstrap/commit/18ff11d))
* **spreadsheet:** styles for spreadsheet toolbar ([7e51ad7](https://github.com/telerik/kendo-theme-bootstrap/commit/7e51ad7))
* **switch:** border-color of switch is too dark ([1659185](https://github.com/telerik/kendo-theme-bootstrap/commit/1659185))
* wrong border color of input in scheduler advanced form ([eaf5e48](https://github.com/telerik/kendo-theme-bootstrap/commit/eaf5e48))
* **switch:** use correct border-radius for switch wrapper ([11f697e](https://github.com/telerik/kendo-theme-bootstrap/commit/11f697e))
* **tabstrip:** update variables to reflect changes in bootstrap ([fc60359](https://github.com/telerik/kendo-theme-bootstrap/commit/fc60359))
* **tabstrip:** use correct border-color when hovering / selecting tabs ([66709a7](https://github.com/telerik/kendo-theme-bootstrap/commit/66709a7))
* **timepicker:** improve popup appearance ([#348](https://github.com/telerik/kendo-theme-bootstrap/issues/348)) ([19e3965](https://github.com/telerik/kendo-theme-bootstrap/commit/19e3965))
* **tooltip:** tooltip cannot be customized in theme builder ([8e220c7](https://github.com/telerik/kendo-theme-bootstrap/commit/8e220c7))
* **tooltip:** use $font-size-sm ([c40001f](https://github.com/telerik/kendo-theme-bootstrap/commit/c40001f))
* **tooltip:** use alert-padding for close button ([2b130c7](https://github.com/telerik/kendo-theme-bootstrap/commit/2b130c7))
* **tooltip:** use contrast function to determine text color based on background ([6bc6c12](https://github.com/telerik/kendo-theme-bootstrap/commit/6bc6c12))
* **tooltip:** use correct padding for collapsible tooltip ([20ec0ad](https://github.com/telerik/kendo-theme-bootstrap/commit/20ec0ad))
* **tooltip:** use tooltip font-size variable ([53b2864](https://github.com/telerik/kendo-theme-bootstrap/commit/53b2864))
* **treeview:** add additional spacing around nodes so box shadow dont overlap ([260a216](https://github.com/telerik/kendo-theme-bootstrap/commit/260a216))
* **treeview:** add border radius to nodes ([184301c](https://github.com/telerik/kendo-theme-bootstrap/commit/184301c))
* **treeview:** focused and selected-focused state are clipped ([56e9445](https://github.com/telerik/kendo-theme-bootstrap/commit/56e9445))
* **treeview:** improve node colors ([9885066](https://github.com/telerik/kendo-theme-bootstrap/commit/9885066))
* **treeview:** reduce spacing between checkbox and item text ([b6426fc](https://github.com/telerik/kendo-theme-bootstrap/commit/b6426fc))
* **upload:** import theme styles from the default theme ([6e330aa](https://github.com/telerik/kendo-theme-bootstrap/commit/6e330aa))
* **window:** add spacing between buttons ([cbd9223](https://github.com/telerik/kendo-theme-bootstrap/commit/cbd9223))
* **window:** fix content bleeding outside of window boundaries ([932c9a7](https://github.com/telerik/kendo-theme-bootstrap/commit/932c9a7))
* **window:** increase window actions padding ([0709998](https://github.com/telerik/kendo-theme-bootstrap/commit/0709998))
* **window:** reduce window action size ([e450346](https://github.com/telerik/kendo-theme-bootstrap/commit/e450346))
* use Listing D:\WORK\kendo-ui\kendo-theme-bootstrap\ New files added to this directory will not be compressed. ([ca44855](https://github.com/telerik/kendo-theme-bootstrap/commit/ca44855))
* **window:** remove box shadow ([2331805](https://github.com/telerik/kendo-theme-bootstrap/commit/2331805))
* switch appearance ([24bb58e](https://github.com/telerik/kendo-theme-bootstrap/commit/24bb58e))
* switch label alignment ([0233b20](https://github.com/telerik/kendo-theme-bootstrap/commit/0233b20))
* Switch to a variable from pixels for font-size of col sorting index text ([55d1140](https://github.com/telerik/kendo-theme-bootstrap/commit/55d1140))
* Switch to separate vars for alert vertical / horizontal padding ([8976522](https://github.com/telerik/kendo-theme-bootstrap/commit/8976522))
* unify design of dialog buttons and action buttons ([a8b8f21](https://github.com/telerik/kendo-theme-bootstrap/commit/a8b8f21))
* unify theme entrypoint name ([1e11ce0](https://github.com/telerik/kendo-theme-bootstrap/commit/1e11ce0))
* update dependencies on build ([c2f835f](https://github.com/telerik/kendo-theme-bootstrap/commit/c2f835f))
* update license ([#277](https://github.com/telerik/kendo-theme-bootstrap/issues/277)) ([f8a0fab](https://github.com/telerik/kendo-theme-bootstrap/commit/f8a0fab))
* update spacer-x / y variables ([9987287](https://github.com/telerik/kendo-theme-bootstrap/commit/9987287))
* update variables for themebuilder ([a7cafcc](https://github.com/telerik/kendo-theme-bootstrap/commit/a7cafcc))
* use ~ paths to reference node_modules ([7bfa24d](https://github.com/telerik/kendo-theme-bootstrap/commit/7bfa24d))
* use bootstrap component-* variables for theme base variables ([130b46f](https://github.com/telerik/kendo-theme-bootstrap/commit/130b46f))
* use box sizing for autocomplete ([0ccb3e8](https://github.com/telerik/kendo-theme-bootstrap/commit/0ccb3e8))
* use correct import path for media player ([fc7ef6f](https://github.com/telerik/kendo-theme-bootstrap/commit/fc7ef6f))
* use correct selectors for focused state ([fec9aae](https://github.com/telerik/kendo-theme-bootstrap/commit/fec9aae))
* use correct values for grid-padding and toolbar-padding ([3b1656a](https://github.com/telerik/kendo-theme-bootstrap/commit/3b1656a))
* use new contrast function ([6df8a35](https://github.com/telerik/kendo-theme-bootstrap/commit/6df8a35))
* use new contrast function ([c8936af](https://github.com/telerik/kendo-theme-bootstrap/commit/c8936af))
* use the correct box sizing for pager ([b939a69](https://github.com/telerik/kendo-theme-bootstrap/commit/b939a69))
* **window:** use correct border color for window ([23f90ff](https://github.com/telerik/kendo-theme-bootstrap/commit/23f90ff))
* use the correct box-sizing for colorpicker ([13233f1](https://github.com/telerik/kendo-theme-bootstrap/commit/13233f1))
* use the correct box-sizing for slider ([e572252](https://github.com/telerik/kendo-theme-bootstrap/commit/e572252))
* **window:** use opacity for window action buttons ([edc9733](https://github.com/telerik/kendo-theme-bootstrap/commit/edc9733))
* **window:** use scoped variables for window ([d56f591](https://github.com/telerik/kendo-theme-bootstrap/commit/d56f591))
* varibles are not properly set ([b3257c9](https://github.com/telerik/kendo-theme-bootstrap/commit/b3257c9))
* various editor fixes ([f16bfbe](https://github.com/telerik/kendo-theme-bootstrap/commit/f16bfbe))
* various fixes in navigation control ([f8ad8f7](https://github.com/telerik/kendo-theme-bootstrap/commit/f8ad8f7))


### Features

* add fill and outline utility mixins ([0e003c7](https://github.com/telerik/kendo-theme-bootstrap/commit/0e003c7))
* Add ListBox styles ([f372ac9](https://github.com/telerik/kendo-theme-bootstrap/commit/f372ac9))
* add media player ([f68e2f5](https://github.com/telerik/kendo-theme-bootstrap/commit/f68e2f5))
* add pivotgrid styles ([e777abf](https://github.com/telerik/kendo-theme-bootstrap/commit/e777abf))
* **button:** add styles for outline button ([b87efdc](https://github.com/telerik/kendo-theme-bootstrap/commit/b87efdc))
* add styles for dialog component ([9401341](https://github.com/telerik/kendo-theme-bootstrap/commit/9401341))
* add styles for gantt ([d463033](https://github.com/telerik/kendo-theme-bootstrap/commit/d463033))
* Add styles for inline Editor ([33f4422](https://github.com/telerik/kendo-theme-bootstrap/commit/33f4422))
* add styles for map ([f7ee367](https://github.com/telerik/kendo-theme-bootstrap/commit/f7ee367))
* add styles for spreadsheet closes [#47](https://github.com/telerik/kendo-theme-bootstrap/issues/47) ([8555777](https://github.com/telerik/kendo-theme-bootstrap/commit/8555777))
* add styling for forms ([#268](https://github.com/telerik/kendo-theme-bootstrap/issues/268)) ([5f65bfe](https://github.com/telerik/kendo-theme-bootstrap/commit/5f65bfe))
* add support for ng-chart colors ([1645717](https://github.com/telerik/kendo-theme-bootstrap/commit/1645717))
* embed dependencies during publish ([2b77ef9](https://github.com/telerik/kendo-theme-bootstrap/commit/2b77ef9))
* enable development channel ([0543ec3](https://github.com/telerik/kendo-theme-bootstrap/commit/0543ec3))
* extract dropdown wrap ([c51f240](https://github.com/telerik/kendo-theme-bootstrap/commit/c51f240))
* publish package with [@progress](https://github.com/progress) prefix ([5c7a061](https://github.com/telerik/kendo-theme-bootstrap/commit/5c7a061))
* remove 'base' mixin folder ([f230f4e](https://github.com/telerik/kendo-theme-bootstrap/commit/f230f4e))
* remove box-sizing override to better comply with 3rd party frameworks ([540e8d1](https://github.com/telerik/kendo-theme-bootstrap/commit/540e8d1))
* standartize folder structure ([e193234](https://github.com/telerik/kendo-theme-bootstrap/commit/e193234))
* styles for barcode and qrcode ([c852789](https://github.com/telerik/kendo-theme-bootstrap/commit/c852789))
* styles for scheduler ([a67afec](https://github.com/telerik/kendo-theme-bootstrap/commit/a67afec))
* styles for scrollview ([fdd5738](https://github.com/telerik/kendo-theme-bootstrap/commit/fdd5738))
* styles for table alignment and media player ([8d65e31](https://github.com/telerik/kendo-theme-bootstrap/commit/8d65e31))
* tie bootstrap dep to a specific commit (latest as of 2017/03/06) ([fd7c42e](https://github.com/telerik/kendo-theme-bootstrap/commit/fd7c42e))
* update bootstrap dependency to 4.0.0-beta ([#299](https://github.com/telerik/kendo-theme-bootstrap/issues/299)) ([2a99728](https://github.com/telerik/kendo-theme-bootstrap/commit/2a99728))
* **grid:** style grid filter button states ([543bbe9](https://github.com/telerik/kendo-theme-bootstrap/commit/543bbe9))
* update bootstrap dependency to v4.0.0 ([3f739c8](https://github.com/telerik/kendo-theme-bootstrap/commit/3f739c8))
* **badge:** add styles for badge telerik/kendo[#7846](https://github.com/telerik/kendo-theme-bootstrap/issues/7846) ([7cd13d2](https://github.com/telerik/kendo-theme-bootstrap/commit/7cd13d2))
* **button:** add styles for bare button ([ca29995](https://github.com/telerik/kendo-theme-bootstrap/commit/ca29995))
* **button:** add styles for flat button ([2b299b7](https://github.com/telerik/kendo-theme-bootstrap/commit/2b299b7))
* **button:** add styles for outline button ([ed1f492](https://github.com/telerik/kendo-theme-bootstrap/commit/ed1f492))
* **calendar:** implement design for kendo-angular ([73268ec](https://github.com/telerik/kendo-theme-bootstrap/commit/73268ec))
* **checkbox:** improve styles for checkboxes ([0afbdde](https://github.com/telerik/kendo-theme-bootstrap/commit/0afbdde))
* **DateInput:** Add invalid state styles ([627057c](https://github.com/telerik/kendo-theme-bootstrap/commit/627057c))
* **DatePicker:** Add DateInput invalid state ([81d3727](https://github.com/telerik/kendo-theme-bootstrap/commit/81d3727))
* **datetimepicker:** Add invalid state styles ([1a14bfa](https://github.com/telerik/kendo-theme-bootstrap/commit/1a14bfa))
* **edit-form:** add styles for edit form ([16a157c](https://github.com/telerik/kendo-theme-bootstrap/commit/16a157c))
* **grid:** Add styles for column sorting ([55abc0e](https://github.com/telerik/kendo-theme-bootstrap/commit/55abc0e))
* **Grid:** Add styles for Grid column sorting order ([85cdfb9](https://github.com/telerik/kendo-theme-bootstrap/commit/85cdfb9))
* **MaskedTextbox:** Add separate styles for MTB, invalid state (telerik/kendo[#6825](https://github.com/telerik/kendo-theme-bootstrap/issues/6825)) ([d1067b0](https://github.com/telerik/kendo-theme-bootstrap/commit/d1067b0))
* **numerictextbox:** add pressed state to increase/decrease arrows; align spinner icons ([47fa757](https://github.com/telerik/kendo-theme-bootstrap/commit/47fa757))
* **radiobutton:** improve styles for radio button ([1a6db60](https://github.com/telerik/kendo-theme-bootstrap/commit/1a6db60))
* **timepicker:** Add invalid state styles ([e22dd7f](https://github.com/telerik/kendo-theme-bootstrap/commit/e22dd7f))
* use mixins from [@telerik](https://github.com/telerik)/kendo-theme-default ([ed4c3d9](https://github.com/telerik/kendo-theme-bootstrap/commit/ed4c3d9))
* use pickerwrap for combo and dropdown ([85ed82d](https://github.com/telerik/kendo-theme-bootstrap/commit/85ed82d))


### BREAKING CHANGES

* Publish with @progress prefix
