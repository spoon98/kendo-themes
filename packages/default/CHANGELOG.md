# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

<a name="4.2.0"></a>
# [4.2.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@4.1.0...@progress/kendo-theme-default@4.2.0) (2019-09-02)


### Bug Fixes

* **card:** update subtitle color to match design ([dbea6f6](https://github.com/telerik/kendo-themes/commit/dbea6f6))
* **grid:** use correct color for search input ([f454860](https://github.com/telerik/kendo-themes/commit/f454860))
* **scheduler:** add event top/bottom action styles ([dc8ea72](https://github.com/telerik/kendo-themes/commit/dc8ea72))
* **window:** button container in window should inherit border color ([74ec78e](https://github.com/telerik/kendo-themes/commit/74ec78e))


### Features

* **card:** add callout and update styles based on the design ([bf3bc1c](https://github.com/telerik/kendo-themes/commit/bf3bc1c))
* **colorpicker:** add clear button styles for angular colorpicker ([a108aa4](https://github.com/telerik/kendo-themes/commit/a108aa4))
* **filter:** widget styles ([2334e35](https://github.com/telerik/kendo-themes/commit/2334e35))
* **pdf-viewer:** add search dialog styles ([4e4742e](https://github.com/telerik/kendo-themes/commit/4e4742e))
* **pdf-viewer:** add text layer sass styles ([bcf3a3a](https://github.com/telerik/kendo-themes/commit/bcf3a3a))
* **scheduler:** implement scheduler flex rendering ([ea42eea](https://github.com/telerik/kendo-themes/commit/ea42eea))
* **timeline:** widget styles ([dbee03c](https://github.com/telerik/kendo-themes/commit/dbee03c))




<a name="4.1.0"></a>
# [4.1.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@4.0.0...@progress/kendo-theme-default@4.1.0) (2019-07-26)


### Bug Fixes

* **notification:** broken layout in IE ([e9e2d09](https://github.com/telerik/kendo-themes/commit/e9e2d09))
* add toolbar to treelist sticky headers ([1ca69f2](https://github.com/telerik/kendo-themes/commit/1ca69f2))
* improve sticky headers of treelist ([9db4dd4](https://github.com/telerik/kendo-themes/commit/9db4dd4))


### Features

* rating styles ([1104050](https://github.com/telerik/kendo-themes/commit/1104050))
* **colorpicker:** add comboview styles ([dd5705f](https://github.com/telerik/kendo-themes/commit/dd5705f))
* **tooltip:** add rtl styles ([13b9816](https://github.com/telerik/kendo-themes/commit/13b9816))




<a name="4.0.0"></a>
# [4.0.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@3.7.0...@progress/kendo-theme-default@4.0.0) (2019-07-08)


### Bug Fixes

* add !default flag to more variables ([5372039](https://github.com/telerik/kendo-themes/commit/5372039))
* background opacity of dialog in window ([ff03b04](https://github.com/telerik/kendo-themes/commit/ff03b04))
* **colorpicker:** styles in RTL view ([0741bc8](https://github.com/telerik/kendo-themes/commit/0741bc8))
* **grid:** no records template ([74c9a7d](https://github.com/telerik/kendo-themes/commit/74c9a7d))
* remove usages of add-two and add-three ([604a730](https://github.com/telerik/kendo-themes/commit/604a730))


### Features

* fit frozen group header text in one row ([17382fe](https://github.com/telerik/kendo-themes/commit/17382fe))
* modify themes for dart-sass ([d3e1c27](https://github.com/telerik/kendo-themes/commit/d3e1c27))
* **grid:** add styles for search bar within grid toolbar ([0460702](https://github.com/telerik/kendo-themes/commit/0460702))
* **slider:** remove unnecessary css properties from k-draghandle class ([9f04809](https://github.com/telerik/kendo-themes/commit/9f04809))


### BREAKING CHANGES

* remove add-two and add-three functions due to dart-sass compatibility issues
* Refactor themes so they can be compiled with dart-sass:

* create `.k-button-flat` selector for `@extend` use
* create `.k-button-overlay` selector for `@extend` use
* replace `@extend` usages of composite selectors `.k-button.k-flat` and `.k-button::before` with said selectors




<a name="3.7.0"></a>
# 3.7.0 (2019-06-12)


### Bug Fixes

* allow notification to be customized through custom class ([ac6ddc8](https://github.com/telerik/kendo-themes/commit/ac6ddc8))
* remove margin between buttons in button group ([ea1bf88](https://github.com/telerik/kendo-themes/commit/ea1bf88))
* **grid:** add no records template styles ([0c64ab0](https://github.com/telerik/kendo-themes/commit/0c64ab0))
* use gulp tasks in themes instead of lerna ([f5d5c0c](https://github.com/telerik/kendo-themes/commit/f5d5c0c))
* use shade() instead of blend-multiply() for themes ([41899bd](https://github.com/telerik/kendo-themes/commit/41899bd))
* **editor:** remove double toolbar border ([7fadbad](https://github.com/telerik/kendo-themes/commit/7fadbad))
* **grid:** adaptive renedering checkbox focused state ([12c2dbe](https://github.com/telerik/kendo-themes/commit/12c2dbe))
* **grid:** Cannot select text if the Grid is inside Splitter pane ([9924a53](https://github.com/telerik/kendo-themes/commit/9924a53))
* **grid:** column menu icons in rtl ([db87fd3](https://github.com/telerik/kendo-themes/commit/db87fd3))
* **notification:** improve alignment of text and icons in notification ([e629688](https://github.com/telerik/kendo-themes/commit/e629688))
* **responsivepanel:** passive event error thrown in chrome ([b4f904b](https://github.com/telerik/kendo-themes/commit/b4f904b))
* **switch:** width in cell in grid edit mode ([4a7cffe](https://github.com/telerik/kendo-themes/commit/4a7cffe))


### Features

* **drawer:** add scrolling styles supported in Mozilla ([07460ab](https://github.com/telerik/kendo-themes/commit/07460ab))
* **grid:** Accessibility improvements for adaptive rendering ([8e5ff21](https://github.com/telerik/kendo-themes/commit/8e5ff21))




<a name="3.6.1"></a>
## [3.6.1](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@3.6.0...@progress/kendo-theme-default@3.6.1) (2019-05-15)




**Note:** Version bump only for package @progress/kendo-theme-default

<a name="3.6.0"></a>
# 3.6.0 (2019-05-13)


### Bug Fixes

* angular editor content spacings and layout ([502d679](https://github.com/telerik/kendo-themes/commit/502d679))
* **colorpicker:** alpha slider bgr using embed assets script ([a300c78](https://github.com/telerik/kendo-themes/commit/a300c78))
* cursor of expand and collapse icons telerik/kendo-ui-core[#5021](https://github.com/telerik/kendo-themes/issues/5021) ([bee7a70](https://github.com/telerik/kendo-themes/commit/bee7a70))
* drawer overlay closed layout ([9b09fa1](https://github.com/telerik/kendo-themes/commit/9b09fa1))
* spacings of colorpicker when opening a popup ([5d617db](https://github.com/telerik/kendo-themes/commit/5d617db))
* style encapsulation does not work ([c7f828b](https://github.com/telerik/kendo-themes/commit/c7f828b))
* **colorpicker:** flex layout glitches when hiding dynamically content ([9711ef9](https://github.com/telerik/kendo-themes/commit/9711ef9))
* **colorpicker:** icon colorpicker hovered states styles ([59057aa](https://github.com/telerik/kendo-themes/commit/59057aa))
* **grid:** override adaptive edit form min-width ([f781dd8](https://github.com/telerik/kendo-themes/commit/f781dd8))
* **pdf-viewer:** pager buttons shadow is not visible ([ad5ac42](https://github.com/telerik/kendo-themes/commit/ad5ac42))
* **spreadsheet:** insufficient textarea height in insert comment dialog ([cff788a](https://github.com/telerik/kendo-themes/commit/cff788a))


### Features

* drawer styles ([76c7ea3](https://github.com/telerik/kendo-themes/commit/76c7ea3))
* **colorpicker:** add new colorpicker layout styles ([873d4c6](https://github.com/telerik/kendo-themes/commit/873d4c6))
* **editor:** add styles to for editor encapsulation ([95b3137](https://github.com/telerik/kendo-themes/commit/95b3137))
* **spreadsheet:** add images sass styles ([b369217](https://github.com/telerik/kendo-themes/commit/b369217))




<a name="3.5.1"></a>
## [3.5.1](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@3.5.0...@progress/kendo-theme-default@3.5.1) (2019-04-09)


### Bug Fixes

* **splitter:** flex splitter does not collapse under IE 11 ([67cd949](https://github.com/telerik/kendo-themes/commit/67cd949))
* **toolbar:** add styles for flexible spacer ([369fc6b](https://github.com/telerik/kendo-themes/commit/369fc6b))
* **toolbar:** wrong primary button appearance in Material ([21af366](https://github.com/telerik/kendo-themes/commit/21af366))




<a name="3.5.0"></a>
# [3.5.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@3.4.0...@progress/kendo-theme-default@3.5.0) (2019-04-08)


### Bug Fixes

* **buttons:** disabled focused buttons styles in mozilla ([961f592](https://github.com/telerik/kendo-themes/commit/961f592))
* **calendar:** improve empty cells size ([22c98fa](https://github.com/telerik/kendo-themes/commit/22c98fa))
* **grid:** column menu icon layout in IE ([ea182ea](https://github.com/telerik/kendo-themes/commit/ea182ea))
* **toolbar:** buttons in overflow menu in IE ([d193b84](https://github.com/telerik/kendo-themes/commit/d193b84))
* **treeview:** dragging icon position ([4e63478](https://github.com/telerik/kendo-themes/commit/4e63478))


### Features

* **calendar:** add styles for Blazor calendar ([8987d65](https://github.com/telerik/kendo-themes/commit/8987d65))
* **pager:** rendering changes and styles ([0a5642b](https://github.com/telerik/kendo-themes/commit/0a5642b))
* **validator:** layout changes ([add9c9c](https://github.com/telerik/kendo-themes/commit/add9c9c))




<a name="3.4.0"></a>
# 3.4.0 (2019-03-14)


### Bug Fixes

* **buttons:** use correct color for .k-button.k-flat:hover.k-state-active ([eebad66](https://github.com/telerik/kendo-themes/commit/eebad66))
* **calendar:** virtual list in ie ([0cdfd08](https://github.com/telerik/kendo-themes/commit/0cdfd08))
* **chat:** toolbar buttons styles ([cbfdf20](https://github.com/telerik/kendo-themes/commit/cbfdf20))
* **colorpalette:** apply cursor-pointer style on tiles ([7d4a7ca](https://github.com/telerik/kendo-themes/commit/7d4a7ca))
* **colorpicker:** wrapper hover styles not applied ([0f5ea5e](https://github.com/telerik/kendo-themes/commit/0f5ea5e))
* **dropdowns:** remove list items transform transitions ([71f3982](https://github.com/telerik/kendo-themes/commit/71f3982))
* **grid:** added active styles for grid column menu ([dfd1bc6](https://github.com/telerik/kendo-themes/commit/dfd1bc6))
* **grid:** grouping header text overflows with frozen columns ([779a216](https://github.com/telerik/kendo-themes/commit/779a216))
* **icons:** add missing icon aliases ([19f8906](https://github.com/telerik/kendo-themes/commit/19f8906))
* **scheduler:** agenda date header in RTL ([7079f86](https://github.com/telerik/kendo-themes/commit/7079f86))
* **scheduler:** fixed position of day toggle button in rtl ([0ca6dbf](https://github.com/telerik/kendo-themes/commit/0ca6dbf))
* **scheduler:** header wrap border ([86c7cf3](https://github.com/telerik/kendo-themes/commit/86c7cf3))
* **scheduler:** icon padding in RTL ([d0c8b09](https://github.com/telerik/kendo-themes/commit/d0c8b09))
* **scheduler:** month view style improvements ([e3dc082](https://github.com/telerik/kendo-themes/commit/e3dc082))
* **scheduler:** reverse event arrow direction in RTL ([e6aeefc](https://github.com/telerik/kendo-themes/commit/e6aeefc))
* upgrade theme dependency to bootstrap 4.3.1 ([eedd116](https://github.com/telerik/kendo-themes/commit/eedd116))
* **scheduler:** rtl layout improvements ([ab9030e](https://github.com/telerik/kendo-themes/commit/ab9030e))
* **switch:** layout in a k-form element ([7827870](https://github.com/telerik/kendo-themes/commit/7827870))
* **tabstrip:** bottom scrolling buttons alignment ([ecd39b6](https://github.com/telerik/kendo-themes/commit/ecd39b6))
* **tabstrip:** bottom scrolling buttons on IE ([7a51980](https://github.com/telerik/kendo-themes/commit/7a51980))
* **tabstrip:** scroll buttons rtl ([f5f2c9d](https://github.com/telerik/kendo-themes/commit/f5f2c9d))
* **toolbar:** added min-height ([452f4c0](https://github.com/telerik/kendo-themes/commit/452f4c0))


### Features

* add k-no-click class ([cf2cf0f](https://github.com/telerik/kendo-themes/commit/cf2cf0f))
* **daterange:** mobile support ([6452219](https://github.com/telerik/kendo-themes/commit/6452219)), closes [telerik/kendo-ui-core#4842](https://github.com/telerik/kendo-ui-core/issues/4842)




<a name="3.3.1"></a>
## [3.3.1](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@3.3.0...@progress/kendo-theme-default@3.3.1) (2019-02-19)


### Bug Fixes

* **gantt:** improve focused toolbar item styles ([1c2d77f](https://github.com/telerik/kendo-themes/commit/1c2d77f))
* **grid:** pdf export layout when pageSize is not set ([3c4a554](https://github.com/telerik/kendo-themes/commit/3c4a554))
* **menu:** context menu horizontal layout ([444c949](https://github.com/telerik/kendo-themes/commit/444c949))
* loading indicator was broken after refactoring ([09eb135](https://github.com/telerik/kendo-themes/commit/09eb135))
* **scheduler:** current time arrow ([75062ee](https://github.com/telerik/kendo-themes/commit/75062ee))
* **scheduler:** improve scheduler event styles ([a37e948](https://github.com/telerik/kendo-themes/commit/a37e948))
* **scheduler:** improved css selectors ([9f878d0](https://github.com/telerik/kendo-themes/commit/9f878d0))




<a name="3.3.0"></a>
# 3.3.0 (2019-02-14)


### Bug Fixes

* **dropdowns:** apply box-shadow only on first group header in angular ([e665b60](https://github.com/telerik/kendo-themes/commit/e665b60))
* **editor:** selected table cells styles ([3e9bc58](https://github.com/telerik/kendo-themes/commit/3e9bc58))
* **gantt:** toggle button is no longer visible on desktop in IE ([1bbd45e](https://github.com/telerik/kendo-themes/commit/1bbd45e))
* **grid:** column menu icon position in IE and Edge ([936c12d](https://github.com/telerik/kendo-themes/commit/936c12d))
* **grid:** footer misalignment when scroll is enabled ([2264ba1](https://github.com/telerik/kendo-themes/commit/2264ba1))
* **grid:** improve styles for column settings menu ([6f5ba27](https://github.com/telerik/kendo-themes/commit/6f5ba27))
* **input:** edge specific style for inputs in flex container ([2e80be3](https://github.com/telerik/kendo-themes/commit/2e80be3))
* **pivotgrid:** bottom border on collapsed items ([23e00f5](https://github.com/telerik/kendo-themes/commit/23e00f5))
* **scheduler:** cell box-sizing in IE ([21ce098](https://github.com/telerik/kendo-themes/commit/21ce098))
* **scheduler:** columns layout in material theme ([20b31c9](https://github.com/telerik/kendo-themes/commit/20b31c9))
* **scheduler:** drag hint time is not visible in angular ([395cf7d](https://github.com/telerik/kendo-themes/commit/395cf7d))
* **scheduler:** header items focus state styles ([7516d9c](https://github.com/telerik/kendo-themes/commit/7516d9c))
* **scheduler:** header text alignment when bootstrap is included ([102a152](https://github.com/telerik/kendo-themes/commit/102a152))
* **scheduler:** incorrect inverse color for event title [#168](https://github.com/telerik/kendo-themes/issues/168) ([b2b2a81](https://github.com/telerik/kendo-themes/commit/b2b2a81))
* **scheduler:** navigation focus state ([9e5b372](https://github.com/telerik/kendo-themes/commit/9e5b372))
* **spreadsheet:** filter menu sort icons ([f9d09ab](https://github.com/telerik/kendo-themes/commit/f9d09ab))
* **treemap:** display treemap title ([96b1896](https://github.com/telerik/kendo-themes/commit/96b1896))
* **validator:** styles for invalid widget wrappers ([6788d79](https://github.com/telerik/kendo-themes/commit/6788d79))
* disabled cell with link in Spreadsheet should navigate telerik/kendo-ui-core[#4824](https://github.com/telerik/kendo-themes/issues/4824) ([448a6a1](https://github.com/telerik/kendo-themes/commit/448a6a1))
* Refactor CSS to solve "Compound selectors may longer be extended." error when compiling ([47d1675](https://github.com/telerik/kendo-themes/commit/47d1675))


### Features

* add support for RTL of Kendo Angular Treeview ([#581](https://github.com/telerik/kendo-themes/issues/581)) ([71eb0ad](https://github.com/telerik/kendo-themes/commit/71eb0ad))
* **dropdowns:** add grouping for angular ([45b7601](https://github.com/telerik/kendo-themes/commit/45b7601))
* **treeview:** add RTL for Angular TreeView ([904bfb6](https://github.com/telerik/kendo-themes/commit/904bfb6))




<a name="3.2.0"></a>
# [3.2.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@3.1.0...@progress/kendo-theme-default@3.2.0) (2019-01-15)


### Bug Fixes

* **popup:** group header styles ([7032efe](https://github.com/telerik/kendo-themes/commit/7032efe))
* **scheduler:** angular edit form recurrence editor layout ([2a75cea](https://github.com/telerik/kendo-themes/commit/2a75cea))
* **scheduler:** angular multi day view missing pane border ([a86fa82](https://github.com/telerik/kendo-themes/commit/a86fa82))


### Features

* **datetimepicker:** add styles for kendo-react ([1aea521](https://github.com/telerik/kendo-themes/commit/1aea521))




<a name="3.1.0"></a>
# [3.1.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@3.0.0...@progress/kendo-theme-default@3.1.0) (2019-01-14)


### Bug Fixes

* **grid:** Filter icon overlap header's text [#207](https://github.com/telerik/kendo-themes/issues/207) ([44b825c](https://github.com/telerik/kendo-themes/commit/44b825c))
* **grid:** grouping header positioning ([43ea7e0](https://github.com/telerik/kendo-themes/commit/43ea7e0))
* **multiviewcalendar:** background of range cells in IE and Edge ([8bf20fa](https://github.com/telerik/kendo-themes/commit/8bf20fa))
* **pager:** hover bg color ([bda7b56](https://github.com/telerik/kendo-themes/commit/bda7b56))


### Features

* add prebuilt swatches to npm package ([5962540](https://github.com/telerik/kendo-themes/commit/5962540)), closes [#36](https://github.com/telerik/kendo-themes/issues/36)




<a name="3.0.0"></a>
# [3.0.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.63.0...@progress/kendo-theme-default@3.0.0) (2019-01-08)


### Features

* **switch:** improvements based on the latest design ([2a1dcec](https://github.com/telerik/kendo-themes/commit/2a1dcec))


### BREAKING CHANGES

* **switch:** Improve switch rendering and remove javascript animations




<a name="2.63.0"></a>
# 2.63.0 (2019-01-07)


### Bug Fixes

* **calendar:** disabled dates on weekend should look disabled ([ef7396f](https://github.com/telerik/kendo-themes/commit/ef7396f))
* **calendar:** remove material header buttons shadow ([1396eec](https://github.com/telerik/kendo-themes/commit/1396eec))
* **dialog:** improve button layouts ([37c988d](https://github.com/telerik/kendo-themes/commit/37c988d))
* **dialog:** there should be no spacing between streched buttons in rtl ([820b9e3](https://github.com/telerik/kendo-themes/commit/820b9e3))
* **dropdowngrid:** column width is not respected when virtualization is enabled ([cf1e90e](https://github.com/telerik/kendo-themes/commit/cf1e90e))
* **grid:** drag clue styles improvements [#252](https://github.com/telerik/kendo-themes/issues/252) ([780ff12](https://github.com/telerik/kendo-themes/commit/780ff12))
* improve clear icon position in dropdowns and pickers ([f83db0f](https://github.com/telerik/kendo-themes/commit/f83db0f))
* upload button has incorrect hover style in IE [#197](https://github.com/telerik/kendo-themes/issues/197) ([25fd603](https://github.com/telerik/kendo-themes/commit/25fd603))
* **grid:** filter menu buttons margin and borders ([471c5b2](https://github.com/telerik/kendo-themes/commit/471c5b2))
* **grid:** remove ellipsis from checkbox column in IE and Edge ([b3a5853](https://github.com/telerik/kendo-themes/commit/b3a5853))
* **material:** dates in century view calendar are not aligned ([44c2883](https://github.com/telerik/kendo-themes/commit/44c2883))
* **multiviewcalendar:** add styles for month headers ([a6b473a](https://github.com/telerik/kendo-themes/commit/a6b473a))
* **pager:** IE layout issues ([8684584](https://github.com/telerik/kendo-themes/commit/8684584))
* **scrollview:** trigger build ([a209ce2](https://github.com/telerik/kendo-themes/commit/a209ce2))


### Features

* add predefined widths for Window and Dialog ([18cab9c](https://github.com/telerik/kendo-themes/commit/18cab9c))
* responsive pager jQuery ([9baeefc](https://github.com/telerik/kendo-themes/commit/9baeefc))
* **daterangepicker:** add jQuery styles ([73eb665](https://github.com/telerik/kendo-themes/commit/73eb665))




<a name="2.62.0"></a>
# [2.62.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.61.0...@progress/kendo-theme-default@2.62.0) (2018-12-07)


### Bug Fixes

* **material:** improve grid, treelist and pivot appearance in dark themes ([95326fe](https://github.com/telerik/kendo-themes/commit/95326fe))
* **material:** improve window appearance in dark themes ([ad56d1e](https://github.com/telerik/kendo-themes/commit/ad56d1e))
* **pager:** expose and use pager variables ([a09f6f4](https://github.com/telerik/kendo-themes/commit/a09f6f4))
* **scheduler:** add styles for slot selection ([e69ac94](https://github.com/telerik/kendo-themes/commit/e69ac94)), closes [#247](https://github.com/telerik/kendo-themes/issues/247)
* **scrollview:** revert regression rendering changes ([398412c](https://github.com/telerik/kendo-themes/commit/398412c))


### Features

* **framework:** add functions to extract directional properties values ([ddfb798](https://github.com/telerik/kendo-themes/commit/ddfb798))




<a name="2.61.0"></a>
# [2.61.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.60.0...@progress/kendo-theme-default@2.61.0) (2018-11-22)


### Bug Fixes

* **button:** button not displayed correctly on IE on small window sizes ([e501671](https://github.com/telerik/kendo-themes/commit/e501671)), closes [#409](https://github.com/telerik/kendo-themes/issues/409)
* **calendar:** add styles for disabled today link [#373](https://github.com/telerik/kendo-themes/issues/373) ([da4db80](https://github.com/telerik/kendo-themes/commit/da4db80))
* **framework:** allow box-shadow to work with nullable arguments ([434f14e](https://github.com/telerik/kendo-themes/commit/434f14e))
* **grid:** grid with visual scrolling not rendered properly in RTL ([d68a1f6](https://github.com/telerik/kendo-themes/commit/d68a1f6))
* **grid:** non-scrollable grid command buttons margins ([43e18ba](https://github.com/telerik/kendo-themes/commit/43e18ba)), closes [#426](https://github.com/telerik/kendo-themes/issues/426)
* **grid:** prevent mobile user text selection on grid's header ([6373203](https://github.com/telerik/kendo-themes/commit/6373203))


### Features

* **grid:** add hover + selected rows styles ([7dde502](https://github.com/telerik/kendo-themes/commit/7dde502))




<a name="2.60.0"></a>
# [2.60.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.59.0...@progress/kendo-theme-default@2.60.0) (2018-11-09)


### Bug Fixes

* **grid:** grouping indicators overflowing ([a75dc9d](https://github.com/telerik/kendo-themes/commit/a75dc9d))
* **scheduler:** adaptive view switcher background ([41bdb94](https://github.com/telerik/kendo-themes/commit/41bdb94))
* **scheduler:** use :hover for buttons ([e296270](https://github.com/telerik/kendo-themes/commit/e296270))


### Features

* add kendo-theme-tasks ([61bda89](https://github.com/telerik/kendo-themes/commit/61bda89))
* **framework:** add try-tint and try-shade functions ([f6bf4b8](https://github.com/telerik/kendo-themes/commit/f6bf4b8))
* **framework:** improve appearance mixins to allow null values ([e3fe770](https://github.com/telerik/kendo-themes/commit/e3fe770))
* **scheduler:** add angular scheduler agenda view styles ([822115b](https://github.com/telerik/kendo-themes/commit/822115b))




<a name="2.59.0"></a>
# [2.59.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.58.0...@progress/kendo-theme-default@2.59.0) (2018-10-31)


### Bug Fixes

* add asp-fallback-test class for use with mvc ([558d47a](https://github.com/telerik/kendo-themes/commit/558d47a)), closes [#393](https://github.com/telerik/kendo-themes/issues/393)
* **scheduler:** buttongroup in edit dialog has wrong border color ([5b2c599](https://github.com/telerik/kendo-themes/commit/5b2c599))
* **scheduler:** double border on scroll in timeline views ([aec6dd6](https://github.com/telerik/kendo-themes/commit/aec6dd6))


### Features

* **multiviewcalendar:** add multiviewcalendar for kendo-jquery ([9761e30](https://github.com/telerik/kendo-themes/commit/9761e30))




<a name="2.58.0"></a>
# [2.58.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.57.1...@progress/kendo-theme-default@2.58.0) (2018-10-29)


### Bug Fixes

* **listbox:** add RTL styles ([05cf69f](https://github.com/telerik/kendo-themes/commit/05cf69f))
* **notification:** base-level rules for RTL throwing SASS compiler error ([becc197](https://github.com/telerik/kendo-themes/commit/becc197))
* promise is never resolved from npm run api ([054e6e1](https://github.com/telerik/kendo-themes/commit/054e6e1))
* **notification:** notification content does not wrap on small screens ([c34c958](https://github.com/telerik/kendo-themes/commit/c34c958))


### Features

* **scheduler:** add angular scheduler layout styles ([0cafb0e](https://github.com/telerik/kendo-themes/commit/0cafb0e))




<a name="2.57.1"></a>
## 2.57.1 (2018-10-16)


### Bug Fixes

* **dropdowns:** remove misleading cursor pointer on combobox border ([2877a87](https://github.com/telerik/kendo-themes/commit/2877a87)), closes [telerik/kendo-angular#1715](https://github.com/telerik/kendo-angular/issues/1715)
* **gantt:** displaced tasks in RTL ([5371a65](https://github.com/telerik/kendo-themes/commit/5371a65))
* **grid:** drag and drop clues improvements ([06c6dbe](https://github.com/telerik/kendo-themes/commit/06c6dbe))
* **grid:** remove extra spacing inside grid grouping row ([213af46](https://github.com/telerik/kendo-themes/commit/213af46))
* **inputs:** apply invalid state only trough class name instead of pseudo class ([4e0c8a2](https://github.com/telerik/kendo-themes/commit/4e0c8a2))
* **multiselect:** increase close button hit area ([520d731](https://github.com/telerik/kendo-themes/commit/520d731))
* **pager:** font-size and alignment corrections ([d44c8dd](https://github.com/telerik/kendo-themes/commit/d44c8dd))
* **pager:** improve spacing between link and page size ([ab00b4f](https://github.com/telerik/kendo-themes/commit/ab00b4f))
* **pager:** wrong RTL icons direction telerik/kendo-theme-default[#774](https://github.com/telerik/kendo-themes/issues/774) ([30ee750](https://github.com/telerik/kendo-themes/commit/30ee750))
* **popup:** group label in dropdowns is squashed ([f1a6ec6](https://github.com/telerik/kendo-themes/commit/f1a6ec6))
* **progressbar:** add rtl styles [#310](https://github.com/telerik/kendo-themes/issues/310) ([e944176](https://github.com/telerik/kendo-themes/commit/e944176))
* **progressbar:** Vertical ProgressBar status position ([b6339d8](https://github.com/telerik/kendo-themes/commit/b6339d8))
* switch from flex '1 1 0' to '1 1 auto' for ie 11 and edge ([ec6ada6](https://github.com/telerik/kendo-themes/commit/ec6ada6))
* **tabstrip:** extract tabstrip variables and use correct values ([699be9c](https://github.com/telerik/kendo-themes/commit/699be9c))
* **tabstrip:** ie11 squashes tabs ([bf05fa5](https://github.com/telerik/kendo-themes/commit/bf05fa5))
* **toolbar:** align splitbutton parts ([979e7b3](https://github.com/telerik/kendo-themes/commit/979e7b3))
* **toolbar:** templates items alignment ([804cbdf](https://github.com/telerik/kendo-themes/commit/804cbdf))




<a name="2.57.0"></a>
# [2.57.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.56.0...@progress/kendo-theme-default@2.57.0) (2018-10-01)


### Bug Fixes

* **grid:** Multi-column headers missing rtl border ([5efe3e8](https://github.com/telerik/kendo-themes/commit/5efe3e8))


### Features

* **notification:** add angular notification rtl styles ([126ccbe](https://github.com/telerik/kendo-themes/commit/126ccbe))




<a name="2.56.0"></a>
# 2.56.0 (2018-09-11)


### Bug Fixes

* **animations:** react animation position and display properties ([9541ba7](https://github.com/telerik/kendo-themes/commit/9541ba7))
* **colorpicker:** ensure input in colorpicker has correct background color ([60b10cd](https://github.com/telerik/kendo-themes/commit/60b10cd))
* improve form variables in accordance to material design ([dcb5a44](https://github.com/telerik/kendo-themes/commit/dcb5a44))
* **colorpicker:** update colorpicker layout to better match material theme ([6181275](https://github.com/telerik/kendo-themes/commit/6181275))
* **combobox:** incorrect styling when importing styles separately ([16da3d5](https://github.com/telerik/kendo-themes/commit/16da3d5))
* **editor:** remove pointer-events none from create table popup ([4457c6f](https://github.com/telerik/kendo-themes/commit/4457c6f))
* **focus:** grid, treelist, and calendar focus styles ([01eb3f6](https://github.com/telerik/kendo-themes/commit/01eb3f6))
* **multiselect:** incorrect styling when importing styles separately ([e5ea1ed](https://github.com/telerik/kendo-themes/commit/e5ea1ed))
* **notification:** angular closable notification spacing ([994a74c](https://github.com/telerik/kendo-themes/commit/994a74c))
* **tooltip:** incorrect styling when importing styles separately ([#304](https://github.com/telerik/kendo-themes/issues/304)) ([f78ff85](https://github.com/telerik/kendo-themes/commit/f78ff85))


### Features

* **spreadsheet:** add Material theme ([#275](https://github.com/telerik/kendo-themes/issues/275)) ([043d7ed](https://github.com/telerik/kendo-themes/commit/043d7ed))
* add Material theme for editor ([c4d6daa](https://github.com/telerik/kendo-themes/commit/c4d6daa))
* add Material theme for gantt ([f38a7ad](https://github.com/telerik/kendo-themes/commit/f38a7ad))
* add Material theme for scheduler ([2e0c352](https://github.com/telerik/kendo-themes/commit/2e0c352))
* add themes for dropdowngrid ([d4171f0](https://github.com/telerik/kendo-themes/commit/d4171f0))




<a name="2.55.0"></a>
# 2.55.0 (2018-08-22)


### Bug Fixes

* **buttons:** remove box-shadow of active outline buttons ([#238](https://github.com/telerik/kendo-themes/issues/238)) ([ff5708f](https://github.com/telerik/kendo-themes/commit/ff5708f)), closes [telerik/kendo-themes#237](https://github.com/telerik/kendo-themes/issues/237)
* **dateinput:** remove double shadow in datepicker ([9f37318](https://github.com/telerik/kendo-themes/commit/9f37318))
* **popup:** layout styles for bootstrap theme ([308d099](https://github.com/telerik/kendo-themes/commit/308d099))
* **progressbar:** use repeating gradient for indeterminate state ([d16368c](https://github.com/telerik/kendo-themes/commit/d16368c))
* **radiobuttons:** checked radio button is misaligned in RTL ([e53ec98](https://github.com/telerik/kendo-themes/commit/e53ec98))
* **tooltip:** Angular tooltip not having box shadow ([e56e2b4](https://github.com/telerik/kendo-themes/commit/e56e2b4))
* **tooltip:** content overflowing and not filling its space ([fe3cd28](https://github.com/telerik/kendo-themes/commit/fe3cd28))


### Features

* **icons:** allow icon font to be loaded from URL ([#250](https://github.com/telerik/kendo-themes/issues/250)) ([464cdcf](https://github.com/telerik/kendo-themes/commit/464cdcf))
* **progressbar:** add Progressbar for Material theme ([1de6d19](https://github.com/telerik/kendo-themes/commit/1de6d19))




<a name="2.54.1"></a>
## [2.54.1](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.54.0...@progress/kendo-theme-default@2.54.1) (2018-07-24)


### Bug Fixes

* **chat:** selected card shadow is trimmed on OSX ([#215](https://github.com/telerik/kendo-themes/issues/215)) ([fc38a6c](https://github.com/telerik/kendo-themes/commit/fc38a6c))
* **dialog:** dialog title cuts off letters ([1192d16](https://github.com/telerik/kendo-themes/commit/1192d16)), closes [telerik/kendo-theme-default#871](https://github.com/telerik/kendo-theme-default/issues/871)
* **spreadsheet:** improve rendering of selected cell ([94d5dd0](https://github.com/telerik/kendo-themes/commit/94d5dd0))
* improve performance in IE11 ([6ce81f1](https://github.com/telerik/kendo-themes/commit/6ce81f1)), closes [telerik/kendo-themes#227](https://github.com/telerik/kendo-themes/issues/227)




<a name="2.54.0"></a>
# [2.54.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.53.2...@progress/kendo-theme-default@2.54.0) (2018-06-18)


### Bug Fixes

* **calendar:** error when compiling standalone calendar ([67aa44a](https://github.com/telerik/kendo-themes/commit/67aa44a))
* **menu:** overflowing items do not wrap ([#206](https://github.com/telerik/kendo-themes/issues/206)) ([9944676](https://github.com/telerik/kendo-themes/commit/9944676))
* **pivotgrid:** pivotgrid stretches beyond container in ie 11 ([d7d052b](https://github.com/telerik/kendo-themes/commit/d7d052b))
* **tooltip:** align closable tooltip icon button ([69f2d09](https://github.com/telerik/kendo-themes/commit/69f2d09))
* **tooltip:** move styles for transparent tooltip to layout ([1b150be](https://github.com/telerik/kendo-themes/commit/1b150be))


### Features

* **tooltip:** add tooltip title styles ([23be01a](https://github.com/telerik/kendo-themes/commit/23be01a))




<a name="2.53.2"></a>
## [2.53.2](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.53.1...@progress/kendo-theme-default@2.53.2) (2018-05-23)


### Bug Fixes

* **autocomplete:** wrong indent in Angular RTL ([a2d05e3](https://github.com/telerik/kendo-themes/commit/a2d05e3))
* **card:** add card states ([0dbf579](https://github.com/telerik/kendo-themes/commit/0dbf579))
* **chat:** allow content size detection with ResizeObserver ([a9937ba](https://github.com/telerik/kendo-themes/commit/a9937ba))
* **chat:** card decks expand beyond the chat container size ([a885344](https://github.com/telerik/kendo-themes/commit/a885344))
* **chat:** smooth scroll for card deck ([ba708bd](https://github.com/telerik/kendo-themes/commit/ba708bd))
* **notification:** add Material styles, improve close icon positioning ([5340230](https://github.com/telerik/kendo-themes/commit/5340230))
* **toolbar:** button group in overflow popup is unstyled ([#179](https://github.com/telerik/kendo-themes/issues/179)) ([29e15f2](https://github.com/telerik/kendo-themes/commit/29e15f2))
* **toolbar:** hover background on disabled button in button group ([88854c3](https://github.com/telerik/kendo-themes/commit/88854c3)), closes [telerik/kendo-themes#142](https://github.com/telerik/kendo-themes/issues/142)




<a name="2.53.1"></a>
## [2.53.1](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.53.0...@progress/kendo-theme-default@2.53.1) (2018-05-16)


### Bug Fixes

* **chat:** scrollable deck is hidden by other messages ([#185](https://github.com/telerik/kendo-themes/issues/185)) ([e5cf671](https://github.com/telerik/kendo-themes/commit/e5cf671))
* **tooltip:** component is larger than specified size ([#187](https://github.com/telerik/kendo-themes/issues/187)) ([8f52bf0](https://github.com/telerik/kendo-themes/commit/8f52bf0))




<a name="2.53.0"></a>
# [2.53.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.52.2...@progress/kendo-theme-default@2.53.0) (2018-05-15)


### Bug Fixes

* **chat:** bad alignment when avatar is not set ([ea1c5b9](https://github.com/telerik/kendo-themes/commit/ea1c5b9))
* **chat:** improve card deck spacing ([dcaa2c8](https://github.com/telerik/kendo-themes/commit/dcaa2c8))
* **chat:** improve RTL send icon alignment ([3899d92](https://github.com/telerik/kendo-themes/commit/3899d92))
* **chat:** prevent overflowing messages with long text ([77503ea](https://github.com/telerik/kendo-themes/commit/77503ea))
* **checkbox:** align text on the left in RTL ([b7b6fcf](https://github.com/telerik/kendo-themes/commit/b7b6fcf))
* **grid:** localized filter menu buttons do not expand ([28b8fe6](https://github.com/telerik/kendo-themes/commit/28b8fe6))
* build error with enable-rounded:false ([fd62e47](https://github.com/telerik/kendo-themes/commit/fd62e47))


### Features

* **cards:** deck scroll buttons ([#177](https://github.com/telerik/kendo-themes/issues/177)) ([52e52c3](https://github.com/telerik/kendo-themes/commit/52e52c3))




<a name="2.52.2"></a>
## [2.52.2](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.52.1...@progress/kendo-theme-default@2.52.2) (2018-05-10)


### Bug Fixes

* **fonts:** remove registration of DejaVu font ([2a566d3](https://github.com/telerik/kendo-themes/commit/2a566d3))
* **popup:** remove border of nested component ([8b4bf84](https://github.com/telerik/kendo-themes/commit/8b4bf84))
* **window:** resizing window to be larger than viewport triggers dragging ([7dc4da7](https://github.com/telerik/kendo-themes/commit/7dc4da7)), closes [/github.com/telerik/kendo-angular/issues/1508#issuecomment-386209573](https://github.com//github.com/telerik/kendo-angular/issues/1508/issues/issuecomment-386209573)
* allow font-size to be set to rem units ([e320c59](https://github.com/telerik/kendo-themes/commit/e320c59)), closes [#169](https://github.com/telerik/kendo-themes/issues/169)




<a name="2.52.1"></a>
## [2.52.1](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.52.0...@progress/kendo-theme-default@2.52.1) (2018-05-09)


### Bug Fixes

* **grid:** add min-width to prevent column menu reflow ([41195eb](https://github.com/telerik/kendo-themes/commit/41195eb))
* **grid:** remove double-borders on multi-column headers ([83cb60b](https://github.com/telerik/kendo-themes/commit/83cb60b))
* **multiselect:** clear icon is not visible on focus ([d33a8a8](https://github.com/telerik/kendo-themes/commit/d33a8a8))
* **treelist:** align columnmenu icon ([b225d2d](https://github.com/telerik/kendo-themes/commit/b225d2d))




<a name="2.52.0"></a>
# 2.52.0 (2018-05-07)


### Bug Fixes

* add card-list layout ([d2ce25b](https://github.com/telerik/kendo-themes/commit/d2ce25b))
* **calendar:** layout is broken inside k-form ([017accd](https://github.com/telerik/kendo-themes/commit/017accd))
* **dropdowntree:** improve spacing of 'Check All' ([784e742](https://github.com/telerik/kendo-themes/commit/784e742))
* **grid:** details row in RTL grid has extra borders ([0a199bb](https://github.com/telerik/kendo-themes/commit/0a199bb))
* **grid:** filter menu icon is misaligned with multicolumn headers ([6e998a4](https://github.com/telerik/kendo-themes/commit/6e998a4))
* **grid:** filter row has no top border ([abedf81](https://github.com/telerik/kendo-themes/commit/abedf81))
* **splitter:** collapsed panes are not hidden in IE10 ([d463f5f](https://github.com/telerik/kendo-themes/commit/d463f5f))
* **timepicker:** separators take no space ([43c5296](https://github.com/telerik/kendo-themes/commit/43c5296))


### Features

* add TabStrip styling ([a93d7cc](https://github.com/telerik/kendo-themes/commit/a93d7cc))
* **grid:** add Angular column menu styling ([38d9486](https://github.com/telerik/kendo-themes/commit/38d9486))




<a name="2.51.0"></a>
# 2.51.0 (2018-04-27)


### Bug Fixes

* **grid:** filter row borders are missing in RTL ([f939f8e](https://github.com/telerik/kendo-themes/commit/f939f8e))
* **grid:** improve grouping header layout in Angular ([1df42eb](https://github.com/telerik/kendo-themes/commit/1df42eb))
* do not apply color to all -wrap elements inside containers ([61843f9](https://github.com/telerik/kendo-themes/commit/61843f9))
* **grid:** improve spacing of boolean filter row ([709d4c2](https://github.com/telerik/kendo-themes/commit/709d4c2))
* **numerictextbox:** stretch buttons with input height ([8c0e8c6](https://github.com/telerik/kendo-themes/commit/8c0e8c6))


### Features

* **calendar:** add range selection styles ([6c8abf7](https://github.com/telerik/kendo-themes/commit/6c8abf7))
* add styles for chat widget ([#146](https://github.com/telerik/kendo-themes/issues/146)) ([5729aec](https://github.com/telerik/kendo-themes/commit/5729aec))
* add styles for Material Upload ([0a183f4](https://github.com/telerik/kendo-themes/commit/0a183f4))
* switch styles for material theme ([277ca4f](https://github.com/telerik/kendo-themes/commit/277ca4f))




<a name="2.50.0"></a>
# 2.50.0 (2018-04-11)


### Bug Fixes

* **dateinput:** improve spinner layout to match numeric ([d8d0842](https://github.com/telerik/kendo-themes/commit/d8d0842))
* **grid:** add styles for loading overlay ([4c0b5dd](https://github.com/telerik/kendo-themes/commit/4c0b5dd))
* **grid:** empty space after virtual content (Angular) ([c8b32b6](https://github.com/telerik/kendo-themes/commit/c8b32b6))
* **listview:** Improve focused and selected state appearance of listview in accordance with design ([4225503](https://github.com/telerik/kendo-themes/commit/4225503))
* **menu:** add angular menu styles ([5b44672](https://github.com/telerik/kendo-themes/commit/5b44672))
* **menu:** improve icon positioning ([4518725](https://github.com/telerik/kendo-themes/commit/4518725))
* **tooltip:** improve close button position ([aab93ae](https://github.com/telerik/kendo-themes/commit/aab93ae))


### Features

* **listbox:** Implement Material skin for ListBox ([1341e86](https://github.com/telerik/kendo-themes/commit/1341e86))




<a name="2.49.1"></a>
## [2.49.1](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.49.0...@progress/kendo-theme-default@2.49.1) (2018-03-26)


### Bug Fixes

* **button:** improve Material styles ([f001c10](https://github.com/telerik/kendo-themes/commit/f001c10))
* **button:** improve styles for flat and bare look ([e2e8b7a](https://github.com/telerik/kendo-themes/commit/e2e8b7a))
* **datetimepicker:** remove button borders in Material ([#81](https://github.com/telerik/kendo-themes/issues/81)) ([c50325a](https://github.com/telerik/kendo-themes/commit/c50325a))
* **grid:** ensure filter popup width in IE ([#75](https://github.com/telerik/kendo-themes/issues/75)) ([7095e66](https://github.com/telerik/kendo-themes/commit/7095e66))
* **grid:** misaligned borders after resizing browser (IE) ([#77](https://github.com/telerik/kendo-themes/issues/77)) ([8422a14](https://github.com/telerik/kendo-themes/commit/8422a14))
* **multiselect:** style custom item ([#69](https://github.com/telerik/kendo-themes/issues/69)) ([d706e69](https://github.com/telerik/kendo-themes/commit/d706e69)), closes [telerik/kendo-theme-default#53](https://github.com/telerik/kendo-theme-default/issues/53)
* **tooltip:** add styles for Angular ([#59](https://github.com/telerik/kendo-themes/issues/59)) ([d1afde4](https://github.com/telerik/kendo-themes/commit/d1afde4))
* move mixin outside control structure ([053ca5f](https://github.com/telerik/kendo-themes/commit/053ca5f))




<a name="2.49.0"></a>
# [2.49.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.48.1...@progress/kendo-theme-default@2.49.0) (2018-03-12)


### Bug Fixes

* **grid:** explicitly declare box sizing to non-locked Grid content ([17bfd17](https://github.com/telerik/kendo-themes/commit/17bfd17))
* **grid:** filter row has double border ([#52](https://github.com/telerik/kendo-themes/issues/52)) ([79d4f0d](https://github.com/telerik/kendo-themes/commit/79d4f0d))
* **grid:** improve layout calculation in hidden containers ([8857e56](https://github.com/telerik/kendo-themes/commit/8857e56))
* **grid:** locked column data is hidden in iOS ([b9aafec](https://github.com/telerik/kendo-themes/commit/b9aafec))
* **icons:** symbols shown in exported PDF ([017584b](https://github.com/telerik/kendo-themes/commit/017584b))
* **pdf-export:** register DejaVu fonts ([795307c](https://github.com/telerik/kendo-themes/commit/795307c))
* **scrollview:** allow interaction in templates ([370d720](https://github.com/telerik/kendo-themes/commit/370d720)), closes [#32](https://github.com/telerik/kendo-themes/issues/32) [telerik/kendo-angular#493](https://github.com/telerik/kendo-angular/issues/493) [telerik/kendo-angular#1311](https://github.com/telerik/kendo-angular/issues/1311)
* add compatibility with node-sass 4.8 ([5192b38](https://github.com/telerik/kendo-themes/commit/5192b38))


### Features

* add floating label for material textarea ([#9](https://github.com/telerik/kendo-themes/issues/9)) ([b059e30](https://github.com/telerik/kendo-themes/commit/b059e30))
* **dropdowns:** add Material theme for dropdowns and inputs ([618c73d](https://github.com/telerik/kendo-themes/commit/618c73d)), closes [#40](https://github.com/telerik/kendo-themes/issues/40) [#43](https://github.com/telerik/kendo-themes/issues/43) [#44](https://github.com/telerik/kendo-themes/issues/44) [#45](https://github.com/telerik/kendo-themes/issues/45)




<a name="2.48.1"></a>
## [2.48.1](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.48.0...@progress/kendo-theme-default@2.48.1) (2018-02-20)


### Bug Fixes

* **grid:** fix misaligned locked columns header in IE ([a14a49a](https://github.com/telerik/kendo-themes/commit/a14a49a))




<a name="2.48.0"></a>
# [2.48.0](https://github.com/telerik/kendo-themes/compare/@progress/kendo-theme-default@2.47.8...@progress/kendo-theme-default@2.48.0) (2018-02-16)


### Bug Fixes

* **dialog:** fix close button position in titleless dialog telerik/kendo-ui-core[#3603](https://github.com/telerik/kendo-themes/issues/3603) ([6686860](https://github.com/telerik/kendo-themes/commit/6686860))
* **dialog:** improve close button alignment telerik/kendo[#8156](https://github.com/telerik/kendo-themes/issues/8156) ([35ebde2](https://github.com/telerik/kendo-themes/commit/35ebde2))
* **dialog:** improve dialog buttons overflow telerik/kendo[#7497](https://github.com/telerik/kendo-themes/issues/7497) ([a481460](https://github.com/telerik/kendo-themes/commit/a481460))
* **editor:** add styles for editor table telerik/kendo[#8213](https://github.com/telerik/kendo-themes/issues/8213) ([5cec16a](https://github.com/telerik/kendo-themes/commit/5cec16a))
* **editor:** hide toolbar buttons groups with all items disabled telerik/kendo[#8212](https://github.com/telerik/kendo-themes/issues/8212) ([5d37cc4](https://github.com/telerik/kendo-themes/commit/5d37cc4))
* **editor:** prevent hiding and flickering icon in inline editor [#8211](https://github.com/telerik/kendo-themes/issues/8211) ([c5fa45a](https://github.com/telerik/kendo-themes/commit/c5fa45a))
* **splitter:** prevent pane overlay from overlaying splitbars ([231e329](https://github.com/telerik/kendo-themes/commit/231e329))
* **spreadsheet:** improve edit buttons position for rtl telerik/kendo[#7476](https://github.com/telerik/kendo-themes/issues/7476) ([3739523](https://github.com/telerik/kendo-themes/commit/3739523))


### Features

* add pager styles for material ([#10](https://github.com/telerik/kendo-themes/issues/10)) ([12e13f4](https://github.com/telerik/kendo-themes/commit/12e13f4))




<a name="2.47.8"></a>
## [2.47.8](https://github.com/telerik/kendo-theme-default/compare/@progress/kendo-theme-default@2.47.7...@progress/kendo-theme-default@2.47.8) (2018-02-13)


### Bug Fixes

* **calendar:** weekdays are not rendered in Edge ([6914a61](https://github.com/telerik/kendo-theme-default/commit/6914a61)), closes [telerik/kendo-themes#5](https://github.com/telerik/kendo-themes/issues/5)
* **splitter:** allow pane children to use 100% height (Angular) ([5720b52](https://github.com/telerik/kendo-theme-default/commit/5720b52))
* bootstrap 4 input groups styling ([0fcc32f](https://github.com/telerik/kendo-theme-default/commit/0fcc32f))




<a name="2.47.7"></a>
## [2.47.7](https://github.com/telerik/kendo-theme-default/compare/@progress/kendo-theme-default@2.47.6...@progress/kendo-theme-default@2.47.7) (2018-02-06)


### Bug Fixes

* **charts:** chart tooltip is hidden behind dialog ([7dd0b16](https://github.com/telerik/kendo-theme-default/commit/7dd0b16))




<a name="2.47.6"></a>
## [2.47.6](https://github.com/telerik/kendo-theme-default/compare/@progress/kendo-theme-default@2.47.5...@progress/kendo-theme-default@2.47.6) (2018-02-06)


### Bug Fixes

* **grid:** rule breaks grunt builds of theme ([a47312f](https://github.com/telerik/kendo-theme-default/commit/a47312f)), closes [#1](https://github.com/telerik/kendo-theme-default/issues/1)




<a name="2.47.5"></a>
## [2.47.5](https://github.com/telerik/kendo-theme-default/compare/@progress/kendo-theme-default@2.47.4...@progress/kendo-theme-default@2.47.5) (2018-02-06)


### Bug Fixes

* **splitter:** allow overriding of component colors ([65facaa](https://github.com/telerik/kendo-theme-default/commit/65facaa))
* **treeview:** allow horizontal scroll of node text ([f67f414](https://github.com/telerik/kendo-theme-default/commit/f67f414))




<a name="2.48.0"></a>
# 2.48.0 (2018-01-30)


### Bug Fixes

* .k-select should be square for default theme ([dc41e43](https://github.com/telerik/kendo-theme-default/commit/dc41e43))
* add animation between different positions of chart tooltip. ([17c845b](https://github.com/telerik/kendo-theme-default/commit/17c845b)), closes [telerik/kendo-theme-default#163](https://github.com/telerik/kendo-theme-default/issues/163)
* add button borders ([7421746](https://github.com/telerik/kendo-theme-default/commit/7421746))
* add buttons package and d.ts file ([#16](https://github.com/telerik/kendo-theme-default/issues/16)) ([d0eef84](https://github.com/telerik/kendo-theme-default/commit/d0eef84))
* add calendar border, align icons ([abdb96e](https://github.com/telerik/kendo-theme-default/commit/abdb96e))
* add contrast function based on WCAG requirements ([8755a4e](https://github.com/telerik/kendo-theme-default/commit/8755a4e))
* add d.ts file for layout package ([d448f9a](https://github.com/telerik/kendo-theme-default/commit/d448f9a))
* add d.ts for TypeScript to stop complaining ([1918bc7](https://github.com/telerik/kendo-theme-default/commit/1918bc7))
* add dialog package scripts ([2747802](https://github.com/telerik/kendo-theme-default/commit/2747802))
* add dialog styles to 'all' package ([77e9f4f](https://github.com/telerik/kendo-theme-default/commit/77e9f4f))
* add dropdowns package and d.ts file ([#17](https://github.com/telerik/kendo-theme-default/issues/17)) ([7f08e08](https://github.com/telerik/kendo-theme-default/commit/7f08e08))
* add expand/collapse icons to panelbar ([90dce13](https://github.com/telerik/kendo-theme-default/commit/90dce13))
* add focused styling for the Grid. ([a7389a3](https://github.com/telerik/kendo-theme-default/commit/a7389a3)), closes [telerik/kendo-theme-default#178](https://github.com/telerik/kendo-theme-default/issues/178)
* add functional map and scroller styles ([1abee64](https://github.com/telerik/kendo-theme-default/commit/1abee64))
* add grid to complete package ([2d781f9](https://github.com/telerik/kendo-theme-default/commit/2d781f9))
* add hover styling to the upload dropzone ([#51](https://github.com/telerik/kendo-theme-default/issues/51)) ([b9c8c78](https://github.com/telerik/kendo-theme-default/commit/b9c8c78))
* add k-display-block for chromeless components ([a05ef96](https://github.com/telerik/kendo-theme-default/commit/a05ef96))
* add k-i-add class for backwards compat ([89a26f6](https://github.com/telerik/kendo-theme-default/commit/89a26f6))
* add k-rtl style ([850c713](https://github.com/telerik/kendo-theme-default/commit/850c713))
* add loading animation styles ([426ceac](https://github.com/telerik/kendo-theme-default/commit/426ceac))
* add mixin for striped gradient ([a5f695a](https://github.com/telerik/kendo-theme-default/commit/a5f695a))
* add panelbar rtl styles ([#153](https://github.com/telerik/kendo-theme-default/issues/153)) ([3e11904](https://github.com/telerik/kendo-theme-default/commit/3e11904)), closes [#102](https://github.com/telerik/kendo-theme-default/issues/102)
* add popup box shadow ([#168](https://github.com/telerik/kendo-theme-default/issues/168)) ([a25fb6e](https://github.com/telerik/kendo-theme-default/commit/a25fb6e)), closes [telerik/kendo-theme-default#165](https://github.com/telerik/kendo-theme-default/issues/165)
* add popup styles to datetime package ([db1e963](https://github.com/telerik/kendo-theme-default/commit/db1e963))
* add popup theme to chart theme ([aa7c1fc](https://github.com/telerik/kendo-theme-default/commit/aa7c1fc))
* add separate bundle of tabstrip styles ([0580feb](https://github.com/telerik/kendo-theme-default/commit/0580feb))
* add styles for centering list items ([110ff7a](https://github.com/telerik/kendo-theme-default/commit/110ff7a))
* add styling for chart tooltips ([#32](https://github.com/telerik/kendo-theme-default/issues/32)) ([2ec2545](https://github.com/telerik/kendo-theme-default/commit/2ec2545))
* add styling for Grid ARIA root element ([75dba15](https://github.com/telerik/kendo-theme-default/commit/75dba15))
* add styling for grid new item row ([#85](https://github.com/telerik/kendo-theme-default/issues/85)) ([b93009e](https://github.com/telerik/kendo-theme-default/commit/b93009e)), closes [telerik/kendo-angular-grid#60](https://github.com/telerik/kendo-angular-grid/issues/60)
* add styling for inputs clear all button ([#82](https://github.com/telerik/kendo-theme-default/issues/82)) ([55dde84](https://github.com/telerik/kendo-theme-default/commit/55dde84))
* add tabstrip animations ([85d10fd](https://github.com/telerik/kendo-theme-default/commit/85d10fd))
* add text alignment to droplowns ([4efa519](https://github.com/telerik/kendo-theme-default/commit/4efa519)), closes [telerik/kendo-angular-dropdowns#75](https://github.com/telerik/kendo-angular-dropdowns/issues/75) [#55](https://github.com/telerik/kendo-theme-default/issues/55)
* add var for chart default font size ([#36](https://github.com/telerik/kendo-theme-default/issues/36)) ([1ed2dea](https://github.com/telerik/kendo-theme-default/commit/1ed2dea))
* adjust loading icon position in MultiSelect and AutoComplete ([#432](https://github.com/telerik/kendo-theme-default/issues/432)) ([d60193f](https://github.com/telerik/kendo-theme-default/commit/d60193f))
* adjust primary button gradient to match design more closely ([0a47c38](https://github.com/telerik/kendo-theme-default/commit/0a47c38)), closes [#283](https://github.com/telerik/kendo-theme-default/issues/283)
* Adjust table wizard padding, sizing telerik/kendo[#6508](https://github.com/telerik/kendo-theme-default/issues/6508) ([#99](https://github.com/telerik/kendo-theme-default/issues/99)) ([b51cb7b](https://github.com/telerik/kendo-theme-default/commit/b51cb7b))
* allow flip-h and flip-v to be used together ([4178df2](https://github.com/telerik/kendo-theme-default/commit/4178df2))
* autocomplete in filter row appearance. ([f7cfec5](https://github.com/telerik/kendo-theme-default/commit/f7cfec5)), closes [telerik/kendo-theme-default#148](https://github.com/telerik/kendo-theme-default/issues/148)
* bare button states are not showing correctly ([8117298](https://github.com/telerik/kendo-theme-default/commit/8117298))
* build process does not prefix classes ([1f31b20](https://github.com/telerik/kendo-theme-default/commit/1f31b20)), closes [#5](https://github.com/telerik/kendo-theme-default/issues/5)
* button icons colors; button padding ([#27](https://github.com/telerik/kendo-theme-default/issues/27)) ([f430ccc](https://github.com/telerik/kendo-theme-default/commit/f430ccc))
* buttons focused / active states; buttons height ([c20c806](https://github.com/telerik/kendo-theme-default/commit/c20c806))
* buttons must be square in editor ([5089ff6](https://github.com/telerik/kendo-theme-default/commit/5089ff6))
* change .k-popup.k-list-container box-sizing to border-box ([4b23415](https://github.com/telerik/kendo-theme-default/commit/4b23415))
* change author ([8b5c9cf](https://github.com/telerik/kendo-theme-default/commit/8b5c9cf))
* change scrollview prev/next button styles due to double rendering in iOS ([1a5b29f](https://github.com/telerik/kendo-theme-default/commit/1a5b29f))
* change theme color; re-calculate widgets colors due to color change ([ded3abe](https://github.com/telerik/kendo-theme-default/commit/ded3abe))
* chart incorrect colors ([dc1b6eb](https://github.com/telerik/kendo-theme-default/commit/dc1b6eb))
* chart selection handles metrics ([63d7189](https://github.com/telerik/kendo-theme-default/commit/63d7189))
* chart tooltip metrics; navigator-hint styling. ([9821d47](https://github.com/telerik/kendo-theme-default/commit/9821d47)), closes [telerik/kendo-theme-default#244](https://github.com/telerik/kendo-theme-default/issues/244)
* chart tooltip styling ([829fc5f](https://github.com/telerik/kendo-theme-default/commit/829fc5f))
* context menu and menu styling ([df180b0](https://github.com/telerik/kendo-theme-default/commit/df180b0))
* correct main file name in NPM package ([d7680c7](https://github.com/telerik/kendo-theme-default/commit/d7680c7))
* cursors are incorrect for multiselect tags and list items ([0e934ca](https://github.com/telerik/kendo-theme-default/commit/0e934ca))
* declare box-sizing for dropdowns ([cd41edb](https://github.com/telerik/kendo-theme-default/commit/cd41edb)), closes [telerik/kendo-angular2#142](https://github.com/telerik/kendo-angular2/issues/142)
* declare main file ([b25614d](https://github.com/telerik/kendo-theme-default/commit/b25614d))
* dialog icon styles ([72454a4](https://github.com/telerik/kendo-theme-default/commit/72454a4))
* disable transitions while dragging handle ([1772726](https://github.com/telerik/kendo-theme-default/commit/1772726))
* dropdownlist and combobox styling ([bacc4dd](https://github.com/telerik/kendo-theme-default/commit/bacc4dd))
* dropdownlist focus state. ([5e00bbe](https://github.com/telerik/kendo-theme-default/commit/5e00bbe)), closes [telerik/kendo-theme-default#235](https://github.com/telerik/kendo-theme-default/issues/235)
* dropdownlist search box appearance ([237f518](https://github.com/telerik/kendo-theme-default/commit/237f518))
* dropdowns focused hover state ([15a11b5](https://github.com/telerik/kendo-theme-default/commit/15a11b5))
* dropdowns styling the match the design ([80a9622](https://github.com/telerik/kendo-theme-default/commit/80a9622))
* dropdowns, pickers, inputs rtl styling ([2a10fe3](https://github.com/telerik/kendo-theme-default/commit/2a10fe3))
* editor toolbar ([#182](https://github.com/telerik/kendo-theme-default/issues/182)) ([04cc6de](https://github.com/telerik/kendo-theme-default/commit/04cc6de)), closes [#177](https://github.com/telerik/kendo-theme-default/issues/177)
* editor toolbar styling [#52](https://github.com/telerik/kendo-theme-default/issues/52) ([#84](https://github.com/telerik/kendo-theme-default/issues/84)) ([7878c21](https://github.com/telerik/kendo-theme-default/commit/7878c21))
* error bars styling ([#38](https://github.com/telerik/kendo-theme-default/issues/38)) ([593bc91](https://github.com/telerik/kendo-theme-default/commit/593bc91))
* expand / collapse icons are switched ([#59](https://github.com/telerik/kendo-theme-default/issues/59)) ([5bc865b](https://github.com/telerik/kendo-theme-default/commit/5bc865b))
* export sass variables for script usage ([2558ab5](https://github.com/telerik/kendo-theme-default/commit/2558ab5))
* filter menu, column menu and dropdown operator must be square ([331df4b](https://github.com/telerik/kendo-theme-default/commit/331df4b))
* focused button box-shadow; multiselect buttons metrics and focused stalying ([424bb7d](https://github.com/telerik/kendo-theme-default/commit/424bb7d))
* footer template height ([#208](https://github.com/telerik/kendo-theme-default/issues/208)) ([d7a078b](https://github.com/telerik/kendo-theme-default/commit/d7a078b))
* gantt toggle button and create task button must be square ([92dca6f](https://github.com/telerik/kendo-theme-default/commit/92dca6f))
* grid footer appearance ([d1da7af](https://github.com/telerik/kendo-theme-default/commit/d1da7af))
* grid hierarchy-cell appearance ([de53481](https://github.com/telerik/kendo-theme-default/commit/de53481))
* grid hierarchy-cell width; grid cells padding ([c9f244e](https://github.com/telerik/kendo-theme-default/commit/c9f244e))
* grid selection background. ([6493129](https://github.com/telerik/kendo-theme-default/commit/6493129)), closes [telerik/kend-theme-default#234](https://github.com/telerik/kend-theme-default/issues/234)
* grouping row p height ([#205](https://github.com/telerik/kendo-theme-default/issues/205)) ([50669c4](https://github.com/telerik/kendo-theme-default/commit/50669c4))
* hide input-bar unless used ([e611799](https://github.com/telerik/kendo-theme-default/commit/e611799))
* hide validator through hidden attribute ([295f09b](https://github.com/telerik/kendo-theme-default/commit/295f09b))
* hierarchical grid icons appearance ([926d403](https://github.com/telerik/kendo-theme-default/commit/926d403))
* hierarchy-cell icon color in selected grid row ([94835cd](https://github.com/telerik/kendo-theme-default/commit/94835cd))
* icon button size must be square for all skins ([c803226](https://github.com/telerik/kendo-theme-default/commit/c803226))
* icons hover / focus state ([ff5a536](https://github.com/telerik/kendo-theme-default/commit/ff5a536))
* import base layout before butto layout ([bbe6c71](https://github.com/telerik/kendo-theme-default/commit/bbe6c71))
* import color functions in variables files ([4eef3f9](https://github.com/telerik/kendo-theme-default/commit/4eef3f9))
* improve button sizing ([#195](https://github.com/telerik/kendo-theme-default/issues/195)) ([fde18c8](https://github.com/telerik/kendo-theme-default/commit/fde18c8))
* improve performance in IE ([0048877](https://github.com/telerik/kendo-theme-default/commit/0048877))
* improve upload styling ([ebe6f5e](https://github.com/telerik/kendo-theme-default/commit/ebe6f5e))
* improve yiq function ([98202c5](https://github.com/telerik/kendo-theme-default/commit/98202c5))
* inputs text-color selection. ([5ba213f](https://github.com/telerik/kendo-theme-default/commit/5ba213f)), closes [telerik/kendo-theme-default#241](https://github.com/telerik/kendo-theme-default/issues/241)
* **upload:** different spacing in RTL mode ([9840073](https://github.com/telerik/kendo-theme-default/commit/9840073)), closes [telerik/kendo-angular-upload#67](https://github.com/telerik/kendo-angular-upload/issues/67)
* in IE11, Edge12, and Edge13 border-radius with background-clip causes visual glitches ([96dad8d](https://github.com/telerik/kendo-theme-default/commit/96dad8d))
* incorrect dialog animation in ie11 ([40679be](https://github.com/telerik/kendo-theme-default/commit/40679be))
* incorrect padding of k-tabstrip-items ([#48](https://github.com/telerik/kendo-theme-default/issues/48)) ([d68f036](https://github.com/telerik/kendo-theme-default/commit/d68f036))
* inputs height in IE ([47b0036](https://github.com/telerik/kendo-theme-default/commit/47b0036))
* inputs placeholder color ([52857a0](https://github.com/telerik/kendo-theme-default/commit/52857a0))
* interpolate value in calc ([83439dd](https://github.com/telerik/kendo-theme-default/commit/83439dd))
* introduce -family-monospace variable ([5031f81](https://github.com/telerik/kendo-theme-default/commit/5031f81))
* invisible action buttons in Bootstrap ([8176d6d](https://github.com/telerik/kendo-theme-default/commit/8176d6d))
* invisible separators and wrong selected items color ([ffed067](https://github.com/telerik/kendo-theme-default/commit/ffed067))
* item list is not aligned properly in RTL ([#67](https://github.com/telerik/kendo-theme-default/issues/67)) ([53c155d](https://github.com/telerik/kendo-theme-default/commit/53c155d))
* kendo colorpicker is not properly styles when clearButton is set [#103](https://github.com/telerik/kendo-theme-default/issues/103) ([328f650](https://github.com/telerik/kendo-theme-default/commit/328f650))
* list items styling ([#79](https://github.com/telerik/kendo-theme-default/issues/79)) ([49a3f92](https://github.com/telerik/kendo-theme-default/commit/49a3f92)), closes [telerik/kendo-theme-default#75](https://github.com/telerik/kendo-theme-default/issues/75)
* loading indicator size; loading indicator in combobox position ([#202](https://github.com/telerik/kendo-theme-default/issues/202)) ([5e58cd9](https://github.com/telerik/kendo-theme-default/commit/5e58cd9)), closes [telerik/kendo-theme-default#200](https://github.com/telerik/kendo-theme-default/issues/200)
* make drag handle visible in all cases #telerik/kendo-ui-core[#3254](https://github.com/telerik/kendo-theme-default/issues/3254) ([9709288](https://github.com/telerik/kendo-theme-default/commit/9709288))
* menu and grid header styles ([c875cf0](https://github.com/telerik/kendo-theme-default/commit/c875cf0))
* menu styling ([#110](https://github.com/telerik/kendo-theme-default/issues/110)) ([7ea682d](https://github.com/telerik/kendo-theme-default/commit/7ea682d))
* misaligned icons in popup items. ([beaaac8](https://github.com/telerik/kendo-theme-default/commit/beaaac8)), closes [telerik/kendo-theme-default#222](https://github.com/telerik/kendo-theme-default/issues/222)
* missing filter button in grid filter row ([9a9b724](https://github.com/telerik/kendo-theme-default/commit/9a9b724))
* move chart height to host element ([0a91a77](https://github.com/telerik/kendo-theme-default/commit/0a91a77))
* move imports to work with newer sass ([f68d746](https://github.com/telerik/kendo-theme-default/commit/f68d746))
* multiselect border; remove input width ([fb94f8c](https://github.com/telerik/kendo-theme-default/commit/fb94f8c))
* multiselect buttons clear icon appearance ([3f892f9](https://github.com/telerik/kendo-theme-default/commit/3f892f9))
* MultiSelect delete buttons visibility ([ffed009](https://github.com/telerik/kendo-theme-default/commit/ffed009)), closes [telerik/kendo-theme-default#87](https://github.com/telerik/kendo-theme-default/issues/87)
* multiselect in ie behavior. ([#206](https://github.com/telerik/kendo-theme-default/issues/206)) ([06fb96d](https://github.com/telerik/kendo-theme-default/commit/06fb96d)), closes [telerik/kendo-angular#191](https://github.com/telerik/kendo-angular/issues/191)
* multiselect input height ([6561c85](https://github.com/telerik/kendo-theme-default/commit/6561c85)), closes [telerik/kendo-theme-default#90](https://github.com/telerik/kendo-theme-default/issues/90)
* multiselect input position ([968bfbd](https://github.com/telerik/kendo-theme-default/commit/968bfbd))
* multiselect items - wrong rounded corners. ([db3c2cc](https://github.com/telerik/kendo-theme-default/commit/db3c2cc)), closes [telerik/kendo-theme-default#239](https://github.com/telerik/kendo-theme-default/issues/239)
* multiselect items margin and icon hover styling ([7672cb8](https://github.com/telerik/kendo-theme-default/commit/7672cb8))
* multiselect loading; close button metrics ([2ae5b9f](https://github.com/telerik/kendo-theme-default/commit/2ae5b9f))
* notes styling, crosshair background ([#37](https://github.com/telerik/kendo-theme-default/issues/37)) ([49d0f06](https://github.com/telerik/kendo-theme-default/commit/49d0f06))
* numerictextbox focus state. telerik/kendo-theme-default[#223](https://github.com/telerik/kendo-theme-default/issues/223) ([71539f4](https://github.com/telerik/kendo-theme-default/commit/71539f4))
* numerictextbox spinner appearance for IE10; selected spinner icon color ([#201](https://github.com/telerik/kendo-theme-default/issues/201)) ([dbd8feb](https://github.com/telerik/kendo-theme-default/commit/dbd8feb))
* numerictextbox spinner icons alignment. ([#191](https://github.com/telerik/kendo-theme-default/issues/191)) ([0c3d964](https://github.com/telerik/kendo-theme-default/commit/0c3d964)), closes [telerik/kendo-theme-default#161](https://github.com/telerik/kendo-theme-default/issues/161)
* opacity for no data template ([3fd2648](https://github.com/telerik/kendo-theme-default/commit/3fd2648))
* output path of build process in derived themes ([7199ee0](https://github.com/telerik/kendo-theme-default/commit/7199ee0))
* pager appearance to match thе design ([381cd57](https://github.com/telerik/kendo-theme-default/commit/381cd57)), closes [telerik/kendo-theme-default#187](https://github.com/telerik/kendo-theme-default/issues/187) [#190](https://github.com/telerik/kendo-theme-default/issues/190)
* pager appearance; grid header height ([a889fe8](https://github.com/telerik/kendo-theme-default/commit/a889fe8))
* panelbar colors to match the new design; delete unused variables ([45f58d6](https://github.com/telerik/kendo-theme-default/commit/45f58d6))
* panelbar disabled items hover color ([1ef8712](https://github.com/telerik/kendo-theme-default/commit/1ef8712))
* popup and animation-container styling ([e6fe577](https://github.com/telerik/kendo-theme-default/commit/e6fe577))
* position dialog-wrapper to viewport 0,0 ([da9bbb1](https://github.com/telerik/kendo-theme-default/commit/da9bbb1))
* prev / next buttons in scheduler must be square ([2b5b418](https://github.com/telerik/kendo-theme-default/commit/2b5b418))
* primary button appearance ([b943ed4](https://github.com/telerik/kendo-theme-default/commit/b943ed4))
* provide icon-font-dir variable to override font location ([12e7a5d](https://github.com/telerik/kendo-theme-default/commit/12e7a5d))
* re-calculate widgets colors which depend on the color; add transparency to all borders ([215b48b](https://github.com/telerik/kendo-theme-default/commit/215b48b))
* regression in slider handle animation ([8cf5be7](https://github.com/telerik/kendo-theme-default/commit/8cf5be7)), closes [#26](https://github.com/telerik/kendo-theme-default/issues/26)
* remove additional focus state shadow and fix button height ([858695b](https://github.com/telerik/kendo-theme-default/commit/858695b))
* remove animation for dropdowns list items ([9904a0d](https://github.com/telerik/kendo-theme-default/commit/9904a0d))
* remove border on dialog buttons ([97ba4ab](https://github.com/telerik/kendo-theme-default/commit/97ba4ab))
* Remove checkbox, radiobutton hover state telerik/kendo[#6508](https://github.com/telerik/kendo-theme-default/issues/6508) ([#120](https://github.com/telerik/kendo-theme-default/issues/120)) ([35a5f5a](https://github.com/telerik/kendo-theme-default/commit/35a5f5a))
* Remove checkbox:checked border to center the check glyph ([a005683](https://github.com/telerik/kendo-theme-default/commit/a005683))
* remove grid focus outline. ([#203](https://github.com/telerik/kendo-theme-default/issues/203)) ([0bd10aa](https://github.com/telerik/kendo-theme-default/commit/0bd10aa)), closes [telerik/kendo-theme-default#199](https://github.com/telerik/kendo-theme-default/issues/199)
* remove hover styles on disabled slider ([3061193](https://github.com/telerik/kendo-theme-default/commit/3061193))
* remove IE7 styles, show link between window and actions padding ([3392625](https://github.com/telerik/kendo-theme-default/commit/3392625))
* **action-buttons:** action-buttons should clear floats ([#113](https://github.com/telerik/kendo-theme-default/issues/113)) ([8045ecb](https://github.com/telerik/kendo-theme-default/commit/8045ecb))
* **action-buttons:** improve action buttons spacing ([c3941c3](https://github.com/telerik/kendo-theme-default/commit/c3941c3))
* **action-buttons:** update action-buttons metrics ([f4c1d30](https://github.com/telerik/kendo-theme-default/commit/f4c1d30))
* **animation:** add expand animation styles ([857ac89](https://github.com/telerik/kendo-theme-default/commit/857ac89))
* **Animation:** Correct zoom-in/out CSS class names ([439e177](https://github.com/telerik/kendo-theme-default/commit/439e177))
* **Animation:** Hide every old entering element ([9ef83ec](https://github.com/telerik/kendo-theme-default/commit/9ef83ec))
* **Animation:** Hide old animated elements only if they are still active ([ae7fe98](https://github.com/telerik/kendo-theme-default/commit/ae7fe98))
* **Animation:** Position enter element relatively. Hide old entering elements ([06f9704](https://github.com/telerik/kendo-theme-default/commit/06f9704))
* **Animation:** use default positioning for the animation container ([#5](https://github.com/telerik/kendo-theme-default/issues/5)) ([b6afea5](https://github.com/telerik/kendo-theme-default/commit/b6afea5))
* **animations:** add missing appear transitions ([db7b765](https://github.com/telerik/kendo-theme-default/commit/db7b765))
* **animations:** change animation-leave selector to animation-exit ([fb69c97](https://github.com/telerik/kendo-theme-default/commit/fb69c97))
* **animations:** nested panelbar expand ([5bc45b6](https://github.com/telerik/kendo-theme-default/commit/5bc45b6))
* **autocomplete:** add box-sizing ([aa4b17e](https://github.com/telerik/kendo-theme-default/commit/aa4b17e))
* **autocomplete:** add invalid state for Angular ([6b41e5b](https://github.com/telerik/kendo-theme-default/commit/6b41e5b))
* **autocomplete:** use correct background-clip for autocomplete ([8f32709](https://github.com/telerik/kendo-theme-default/commit/8f32709))
* **autocomplete:** use correct padding for autocomplete ([ecacbce](https://github.com/telerik/kendo-theme-default/commit/ecacbce))
* **button:** Add background-clip; adjust primary button focused shadow transparency ([#172](https://github.com/telerik/kendo-theme-default/issues/172)) ([f1d3417](https://github.com/telerik/kendo-theme-default/commit/f1d3417))
* **button:** add height to icon button for proper vertical alignment ([df4d3f4](https://github.com/telerik/kendo-theme-default/commit/df4d3f4))
* **button:** add styles for icon buttons in RTL ([a5de136](https://github.com/telerik/kendo-theme-default/commit/a5de136))
* **button:** add styles for radiobutton group that look like button group ([be14283](https://github.com/telerik/kendo-theme-default/commit/be14283))
* **button:** extract variable for bare button hover opacity ([#655](https://github.com/telerik/kendo-theme-default/issues/655)) ([8671249](https://github.com/telerik/kendo-theme-default/commit/8671249))
* **button:** icon button height should be equal to the other buttons ([3eba04f](https://github.com/telerik/kendo-theme-default/commit/3eba04f))
* **button:** improve border radius for rtl ([cc51a24](https://github.com/telerik/kendo-theme-default/commit/cc51a24))
* **button:** make buttons relative by default ([89d1280](https://github.com/telerik/kendo-theme-default/commit/89d1280))
* **button:** outline primary buttons appearance ([14e636e](https://github.com/telerik/kendo-theme-default/commit/14e636e))
* **button:** update variables to match design ([ac85fe9](https://github.com/telerik/kendo-theme-default/commit/ac85fe9))
* **button:** use correct pressed-like button appearance ([7613188](https://github.com/telerik/kendo-theme-default/commit/7613188))
* **button:** use correct states for selected button in button group ([ae8fdbc](https://github.com/telerik/kendo-theme-default/commit/ae8fdbc))
* **button:** use variable for buttongroup buttons left margin ([b24a1e4](https://github.com/telerik/kendo-theme-default/commit/b24a1e4))
* **buttongroup:** use correct background-clip for buttongroup ([583ed8c](https://github.com/telerik/kendo-theme-default/commit/583ed8c))
* **buttonGroup:** add focus state to disabled button in button group telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([c255c82](https://github.com/telerik/kendo-theme-default/commit/c255c82))
* **buttonGroup:** fix border radius after reverting rendering changes telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([0f68691](https://github.com/telerik/kendo-theme-default/commit/0f68691))
* **buttonGroup:** fix border radius after reverting rendering changes telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([e088f72](https://github.com/telerik/kendo-theme-default/commit/e088f72))
* **buttonGroupd:** add focus state to button in disabled button group telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([13b0de5](https://github.com/telerik/kendo-theme-default/commit/13b0de5))
* **buttons:** add RTL support for button icons ([#170](https://github.com/telerik/kendo-theme-default/issues/170)) ([82d5401](https://github.com/telerik/kendo-theme-default/commit/82d5401))
* **buttons:** add variable for border width ([3fae15f](https://github.com/telerik/kendo-theme-default/commit/3fae15f))
* **buttons:** fix missing border radius ([5fcf831](https://github.com/telerik/kendo-theme-default/commit/5fcf831))
* **buttons:** use variable for bare buttons positions ([0b162be](https://github.com/telerik/kendo-theme-default/commit/0b162be))
* **calendar:** add hints for endless scrolling in infinite calendar ([9289990](https://github.com/telerik/kendo-theme-default/commit/9289990))
* **calendar:** add RTL styles for infinite mode ([b061418](https://github.com/telerik/kendo-theme-default/commit/b061418))
* **calendar:** Add specificity to selected weekend day selector ([#561](https://github.com/telerik/kendo-theme-default/issues/561)) ([1ca705b](https://github.com/telerik/kendo-theme-default/commit/1ca705b))
* **calendar:** add styles for infinite mode ([313856d](https://github.com/telerik/kendo-theme-default/commit/313856d))
* **calendar:** adjust navigation padding ([9e07572](https://github.com/telerik/kendo-theme-default/commit/9e07572))
* **calendar:** bring Calendar styles up to date with design ([c08e38a](https://github.com/telerik/kendo-theme-default/commit/c08e38a))
* **calendar:** Center dates per latest design, fix selected weekend background ([14698e1](https://github.com/telerik/kendo-theme-default/commit/14698e1))
* **calendar:** center navigation text ([57e9c1c](https://github.com/telerik/kendo-theme-default/commit/57e9c1c))
* **calendar:** correct padding for navigation on OSX ([#379](https://github.com/telerik/kendo-theme-default/issues/379)) ([0e64cc7](https://github.com/telerik/kendo-theme-default/commit/0e64cc7)), closes [#353](https://github.com/telerik/kendo-theme-default/issues/353)
* **calendar:** improve layout for months with few days ([078f2e4](https://github.com/telerik/kendo-theme-default/commit/078f2e4))
* **calendar:** improve layout in IE10 ([0238c1b](https://github.com/telerik/kendo-theme-default/commit/0238c1b))
* **calendar:** Improve styling ([6d55d7a](https://github.com/telerik/kendo-theme-default/commit/6d55d7a))
* **calendar:** increase height to show second month ([2e62660](https://github.com/telerik/kendo-theme-default/commit/2e62660))
* **calendar:** remove the float style from k-content ([6f1f930](https://github.com/telerik/kendo-theme-default/commit/6f1f930))
* **calendar:** Switch to display: block ([3f3932b](https://github.com/telerik/kendo-theme-default/commit/3f3932b))
* **calendar:** Updates Calendar styles to match design ([04ad7d7](https://github.com/telerik/kendo-theme-default/commit/04ad7d7))
* **calendar:** use correct background-clip for calendar ([17b51e4](https://github.com/telerik/kendo-theme-default/commit/17b51e4))
* **calendar:** wrong view width in pages with bootstrap 3 ([1f4be2f](https://github.com/telerik/kendo-theme-default/commit/1f4be2f))
* **chart:** add k-chart-dragging class ([059c9cd](https://github.com/telerik/kendo-theme-default/commit/059c9cd))
* **chart:** add missing popup dependency ([#549](https://github.com/telerik/kendo-theme-default/issues/549)) ([6ce5dea](https://github.com/telerik/kendo-theme-default/commit/6ce5dea))
* **chart:** add transitions if the wrapper and the popup are the same element ([0d225c4](https://github.com/telerik/kendo-theme-default/commit/0d225c4))
* **chart:** remove spacing from tooltip ([bcbb789](https://github.com/telerik/kendo-theme-default/commit/bcbb789))
* **chart:** tooltip animation transtions ([56c42d8](https://github.com/telerik/kendo-theme-default/commit/56c42d8))
* **checkbox:** imrpove checkbox states ([c69e527](https://github.com/telerik/kendo-theme-default/commit/c69e527))
* **checkbox:** remove double opacity on checkboxes ([f7c3951](https://github.com/telerik/kendo-theme-default/commit/f7c3951))
* **colorpicker:** Add style for Colorpicker with tool icon ([#137](https://github.com/telerik/kendo-theme-default/issues/137)) ([838d4af](https://github.com/telerik/kendo-theme-default/commit/838d4af))
* **colorpicker:** use correct background-clip for colorpicker ([70923c3](https://github.com/telerik/kendo-theme-default/commit/70923c3))
* **colorpicker:** use correct size and box-sizing for color preview ([551d79e](https://github.com/telerik/kendo-theme-default/commit/551d79e))
* **combobox:** allow mixed units for right padding ([#399](https://github.com/telerik/kendo-theme-default/issues/399)) ([b543b43](https://github.com/telerik/kendo-theme-default/commit/b543b43))
* **combobox:** clear button overlaps the selected item ([#395](https://github.com/telerik/kendo-theme-default/issues/395)) ([b17e409](https://github.com/telerik/kendo-theme-default/commit/b17e409)), closes [telerik/kendo-theme-default#261](https://github.com/telerik/kendo-theme-default/issues/261)
* **combobox:** left padding in rtl mode ([f3927c0](https://github.com/telerik/kendo-theme-default/commit/f3927c0))
* **combobox:** use correct background-clip for combobox ([8fb34d2](https://github.com/telerik/kendo-theme-default/commit/8fb34d2))
* **combobox:** wrong styling on focused item. ([8c70c62](https://github.com/telerik/kendo-theme-default/commit/8c70c62)), closes [telerik/kendo-theme-default#309](https://github.com/telerik/kendo-theme-default/issues/309)
* **common:** add styles for reorder cue ([9a7971e](https://github.com/telerik/kendo-theme-default/commit/9a7971e))
* **common:** add styles for text selection ([0bc9d90](https://github.com/telerik/kendo-theme-default/commit/0bc9d90))
* **common:** extract edit form styles to common/base ([4900d15](https://github.com/telerik/kendo-theme-default/commit/4900d15))
* **common:** improve common states ([#117](https://github.com/telerik/kendo-theme-default/issues/117)) ([843dcd3](https://github.com/telerik/kendo-theme-default/commit/843dcd3))
* **contextmenu:** improve separator and horizontal contextmenu ([7fe82fc](https://github.com/telerik/kendo-theme-default/commit/7fe82fc))
* **dateinput:** focused / selected state appearance ([6d3d9ba](https://github.com/telerik/kendo-theme-default/commit/6d3d9ba))
* **DateInput:** Add RTL styles ([28763cb](https://github.com/telerik/kendo-theme-default/commit/28763cb))
* **dateinputs:** calendar and timepicker colors ([2a0634c](https://github.com/telerik/kendo-theme-default/commit/2a0634c))
* **datepicker:** add hover style; wrong width and height ([a5fb667](https://github.com/telerik/kendo-theme-default/commit/a5fb667))
* **datepicker:** fix Angular validation styles ([7104d88](https://github.com/telerik/kendo-theme-default/commit/7104d88))
* **datepicker:** override margin when applied to .k-widget ([e581514](https://github.com/telerik/kendo-theme-default/commit/e581514))
* **datepicker:** Switch rounded corners for select button in RTL; style imrovements ([c19178a](https://github.com/telerik/kendo-theme-default/commit/c19178a))
* **datepicker:** wrong width of the internal DateInput component in IE11 ([2505558](https://github.com/telerik/kendo-theme-default/commit/2505558))
* **datetime:** add dependency to calendar ([d23888c](https://github.com/telerik/kendo-theme-default/commit/d23888c))
* **datetime:** use corerct background-clip for datetime ([6937500](https://github.com/telerik/kendo-theme-default/commit/6937500))
* **datetimepicker:** allow buttons to work in any box-sizing context ([#722](https://github.com/telerik/kendo-theme-default/issues/722)) ([417a181](https://github.com/telerik/kendo-theme-default/commit/417a181))
* **diagram:** use accent-contrast color ([#378](https://github.com/telerik/kendo-theme-default/issues/378)) ([0f5f063](https://github.com/telerik/kendo-theme-default/commit/0f5f063))
* **dialog:** add border between buttons in RTL ([8086b63](https://github.com/telerik/kendo-theme-default/commit/8086b63))
* **dialog:** alignment in IE11 and Firefox RTL ([7bd2d19](https://github.com/telerik/kendo-theme-default/commit/7bd2d19))
* **dialog:** animation styles ([2cc7ad4](https://github.com/telerik/kendo-theme-default/commit/2cc7ad4))
* **dialog:** Bring button layout in line with design telerik/kendo[#6508](https://github.com/telerik/kendo-theme-default/issues/6508) ([#108](https://github.com/telerik/kendo-theme-default/issues/108)) ([703c465](https://github.com/telerik/kendo-theme-default/commit/703c465))
* **dialog:** center action button text in Safari ([6240433](https://github.com/telerik/kendo-theme-default/commit/6240433)), closes [#158](https://github.com/telerik/kendo-theme-default/issues/158)
* **dialog:** close button styles ([01e8a90](https://github.com/telerik/kendo-theme-default/commit/01e8a90))
* **dialog:** content is not visible in IE11 ([7b86eef](https://github.com/telerik/kendo-theme-default/commit/7b86eef)), closes [telerik/kendo-angular2#192](https://github.com/telerik/kendo-angular2/issues/192)
* **dialog:** do not collapse buttons in scrollable content ([da300ff](https://github.com/telerik/kendo-theme-default/commit/da300ff))
* **dialog:** do not hide action buttons if window is higher than viewport in IE11 ([#814](https://github.com/telerik/kendo-theme-default/issues/814)) ([a060d04](https://github.com/telerik/kendo-theme-default/commit/a060d04))
* **dialog:** do not modify custom content ([400ccd1](https://github.com/telerik/kendo-theme-default/commit/400ccd1)), closes [#180](https://github.com/telerik/kendo-theme-default/issues/180)
* **dialog:** Improve dialog content, titlebar centering ([9aea365](https://github.com/telerik/kendo-theme-default/commit/9aea365))
* **dialog:** limit height to viewport height ([157c323](https://github.com/telerik/kendo-theme-default/commit/157c323))
* **dialog:** pager buttons appear above modal dialog ([898c31f](https://github.com/telerik/kendo-theme-default/commit/898c31f))
* **dialog:** use accent colors by default ([0ddcbee](https://github.com/telerik/kendo-theme-default/commit/0ddcbee))
* **dropdownlist:** improve styles for dropdown operator in grid filtering ([5260e7f](https://github.com/telerik/kendo-theme-default/commit/5260e7f))
* **dropdownlist:** long text in filter input interferes with the icon. ([f28d9fe](https://github.com/telerik/kendo-theme-default/commit/f28d9fe)), closes [telerik/kendo-theme-default#564](https://github.com/telerik/kendo-theme-default/issues/564)
* **dropdownlist:** use correct background-clip for dropdownlist ([b282964](https://github.com/telerik/kendo-theme-default/commit/b282964))
* **DropDownList:** remove the default clear button in IE ([7319d02](https://github.com/telerik/kendo-theme-default/commit/7319d02))
* **dropdowns:** appearance in rtl mode ([691ef52](https://github.com/telerik/kendo-theme-default/commit/691ef52))
* **dropdowns:** calculate size of list filter ([32404e9](https://github.com/telerik/kendo-theme-default/commit/32404e9))
* **dropdowns:** filtering input / label rtl alignment ([4ad8121](https://github.com/telerik/kendo-theme-default/commit/4ad8121))
* **dropdowns:** misaligned loading indicator; wrong select width ([#545](https://github.com/telerik/kendo-theme-default/issues/545)) ([8edc50a](https://github.com/telerik/kendo-theme-default/commit/8edc50a))
* **dropdowns:** noDataTemplate styling ([753347f](https://github.com/telerik/kendo-theme-default/commit/753347f)), closes [telerik/kendo-theme-default#327](https://github.com/telerik/kendo-theme-default/issues/327)
* **dropdowns:** update dropdowns styling because of changed rendering ([#388](https://github.com/telerik/kendo-theme-default/issues/388)) ([9b6ac0e](https://github.com/telerik/kendo-theme-default/commit/9b6ac0e))
* **dropdowns:** visual glitches ([e41d8eb](https://github.com/telerik/kendo-theme-default/commit/e41d8eb))
* **edit-form:** colorpickers must not be 100% wide in edit form ([52fb2fe](https://github.com/telerik/kendo-theme-default/commit/52fb2fe))
* **editform:** use min width in addition to width ([d0b5b44](https://github.com/telerik/kendo-theme-default/commit/d0b5b44))
* **editor:** add header border color for Firefox ([d68f6a6](https://github.com/telerik/kendo-theme-default/commit/d68f6a6))
* **editor:** add layout for filebrowser / image browser dialog ([1576167](https://github.com/telerik/kendo-theme-default/commit/1576167))
* **editor:** add spacing between widgets in toolbar group ([42e7e45](https://github.com/telerik/kendo-theme-default/commit/42e7e45))
* **editor:** add styles for browser dialogs ([64ab51a](https://github.com/telerik/kendo-theme-default/commit/64ab51a))
* **editor:** Adjust Colorpicker size, unhide color preview strip ([#143](https://github.com/telerik/kendo-theme-default/issues/143)) ([74cc2c3](https://github.com/telerik/kendo-theme-default/commit/74cc2c3))
* **editor:** align template content vertially ([eb63cbe](https://github.com/telerik/kendo-theme-default/commit/eb63cbe))
* **editor:** broken layout of file and image browsers ([fe0243d](https://github.com/telerik/kendo-theme-default/commit/fe0243d))
* **editor:** content of editor toolbar exceeds the size of the container ([a1310be](https://github.com/telerik/kendo-theme-default/commit/a1310be))
* **editor:** fix displaced combobox button in editor in Edge [#625](https://github.com/telerik/kendo-theme-default/issues/625) ([e930ce5](https://github.com/telerik/kendo-theme-default/commit/e930ce5))
* **editor:** fix editor's file and image browser dialogs telerik/kendo-ui-core[#2819](https://github.com/telerik/kendo-theme-default/issues/2819) ([8faf610](https://github.com/telerik/kendo-theme-default/commit/8faf610))
* **editor:** fix scrolled content height in the table wizard dialog [#665](https://github.com/telerik/kendo-theme-default/issues/665) ([138b952](https://github.com/telerik/kendo-theme-default/commit/138b952))
* **editor:** fix searchbox in filebrowser dialog ([e1ae582](https://github.com/telerik/kendo-theme-default/commit/e1ae582))
* **editor:** fix type in editor selector ([8a1a669](https://github.com/telerik/kendo-theme-default/commit/8a1a669))
* **editor:** improve numeric and colorpickers in table wizard ([4f0b323](https://github.com/telerik/kendo-theme-default/commit/4f0b323))
* **editor:** improve styling of tabstrip in window ([39a91b4](https://github.com/telerik/kendo-theme-default/commit/39a91b4))
* **editor:** improve table wizard alignment dropdowns ([d517b2f](https://github.com/telerik/kendo-theme-default/commit/d517b2f))
* **editor:** improve table wizzard dropdown ([59a424c](https://github.com/telerik/kendo-theme-default/commit/59a424c))
* **editor:** improve tiles gird styles ([f0145ec](https://github.com/telerik/kendo-theme-default/commit/f0145ec))
* **editor:** Inconsistent Editor indent/outdent icons in RTL ([d6bcc52](https://github.com/telerik/kendo-theme-default/commit/d6bcc52))
* **editor:** make editor dialog content as wide as dialog ([83eda33](https://github.com/telerik/kendo-theme-default/commit/83eda33))
* **editor:** make scrollbars of Editor's dialogs to be consistent ([12e24e2](https://github.com/telerik/kendo-theme-default/commit/12e24e2))
* **editor:** make scrollbars of Editor's dialogs to be consistent ([c7330e0](https://github.com/telerik/kendo-theme-default/commit/c7330e0))
* **editor:** prevent overflowing file and image browsers content telerik/kendo-theme-bootstrap[#206](https://github.com/telerik/kendo-theme-default/issues/206) ([877575f](https://github.com/telerik/kendo-theme-default/commit/877575f))
* **editor:** prevent resize handler to oerlap scrolling arrow telerik/kendo-ui.core[#3445](https://github.com/telerik/kendo-theme-default/issues/3445) ([1fa2a8b](https://github.com/telerik/kendo-theme-default/commit/1fa2a8b))
* **editor:** reduce size of inlie editor toolbar ([06d1caf](https://github.com/telerik/kendo-theme-default/commit/06d1caf))
* **editor:** uniform scrollnig in editor dialogs ([e43cb41](https://github.com/telerik/kendo-theme-default/commit/e43cb41))
* **editor:** use border-color: inhreit for editor toolbar and editable area ([2932e19](https://github.com/telerik/kendo-theme-default/commit/2932e19))
* **editor:** use correct colors for toggled button ([57c51b4](https://github.com/telerik/kendo-theme-default/commit/57c51b4))
* **editor:** use corret background-clip for editor ([237124a](https://github.com/telerik/kendo-theme-default/commit/237124a))
* **editors:** common layout glitches ([9e66aad](https://github.com/telerik/kendo-theme-default/commit/9e66aad))
* **forms:** align labels in forms in dialog ([e488260](https://github.com/telerik/kendo-theme-default/commit/e488260))
* **forms:** align text, field-info, radiobuttons and checkboxes in forms ([607a48d](https://github.com/telerik/kendo-theme-default/commit/607a48d))
* **forms:** allow use of k-state-invalid class for invalid state ([#823](https://github.com/telerik/kendo-theme-default/issues/823)) ([8367d13](https://github.com/telerik/kendo-theme-default/commit/8367d13))
* **gantt:** broken tasks and dependencies position in RTL ([afef5d0](https://github.com/telerik/kendo-theme-default/commit/afef5d0))
* **gantt:** broken tasks and dependencies positions in RTL ([96e9e1f](https://github.com/telerik/kendo-theme-default/commit/96e9e1f))
* **gantt:** broken tasks in IE ([8325c2a](https://github.com/telerik/kendo-theme-default/commit/8325c2a))
* **gantt:** imporve task percentagle complete handle position ([a4b3f84](https://github.com/telerik/kendo-theme-default/commit/a4b3f84))
* **gantt:** improve gantt size by setting align to k-icon ([29ca321](https://github.com/telerik/kendo-theme-default/commit/29ca321))
* **gantt:** improve milestone RTL position ([cf04b8f](https://github.com/telerik/kendo-theme-default/commit/cf04b8f))
* **gantt:** move tasks to prevent overlapping dependency arrows ([2d5e8bd](https://github.com/telerik/kendo-theme-default/commit/2d5e8bd))
* **gantt:** move tasks to prevent overlapping dependency in RTL ([d1ea3fa](https://github.com/telerik/kendo-theme-default/commit/d1ea3fa))
* **gantt:** remove font size from task content ([ca2d996](https://github.com/telerik/kendo-theme-default/commit/ca2d996))
* **gantt:** remove overriding styles from splitter in accordance with design ([37201f2](https://github.com/telerik/kendo-theme-default/commit/37201f2))
* **gantt:** show delete-task-link only on task hover ([35171d3](https://github.com/telerik/kendo-theme-default/commit/35171d3))
* **gantt:** show task progress drag handle only on hover ([e8a9873](https://github.com/telerik/kendo-theme-default/commit/e8a9873))
* **gantt:** text is not vertically aligned wihtin headers ([cd3c947](https://github.com/telerik/kendo-theme-default/commit/cd3c947))
* **gantt:** treelist header is not correctly aligned with timeline headers ([b660ced](https://github.com/telerik/kendo-theme-default/commit/b660ced))
* **gantt:** update gant task in accordance with design ([f461593](https://github.com/telerik/kendo-theme-default/commit/f461593))
* **gantt:** update gantt header height in accordance with design ([12fd992](https://github.com/telerik/kendo-theme-default/commit/12fd992))
* **gantt:** update gantt in accordance with design ([9389b48](https://github.com/telerik/kendo-theme-default/commit/9389b48))
* **gantt:** update task tooltip in accordance with design ([b2ff91a](https://github.com/telerik/kendo-theme-default/commit/b2ff91a))
* **gantt:** update task-milestone in accordance with design ([b67f98e](https://github.com/telerik/kendo-theme-default/commit/b67f98e))
* **gantt:** update task-summary in accordance with design ([5fc1fc9](https://github.com/telerik/kendo-theme-default/commit/5fc1fc9))
* **gantt:** use correct background-clip for gantt ([16a10a0](https://github.com/telerik/kendo-theme-default/commit/16a10a0))
* **gantt:** use correct variables for toolbar padding ([d95f93b](https://github.com/telerik/kendo-theme-default/commit/d95f93b))
* **gantt:** use vertical-align middle for gantt treelist content cells ([c57f84e](https://github.com/telerik/kendo-theme-default/commit/c57f84e))
* **gantt:** view switcher is missing selected state ([015b7ec](https://github.com/telerik/kendo-theme-default/commit/015b7ec))
* **gantt:** wrong action button position ([4a76cd6](https://github.com/telerik/kendo-theme-default/commit/4a76cd6))
* **gantt:** wrong task complete position ([873cbf7](https://github.com/telerik/kendo-theme-default/commit/873cbf7))
* **grid:** (Angular) resize contents to fit wrapper ([#859](https://github.com/telerik/kendo-theme-default/issues/859)) ([e57a000](https://github.com/telerik/kendo-theme-default/commit/e57a000))
* **grid:** add autofitting styles for jQuery grid ([116dcfd](https://github.com/telerik/kendo-theme-default/commit/116dcfd))
* **grid:** Add calculation and apply it to form elements margin ([1db82a0](https://github.com/telerik/kendo-theme-default/commit/1db82a0))
* **grid:** Add missing dirty cell styling ([4ec31bf](https://github.com/telerik/kendo-theme-default/commit/4ec31bf))
* **grid:** Add missing loading spinner ([#539](https://github.com/telerik/kendo-theme-default/issues/539)) ([8055d53](https://github.com/telerik/kendo-theme-default/commit/8055d53))
* **grid:** Add negative widget offset margins to column menu icon in header ([29a744d](https://github.com/telerik/kendo-theme-default/commit/29a744d))
* **grid:** Add no-text class styling to checkbox label ([713bbc1](https://github.com/telerik/kendo-theme-default/commit/713bbc1))
* **grid:** add reorder styles for ng grid ([5fc5a30](https://github.com/telerik/kendo-theme-default/commit/5fc5a30))
* **grid:** Add RTL styles for dirty cells ([f683eb1](https://github.com/telerik/kendo-theme-default/commit/f683eb1))
* **grid:** add spacing between buttons ([89de27c](https://github.com/telerik/kendo-theme-default/commit/89de27c))
* **grid:** add styles for virtual content ([05aad12](https://github.com/telerik/kendo-theme-default/commit/05aad12))
* **grid:** Add styles positioning the PDF export progress bar ([ce1c967](https://github.com/telerik/kendo-theme-default/commit/ce1c967))
* **grid:** Adjust checkbox margin in RTL ([22096dd](https://github.com/telerik/kendo-theme-default/commit/22096dd))
* **grid:** Adjust column sorting icon and index positions ([5d3230d](https://github.com/telerik/kendo-theme-default/commit/5d3230d))
* **grid:** Adjust filter row Numerictextbox width ([b61ee19](https://github.com/telerik/kendo-theme-default/commit/b61ee19))
* **grid:** Adjust filterable+sortable header margin for the sake of Edge ([488fe21](https://github.com/telerik/kendo-theme-default/commit/488fe21))
* **grid:** Adjust header styles ([afe0bb8](https://github.com/telerik/kendo-theme-default/commit/afe0bb8))
* **grid:** Adjust input width in edit modes ([2faed78](https://github.com/telerik/kendo-theme-default/commit/2faed78))
* **grid:** adjust row height and grouping token size ([ffb4b65](https://github.com/telerik/kendo-theme-default/commit/ffb4b65))
* **grid:** Adjust sorting index position ([487d077](https://github.com/telerik/kendo-theme-default/commit/487d077))
* **grid:** Adjust sorting indicators positions ([988ff92](https://github.com/telerik/kendo-theme-default/commit/988ff92))
* **grid:** adjust the space between the input and row / cell border ([#296](https://github.com/telerik/kendo-theme-default/issues/296)) ([1e6e487](https://github.com/telerik/kendo-theme-default/commit/1e6e487)), closes [telerik/kendo-theme-default#294](https://github.com/telerik/kendo-theme-default/issues/294)
* **grid:** align bottom multi-column headers ([c3f3bdc](https://github.com/telerik/kendo-theme-default/commit/c3f3bdc))
* **grid:** Align popup checkbox with text ([fd447e7](https://github.com/telerik/kendo-theme-default/commit/fd447e7))
* **grid:** allow filter row components to shrink below min-width ([03ddb42](https://github.com/telerik/kendo-theme-default/commit/03ddb42))
* **grid:** allow filter row to render TD cells ([996a8b6](https://github.com/telerik/kendo-theme-default/commit/996a8b6))
* **grid:** allow for filterable cell input resizing ([6c67e7f](https://github.com/telerik/kendo-theme-default/commit/6c67e7f))
* **grid:** allow integration of resize sensor ([d6dcaaa](https://github.com/telerik/kendo-theme-default/commit/d6dcaaa))
* **grid:** allow use without flexbox in jQuery grid ([#439](https://github.com/telerik/kendo-theme-default/issues/439)) ([4fe6fb4](https://github.com/telerik/kendo-theme-default/commit/4fe6fb4))
* **grid:** Angular grouping header is collapsed in IE ([621cebf](https://github.com/telerik/kendo-theme-default/commit/621cebf))
* **grid:** broken layout when virtualization is used ([11b4775](https://github.com/telerik/kendo-theme-default/commit/11b4775)), closes [telerik/kendo-theme-default#324](https://github.com/telerik/kendo-theme-default/issues/324)
* **grid:** buttons in Grid editor templates misalignments ([b9bf599](https://github.com/telerik/kendo-theme-default/commit/b9bf599))
* **grid:** Change positioning of dirty cell TD in edit mode ([16635bd](https://github.com/telerik/kendo-theme-default/commit/16635bd))
* **grid:** column header text breaks out of narrow columns ([#754](https://github.com/telerik/kendo-theme-default/issues/754)) ([994c116](https://github.com/telerik/kendo-theme-default/commit/994c116))
* **grid:** columns misalignment when Bootstrap is used. ([f6c2828](https://github.com/telerik/kendo-theme-default/commit/f6c2828)), closes [telerik/kendo-theme-default#285](https://github.com/telerik/kendo-theme-default/issues/285)
* **grid:** do not resize columns when all their widths are set ([ca1050c](https://github.com/telerik/kendo-theme-default/commit/ca1050c)), closes [telerik/kendo-angular#689](https://github.com/telerik/kendo-angular/issues/689)
* **grid:** dragclue and grouping clue appearance ([a7d9c44](https://github.com/telerik/kendo-theme-default/commit/a7d9c44))
* **grid:** edit row buttons overlap ([4cb2711](https://github.com/telerik/kendo-theme-default/commit/4cb2711))
* **grid:** enable group ordering ([#795](https://github.com/telerik/kendo-theme-default/issues/795)) ([8156a3a](https://github.com/telerik/kendo-theme-default/commit/8156a3a))
* **grid:** expand/collapse icon is not centered ([599b8ff](https://github.com/telerik/kendo-theme-default/commit/599b8ff))
* **grid:** expand/collapse icon is not centered ([b6df0e2](https://github.com/telerik/kendo-theme-default/commit/b6df0e2))
* **grid:** filter button height ([b5639cd](https://github.com/telerik/kendo-theme-default/commit/b5639cd))
* **grid:** filter menu styles ([ca0d191](https://github.com/telerik/kendo-theme-default/commit/ca0d191))
* **grid:** filter row boolean filter appearance ([76924b9](https://github.com/telerik/kendo-theme-default/commit/76924b9))
* **grid:** filter row boolean operator styling ([da252ed](https://github.com/telerik/kendo-theme-default/commit/da252ed))
* **grid:** filter row components do not shrink ([f75a9a4](https://github.com/telerik/kendo-theme-default/commit/f75a9a4))
* **grid:** filter row height is incorrect in IE when height is set ([c68d26c](https://github.com/telerik/kendo-theme-default/commit/c68d26c))
* **grid:** filter row operators appearance ([ee32c9f](https://github.com/telerik/kendo-theme-default/commit/ee32c9f))
* **grid:** filter row span outside cells ([357d0b7](https://github.com/telerik/kendo-theme-default/commit/357d0b7)), closes [telerik/kendo-angular#830](https://github.com/telerik/kendo-angular/issues/830)
* **grid:** filter row styles ([9e41a82](https://github.com/telerik/kendo-theme-default/commit/9e41a82))
* **grid:** filter row styling ([#262](https://github.com/telerik/kendo-theme-default/issues/262)) ([0edba58](https://github.com/telerik/kendo-theme-default/commit/0edba58))
* **grid:** fix calc usage ([4f7cdd2](https://github.com/telerik/kendo-theme-default/commit/4f7cdd2))
* **grid:** Fix column resizing with virtual scrolling enabled ([16113fb](https://github.com/telerik/kendo-theme-default/commit/16113fb))
* **grid:** fix header layout for locked columns ([022070f](https://github.com/telerik/kendo-theme-default/commit/022070f))
* **grid:** fix header misalignment in Kendo UI for jQuery ([#816](https://github.com/telerik/kendo-theme-default/issues/816)) ([a66bf9c](https://github.com/telerik/kendo-theme-default/commit/a66bf9c))
* **grid:** grouping clue is small in pages that use Bootstrap ([fd0feb9](https://github.com/telerik/kendo-theme-default/commit/fd0feb9))
* **grid:** headers border color ([df33e0f](https://github.com/telerik/kendo-theme-default/commit/df33e0f))
* **grid:** headers misalignment. ([e13234f](https://github.com/telerik/kendo-theme-default/commit/e13234f)), closes [telerik/kendo-theme-default#284](https://github.com/telerik/kendo-theme-default/issues/284)
* **grid:** Improve column selection checkbox position in RTL styling ([a7bb3c8](https://github.com/telerik/kendo-theme-default/commit/a7bb3c8))
* **grid:** Improve dirty cell styling ([78bf826](https://github.com/telerik/kendo-theme-default/commit/78bf826))
* **grid:** improve drag clue layout ([2520770](https://github.com/telerik/kendo-theme-default/commit/2520770))
* **grid:** improve filter menu layout ([900d53e](https://github.com/telerik/kendo-theme-default/commit/900d53e))
* **grid:** Improve filter row styling for jQuery ([b1541a3](https://github.com/telerik/kendo-theme-default/commit/b1541a3))
* **grid:** improve grid group indicator appearance ([e2da9f7](https://github.com/telerik/kendo-theme-default/commit/e2da9f7))
* **grid:** Improve Grid popup editor checkbox alignment ([f8a5bd6](https://github.com/telerik/kendo-theme-default/commit/f8a5bd6))
* **grid:** improve layout calculation performance ([a098fcd](https://github.com/telerik/kendo-theme-default/commit/a098fcd))
* **grid:** Increase specificity of the menu styles ([2f9b010](https://github.com/telerik/kendo-theme-default/commit/2f9b010))
* **grid:** layout is broken in RTL when all column widths are set ([#577](https://github.com/telerik/kendo-theme-default/issues/577)) ([173220f](https://github.com/telerik/kendo-theme-default/commit/173220f)), closes [telerik/kendo-angular#689](https://github.com/telerik/kendo-angular/issues/689)
* **grid:** layout regression when no height is set ([#358](https://github.com/telerik/kendo-theme-default/issues/358)) ([096b5f2](https://github.com/telerik/kendo-theme-default/commit/096b5f2)), closes [telerik/kendo-angular#429](https://github.com/telerik/kendo-angular/issues/429)
* **grid:** multiheaders missing borders ([2c6ef3b](https://github.com/telerik/kendo-theme-default/commit/2c6ef3b)), closes [telerik/kendo-theme-default#298](https://github.com/telerik/kendo-theme-default/issues/298)
* **grid:** multiselect in filter row appearance ([19672ba](https://github.com/telerik/kendo-theme-default/commit/19672ba))
* **grid:** pager items placement. ([29a197a](https://github.com/telerik/kendo-theme-default/commit/29a197a)), closes [telerik/kendo-theme-default#321](https://github.com/telerik/kendo-theme-default/issues/321)
* **grid:** Prevent batch edit mode inputs from overflowing in RTL ([7b9462e](https://github.com/telerik/kendo-theme-default/commit/7b9462e))
* **grid:** prevent grid header from collapsing ([1c8267e](https://github.com/telerik/kendo-theme-default/commit/1c8267e))
* **grid:** prevent wraping and vertically align header column menu in IE ([55c1df1](https://github.com/telerik/kendo-theme-default/commit/55c1df1))
* **grid:** Recalculate edit mode textbox width ([f2354b5](https://github.com/telerik/kendo-theme-default/commit/f2354b5))
* **grid:** remove double border for browsers without scrollbar ([10c9980](https://github.com/telerik/kendo-theme-default/commit/10c9980))
* **grid:** Remove extra margin in header title in Firefox ([6a31326](https://github.com/telerik/kendo-theme-default/commit/6a31326))
* **grid:** remove extra padding in edit mode ([065c713](https://github.com/telerik/kendo-theme-default/commit/065c713))
* **grid:** Remove unnecessary checkbox styles (telerik/kendo[#7680](https://github.com/telerik/kendo-theme-default/issues/7680)) ([1f7abac](https://github.com/telerik/kendo-theme-default/commit/1f7abac))
* **grid:** selected alt rows must have the same shade as non-alt selected rows ([ce6ade1](https://github.com/telerik/kendo-theme-default/commit/ce6ade1))
* **grid:** Switch dirty cell overflow to visible ([f48d44c](https://github.com/telerik/kendo-theme-default/commit/f48d44c))
* **grid:** Tweak in-Grid edit mode widget width ([2474ea5](https://github.com/telerik/kendo-theme-default/commit/2474ea5))
* **grid:** update layout to be reused by other themes ([#230](https://github.com/telerik/kendo-theme-default/issues/230)) ([9a4838a](https://github.com/telerik/kendo-theme-default/commit/9a4838a))
* **grid:** use correct background-clip for grid ([decd830](https://github.com/telerik/kendo-theme-default/commit/decd830))
* **grid:** use flexbox chrome only when scrolling ([f2f5d92](https://github.com/telerik/kendo-theme-default/commit/f2f5d92))
* **grid:** virtual scrolling layout ([dca95a0](https://github.com/telerik/kendo-theme-default/commit/dca95a0)), closes [telerik/kendo-angular#449](https://github.com/telerik/kendo-angular/issues/449)
* **Grid:** Add validation tooltip styling ([1bfa082](https://github.com/telerik/kendo-theme-default/commit/1bfa082))
* **Grid:** Remove Batch edit mode TD padding ([7b77dab](https://github.com/telerik/kendo-theme-default/commit/7b77dab))
* **Grid:** Remove negative margins from input elements in inline edit mode ([e4fe447](https://github.com/telerik/kendo-theme-default/commit/e4fe447))
* **icons:** add aliases for portrait and landscape orientation icons ([cee4852](https://github.com/telerik/kendo-theme-default/commit/cee4852))
* **icons:** Add RTL styles for expand icon (telerik/kendo-ui-core[#3360](https://github.com/telerik/kendo-theme-default/issues/3360)) ([126ebf4](https://github.com/telerik/kendo-theme-default/commit/126ebf4))
* **icons:** update font to include KPI status and trend icons ([b3c0622](https://github.com/telerik/kendo-theme-default/commit/b3c0622))
* **icons:** update incorrect woff file path ([8aab17a](https://github.com/telerik/kendo-theme-default/commit/8aab17a))
* **icons:** use horizontal flipping for specifc rtl icons ([9c48e19](https://github.com/telerik/kendo-theme-default/commit/9c48e19))
* **icons:** use stronger selector for loading-icon ([#118](https://github.com/telerik/kendo-theme-default/issues/118)) ([38a6289](https://github.com/telerik/kendo-theme-default/commit/38a6289))
* **input:** handle special case of .k-input.k-textbox ([#114](https://github.com/telerik/kendo-theme-default/issues/114)) ([1c2285c](https://github.com/telerik/kendo-theme-default/commit/1c2285c))
* **input:** hide -ms-clear element [#105](https://github.com/telerik/kendo-theme-default/issues/105) ([58df7c5](https://github.com/telerik/kendo-theme-default/commit/58df7c5))
* **input:** use correct background-clip for input ([e2d3b5f](https://github.com/telerik/kendo-theme-default/commit/e2d3b5f))
* **inputs:** add missing focused styling to slider and switch ([4f72963](https://github.com/telerik/kendo-theme-default/commit/4f72963))
* **inputs:** apply font-size variable to simple textbox ([#853](https://github.com/telerik/kendo-theme-default/issues/853)) ([5f4dcc4](https://github.com/telerik/kendo-theme-default/commit/5f4dcc4))
* **inputs:** prioritize angular validation over HTML5 validation ([0adecba](https://github.com/telerik/kendo-theme-default/commit/0adecba)), closes [telerik/kendo-angular#511](https://github.com/telerik/kendo-angular/issues/511)
* **listbox:** use correct background-clip for listbox ([3fe2240](https://github.com/telerik/kendo-theme-default/commit/3fe2240))
* **ListBox:** Add vertical alignment addressing telerik/kendo[#7013](https://github.com/telerik/kendo-theme-default/issues/7013) ([7b0194e](https://github.com/telerik/kendo-theme-default/commit/7b0194e))
* **ListBox:** Set correct cursor for ListBox item ([fc9ce15](https://github.com/telerik/kendo-theme-default/commit/fc9ce15))
* **listview:** Add missing focused state, listview component to theme ([df4d3c9](https://github.com/telerik/kendo-theme-default/commit/df4d3c9))
* **loading:** small icon is invisible in Chrome 61 ([642a796](https://github.com/telerik/kendo-theme-default/commit/642a796))
* **loading-icon:** hide text inside loading icon ([d0f47f1](https://github.com/telerik/kendo-theme-default/commit/d0f47f1))
* **map:** Add 100% height to the Map's scroll container ([bc94117](https://github.com/telerik/kendo-theme-default/commit/bc94117))
* **map:** Add marker color ([383206d](https://github.com/telerik/kendo-theme-default/commit/383206d))
* **map:** use svg / font icon instead of image sprite ([491a1f4](https://github.com/telerik/kendo-theme-default/commit/491a1f4))
* **masked/numeric:** Correct position of invalid state icon in RTL ([c999ab2](https://github.com/telerik/kendo-theme-default/commit/c999ab2))
* **maskedtextbox:** allow width to be set on host element ([215890b](https://github.com/telerik/kendo-theme-default/commit/215890b))
* **maskedtextbox:** appearance ([f4a5de3](https://github.com/telerik/kendo-theme-default/commit/f4a5de3))
* **maskedtextbox:** missing border ([ffdfad1](https://github.com/telerik/kendo-theme-default/commit/ffdfad1)), closes [telerik/kendo-theme-default#331](https://github.com/telerik/kendo-theme-default/issues/331)
* **maskedtextbox:** styling refactoring ([8b7c4e5](https://github.com/telerik/kendo-theme-default/commit/8b7c4e5))
* **math:** handle zero values in add-* mixins ([dff792b](https://github.com/telerik/kendo-theme-default/commit/dff792b))
* **mediaplayer:** add opacity to toolbar ([8919a30](https://github.com/telerik/kendo-theme-default/commit/8919a30))
* **mediaplayer:** drag handle in volume slider is not correctly positioned ([80c09fa](https://github.com/telerik/kendo-theme-default/commit/80c09fa))
* **mediaplayer:** make track slider 100% wide ([2f65105](https://github.com/telerik/kendo-theme-default/commit/2f65105))
* **mediaplayer:** use correct padding for mediaplayer toolbar ([c39318b](https://github.com/telerik/kendo-theme-default/commit/c39318b))
* **mediaplyer:** use correct background-clip for mediaplayer ([ffd580a](https://github.com/telerik/kendo-theme-default/commit/ffd580a))
* **menu:** add missing styles for context menu wrapper ([a690733](https://github.com/telerik/kendo-theme-default/commit/a690733))
* **menu:** Add nowrap rule for Menu links ([f832b6b](https://github.com/telerik/kendo-theme-default/commit/f832b6b))
* **menu:** add styles for menu rtl ([e2fd491](https://github.com/telerik/kendo-theme-default/commit/e2fd491))
* **menu:** menu items must nost srink when scrolling is enabled ([3f7dd04](https://github.com/telerik/kendo-theme-default/commit/3f7dd04))
* **menu:** scroll arrows are missaligned ([a8019a7](https://github.com/telerik/kendo-theme-default/commit/a8019a7))
* **menu:** use correct background-clip for menu ([6ede243](https://github.com/telerik/kendo-theme-default/commit/6ede243))
* **multiselect:** add invalid state for Angular ([9af0ad4](https://github.com/telerik/kendo-theme-default/commit/9af0ad4))
* **multiselect:** align search bar after tokens ([582baa8](https://github.com/telerik/kendo-theme-default/commit/582baa8))
* **multiselect:** clear button position ([#576](https://github.com/telerik/kendo-theme-default/issues/576)) ([1ebac36](https://github.com/telerik/kendo-theme-default/commit/1ebac36))
* **multiselect:** do not inherit global .k-button width ([8ffb16c](https://github.com/telerik/kendo-theme-default/commit/8ffb16c))
* **multiselect:** extract border-radius to multiselect layout ([7d19828](https://github.com/telerik/kendo-theme-default/commit/7d19828))
* **multiselect:** hide loading icon ([1cbd639](https://github.com/telerik/kendo-theme-default/commit/1cbd639))
* **multiselect:** improve height of token with empty string telerik/kendo-ui-core[#3723](https://github.com/telerik/kendo-theme-default/issues/3723) ([f8713c4](https://github.com/telerik/kendo-theme-default/commit/f8713c4))
* **multiselect:** layout fixes ([467d8c1](https://github.com/telerik/kendo-theme-default/commit/467d8c1))
* **multiselect:** use correct background-clip for multiselect ([0f9ceaf](https://github.com/telerik/kendo-theme-default/commit/0f9ceaf))
* **multiselect:** use text cursor across focusable area ([8207562](https://github.com/telerik/kendo-theme-default/commit/8207562))
* **multiselect:** virtualized items are not styled ([2c9dfb8](https://github.com/telerik/kendo-theme-default/commit/2c9dfb8))
* **multiselect:** wrap text on long items ([f512790](https://github.com/telerik/kendo-theme-default/commit/f512790)), closes [#263](https://github.com/telerik/kendo-theme-default/issues/263)
* **multiselect:** wrong padding in RTL ([3ef4f71](https://github.com/telerik/kendo-theme-default/commit/3ef4f71))
* **multiselect:** wrong width in IE ([accf6ee](https://github.com/telerik/kendo-theme-default/commit/accf6ee))
* **notification:** add styles for rtl ([9ae4f92](https://github.com/telerik/kendo-theme-default/commit/9ae4f92))
* **notification:** Adjust close icon position ([#78](https://github.com/telerik/kendo-theme-default/issues/78)) ([#162](https://github.com/telerik/kendo-theme-default/issues/162)) ([83bcc85](https://github.com/telerik/kendo-theme-default/commit/83bcc85))
* **notification:** fix padding and close button position ([b5483f6](https://github.com/telerik/kendo-theme-default/commit/b5483f6))
* **notification:** improve close button position ([c5ae062](https://github.com/telerik/kendo-theme-default/commit/c5ae062))
* **notification:** Position close button ([#131](https://github.com/telerik/kendo-theme-default/issues/131)) ([4b2cb7f](https://github.com/telerik/kendo-theme-default/commit/4b2cb7f))
* **notification:** use small font size, introduce variables ([ba6a6b4](https://github.com/telerik/kendo-theme-default/commit/ba6a6b4))
* **numercitextbox:** use correct background-clip for numercitextbox ([1a29f67](https://github.com/telerik/kendo-theme-default/commit/1a29f67))
* **NumericTB:** Fix invalid state spinners color ([1605c01](https://github.com/telerik/kendo-theme-default/commit/1605c01))
* **numerictextbox:** Adjust flex of input fixing Edge weirdness ([d6a758a](https://github.com/telerik/kendo-theme-default/commit/d6a758a))
* **numerictextbox:** icons are not vertically aligned ([7a55a83](https://github.com/telerik/kendo-theme-default/commit/7a55a83))
* **numerictextbox:** k-select links alignment ([9b34417](https://github.com/telerik/kendo-theme-default/commit/9b34417))
* **numerictextbox:** remove invalid input border in Firefox ([08a2770](https://github.com/telerik/kendo-theme-default/commit/08a2770))
* **numerictextbox:** spinner icons alignment; fix select width ([ac4ad5f](https://github.com/telerik/kendo-theme-default/commit/ac4ad5f))
* **numerictextbox:** spinners active appearance ([50d5c8a](https://github.com/telerik/kendo-theme-default/commit/50d5c8a))
* **NumericTextbox:** Improve invalid state feedback icon positioning ([0dce499](https://github.com/telerik/kendo-theme-default/commit/0dce499))
* **pager:** disabled pager links should inherit color ([be5ed18](https://github.com/telerik/kendo-theme-default/commit/be5ed18))
* **pager:** use -padding- for pager ([aa00773](https://github.com/telerik/kendo-theme-default/commit/aa00773))
* **pager:** use flexbox to improve numeric pager align ([540f548](https://github.com/telerik/kendo-theme-default/commit/540f548))
* **panelbar:** style fixes ([#115](https://github.com/telerik/kendo-theme-default/issues/115)) ([67cb403](https://github.com/telerik/kendo-theme-default/commit/67cb403))
* **panelbar:** toggle arrow is in the wrong place for k1 ([2d325c3](https://github.com/telerik/kendo-theme-default/commit/2d325c3))
* **panelbar:** use correct background-clip for panelbar ([3f30da3](https://github.com/telerik/kendo-theme-default/commit/3f30da3))
* **panelbar:** use header variables for item padding ([#265](https://github.com/telerik/kendo-theme-default/issues/265)) ([2ab5c58](https://github.com/telerik/kendo-theme-default/commit/2ab5c58))
* **PanelBar:** update border color of subgroups ([ec933d0](https://github.com/telerik/kendo-theme-default/commit/ec933d0))
* **panels:** styling panels ([0e5c9b8](https://github.com/telerik/kendo-theme-default/commit/0e5c9b8))
* **pickers:** remove focus outline ([16064f3](https://github.com/telerik/kendo-theme-default/commit/16064f3))
* **pivot:** use correct background-clip for pivot ([e745463](https://github.com/telerik/kendo-theme-default/commit/e745463))
* **pivotgrid:** Add missing styles for pseudo elements in PDF export ([28714b1](https://github.com/telerik/kendo-theme-default/commit/28714b1))
* **pivotgrid:** Make grid cells non-wrapable ([defff41](https://github.com/telerik/kendo-theme-default/commit/defff41))
* **pivotgrid:** Remove flex from Grid container, add border-width ([2711bbc](https://github.com/telerik/kendo-theme-default/commit/2711bbc))
* **pivotgrid:** use correct KPI icons ([70b5a56](https://github.com/telerik/kendo-theme-default/commit/70b5a56))
* **popup:** apply popup styles to animation-container ([c6e24ca](https://github.com/telerik/kendo-theme-default/commit/c6e24ca))
* **popup:** no data template alignment in IE ([7263fb7](https://github.com/telerik/kendo-theme-default/commit/7263fb7))
* **popup:** style option label like regular items ([10c9d55](https://github.com/telerik/kendo-theme-default/commit/10c9d55))
* **popup:** use correct background-clip for popup ([1c0046c](https://github.com/telerik/kendo-theme-default/commit/1c0046c))
* **popup:** use specific variable for selected text ([fea14bd](https://github.com/telerik/kendo-theme-default/commit/fea14bd))
* **progressbar:** Add progress status background color ([#129](https://github.com/telerik/kendo-theme-default/issues/129)) ([3923c46](https://github.com/telerik/kendo-theme-default/commit/3923c46))
* **progressbar:** improve fluid progress ([62c6447](https://github.com/telerik/kendo-theme-default/commit/62c6447))
* **progressbar:** improve styling of chunked upload ([d38567a](https://github.com/telerik/kendo-theme-default/commit/d38567a))
* **progressbar:** imrpove selected state position [#764](https://github.com/telerik/kendo-theme-default/issues/764) ([702111f](https://github.com/telerik/kendo-theme-default/commit/702111f))
* **progressbar:** progressbar is missing gradient ([200bfef](https://github.com/telerik/kendo-theme-default/commit/200bfef))
* **progressbar:** use correct background-clip for progressbar ([7a69c77](https://github.com/telerik/kendo-theme-default/commit/7a69c77))
* **progressbar:** use correct border-radius ([ffeaf81](https://github.com/telerik/kendo-theme-default/commit/ffeaf81))
* **ripple:** contain ripple in its container ([5a65049](https://github.com/telerik/kendo-theme-default/commit/5a65049))
* **ripple:** improve effect in flat primary button ([b44fd95](https://github.com/telerik/kendo-theme-default/commit/b44fd95))
* **scheduler:** add spacing between text and icon in show full day ([9af6039](https://github.com/telerik/kendo-theme-default/commit/9af6039))
* **scheduler:** border-color is not properly inherited in FireFox and IE ([35bf322](https://github.com/telerik/kendo-theme-default/commit/35bf322))
* **scheduler:** expand scheduler to its content in IE ([cc190d9](https://github.com/telerik/kendo-theme-default/commit/cc190d9))
* **scheduler:** improve inner dimensions of scheduler ([2d6008f](https://github.com/telerik/kendo-theme-default/commit/2d6008f))
* **scheduler:** RTL appointment resizing issues ([48c33a6](https://github.com/telerik/kendo-theme-default/commit/48c33a6))
* **scheduler:** rtl buttons positioning and border radiuses ([6a5d273](https://github.com/telerik/kendo-theme-default/commit/6a5d273))
* **scheduler:** scope styles for recurrence editors ([bf61394](https://github.com/telerik/kendo-theme-default/commit/bf61394))
* **scheduler:** use correct background-clip for scheduler ([35eb805](https://github.com/telerik/kendo-theme-default/commit/35eb805))
* **scheduler:** wrong close button position in agenda view in rtl ([57aa9bc](https://github.com/telerik/kendo-theme-default/commit/57aa9bc))
* **scheduler:** wrong event actions position ([b75695e](https://github.com/telerik/kendo-theme-default/commit/b75695e))
* **scrollview:** add min flex width for pager ([ecf608d](https://github.com/telerik/kendo-theme-default/commit/ecf608d))
* **scrollview:** add static position for kendo-jquery-scrollview ([7c19eac](https://github.com/telerik/kendo-theme-default/commit/7c19eac))
* **scrollview:** add styles for kendo-jquery-scrollview ([7b464fe](https://github.com/telerik/kendo-theme-default/commit/7b464fe))
* **scrollview:** Add styles for Mobile widget (telerik/kendo[#6508](https://github.com/telerik/kendo-theme-default/issues/6508)) ([#125](https://github.com/telerik/kendo-theme-default/issues/125)) ([a014812](https://github.com/telerik/kendo-theme-default/commit/a014812))
* **scrollview:** add styles for scrollview pager for kendo-jquery ([fce1ebe](https://github.com/telerik/kendo-theme-default/commit/fce1ebe))
* **scrollview:** handle variable button size ([3168f58](https://github.com/telerik/kendo-theme-default/commit/3168f58))
* **scrollview:** tweak flex-grow for pager items ([59f55e5](https://github.com/telerik/kendo-theme-default/commit/59f55e5))
* **scrollview:** use flexbox for scrollview pager ([6bfa1c7](https://github.com/telerik/kendo-theme-default/commit/6bfa1c7))
* **scrollview:** wrong styling on prev/next arrows ([d5a0875](https://github.com/telerik/kendo-theme-default/commit/d5a0875)), closes [telerik/kendo-theme-default#342](https://github.com/telerik/kendo-theme-default/issues/342)
* **slider:** add d.ts file for slider ([#12](https://github.com/telerik/kendo-theme-default/issues/12)) ([83ce469](https://github.com/telerik/kendo-theme-default/commit/83ce469))
* **slider:** draghandle styling improvements ([c451203](https://github.com/telerik/kendo-theme-default/commit/c451203))
* **slider:** extract metrics variables ([#619](https://github.com/telerik/kendo-theme-default/issues/619)) ([fbf5628](https://github.com/telerik/kendo-theme-default/commit/fbf5628))
* **slider:** include component name in path to icons ([038bc1f](https://github.com/telerik/kendo-theme-default/commit/038bc1f))
* **slider:** interaction states. ([238dde0](https://github.com/telerik/kendo-theme-default/commit/238dde0)), closes [telerik/kendo-theme-default#225](https://github.com/telerik/kendo-theme-default/issues/225)
* **slider:** large ticks appearance ([095b645](https://github.com/telerik/kendo-theme-default/commit/095b645))
* **slider:** remove focus outline ([be18669](https://github.com/telerik/kendo-theme-default/commit/be18669))
* **slider:** revert regression in slider animation ([3e96000](https://github.com/telerik/kendo-theme-default/commit/3e96000))
* **slider:** rtl buttons styling ([862d561](https://github.com/telerik/kendo-theme-default/commit/862d561))
* **slider:** vertical ticks are misaligned ([c602975](https://github.com/telerik/kendo-theme-default/commit/c602975))
* **sortable:** apply default display to sortable container ([d1bfa95](https://github.com/telerik/kendo-theme-default/commit/d1bfa95))
* **sparkline:** remove border and padding from tooltip ([1f77425](https://github.com/telerik/kendo-theme-default/commit/1f77425))
* **splitter:** fix flipped collapse arrow in rtl ([9095247](https://github.com/telerik/kendo-theme-default/commit/9095247))
* **splitter:** Fix resize handle, pointer cursor telerik/kendo[#6508](https://github.com/telerik/kendo-theme-default/issues/6508) ([#122](https://github.com/telerik/kendo-theme-default/issues/122)) ([07dfc3a](https://github.com/telerik/kendo-theme-default/commit/07dfc3a))
* **splitter:** nested resize handles have the wrong background ([cfa1aab](https://github.com/telerik/kendo-theme-default/commit/cfa1aab))
* **splitter:** reverse panes in RTL mode ([bd373d3](https://github.com/telerik/kendo-theme-default/commit/bd373d3))
* **splitter:** splitter needs to be inline-flex in gantt ([1016d2a](https://github.com/telerik/kendo-theme-default/commit/1016d2a))
* **splitter:** use col/row-resize cursors ([d1bf7cd](https://github.com/telerik/kendo-theme-default/commit/d1bf7cd))
* **splitter:** use correct background-clip for splitter ([de4a4bb](https://github.com/telerik/kendo-theme-default/commit/de4a4bb))
* **splitter:** use correct colors for splitter normal and hover state ([e5a1f91](https://github.com/telerik/kendo-theme-default/commit/e5a1f91))
* **spreadhsheet:** Add styles for active cell within selection ([574c4ca](https://github.com/telerik/kendo-theme-default/commit/574c4ca))
* **spreadsheet:** add assumed box-sizing for buttons ([00d5fd6](https://github.com/telerik/kendo-theme-default/commit/00d5fd6))
* **spreadsheet:** add styles for formula bar icon ([282156f](https://github.com/telerik/kendo-theme-default/commit/282156f))
* **spreadsheet:** add styles for formula list ([73a2144](https://github.com/telerik/kendo-theme-default/commit/73a2144))
* **spreadsheet:** add styles for spreadsheet autofill range resizing ([f5dc736](https://github.com/telerik/kendo-theme-default/commit/f5dc736))
* **spreadsheet:** borders do not render in 2017.2.x ([7d6b34a](https://github.com/telerik/kendo-theme-default/commit/7d6b34a))
* **spreadsheet:** custom editor button not visible ([f6e3c91](https://github.com/telerik/kendo-theme-default/commit/f6e3c91))
* **spreadsheet:** fix more format layout ([d34f221](https://github.com/telerik/kendo-theme-default/commit/d34f221))
* **spreadsheet:** improve active cell borders by frozen cells telerik/kendo-ui-core[#3254](https://github.com/telerik/kendo-theme-default/issues/3254) ([44bcf30](https://github.com/telerik/kendo-theme-default/commit/44bcf30))
* **spreadsheet:** improve custom formatting dialog ([31f3092](https://github.com/telerik/kendo-theme-default/commit/31f3092))
* **spreadsheet:** improve formula syntax highlight ([dde4575](https://github.com/telerik/kendo-theme-default/commit/dde4575))
* **spreadsheet:** improve formula syntax highlight ([1bdb226](https://github.com/telerik/kendo-theme-default/commit/1bdb226))
* **spreadsheet:** improve spreadsheet dialog layout ([b9fa2ad](https://github.com/telerik/kendo-theme-default/commit/b9fa2ad))
* **spreadsheet:** improve spreadsheet toolbar and tabstrip layout ([615cd91](https://github.com/telerik/kendo-theme-default/commit/615cd91))
* **spreadsheet:** Missing indicator for Spreadsheet range resizing ([6922fd4](https://github.com/telerik/kendo-theme-default/commit/6922fd4))
* **spreadsheet:** page orientation icon in export dialog is not properly positioned ([67c4f2b](https://github.com/telerik/kendo-theme-default/commit/67c4f2b))
* **spreadsheet:** remove border radius of spreadsheet toolbar area ([f3dbdf9](https://github.com/telerik/kendo-theme-default/commit/f3dbdf9))
* **spreadsheet:** remove window customization from spreadsheet ([67fe651](https://github.com/telerik/kendo-theme-default/commit/67fe651))
* **spreadsheet:** replace hardcoded color for merged-cell by variable ([951e2bf](https://github.com/telerik/kendo-theme-default/commit/951e2bf))
* **spreadsheet:** use correct background-clip for spreadsheet ([92e9e27](https://github.com/telerik/kendo-theme-default/commit/92e9e27))
* **spreadsheet:** wrong custom editor button width ([1cb3bdd](https://github.com/telerik/kendo-theme-default/commit/1cb3bdd))
* **stockchart:** navigator handles layout ([64c46b2](https://github.com/telerik/kendo-theme-default/commit/64c46b2))
* **switch:** displaced switch handle ([7296a65](https://github.com/telerik/kendo-theme-default/commit/7296a65)), closes [telerik/kendo-theme-default#226](https://github.com/telerik/kendo-theme-default/issues/226)
* **switch:** improve labels positioning ([#758](https://github.com/telerik/kendo-theme-default/issues/758)) ([dd770bb](https://github.com/telerik/kendo-theme-default/commit/dd770bb))
* **switch:** metrics ([b604715](https://github.com/telerik/kendo-theme-default/commit/b604715))
* **switch:** missing border on macOS / retina displays ([#374](https://github.com/telerik/kendo-theme-default/issues/374)) ([a4728bf](https://github.com/telerik/kendo-theme-default/commit/a4728bf)), closes [telerik/kendo-theme-default#367](https://github.com/telerik/kendo-theme-default/issues/367)
* **switch:** off lable color and contrast ([67c8f35](https://github.com/telerik/kendo-theme-default/commit/67c8f35))
* **switch:** remove focus outline ([57a790a](https://github.com/telerik/kendo-theme-default/commit/57a790a))
* **switch:** use calc for mixed units ([39c52a9](https://github.com/telerik/kendo-theme-default/commit/39c52a9))
* **switch:** use correct background-clip for switch ([a28958a](https://github.com/telerik/kendo-theme-default/commit/a28958a))
* **switch:** use variable units for RTL labels ([#346](https://github.com/telerik/kendo-theme-default/issues/346)) ([4aed3e7](https://github.com/telerik/kendo-theme-default/commit/4aed3e7))
* **tabstrip:** add styles for closable tabstrip ([dbea750](https://github.com/telerik/kendo-theme-default/commit/dbea750))
* **tabstrip:** enable :normal and :hover state customization of individual tabstrip items ([0e0579a](https://github.com/telerik/kendo-theme-default/commit/0e0579a))
* **tabstrip:** improve alignment of close icon ([347e8ad](https://github.com/telerik/kendo-theme-default/commit/347e8ad))
* **tabstrip:** improve layout when wrapper height is set ([bb49170](https://github.com/telerik/kendo-theme-default/commit/bb49170)), closes [#495](https://github.com/telerik/kendo-theme-default/issues/495)
* **tabstrip:** set host display ([3a3f40d](https://github.com/telerik/kendo-theme-default/commit/3a3f40d))
* **tabstrip:** tabstrip scrolling ([#112](https://github.com/telerik/kendo-theme-default/issues/112)) ([f2e6b10](https://github.com/telerik/kendo-theme-default/commit/f2e6b10))
* **tabstrip:** tweak tabstrip styles ([#111](https://github.com/telerik/kendo-theme-default/issues/111)) ([bb5187b](https://github.com/telerik/kendo-theme-default/commit/bb5187b))
* **tabstrip:** use correct background-clip for tabstrip ([2f5292e](https://github.com/telerik/kendo-theme-default/commit/2f5292e))
* **tabstrip:** use scoped tabstrip variables for styling ([4e61adf](https://github.com/telerik/kendo-theme-default/commit/4e61adf))
* **textbox:** add RTL styles for floating label ([#842](https://github.com/telerik/kendo-theme-default/issues/842)) ([5639c7a](https://github.com/telerik/kendo-theme-default/commit/5639c7a))
* **textbox:** apply default width to textbox container ([0b8cd37](https://github.com/telerik/kendo-theme-default/commit/0b8cd37))
* **textbox:** disallow selection of floating label ([54df3e1](https://github.com/telerik/kendo-theme-default/commit/54df3e1))
* **textbox:** inherit kendo-textbox-container size ([e448eac](https://github.com/telerik/kendo-theme-default/commit/e448eac))
* **textbox:** use classes for styling ([4601174](https://github.com/telerik/kendo-theme-default/commit/4601174))
* **textbox:** workaround IE11 limitation ([1cfc1a9](https://github.com/telerik/kendo-theme-default/commit/1cfc1a9))
* **timepicker:** add time list focus state ([#656](https://github.com/telerik/kendo-theme-default/issues/656)) ([e852cda](https://github.com/telerik/kendo-theme-default/commit/e852cda))
* **timepicker:** align time list on MacOS ([f8b9de7](https://github.com/telerik/kendo-theme-default/commit/f8b9de7))
* **timepicker:** update highlight border-color ([7dd890d](https://github.com/telerik/kendo-theme-default/commit/7dd890d))
* **timepicker:** update time list focus state ([#662](https://github.com/telerik/kendo-theme-default/issues/662)) ([aeccee5](https://github.com/telerik/kendo-theme-default/commit/aeccee5))
* **toolbar:** fix overflow button position in RTL telerik/kendo[#8009](https://github.com/telerik/kendo-theme-default/issues/8009) ([2389a89](https://github.com/telerik/kendo-theme-default/commit/2389a89))
* **toolbar:** improve disabled appearance of button telerik/kendo-ui-core[#3684](https://github.com/telerik/kendo-theme-default/issues/3684) ([1d2b3f3](https://github.com/telerik/kendo-theme-default/commit/1d2b3f3))
* **toolbar:** prevent overflowing templates content [#784](https://github.com/telerik/kendo-theme-default/issues/784) ([1e556c5](https://github.com/telerik/kendo-theme-default/commit/1e556c5))
* **toolbar:** use correct background-clip for toolbar ([bb3fa99](https://github.com/telerik/kendo-theme-default/commit/bb3fa99))
* **toolbar:** use correct colors for toggled button ([d53c49f](https://github.com/telerik/kendo-theme-default/commit/d53c49f))
* **toolbar:** wrong split button focus and expand state ([37e45ea](https://github.com/telerik/kendo-theme-default/commit/37e45ea))
* **tooltip:** add callout styles ([9882ec1](https://github.com/telerik/kendo-theme-default/commit/9882ec1))
* **tooltip:** use contrast-wcag for tooltip ([cc86875](https://github.com/telerik/kendo-theme-default/commit/cc86875))
* **tooltip:** use correct padding for collapsible tooltip ([844037f](https://github.com/telerik/kendo-theme-default/commit/844037f))
* **tooltip:** use correct padding for collapsible tooltip ([2ad3894](https://github.com/telerik/kendo-theme-default/commit/2ad3894))
* **Treelist:** Add k-display-block class to handle frozen columns ([98b891d](https://github.com/telerik/kendo-theme-default/commit/98b891d))
* **treeview:** add treeview rtl styles ([40699b5](https://github.com/telerik/kendo-theme-default/commit/40699b5))
* **treeview:** hide scrollbars during a node expansion ([d6541f4](https://github.com/telerik/kendo-theme-default/commit/d6541f4))
* **treeview:** reduce spacing between checkbox and item text ([0556e46](https://github.com/telerik/kendo-theme-default/commit/0556e46))
* **treeview:** remove outline when focus is on items ([b062f16](https://github.com/telerik/kendo-theme-default/commit/b062f16))
* **treeview:** treeview alignment ([#116](https://github.com/telerik/kendo-theme-default/issues/116)) ([4dce864](https://github.com/telerik/kendo-theme-default/commit/4dce864))
* **treeview:** update item layout ([#259](https://github.com/telerik/kendo-theme-default/issues/259)) ([28d3411](https://github.com/telerik/kendo-theme-default/commit/28d3411))
* **treeview:** use correct background-clip for treeview ([90b7960](https://github.com/telerik/kendo-theme-default/commit/90b7960))
* **treeview:** use correct border radius and box shadow for treeview items ([22a75bc](https://github.com/telerik/kendo-theme-default/commit/22a75bc))
* **treeview:** use correct metrics for treeview ([80c8215](https://github.com/telerik/kendo-theme-default/commit/80c8215))
* **upload:** add RTL styling ([#245](https://github.com/telerik/kendo-theme-default/issues/245)) ([fc49b80](https://github.com/telerik/kendo-theme-default/commit/fc49b80))
* **upload:** decrease metric of file list ([441c163](https://github.com/telerik/kendo-theme-default/commit/441c163))
* **upload:** extract metrics variables ([d9db8d3](https://github.com/telerik/kendo-theme-default/commit/d9db8d3))
* **upload:** failed to upload item icon color ([575cd8b](https://github.com/telerik/kendo-theme-default/commit/575cd8b))
* **upload:** improve metrics of toolbar ([a8e8fe7](https://github.com/telerik/kendo-theme-default/commit/a8e8fe7))
* **upload:** incorrect icon size when used with Bootstrap ([47fe0e7](https://github.com/telerik/kendo-theme-default/commit/47fe0e7)), closes [telerik/kendo-angular-upload#39](https://github.com/telerik/kendo-angular-upload/issues/39) [#151](https://github.com/telerik/kendo-theme-default/issues/151)
* **upload:** increase empty space after file name for chunk upload telerik/kendo-ui-core[#3021](https://github.com/telerik/kendo-theme-default/issues/3021) ([b51d5b7](https://github.com/telerik/kendo-theme-default/commit/b51d5b7))
* **upload:** move some metrics to the theme file ([8b3d214](https://github.com/telerik/kendo-theme-default/commit/8b3d214))
* **upload:** trim long file names ([aaa4ff7](https://github.com/telerik/kendo-theme-default/commit/aaa4ff7))
* **upload:** un-nest k-upload button selector ([547ef6a](https://github.com/telerik/kendo-theme-default/commit/547ef6a))
* **upload:** use correct background-clip for upload ([51ccb48](https://github.com/telerik/kendo-theme-default/commit/51ccb48))
* **upload:** visual glitches ([#97](https://github.com/telerik/kendo-theme-default/issues/97)) ([4d00a64](https://github.com/telerik/kendo-theme-default/commit/4d00a64)), closes [telerik/kendo-theme-default#95](https://github.com/telerik/kendo-theme-default/issues/95)
* **validation:** allow nesting of validation tooltip in kendo-popup ([874d572](https://github.com/telerik/kendo-theme-default/commit/874d572))
* **validation:** check ng-dirty and ng-touched before showing errors ([35cef0d](https://github.com/telerik/kendo-theme-default/commit/35cef0d)), closes [#127](https://github.com/telerik/kendo-theme-default/issues/127)
* **validator:** validation message is not aligned ([3f1e21a](https://github.com/telerik/kendo-theme-default/commit/3f1e21a))
* **window:** add styles for content frame ([36bbcfa](https://github.com/telerik/kendo-theme-default/commit/36bbcfa)), closes [#510](https://github.com/telerik/kendo-theme-default/issues/510)
* **window:** add styles for predefined dialog prompt ([454abd7](https://github.com/telerik/kendo-theme-default/commit/454abd7))
* **window:** Adjust header height telerik/kendo[#6508](https://github.com/telerik/kendo-theme-default/issues/6508) ([#100](https://github.com/telerik/kendo-theme-default/issues/100)) ([5fa3cf0](https://github.com/telerik/kendo-theme-default/commit/5fa3cf0))
* **window:** align content with title text ([581f650](https://github.com/telerik/kendo-theme-default/commit/581f650))
* **window:** fix title height for Bootstrap skin [#752](https://github.com/telerik/kendo-theme-default/issues/752) ([9045a54](https://github.com/telerik/kendo-theme-default/commit/9045a54))
* remove inappropriate rule ([a7664f6](https://github.com/telerik/kendo-theme-default/commit/a7664f6))
* remove inherited background from pickers ([212bae6](https://github.com/telerik/kendo-theme-default/commit/212bae6))
* remove native focus outline from popup items ([62cb150](https://github.com/telerik/kendo-theme-default/commit/62cb150))
* remove negative margin of action buttons ([abe8f5f](https://github.com/telerik/kendo-theme-default/commit/abe8f5f))
* remove outdated rule ([956985d](https://github.com/telerik/kendo-theme-default/commit/956985d))
* remove redundant font formats ([5bdc800](https://github.com/telerik/kendo-theme-default/commit/5bdc800))
* remove slider outline ([3075766](https://github.com/telerik/kendo-theme-default/commit/3075766))
* remove switch outline ([09c3a00](https://github.com/telerik/kendo-theme-default/commit/09c3a00))
* remove text-decoration of links ([b402fc5](https://github.com/telerik/kendo-theme-default/commit/b402fc5)), closes [telerik/kendo-angular-scrollview#49](https://github.com/telerik/kendo-angular-scrollview/issues/49)
* remove unnecessary variable ([2643b98](https://github.com/telerik/kendo-theme-default/commit/2643b98))
* remove widgets focus outline ([e19501d](https://github.com/telerik/kendo-theme-default/commit/e19501d))
* rename dialog slide-in effect ([92f90f0](https://github.com/telerik/kendo-theme-default/commit/92f90f0))
* rename input-container to textbox-container, use k-state-empty class ([4c03d85](https://github.com/telerik/kendo-theme-default/commit/4c03d85))
* resolve ruby sass error ([8071100](https://github.com/telerik/kendo-theme-default/commit/8071100))
* reuse common module webpack config for building theme ([92b267c](https://github.com/telerik/kendo-theme-default/commit/92b267c))
* revert 2ff88d3 ([ee1af32](https://github.com/telerik/kendo-theme-default/commit/ee1af32))
* RTL styles for the Slider and Switch ([#344](https://github.com/telerik/kendo-theme-default/issues/344)) ([8f0b432](https://github.com/telerik/kendo-theme-default/commit/8f0b432))
* set block display for dialog host elements ([abc8437](https://github.com/telerik/kendo-theme-default/commit/abc8437))
* set display type of panelbar to work with ng2 host elements ([c460011](https://github.com/telerik/kendo-theme-default/commit/c460011))
* sparkline tooltip marker appearance. ([27d1b72](https://github.com/telerik/kendo-theme-default/commit/27d1b72)), closes [telerik/kendo-theme-default#249](https://github.com/telerik/kendo-theme-default/issues/249)
* split button in normal state misses borders, bg and border-radius ([a953400](https://github.com/telerik/kendo-theme-default/commit/a953400))
* split button in normal state misses borders, bg and border-radius ([b045e71](https://github.com/telerik/kendo-theme-default/commit/b045e71))
* style new overflow wrapper telerik/kendo-ui-core[#3254](https://github.com/telerik/kendo-theme-default/issues/3254) ([1ce1415](https://github.com/telerik/kendo-theme-default/commit/1ce1415))
* tab hover styles ([c76e205](https://github.com/telerik/kendo-theme-default/commit/c76e205))
* tabs alignment in right/left positions ([54e5577](https://github.com/telerik/kendo-theme-default/commit/54e5577))
* tabstrip active tab border ([5961f0d](https://github.com/telerik/kendo-theme-default/commit/5961f0d))
* textbox focused box-shadow ([75f9011](https://github.com/telerik/kendo-theme-default/commit/75f9011))
* title bar overflows dialog ([3347a45](https://github.com/telerik/kendo-theme-default/commit/3347a45))
* tooltip validation appearance ([96fb5de](https://github.com/telerik/kendo-theme-default/commit/96fb5de))
* trim down npm package, provide dist files ([cf6c77a](https://github.com/telerik/kendo-theme-default/commit/cf6c77a))
* Tweak pressed button shadow ([#172](https://github.com/telerik/kendo-theme-default/issues/172)) ([#210](https://github.com/telerik/kendo-theme-default/issues/210)) ([476d504](https://github.com/telerik/kendo-theme-default/commit/476d504))
* unify design of dialog buttons and action buttons ([e54a288](https://github.com/telerik/kendo-theme-default/commit/e54a288))
* update bootstrap dependency ([#765](https://github.com/telerik/kendo-theme-default/issues/765)) ([b53effc](https://github.com/telerik/kendo-theme-default/commit/b53effc))
* update Bootstrap dependency to v4 official ([e96f66b](https://github.com/telerik/kendo-theme-default/commit/e96f66b))
* update dialog action buttons layout; update dialog titlebar sizing ([d87857d](https://github.com/telerik/kendo-theme-default/commit/d87857d))
* update dropdowns transtions ([da3ac97](https://github.com/telerik/kendo-theme-default/commit/da3ac97))
* update license ([8e9fbe6](https://github.com/telerik/kendo-theme-default/commit/8e9fbe6))
* update panelbar states colors ([085bb05](https://github.com/telerik/kendo-theme-default/commit/085bb05))
* update upload styling to match the new design. ([642d3f4](https://github.com/telerik/kendo-theme-default/commit/642d3f4)), closes [telerik/kendo-theme-default#152](https://github.com/telerik/kendo-theme-default/issues/152)
* upload action buttons styling; disabled upload styling ([f58863e](https://github.com/telerik/kendo-theme-default/commit/f58863e))
* upload header background ([e16bf1f](https://github.com/telerik/kendo-theme-default/commit/e16bf1f))
* upload status icon margin ([c0e4cdf](https://github.com/telerik/kendo-theme-default/commit/c0e4cdf))
* use .k-fieldset class to style fieldsets ([#146](https://github.com/telerik/kendo-theme-default/issues/146)) ([e94b839](https://github.com/telerik/kendo-theme-default/commit/e94b839)), closes [telerik/kendo-angular2#193](https://github.com/telerik/kendo-angular2/issues/193)
* use calc to allow mixing of rem/px ([#166](https://github.com/telerik/kendo-theme-default/issues/166)) ([7b07f4b](https://github.com/telerik/kendo-theme-default/commit/7b07f4b))
* use contrast-wcag for variables and grid ([bffe632](https://github.com/telerik/kendo-theme-default/commit/bffe632))
* use correct line-height in autocomplete ([a4bdb22](https://github.com/telerik/kendo-theme-default/commit/a4bdb22))
* use deeper path to hint widget for proper font path ([723bd80](https://github.com/telerik/kendo-theme-default/commit/723bd80))
* use flexbox for dialog centering ([307fad0](https://github.com/telerik/kendo-theme-default/commit/307fad0)), closes [telerik/kendo-angular#227](https://github.com/telerik/kendo-angular/issues/227)
* use icon-size instead of mixed units in checkboxes ([8ef1684](https://github.com/telerik/kendo-theme-default/commit/8ef1684))
* use improved border-radius mixin ([#516](https://github.com/telerik/kendo-theme-default/issues/516)) ([c5fa5a5](https://github.com/telerik/kendo-theme-default/commit/c5fa5a5))
* use setting for border-radius in respective mixins ([57686e7](https://github.com/telerik/kendo-theme-default/commit/57686e7))
* use setting for box-shadow in respective mixins ([a729c5c](https://github.com/telerik/kendo-theme-default/commit/a729c5c))
* use setting for linear-gradient in respective mixins ([6e4b92a](https://github.com/telerik/kendo-theme-default/commit/6e4b92a))
* use transparent border for dialog actions ([a7172b3](https://github.com/telerik/kendo-theme-default/commit/a7172b3))
* variables not inlined into calc blocks ([dd17363](https://github.com/telerik/kendo-theme-default/commit/dd17363))
* vertical align chart shared tooltip marker ([#43](https://github.com/telerik/kendo-theme-default/issues/43)) ([a646c54](https://github.com/telerik/kendo-theme-default/commit/a646c54))
* **window:** reducing title height [#752](https://github.com/telerik/kendo-theme-default/issues/752) ([32244f3](https://github.com/telerik/kendo-theme-default/commit/32244f3))
* visual glitches ([4d4d178](https://github.com/telerik/kendo-theme-default/commit/4d4d178))
* **window:** set layout for resize handles ([f9a29ce](https://github.com/telerik/kendo-theme-default/commit/f9a29ce))
* wrong appearance of the overflow button in editor toolbar ([36c6cc2](https://github.com/telerik/kendo-theme-default/commit/36c6cc2))
* wrong borders in grid ([dd5bcfa](https://github.com/telerik/kendo-theme-default/commit/dd5bcfa))
* wrong colorpcker metrics and states [#174](https://github.com/telerik/kendo-theme-default/issues/174) ([b18b5a5](https://github.com/telerik/kendo-theme-default/commit/b18b5a5))
* wrong styles of toolbar buttons ([1e3965e](https://github.com/telerik/kendo-theme-default/commit/1e3965e))
* wrong styles of toolbar buttons ([389532e](https://github.com/telerik/kendo-theme-default/commit/389532e))
* **window:** streamline window and dialog layout ([a60b9ab](https://github.com/telerik/kendo-theme-default/commit/a60b9ab))
* wrong titleless window selector ([bda4a3b](https://github.com/telerik/kendo-theme-default/commit/bda4a3b))


### Features

* add animated loading indicator ([#77](https://github.com/telerik/kendo-theme-default/issues/77)) ([1e56d09](https://github.com/telerik/kendo-theme-default/commit/1e56d09)), closes [telerik/kendo-theme-default#65](https://github.com/telerik/kendo-theme-default/issues/65)
* add background-color transitions ([12337c6](https://github.com/telerik/kendo-theme-default/commit/12337c6))
* add chart donut center template styles ([edec094](https://github.com/telerik/kendo-theme-default/commit/edec094))
* add classes for styling forms ([#391](https://github.com/telerik/kendo-theme-default/issues/391)) ([f9850b7](https://github.com/telerik/kendo-theme-default/commit/f9850b7))
* add default font-size to components ([6ec271d](https://github.com/telerik/kendo-theme-default/commit/6ec271d)), closes [#33](https://github.com/telerik/kendo-theme-default/issues/33)
* add gantt styles ([e041966](https://github.com/telerik/kendo-theme-default/commit/e041966))
* add grid toolbar styling ([5a57e69](https://github.com/telerik/kendo-theme-default/commit/5a57e69))
* add icon font ([7e4cf6a](https://github.com/telerik/kendo-theme-default/commit/7e4cf6a))
* add layout fixes file for IE9 ([349bbce](https://github.com/telerik/kendo-theme-default/commit/349bbce))
* Add Listbox styles ([08072c6](https://github.com/telerik/kendo-theme-default/commit/08072c6))
* add panelbar styles ([3d0e671](https://github.com/telerik/kendo-theme-default/commit/3d0e671))
* add pivotgrid styles ([#126](https://github.com/telerik/kendo-theme-default/issues/126)) ([eb7177f](https://github.com/telerik/kendo-theme-default/commit/eb7177f))
* add progressbar styles ([99978d1](https://github.com/telerik/kendo-theme-default/commit/99978d1))
* add ripple effect styles ([e1e15f1](https://github.com/telerik/kendo-theme-default/commit/e1e15f1))
* add slider styles ([1b27dce](https://github.com/telerik/kendo-theme-default/commit/1b27dce))
* add styles for gauges ([d67cfa0](https://github.com/telerik/kendo-theme-default/commit/d67cfa0))
* add styles for grid with virtual scrolling enabled ([ad33589](https://github.com/telerik/kendo-theme-default/commit/ad33589))
* add styling for chart selection ([#46](https://github.com/telerik/kendo-theme-default/issues/46)) ([392a480](https://github.com/telerik/kendo-theme-default/commit/392a480))
* add switch styles ([0b4e40d](https://github.com/telerik/kendo-theme-default/commit/0b4e40d))
* add variables for styling checkboxes ([d9316e8](https://github.com/telerik/kendo-theme-default/commit/d9316e8))
* add variables for styling dialog and window ([#574](https://github.com/telerik/kendo-theme-default/issues/574)) ([fb84a4f](https://github.com/telerik/kendo-theme-default/commit/fb84a4f))
* add variables to disabled mixin ([c76535a](https://github.com/telerik/kendo-theme-default/commit/c76535a))
* allow changing of checkbox/radio size ([0f1b4cd](https://github.com/telerik/kendo-theme-default/commit/0f1b4cd))
* bare button class ([#188](https://github.com/telerik/kendo-theme-default/issues/188)) ([eab2862](https://github.com/telerik/kendo-theme-default/commit/eab2862))
* basic window styling ([1a43eb9](https://github.com/telerik/kendo-theme-default/commit/1a43eb9))
* charts package ([a5ff54d](https://github.com/telerik/kendo-theme-default/commit/a5ff54d))
* charts package ([4b6e382](https://github.com/telerik/kendo-theme-default/commit/4b6e382))
* content in panelbar headers should not be selectable ([#29](https://github.com/telerik/kendo-theme-default/issues/29)) ([dd2035b](https://github.com/telerik/kendo-theme-default/commit/dd2035b))
* define active state to allow its use in widgets ([de28454](https://github.com/telerik/kendo-theme-default/commit/de28454))
* define classes for icons different font-size ([#28](https://github.com/telerik/kendo-theme-default/issues/28)) ([671b192](https://github.com/telerik/kendo-theme-default/commit/671b192))
* enable integration with bootstrap forms ([91d5969](https://github.com/telerik/kendo-theme-default/commit/91d5969))
* enable release channels ([2b9f436](https://github.com/telerik/kendo-theme-default/commit/2b9f436))
* Example component CSS ([da1bf90](https://github.com/telerik/kendo-theme-default/commit/da1bf90))
* export variable for icon sizing ([610b08e](https://github.com/telerik/kendo-theme-default/commit/610b08e))
* import basic styles from kendo ([4d9452b](https://github.com/telerik/kendo-theme-default/commit/4d9452b))
* **animation:** change animation container position to fixed ([#45](https://github.com/telerik/kendo-theme-default/issues/45)) ([2c55158](https://github.com/telerik/kendo-theme-default/commit/2c55158))
* **Animation:** Add a toggle effect for a single element animation ([66f01a7](https://github.com/telerik/kendo-theme-default/commit/66f01a7))
* **Animation:** Add Animation effects CSS classes ([2459a09](https://github.com/telerik/kendo-theme-default/commit/2459a09))
* **Animation:** Add appear animation variation of current animation effects ([304549f](https://github.com/telerik/kendo-theme-default/commit/304549f))
* **Animation:** Add slide down/up animation effect ([486edbf](https://github.com/telerik/kendo-theme-default/commit/486edbf))
* **Animation:** Import animation styles into main entry point ([885038e](https://github.com/telerik/kendo-theme-default/commit/885038e))
* **animation-effects:** add horizontal slide effects ([#10](https://github.com/telerik/kendo-theme-default/issues/10)) ([069e272](https://github.com/telerik/kendo-theme-default/commit/069e272))
* **badge:** add styles for badges telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([97cc16d](https://github.com/telerik/kendo-theme-default/commit/97cc16d))
* **badge:** improve styles using variables telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([e83ccc6](https://github.com/telerik/kendo-theme-default/commit/e83ccc6))
* **badge:** prevent expanding badge more than the button width telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([97bf50c](https://github.com/telerik/kendo-theme-default/commit/97bf50c))
* **button:** improve common styles for adding bare button in Bootstrap ([e1b9a0a](https://github.com/telerik/kendo-theme-default/commit/e1b9a0a))
* **buttongroup:** add styles for responsive buttongroup ([#290](https://github.com/telerik/kendo-theme-default/issues/290)) ([f73c892](https://github.com/telerik/kendo-theme-default/commit/f73c892))
* **buttongroup:** add styles for responsive buttongroup ([#290](https://github.com/telerik/kendo-theme-default/issues/290)) ([0941ef6](https://github.com/telerik/kendo-theme-default/commit/0941ef6))
* **buttonGroup:** add styles for button group telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([227e96e](https://github.com/telerik/kendo-theme-default/commit/227e96e))
* **buttonGroup:** improve border radius after improving rendering telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([1f2d915](https://github.com/telerik/kendo-theme-default/commit/1f2d915))
* **buttons:** Add new design styles and improvements ([#91](https://github.com/telerik/kendo-theme-default/issues/91)) ([6ae48ba](https://github.com/telerik/kendo-theme-default/commit/6ae48ba))
* **checkbox:** allow changing of indeterminate state ([9c58b9b](https://github.com/telerik/kendo-theme-default/commit/9c58b9b))
* **checkbox:** introduce variables for checkbox sizing ([543e8d3](https://github.com/telerik/kendo-theme-default/commit/543e8d3))
* **dateinput:** add dateinput ([#128](https://github.com/telerik/kendo-theme-default/issues/128)) ([8922425](https://github.com/telerik/kendo-theme-default/commit/8922425))
* **DateInput:** Add invalid state styles ([5df409f](https://github.com/telerik/kendo-theme-default/commit/5df409f))
* **DatePicker:** Add styles for embedded DateInput - invalid state ([3c4f527](https://github.com/telerik/kendo-theme-default/commit/3c4f527))
* **datetimepicker:** Add invalid state styles ([9aea3f9](https://github.com/telerik/kendo-theme-default/commit/9aea3f9))
* **dropdowns:** add styling for invalid state ([de91d7a](https://github.com/telerik/kendo-theme-default/commit/de91d7a))
* **fade-animation:** rename fade-in to fade. Add fade out effect ([#8](https://github.com/telerik/kendo-theme-default/issues/8)) ([c42632d](https://github.com/telerik/kendo-theme-default/commit/c42632d))
* **forms:** add styling for integration with Bootstrap form-control-sm and form-control-lg classes ([f435f18](https://github.com/telerik/kendo-theme-default/commit/f435f18))
* **grid:** add grid pdf export styling ([#368](https://github.com/telerik/kendo-theme-default/issues/368)) ([e5e659f](https://github.com/telerik/kendo-theme-default/commit/e5e659f))
* **grid:** add rtl styling ([4e9e59a](https://github.com/telerik/kendo-theme-default/commit/4e9e59a))
* **grid:** Add styles for column selection checkboxes ([c4e0f09](https://github.com/telerik/kendo-theme-default/commit/c4e0f09))
* **grid:** Add styles for opaque loading mask ([c8dd437](https://github.com/telerik/kendo-theme-default/commit/c8dd437))
* **grid:** Add styles for sorted column shading ([b72e060](https://github.com/telerik/kendo-theme-default/commit/b72e060))
* **grid:** Improve Grid editor checkbox styling (telerik/kendo[#6747](https://github.com/telerik/kendo-theme-default/issues/6747)) ([5bcd4da](https://github.com/telerik/kendo-theme-default/commit/5bcd4da))
* **grid:** resize when height is set on container ([#400](https://github.com/telerik/kendo-theme-default/issues/400)) ([8b232a8](https://github.com/telerik/kendo-theme-default/commit/8b232a8))
* **grid:** simplification of formula for column menu margin ([78d96f3](https://github.com/telerik/kendo-theme-default/commit/78d96f3))
* **Grid:** Add column sorting order styles ([e746cdc](https://github.com/telerik/kendo-theme-default/commit/e746cdc))
* import button styles ([5c68023](https://github.com/telerik/kendo-theme-default/commit/5c68023))
* import calendar styles ([95e2b86](https://github.com/telerik/kendo-theme-default/commit/95e2b86))
* Improve popup styling for use in DropDownButton ([ff79685](https://github.com/telerik/kendo-theme-default/commit/ff79685))
* introduce dependencies between widgets ([dd6447e](https://github.com/telerik/kendo-theme-default/commit/dd6447e))
* loading indicator improvements ([#366](https://github.com/telerik/kendo-theme-default/issues/366)) ([e4c6b59](https://github.com/telerik/kendo-theme-default/commit/e4c6b59)), closes [telerik/kendo-theme-default#365](https://github.com/telerik/kendo-theme-default/issues/365)
* prefix class names, stop using css modules ([307eaaa](https://github.com/telerik/kendo-theme-default/commit/307eaaa))
* remove box-sizing override ([0fbeeff](https://github.com/telerik/kendo-theme-default/commit/0fbeeff))
* styles for calendar ([433ddfd](https://github.com/telerik/kendo-theme-default/commit/433ddfd))
* **timepicker:** Add invalid state styles ([4d1f5fc](https://github.com/telerik/kendo-theme-default/commit/4d1f5fc))
* styling for grid grouping ([#54](https://github.com/telerik/kendo-theme-default/issues/54)) ([47f3cd4](https://github.com/telerik/kendo-theme-default/commit/47f3cd4))
* **icons:** allow icons to have modifiers ([8a586da](https://github.com/telerik/kendo-theme-default/commit/8a586da)), closes [#806](https://github.com/telerik/kendo-theme-default/issues/806)
* **ListBox:** Add drag and drop styling ([01044fb](https://github.com/telerik/kendo-theme-default/commit/01044fb))
* **MaskedTextbox:** Add separate styles for MTB, invalid state (telerik/kendo[#6825](https://github.com/telerik/kendo-theme-default/issues/6825)) ([0769b10](https://github.com/telerik/kendo-theme-default/commit/0769b10))
* **mediaplayer:** styles for mediaplayer ([a1f1f13](https://github.com/telerik/kendo-theme-default/commit/a1f1f13))
* **menu:** add styling for menu scrolling ([5ae60f0](https://github.com/telerik/kendo-theme-default/commit/5ae60f0))
* **NumericTextbox:** Add invalid state styles(telerik/kendo[#6796](https://github.com/telerik/kendo-theme-default/issues/6796)) ([2ea8f85](https://github.com/telerik/kendo-theme-default/commit/2ea8f85))
* **popup:** introduce a popup styles package ([#18](https://github.com/telerik/kendo-theme-default/issues/18)) ([d89eee4](https://github.com/telerik/kendo-theme-default/commit/d89eee4))
* **radiobutton:** change dot positioning ([fe25c90](https://github.com/telerik/kendo-theme-default/commit/fe25c90))
* **slider:** enable transitions through class ([63db42e](https://github.com/telerik/kendo-theme-default/commit/63db42e))
* **slider:** transition drag handle state ([d8a519a](https://github.com/telerik/kendo-theme-default/commit/d8a519a))
* **splitter:** add styles for flexbox splitter ([f3eb2b0](https://github.com/telerik/kendo-theme-default/commit/f3eb2b0))
* **style:** add lint and commit message validation ([1c648e7](https://github.com/telerik/kendo-theme-default/commit/1c648e7))
* **textbox:** introduce textbox-line-height variable ([536bb3c](https://github.com/telerik/kendo-theme-default/commit/536bb3c))
* **timepicker:** add initial styling ([#640](https://github.com/telerik/kendo-theme-default/issues/640)) ([e8fa4d6](https://github.com/telerik/kendo-theme-default/commit/e8fa4d6))
* **upload:** add correct icon to chunk upload functionality ([72c2c03](https://github.com/telerik/kendo-theme-default/commit/72c2c03))
* **upload:** add styles for focused state ([8f6dc6c](https://github.com/telerik/kendo-theme-default/commit/8f6dc6c)), closes [telerik/kendo-theme-default#312](https://github.com/telerik/kendo-theme-default/issues/312)
* test via node-sass prior to pushing ([5f0011e](https://github.com/telerik/kendo-theme-default/commit/5f0011e))
* update default theme to new design ([2284cc2](https://github.com/telerik/kendo-theme-default/commit/2284cc2))
* use sans-serif by default, add header bg ([432d499](https://github.com/telerik/kendo-theme-default/commit/432d499))


### Reverts

* **common:** revert state-selected ([#130](https://github.com/telerik/kendo-theme-default/issues/130)) ([4248007](https://github.com/telerik/kendo-theme-default/commit/4248007))




<a name="2.48.0-dev.c7ddd20b"></a>
# 2.48.0-dev.c7ddd20b (2018-01-30)


### Bug Fixes

* .k-select should be square for default theme ([dc41e43](https://github.com/telerik/kendo-theme-default/commit/dc41e43))
* add animation between different positions of chart tooltip. ([17c845b](https://github.com/telerik/kendo-theme-default/commit/17c845b)), closes [telerik/kendo-theme-default#163](https://github.com/telerik/kendo-theme-default/issues/163)
* add button borders ([7421746](https://github.com/telerik/kendo-theme-default/commit/7421746))
* add buttons package and d.ts file ([#16](https://github.com/telerik/kendo-theme-default/issues/16)) ([d0eef84](https://github.com/telerik/kendo-theme-default/commit/d0eef84))
* add calendar border, align icons ([abdb96e](https://github.com/telerik/kendo-theme-default/commit/abdb96e))
* add contrast function based on WCAG requirements ([8755a4e](https://github.com/telerik/kendo-theme-default/commit/8755a4e))
* add d.ts file for layout package ([d448f9a](https://github.com/telerik/kendo-theme-default/commit/d448f9a))
* add d.ts for TypeScript to stop complaining ([1918bc7](https://github.com/telerik/kendo-theme-default/commit/1918bc7))
* add dialog package scripts ([2747802](https://github.com/telerik/kendo-theme-default/commit/2747802))
* add dialog styles to 'all' package ([77e9f4f](https://github.com/telerik/kendo-theme-default/commit/77e9f4f))
* add dropdowns package and d.ts file ([#17](https://github.com/telerik/kendo-theme-default/issues/17)) ([7f08e08](https://github.com/telerik/kendo-theme-default/commit/7f08e08))
* add expand/collapse icons to panelbar ([90dce13](https://github.com/telerik/kendo-theme-default/commit/90dce13))
* add focused styling for the Grid. ([a7389a3](https://github.com/telerik/kendo-theme-default/commit/a7389a3)), closes [telerik/kendo-theme-default#178](https://github.com/telerik/kendo-theme-default/issues/178)
* add functional map and scroller styles ([1abee64](https://github.com/telerik/kendo-theme-default/commit/1abee64))
* add grid to complete package ([2d781f9](https://github.com/telerik/kendo-theme-default/commit/2d781f9))
* add hover styling to the upload dropzone ([#51](https://github.com/telerik/kendo-theme-default/issues/51)) ([b9c8c78](https://github.com/telerik/kendo-theme-default/commit/b9c8c78))
* add k-display-block for chromeless components ([a05ef96](https://github.com/telerik/kendo-theme-default/commit/a05ef96))
* add k-i-add class for backwards compat ([89a26f6](https://github.com/telerik/kendo-theme-default/commit/89a26f6))
* add k-rtl style ([850c713](https://github.com/telerik/kendo-theme-default/commit/850c713))
* add loading animation styles ([426ceac](https://github.com/telerik/kendo-theme-default/commit/426ceac))
* add mixin for striped gradient ([a5f695a](https://github.com/telerik/kendo-theme-default/commit/a5f695a))
* add panelbar rtl styles ([#153](https://github.com/telerik/kendo-theme-default/issues/153)) ([3e11904](https://github.com/telerik/kendo-theme-default/commit/3e11904)), closes [#102](https://github.com/telerik/kendo-theme-default/issues/102)
* add popup box shadow ([#168](https://github.com/telerik/kendo-theme-default/issues/168)) ([a25fb6e](https://github.com/telerik/kendo-theme-default/commit/a25fb6e)), closes [telerik/kendo-theme-default#165](https://github.com/telerik/kendo-theme-default/issues/165)
* add popup styles to datetime package ([db1e963](https://github.com/telerik/kendo-theme-default/commit/db1e963))
* add popup theme to chart theme ([aa7c1fc](https://github.com/telerik/kendo-theme-default/commit/aa7c1fc))
* add separate bundle of tabstrip styles ([0580feb](https://github.com/telerik/kendo-theme-default/commit/0580feb))
* add styles for centering list items ([110ff7a](https://github.com/telerik/kendo-theme-default/commit/110ff7a))
* add styling for chart tooltips ([#32](https://github.com/telerik/kendo-theme-default/issues/32)) ([2ec2545](https://github.com/telerik/kendo-theme-default/commit/2ec2545))
* add styling for Grid ARIA root element ([75dba15](https://github.com/telerik/kendo-theme-default/commit/75dba15))
* add styling for grid new item row ([#85](https://github.com/telerik/kendo-theme-default/issues/85)) ([b93009e](https://github.com/telerik/kendo-theme-default/commit/b93009e)), closes [telerik/kendo-angular-grid#60](https://github.com/telerik/kendo-angular-grid/issues/60)
* add styling for inputs clear all button ([#82](https://github.com/telerik/kendo-theme-default/issues/82)) ([55dde84](https://github.com/telerik/kendo-theme-default/commit/55dde84))
* add tabstrip animations ([85d10fd](https://github.com/telerik/kendo-theme-default/commit/85d10fd))
* add text alignment to droplowns ([4efa519](https://github.com/telerik/kendo-theme-default/commit/4efa519)), closes [telerik/kendo-angular-dropdowns#75](https://github.com/telerik/kendo-angular-dropdowns/issues/75) [#55](https://github.com/telerik/kendo-theme-default/issues/55)
* add var for chart default font size ([#36](https://github.com/telerik/kendo-theme-default/issues/36)) ([1ed2dea](https://github.com/telerik/kendo-theme-default/commit/1ed2dea))
* adjust loading icon position in MultiSelect and AutoComplete ([#432](https://github.com/telerik/kendo-theme-default/issues/432)) ([d60193f](https://github.com/telerik/kendo-theme-default/commit/d60193f))
* adjust primary button gradient to match design more closely ([0a47c38](https://github.com/telerik/kendo-theme-default/commit/0a47c38)), closes [#283](https://github.com/telerik/kendo-theme-default/issues/283)
* Adjust table wizard padding, sizing telerik/kendo[#6508](https://github.com/telerik/kendo-theme-default/issues/6508) ([#99](https://github.com/telerik/kendo-theme-default/issues/99)) ([b51cb7b](https://github.com/telerik/kendo-theme-default/commit/b51cb7b))
* allow flip-h and flip-v to be used together ([4178df2](https://github.com/telerik/kendo-theme-default/commit/4178df2))
* autocomplete in filter row appearance. ([f7cfec5](https://github.com/telerik/kendo-theme-default/commit/f7cfec5)), closes [telerik/kendo-theme-default#148](https://github.com/telerik/kendo-theme-default/issues/148)
* bare button states are not showing correctly ([8117298](https://github.com/telerik/kendo-theme-default/commit/8117298))
* build process does not prefix classes ([1f31b20](https://github.com/telerik/kendo-theme-default/commit/1f31b20)), closes [#5](https://github.com/telerik/kendo-theme-default/issues/5)
* button icons colors; button padding ([#27](https://github.com/telerik/kendo-theme-default/issues/27)) ([f430ccc](https://github.com/telerik/kendo-theme-default/commit/f430ccc))
* buttons focused / active states; buttons height ([c20c806](https://github.com/telerik/kendo-theme-default/commit/c20c806))
* buttons must be square in editor ([5089ff6](https://github.com/telerik/kendo-theme-default/commit/5089ff6))
* change .k-popup.k-list-container box-sizing to border-box ([4b23415](https://github.com/telerik/kendo-theme-default/commit/4b23415))
* change author ([8b5c9cf](https://github.com/telerik/kendo-theme-default/commit/8b5c9cf))
* change scrollview prev/next button styles due to double rendering in iOS ([1a5b29f](https://github.com/telerik/kendo-theme-default/commit/1a5b29f))
* change theme color; re-calculate widgets colors due to color change ([ded3abe](https://github.com/telerik/kendo-theme-default/commit/ded3abe))
* chart incorrect colors ([dc1b6eb](https://github.com/telerik/kendo-theme-default/commit/dc1b6eb))
* chart selection handles metrics ([63d7189](https://github.com/telerik/kendo-theme-default/commit/63d7189))
* chart tooltip metrics; navigator-hint styling. ([9821d47](https://github.com/telerik/kendo-theme-default/commit/9821d47)), closes [telerik/kendo-theme-default#244](https://github.com/telerik/kendo-theme-default/issues/244)
* chart tooltip styling ([829fc5f](https://github.com/telerik/kendo-theme-default/commit/829fc5f))
* context menu and menu styling ([df180b0](https://github.com/telerik/kendo-theme-default/commit/df180b0))
* correct main file name in NPM package ([d7680c7](https://github.com/telerik/kendo-theme-default/commit/d7680c7))
* cursors are incorrect for multiselect tags and list items ([0e934ca](https://github.com/telerik/kendo-theme-default/commit/0e934ca))
* declare box-sizing for dropdowns ([cd41edb](https://github.com/telerik/kendo-theme-default/commit/cd41edb)), closes [telerik/kendo-angular2#142](https://github.com/telerik/kendo-angular2/issues/142)
* declare main file ([b25614d](https://github.com/telerik/kendo-theme-default/commit/b25614d))
* dialog icon styles ([72454a4](https://github.com/telerik/kendo-theme-default/commit/72454a4))
* disable transitions while dragging handle ([1772726](https://github.com/telerik/kendo-theme-default/commit/1772726))
* dropdownlist and combobox styling ([bacc4dd](https://github.com/telerik/kendo-theme-default/commit/bacc4dd))
* dropdownlist focus state. ([5e00bbe](https://github.com/telerik/kendo-theme-default/commit/5e00bbe)), closes [telerik/kendo-theme-default#235](https://github.com/telerik/kendo-theme-default/issues/235)
* dropdownlist search box appearance ([237f518](https://github.com/telerik/kendo-theme-default/commit/237f518))
* dropdowns focused hover state ([15a11b5](https://github.com/telerik/kendo-theme-default/commit/15a11b5))
* dropdowns styling the match the design ([80a9622](https://github.com/telerik/kendo-theme-default/commit/80a9622))
* dropdowns, pickers, inputs rtl styling ([2a10fe3](https://github.com/telerik/kendo-theme-default/commit/2a10fe3))
* editor toolbar ([#182](https://github.com/telerik/kendo-theme-default/issues/182)) ([04cc6de](https://github.com/telerik/kendo-theme-default/commit/04cc6de)), closes [#177](https://github.com/telerik/kendo-theme-default/issues/177)
* editor toolbar styling [#52](https://github.com/telerik/kendo-theme-default/issues/52) ([#84](https://github.com/telerik/kendo-theme-default/issues/84)) ([7878c21](https://github.com/telerik/kendo-theme-default/commit/7878c21))
* error bars styling ([#38](https://github.com/telerik/kendo-theme-default/issues/38)) ([593bc91](https://github.com/telerik/kendo-theme-default/commit/593bc91))
* expand / collapse icons are switched ([#59](https://github.com/telerik/kendo-theme-default/issues/59)) ([5bc865b](https://github.com/telerik/kendo-theme-default/commit/5bc865b))
* export sass variables for script usage ([2558ab5](https://github.com/telerik/kendo-theme-default/commit/2558ab5))
* filter menu, column menu and dropdown operator must be square ([331df4b](https://github.com/telerik/kendo-theme-default/commit/331df4b))
* focused button box-shadow; multiselect buttons metrics and focused stalying ([424bb7d](https://github.com/telerik/kendo-theme-default/commit/424bb7d))
* footer template height ([#208](https://github.com/telerik/kendo-theme-default/issues/208)) ([d7a078b](https://github.com/telerik/kendo-theme-default/commit/d7a078b))
* gantt toggle button and create task button must be square ([92dca6f](https://github.com/telerik/kendo-theme-default/commit/92dca6f))
* grid footer appearance ([d1da7af](https://github.com/telerik/kendo-theme-default/commit/d1da7af))
* grid hierarchy-cell appearance ([de53481](https://github.com/telerik/kendo-theme-default/commit/de53481))
* grid hierarchy-cell width; grid cells padding ([c9f244e](https://github.com/telerik/kendo-theme-default/commit/c9f244e))
* grid selection background. ([6493129](https://github.com/telerik/kendo-theme-default/commit/6493129)), closes [telerik/kend-theme-default#234](https://github.com/telerik/kend-theme-default/issues/234)
* grouping row p height ([#205](https://github.com/telerik/kendo-theme-default/issues/205)) ([50669c4](https://github.com/telerik/kendo-theme-default/commit/50669c4))
* hide input-bar unless used ([e611799](https://github.com/telerik/kendo-theme-default/commit/e611799))
* hide validator through hidden attribute ([295f09b](https://github.com/telerik/kendo-theme-default/commit/295f09b))
* hierarchical grid icons appearance ([926d403](https://github.com/telerik/kendo-theme-default/commit/926d403))
* hierarchy-cell icon color in selected grid row ([94835cd](https://github.com/telerik/kendo-theme-default/commit/94835cd))
* icon button size must be square for all skins ([c803226](https://github.com/telerik/kendo-theme-default/commit/c803226))
* icons hover / focus state ([ff5a536](https://github.com/telerik/kendo-theme-default/commit/ff5a536))
* import base layout before butto layout ([bbe6c71](https://github.com/telerik/kendo-theme-default/commit/bbe6c71))
* import color functions in variables files ([4eef3f9](https://github.com/telerik/kendo-theme-default/commit/4eef3f9))
* improve button sizing ([#195](https://github.com/telerik/kendo-theme-default/issues/195)) ([fde18c8](https://github.com/telerik/kendo-theme-default/commit/fde18c8))
* improve performance in IE ([0048877](https://github.com/telerik/kendo-theme-default/commit/0048877))
* improve upload styling ([ebe6f5e](https://github.com/telerik/kendo-theme-default/commit/ebe6f5e))
* improve yiq function ([98202c5](https://github.com/telerik/kendo-theme-default/commit/98202c5))
* inputs text-color selection. ([5ba213f](https://github.com/telerik/kendo-theme-default/commit/5ba213f)), closes [telerik/kendo-theme-default#241](https://github.com/telerik/kendo-theme-default/issues/241)
* **upload:** different spacing in RTL mode ([9840073](https://github.com/telerik/kendo-theme-default/commit/9840073)), closes [telerik/kendo-angular-upload#67](https://github.com/telerik/kendo-angular-upload/issues/67)
* in IE11, Edge12, and Edge13 border-radius with background-clip causes visual glitches ([96dad8d](https://github.com/telerik/kendo-theme-default/commit/96dad8d))
* incorrect dialog animation in ie11 ([40679be](https://github.com/telerik/kendo-theme-default/commit/40679be))
* incorrect padding of k-tabstrip-items ([#48](https://github.com/telerik/kendo-theme-default/issues/48)) ([d68f036](https://github.com/telerik/kendo-theme-default/commit/d68f036))
* inputs height in IE ([47b0036](https://github.com/telerik/kendo-theme-default/commit/47b0036))
* inputs placeholder color ([52857a0](https://github.com/telerik/kendo-theme-default/commit/52857a0))
* interpolate value in calc ([83439dd](https://github.com/telerik/kendo-theme-default/commit/83439dd))
* introduce -family-monospace variable ([5031f81](https://github.com/telerik/kendo-theme-default/commit/5031f81))
* invisible action buttons in Bootstrap ([8176d6d](https://github.com/telerik/kendo-theme-default/commit/8176d6d))
* invisible separators and wrong selected items color ([ffed067](https://github.com/telerik/kendo-theme-default/commit/ffed067))
* item list is not aligned properly in RTL ([#67](https://github.com/telerik/kendo-theme-default/issues/67)) ([53c155d](https://github.com/telerik/kendo-theme-default/commit/53c155d))
* kendo colorpicker is not properly styles when clearButton is set [#103](https://github.com/telerik/kendo-theme-default/issues/103) ([328f650](https://github.com/telerik/kendo-theme-default/commit/328f650))
* list items styling ([#79](https://github.com/telerik/kendo-theme-default/issues/79)) ([49a3f92](https://github.com/telerik/kendo-theme-default/commit/49a3f92)), closes [telerik/kendo-theme-default#75](https://github.com/telerik/kendo-theme-default/issues/75)
* loading indicator size; loading indicator in combobox position ([#202](https://github.com/telerik/kendo-theme-default/issues/202)) ([5e58cd9](https://github.com/telerik/kendo-theme-default/commit/5e58cd9)), closes [telerik/kendo-theme-default#200](https://github.com/telerik/kendo-theme-default/issues/200)
* make drag handle visible in all cases #telerik/kendo-ui-core[#3254](https://github.com/telerik/kendo-theme-default/issues/3254) ([9709288](https://github.com/telerik/kendo-theme-default/commit/9709288))
* menu and grid header styles ([c875cf0](https://github.com/telerik/kendo-theme-default/commit/c875cf0))
* menu styling ([#110](https://github.com/telerik/kendo-theme-default/issues/110)) ([7ea682d](https://github.com/telerik/kendo-theme-default/commit/7ea682d))
* misaligned icons in popup items. ([beaaac8](https://github.com/telerik/kendo-theme-default/commit/beaaac8)), closes [telerik/kendo-theme-default#222](https://github.com/telerik/kendo-theme-default/issues/222)
* missing filter button in grid filter row ([9a9b724](https://github.com/telerik/kendo-theme-default/commit/9a9b724))
* move chart height to host element ([0a91a77](https://github.com/telerik/kendo-theme-default/commit/0a91a77))
* move imports to work with newer sass ([f68d746](https://github.com/telerik/kendo-theme-default/commit/f68d746))
* multiselect border; remove input width ([fb94f8c](https://github.com/telerik/kendo-theme-default/commit/fb94f8c))
* multiselect buttons clear icon appearance ([3f892f9](https://github.com/telerik/kendo-theme-default/commit/3f892f9))
* MultiSelect delete buttons visibility ([ffed009](https://github.com/telerik/kendo-theme-default/commit/ffed009)), closes [telerik/kendo-theme-default#87](https://github.com/telerik/kendo-theme-default/issues/87)
* multiselect in ie behavior. ([#206](https://github.com/telerik/kendo-theme-default/issues/206)) ([06fb96d](https://github.com/telerik/kendo-theme-default/commit/06fb96d)), closes [telerik/kendo-angular#191](https://github.com/telerik/kendo-angular/issues/191)
* multiselect input height ([6561c85](https://github.com/telerik/kendo-theme-default/commit/6561c85)), closes [telerik/kendo-theme-default#90](https://github.com/telerik/kendo-theme-default/issues/90)
* multiselect input position ([968bfbd](https://github.com/telerik/kendo-theme-default/commit/968bfbd))
* multiselect items - wrong rounded corners. ([db3c2cc](https://github.com/telerik/kendo-theme-default/commit/db3c2cc)), closes [telerik/kendo-theme-default#239](https://github.com/telerik/kendo-theme-default/issues/239)
* multiselect items margin and icon hover styling ([7672cb8](https://github.com/telerik/kendo-theme-default/commit/7672cb8))
* multiselect loading; close button metrics ([2ae5b9f](https://github.com/telerik/kendo-theme-default/commit/2ae5b9f))
* notes styling, crosshair background ([#37](https://github.com/telerik/kendo-theme-default/issues/37)) ([49d0f06](https://github.com/telerik/kendo-theme-default/commit/49d0f06))
* numerictextbox focus state. telerik/kendo-theme-default[#223](https://github.com/telerik/kendo-theme-default/issues/223) ([71539f4](https://github.com/telerik/kendo-theme-default/commit/71539f4))
* numerictextbox spinner appearance for IE10; selected spinner icon color ([#201](https://github.com/telerik/kendo-theme-default/issues/201)) ([dbd8feb](https://github.com/telerik/kendo-theme-default/commit/dbd8feb))
* numerictextbox spinner icons alignment. ([#191](https://github.com/telerik/kendo-theme-default/issues/191)) ([0c3d964](https://github.com/telerik/kendo-theme-default/commit/0c3d964)), closes [telerik/kendo-theme-default#161](https://github.com/telerik/kendo-theme-default/issues/161)
* opacity for no data template ([3fd2648](https://github.com/telerik/kendo-theme-default/commit/3fd2648))
* output path of build process in derived themes ([7199ee0](https://github.com/telerik/kendo-theme-default/commit/7199ee0))
* pager appearance to match thе design ([381cd57](https://github.com/telerik/kendo-theme-default/commit/381cd57)), closes [telerik/kendo-theme-default#187](https://github.com/telerik/kendo-theme-default/issues/187) [#190](https://github.com/telerik/kendo-theme-default/issues/190)
* pager appearance; grid header height ([a889fe8](https://github.com/telerik/kendo-theme-default/commit/a889fe8))
* panelbar colors to match the new design; delete unused variables ([45f58d6](https://github.com/telerik/kendo-theme-default/commit/45f58d6))
* panelbar disabled items hover color ([1ef8712](https://github.com/telerik/kendo-theme-default/commit/1ef8712))
* popup and animation-container styling ([e6fe577](https://github.com/telerik/kendo-theme-default/commit/e6fe577))
* position dialog-wrapper to viewport 0,0 ([da9bbb1](https://github.com/telerik/kendo-theme-default/commit/da9bbb1))
* prev / next buttons in scheduler must be square ([2b5b418](https://github.com/telerik/kendo-theme-default/commit/2b5b418))
* primary button appearance ([b943ed4](https://github.com/telerik/kendo-theme-default/commit/b943ed4))
* provide icon-font-dir variable to override font location ([12e7a5d](https://github.com/telerik/kendo-theme-default/commit/12e7a5d))
* re-calculate widgets colors which depend on the color; add transparency to all borders ([215b48b](https://github.com/telerik/kendo-theme-default/commit/215b48b))
* regression in slider handle animation ([8cf5be7](https://github.com/telerik/kendo-theme-default/commit/8cf5be7)), closes [#26](https://github.com/telerik/kendo-theme-default/issues/26)
* remove additional focus state shadow and fix button height ([858695b](https://github.com/telerik/kendo-theme-default/commit/858695b))
* remove animation for dropdowns list items ([9904a0d](https://github.com/telerik/kendo-theme-default/commit/9904a0d))
* remove border on dialog buttons ([97ba4ab](https://github.com/telerik/kendo-theme-default/commit/97ba4ab))
* Remove checkbox, radiobutton hover state telerik/kendo[#6508](https://github.com/telerik/kendo-theme-default/issues/6508) ([#120](https://github.com/telerik/kendo-theme-default/issues/120)) ([35a5f5a](https://github.com/telerik/kendo-theme-default/commit/35a5f5a))
* Remove checkbox:checked border to center the check glyph ([a005683](https://github.com/telerik/kendo-theme-default/commit/a005683))
* remove grid focus outline. ([#203](https://github.com/telerik/kendo-theme-default/issues/203)) ([0bd10aa](https://github.com/telerik/kendo-theme-default/commit/0bd10aa)), closes [telerik/kendo-theme-default#199](https://github.com/telerik/kendo-theme-default/issues/199)
* remove hover styles on disabled slider ([3061193](https://github.com/telerik/kendo-theme-default/commit/3061193))
* remove IE7 styles, show link between window and actions padding ([3392625](https://github.com/telerik/kendo-theme-default/commit/3392625))
* **action-buttons:** action-buttons should clear floats ([#113](https://github.com/telerik/kendo-theme-default/issues/113)) ([8045ecb](https://github.com/telerik/kendo-theme-default/commit/8045ecb))
* **action-buttons:** improve action buttons spacing ([c3941c3](https://github.com/telerik/kendo-theme-default/commit/c3941c3))
* **action-buttons:** update action-buttons metrics ([f4c1d30](https://github.com/telerik/kendo-theme-default/commit/f4c1d30))
* **animation:** add expand animation styles ([857ac89](https://github.com/telerik/kendo-theme-default/commit/857ac89))
* **Animation:** Correct zoom-in/out CSS class names ([439e177](https://github.com/telerik/kendo-theme-default/commit/439e177))
* **Animation:** Hide every old entering element ([9ef83ec](https://github.com/telerik/kendo-theme-default/commit/9ef83ec))
* **Animation:** Hide old animated elements only if they are still active ([ae7fe98](https://github.com/telerik/kendo-theme-default/commit/ae7fe98))
* **Animation:** Position enter element relatively. Hide old entering elements ([06f9704](https://github.com/telerik/kendo-theme-default/commit/06f9704))
* **Animation:** use default positioning for the animation container ([#5](https://github.com/telerik/kendo-theme-default/issues/5)) ([b6afea5](https://github.com/telerik/kendo-theme-default/commit/b6afea5))
* **animations:** add missing appear transitions ([db7b765](https://github.com/telerik/kendo-theme-default/commit/db7b765))
* **animations:** change animation-leave selector to animation-exit ([fb69c97](https://github.com/telerik/kendo-theme-default/commit/fb69c97))
* **animations:** nested panelbar expand ([5bc45b6](https://github.com/telerik/kendo-theme-default/commit/5bc45b6))
* **autocomplete:** add box-sizing ([aa4b17e](https://github.com/telerik/kendo-theme-default/commit/aa4b17e))
* **autocomplete:** add invalid state for Angular ([6b41e5b](https://github.com/telerik/kendo-theme-default/commit/6b41e5b))
* **autocomplete:** use correct background-clip for autocomplete ([8f32709](https://github.com/telerik/kendo-theme-default/commit/8f32709))
* **autocomplete:** use correct padding for autocomplete ([ecacbce](https://github.com/telerik/kendo-theme-default/commit/ecacbce))
* **button:** Add background-clip; adjust primary button focused shadow transparency ([#172](https://github.com/telerik/kendo-theme-default/issues/172)) ([f1d3417](https://github.com/telerik/kendo-theme-default/commit/f1d3417))
* **button:** add height to icon button for proper vertical alignment ([df4d3f4](https://github.com/telerik/kendo-theme-default/commit/df4d3f4))
* **button:** add styles for icon buttons in RTL ([a5de136](https://github.com/telerik/kendo-theme-default/commit/a5de136))
* **button:** add styles for radiobutton group that look like button group ([be14283](https://github.com/telerik/kendo-theme-default/commit/be14283))
* **button:** extract variable for bare button hover opacity ([#655](https://github.com/telerik/kendo-theme-default/issues/655)) ([8671249](https://github.com/telerik/kendo-theme-default/commit/8671249))
* **button:** icon button height should be equal to the other buttons ([3eba04f](https://github.com/telerik/kendo-theme-default/commit/3eba04f))
* **button:** improve border radius for rtl ([cc51a24](https://github.com/telerik/kendo-theme-default/commit/cc51a24))
* **button:** make buttons relative by default ([89d1280](https://github.com/telerik/kendo-theme-default/commit/89d1280))
* **button:** outline primary buttons appearance ([14e636e](https://github.com/telerik/kendo-theme-default/commit/14e636e))
* **button:** update variables to match design ([ac85fe9](https://github.com/telerik/kendo-theme-default/commit/ac85fe9))
* **button:** use correct pressed-like button appearance ([7613188](https://github.com/telerik/kendo-theme-default/commit/7613188))
* **button:** use correct states for selected button in button group ([ae8fdbc](https://github.com/telerik/kendo-theme-default/commit/ae8fdbc))
* **button:** use variable for buttongroup buttons left margin ([b24a1e4](https://github.com/telerik/kendo-theme-default/commit/b24a1e4))
* **buttongroup:** use correct background-clip for buttongroup ([583ed8c](https://github.com/telerik/kendo-theme-default/commit/583ed8c))
* **buttonGroup:** add focus state to disabled button in button group telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([c255c82](https://github.com/telerik/kendo-theme-default/commit/c255c82))
* **buttonGroup:** fix border radius after reverting rendering changes telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([0f68691](https://github.com/telerik/kendo-theme-default/commit/0f68691))
* **buttonGroup:** fix border radius after reverting rendering changes telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([e088f72](https://github.com/telerik/kendo-theme-default/commit/e088f72))
* **buttonGroupd:** add focus state to button in disabled button group telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([13b0de5](https://github.com/telerik/kendo-theme-default/commit/13b0de5))
* **buttons:** add RTL support for button icons ([#170](https://github.com/telerik/kendo-theme-default/issues/170)) ([82d5401](https://github.com/telerik/kendo-theme-default/commit/82d5401))
* **buttons:** add variable for border width ([3fae15f](https://github.com/telerik/kendo-theme-default/commit/3fae15f))
* **buttons:** fix missing border radius ([5fcf831](https://github.com/telerik/kendo-theme-default/commit/5fcf831))
* **buttons:** use variable for bare buttons positions ([0b162be](https://github.com/telerik/kendo-theme-default/commit/0b162be))
* **calendar:** add hints for endless scrolling in infinite calendar ([9289990](https://github.com/telerik/kendo-theme-default/commit/9289990))
* **calendar:** add RTL styles for infinite mode ([b061418](https://github.com/telerik/kendo-theme-default/commit/b061418))
* **calendar:** Add specificity to selected weekend day selector ([#561](https://github.com/telerik/kendo-theme-default/issues/561)) ([1ca705b](https://github.com/telerik/kendo-theme-default/commit/1ca705b))
* **calendar:** add styles for infinite mode ([313856d](https://github.com/telerik/kendo-theme-default/commit/313856d))
* **calendar:** adjust navigation padding ([9e07572](https://github.com/telerik/kendo-theme-default/commit/9e07572))
* **calendar:** bring Calendar styles up to date with design ([c08e38a](https://github.com/telerik/kendo-theme-default/commit/c08e38a))
* **calendar:** Center dates per latest design, fix selected weekend background ([14698e1](https://github.com/telerik/kendo-theme-default/commit/14698e1))
* **calendar:** center navigation text ([57e9c1c](https://github.com/telerik/kendo-theme-default/commit/57e9c1c))
* **calendar:** correct padding for navigation on OSX ([#379](https://github.com/telerik/kendo-theme-default/issues/379)) ([0e64cc7](https://github.com/telerik/kendo-theme-default/commit/0e64cc7)), closes [#353](https://github.com/telerik/kendo-theme-default/issues/353)
* **calendar:** improve layout for months with few days ([078f2e4](https://github.com/telerik/kendo-theme-default/commit/078f2e4))
* **calendar:** improve layout in IE10 ([0238c1b](https://github.com/telerik/kendo-theme-default/commit/0238c1b))
* **calendar:** Improve styling ([6d55d7a](https://github.com/telerik/kendo-theme-default/commit/6d55d7a))
* **calendar:** increase height to show second month ([2e62660](https://github.com/telerik/kendo-theme-default/commit/2e62660))
* **calendar:** remove the float style from k-content ([6f1f930](https://github.com/telerik/kendo-theme-default/commit/6f1f930))
* **calendar:** Switch to display: block ([3f3932b](https://github.com/telerik/kendo-theme-default/commit/3f3932b))
* **calendar:** Updates Calendar styles to match design ([04ad7d7](https://github.com/telerik/kendo-theme-default/commit/04ad7d7))
* **calendar:** use correct background-clip for calendar ([17b51e4](https://github.com/telerik/kendo-theme-default/commit/17b51e4))
* **calendar:** wrong view width in pages with bootstrap 3 ([1f4be2f](https://github.com/telerik/kendo-theme-default/commit/1f4be2f))
* **chart:** add k-chart-dragging class ([059c9cd](https://github.com/telerik/kendo-theme-default/commit/059c9cd))
* **chart:** add missing popup dependency ([#549](https://github.com/telerik/kendo-theme-default/issues/549)) ([6ce5dea](https://github.com/telerik/kendo-theme-default/commit/6ce5dea))
* **chart:** add transitions if the wrapper and the popup are the same element ([0d225c4](https://github.com/telerik/kendo-theme-default/commit/0d225c4))
* **chart:** remove spacing from tooltip ([bcbb789](https://github.com/telerik/kendo-theme-default/commit/bcbb789))
* **chart:** tooltip animation transtions ([56c42d8](https://github.com/telerik/kendo-theme-default/commit/56c42d8))
* **checkbox:** imrpove checkbox states ([c69e527](https://github.com/telerik/kendo-theme-default/commit/c69e527))
* **checkbox:** remove double opacity on checkboxes ([f7c3951](https://github.com/telerik/kendo-theme-default/commit/f7c3951))
* **colorpicker:** Add style for Colorpicker with tool icon ([#137](https://github.com/telerik/kendo-theme-default/issues/137)) ([838d4af](https://github.com/telerik/kendo-theme-default/commit/838d4af))
* **colorpicker:** use correct background-clip for colorpicker ([70923c3](https://github.com/telerik/kendo-theme-default/commit/70923c3))
* **colorpicker:** use correct size and box-sizing for color preview ([551d79e](https://github.com/telerik/kendo-theme-default/commit/551d79e))
* **combobox:** allow mixed units for right padding ([#399](https://github.com/telerik/kendo-theme-default/issues/399)) ([b543b43](https://github.com/telerik/kendo-theme-default/commit/b543b43))
* **combobox:** clear button overlaps the selected item ([#395](https://github.com/telerik/kendo-theme-default/issues/395)) ([b17e409](https://github.com/telerik/kendo-theme-default/commit/b17e409)), closes [telerik/kendo-theme-default#261](https://github.com/telerik/kendo-theme-default/issues/261)
* **combobox:** left padding in rtl mode ([f3927c0](https://github.com/telerik/kendo-theme-default/commit/f3927c0))
* **combobox:** use correct background-clip for combobox ([8fb34d2](https://github.com/telerik/kendo-theme-default/commit/8fb34d2))
* **combobox:** wrong styling on focused item. ([8c70c62](https://github.com/telerik/kendo-theme-default/commit/8c70c62)), closes [telerik/kendo-theme-default#309](https://github.com/telerik/kendo-theme-default/issues/309)
* **common:** add styles for reorder cue ([9a7971e](https://github.com/telerik/kendo-theme-default/commit/9a7971e))
* **common:** add styles for text selection ([0bc9d90](https://github.com/telerik/kendo-theme-default/commit/0bc9d90))
* **common:** extract edit form styles to common/base ([4900d15](https://github.com/telerik/kendo-theme-default/commit/4900d15))
* **common:** improve common states ([#117](https://github.com/telerik/kendo-theme-default/issues/117)) ([843dcd3](https://github.com/telerik/kendo-theme-default/commit/843dcd3))
* **contextmenu:** improve separator and horizontal contextmenu ([7fe82fc](https://github.com/telerik/kendo-theme-default/commit/7fe82fc))
* **dateinput:** focused / selected state appearance ([6d3d9ba](https://github.com/telerik/kendo-theme-default/commit/6d3d9ba))
* **DateInput:** Add RTL styles ([28763cb](https://github.com/telerik/kendo-theme-default/commit/28763cb))
* **dateinputs:** calendar and timepicker colors ([2a0634c](https://github.com/telerik/kendo-theme-default/commit/2a0634c))
* **datepicker:** add hover style; wrong width and height ([a5fb667](https://github.com/telerik/kendo-theme-default/commit/a5fb667))
* **datepicker:** fix Angular validation styles ([7104d88](https://github.com/telerik/kendo-theme-default/commit/7104d88))
* **datepicker:** override margin when applied to .k-widget ([e581514](https://github.com/telerik/kendo-theme-default/commit/e581514))
* **datepicker:** Switch rounded corners for select button in RTL; style imrovements ([c19178a](https://github.com/telerik/kendo-theme-default/commit/c19178a))
* **datepicker:** wrong width of the internal DateInput component in IE11 ([2505558](https://github.com/telerik/kendo-theme-default/commit/2505558))
* **datetime:** add dependency to calendar ([d23888c](https://github.com/telerik/kendo-theme-default/commit/d23888c))
* **datetime:** use corerct background-clip for datetime ([6937500](https://github.com/telerik/kendo-theme-default/commit/6937500))
* **datetimepicker:** allow buttons to work in any box-sizing context ([#722](https://github.com/telerik/kendo-theme-default/issues/722)) ([417a181](https://github.com/telerik/kendo-theme-default/commit/417a181))
* **diagram:** use accent-contrast color ([#378](https://github.com/telerik/kendo-theme-default/issues/378)) ([0f5f063](https://github.com/telerik/kendo-theme-default/commit/0f5f063))
* **dialog:** add border between buttons in RTL ([8086b63](https://github.com/telerik/kendo-theme-default/commit/8086b63))
* **dialog:** alignment in IE11 and Firefox RTL ([7bd2d19](https://github.com/telerik/kendo-theme-default/commit/7bd2d19))
* **dialog:** animation styles ([2cc7ad4](https://github.com/telerik/kendo-theme-default/commit/2cc7ad4))
* **dialog:** Bring button layout in line with design telerik/kendo[#6508](https://github.com/telerik/kendo-theme-default/issues/6508) ([#108](https://github.com/telerik/kendo-theme-default/issues/108)) ([703c465](https://github.com/telerik/kendo-theme-default/commit/703c465))
* **dialog:** center action button text in Safari ([6240433](https://github.com/telerik/kendo-theme-default/commit/6240433)), closes [#158](https://github.com/telerik/kendo-theme-default/issues/158)
* **dialog:** close button styles ([01e8a90](https://github.com/telerik/kendo-theme-default/commit/01e8a90))
* **dialog:** content is not visible in IE11 ([7b86eef](https://github.com/telerik/kendo-theme-default/commit/7b86eef)), closes [telerik/kendo-angular2#192](https://github.com/telerik/kendo-angular2/issues/192)
* **dialog:** do not collapse buttons in scrollable content ([da300ff](https://github.com/telerik/kendo-theme-default/commit/da300ff))
* **dialog:** do not hide action buttons if window is higher than viewport in IE11 ([#814](https://github.com/telerik/kendo-theme-default/issues/814)) ([a060d04](https://github.com/telerik/kendo-theme-default/commit/a060d04))
* **dialog:** do not modify custom content ([400ccd1](https://github.com/telerik/kendo-theme-default/commit/400ccd1)), closes [#180](https://github.com/telerik/kendo-theme-default/issues/180)
* **dialog:** Improve dialog content, titlebar centering ([9aea365](https://github.com/telerik/kendo-theme-default/commit/9aea365))
* **dialog:** limit height to viewport height ([157c323](https://github.com/telerik/kendo-theme-default/commit/157c323))
* **dialog:** pager buttons appear above modal dialog ([898c31f](https://github.com/telerik/kendo-theme-default/commit/898c31f))
* **dialog:** use accent colors by default ([0ddcbee](https://github.com/telerik/kendo-theme-default/commit/0ddcbee))
* **dropdownlist:** improve styles for dropdown operator in grid filtering ([5260e7f](https://github.com/telerik/kendo-theme-default/commit/5260e7f))
* **dropdownlist:** long text in filter input interferes with the icon. ([f28d9fe](https://github.com/telerik/kendo-theme-default/commit/f28d9fe)), closes [telerik/kendo-theme-default#564](https://github.com/telerik/kendo-theme-default/issues/564)
* **dropdownlist:** use correct background-clip for dropdownlist ([b282964](https://github.com/telerik/kendo-theme-default/commit/b282964))
* **DropDownList:** remove the default clear button in IE ([7319d02](https://github.com/telerik/kendo-theme-default/commit/7319d02))
* **dropdowns:** appearance in rtl mode ([691ef52](https://github.com/telerik/kendo-theme-default/commit/691ef52))
* **dropdowns:** calculate size of list filter ([32404e9](https://github.com/telerik/kendo-theme-default/commit/32404e9))
* **dropdowns:** filtering input / label rtl alignment ([4ad8121](https://github.com/telerik/kendo-theme-default/commit/4ad8121))
* **dropdowns:** misaligned loading indicator; wrong select width ([#545](https://github.com/telerik/kendo-theme-default/issues/545)) ([8edc50a](https://github.com/telerik/kendo-theme-default/commit/8edc50a))
* **dropdowns:** noDataTemplate styling ([753347f](https://github.com/telerik/kendo-theme-default/commit/753347f)), closes [telerik/kendo-theme-default#327](https://github.com/telerik/kendo-theme-default/issues/327)
* **dropdowns:** update dropdowns styling because of changed rendering ([#388](https://github.com/telerik/kendo-theme-default/issues/388)) ([9b6ac0e](https://github.com/telerik/kendo-theme-default/commit/9b6ac0e))
* **dropdowns:** visual glitches ([e41d8eb](https://github.com/telerik/kendo-theme-default/commit/e41d8eb))
* **edit-form:** colorpickers must not be 100% wide in edit form ([52fb2fe](https://github.com/telerik/kendo-theme-default/commit/52fb2fe))
* **editform:** use min width in addition to width ([d0b5b44](https://github.com/telerik/kendo-theme-default/commit/d0b5b44))
* **editor:** add header border color for Firefox ([d68f6a6](https://github.com/telerik/kendo-theme-default/commit/d68f6a6))
* **editor:** add layout for filebrowser / image browser dialog ([1576167](https://github.com/telerik/kendo-theme-default/commit/1576167))
* **editor:** add spacing between widgets in toolbar group ([42e7e45](https://github.com/telerik/kendo-theme-default/commit/42e7e45))
* **editor:** add styles for browser dialogs ([64ab51a](https://github.com/telerik/kendo-theme-default/commit/64ab51a))
* **editor:** Adjust Colorpicker size, unhide color preview strip ([#143](https://github.com/telerik/kendo-theme-default/issues/143)) ([74cc2c3](https://github.com/telerik/kendo-theme-default/commit/74cc2c3))
* **editor:** align template content vertially ([eb63cbe](https://github.com/telerik/kendo-theme-default/commit/eb63cbe))
* **editor:** broken layout of file and image browsers ([fe0243d](https://github.com/telerik/kendo-theme-default/commit/fe0243d))
* **editor:** content of editor toolbar exceeds the size of the container ([a1310be](https://github.com/telerik/kendo-theme-default/commit/a1310be))
* **editor:** fix displaced combobox button in editor in Edge [#625](https://github.com/telerik/kendo-theme-default/issues/625) ([e930ce5](https://github.com/telerik/kendo-theme-default/commit/e930ce5))
* **editor:** fix editor's file and image browser dialogs telerik/kendo-ui-core[#2819](https://github.com/telerik/kendo-theme-default/issues/2819) ([8faf610](https://github.com/telerik/kendo-theme-default/commit/8faf610))
* **editor:** fix scrolled content height in the table wizard dialog [#665](https://github.com/telerik/kendo-theme-default/issues/665) ([138b952](https://github.com/telerik/kendo-theme-default/commit/138b952))
* **editor:** fix searchbox in filebrowser dialog ([e1ae582](https://github.com/telerik/kendo-theme-default/commit/e1ae582))
* **editor:** fix type in editor selector ([8a1a669](https://github.com/telerik/kendo-theme-default/commit/8a1a669))
* **editor:** improve numeric and colorpickers in table wizard ([4f0b323](https://github.com/telerik/kendo-theme-default/commit/4f0b323))
* **editor:** improve styling of tabstrip in window ([39a91b4](https://github.com/telerik/kendo-theme-default/commit/39a91b4))
* **editor:** improve table wizard alignment dropdowns ([d517b2f](https://github.com/telerik/kendo-theme-default/commit/d517b2f))
* **editor:** improve table wizzard dropdown ([59a424c](https://github.com/telerik/kendo-theme-default/commit/59a424c))
* **editor:** improve tiles gird styles ([f0145ec](https://github.com/telerik/kendo-theme-default/commit/f0145ec))
* **editor:** Inconsistent Editor indent/outdent icons in RTL ([d6bcc52](https://github.com/telerik/kendo-theme-default/commit/d6bcc52))
* **editor:** make editor dialog content as wide as dialog ([83eda33](https://github.com/telerik/kendo-theme-default/commit/83eda33))
* **editor:** make scrollbars of Editor's dialogs to be consistent ([12e24e2](https://github.com/telerik/kendo-theme-default/commit/12e24e2))
* **editor:** make scrollbars of Editor's dialogs to be consistent ([c7330e0](https://github.com/telerik/kendo-theme-default/commit/c7330e0))
* **editor:** prevent overflowing file and image browsers content telerik/kendo-theme-bootstrap[#206](https://github.com/telerik/kendo-theme-default/issues/206) ([877575f](https://github.com/telerik/kendo-theme-default/commit/877575f))
* **editor:** prevent resize handler to oerlap scrolling arrow telerik/kendo-ui.core[#3445](https://github.com/telerik/kendo-theme-default/issues/3445) ([1fa2a8b](https://github.com/telerik/kendo-theme-default/commit/1fa2a8b))
* **editor:** reduce size of inlie editor toolbar ([06d1caf](https://github.com/telerik/kendo-theme-default/commit/06d1caf))
* **editor:** uniform scrollnig in editor dialogs ([e43cb41](https://github.com/telerik/kendo-theme-default/commit/e43cb41))
* **editor:** use border-color: inhreit for editor toolbar and editable area ([2932e19](https://github.com/telerik/kendo-theme-default/commit/2932e19))
* **editor:** use correct colors for toggled button ([57c51b4](https://github.com/telerik/kendo-theme-default/commit/57c51b4))
* **editor:** use corret background-clip for editor ([237124a](https://github.com/telerik/kendo-theme-default/commit/237124a))
* **editors:** common layout glitches ([9e66aad](https://github.com/telerik/kendo-theme-default/commit/9e66aad))
* **forms:** align labels in forms in dialog ([e488260](https://github.com/telerik/kendo-theme-default/commit/e488260))
* **forms:** align text, field-info, radiobuttons and checkboxes in forms ([607a48d](https://github.com/telerik/kendo-theme-default/commit/607a48d))
* **forms:** allow use of k-state-invalid class for invalid state ([#823](https://github.com/telerik/kendo-theme-default/issues/823)) ([8367d13](https://github.com/telerik/kendo-theme-default/commit/8367d13))
* **gantt:** broken tasks and dependencies position in RTL ([afef5d0](https://github.com/telerik/kendo-theme-default/commit/afef5d0))
* **gantt:** broken tasks and dependencies positions in RTL ([96e9e1f](https://github.com/telerik/kendo-theme-default/commit/96e9e1f))
* **gantt:** broken tasks in IE ([8325c2a](https://github.com/telerik/kendo-theme-default/commit/8325c2a))
* **gantt:** imporve task percentagle complete handle position ([a4b3f84](https://github.com/telerik/kendo-theme-default/commit/a4b3f84))
* **gantt:** improve gantt size by setting align to k-icon ([29ca321](https://github.com/telerik/kendo-theme-default/commit/29ca321))
* **gantt:** improve milestone RTL position ([cf04b8f](https://github.com/telerik/kendo-theme-default/commit/cf04b8f))
* **gantt:** move tasks to prevent overlapping dependency arrows ([2d5e8bd](https://github.com/telerik/kendo-theme-default/commit/2d5e8bd))
* **gantt:** move tasks to prevent overlapping dependency in RTL ([d1ea3fa](https://github.com/telerik/kendo-theme-default/commit/d1ea3fa))
* **gantt:** remove font size from task content ([ca2d996](https://github.com/telerik/kendo-theme-default/commit/ca2d996))
* **gantt:** remove overriding styles from splitter in accordance with design ([37201f2](https://github.com/telerik/kendo-theme-default/commit/37201f2))
* **gantt:** show delete-task-link only on task hover ([35171d3](https://github.com/telerik/kendo-theme-default/commit/35171d3))
* **gantt:** show task progress drag handle only on hover ([e8a9873](https://github.com/telerik/kendo-theme-default/commit/e8a9873))
* **gantt:** text is not vertically aligned wihtin headers ([cd3c947](https://github.com/telerik/kendo-theme-default/commit/cd3c947))
* **gantt:** treelist header is not correctly aligned with timeline headers ([b660ced](https://github.com/telerik/kendo-theme-default/commit/b660ced))
* **gantt:** update gant task in accordance with design ([f461593](https://github.com/telerik/kendo-theme-default/commit/f461593))
* **gantt:** update gantt header height in accordance with design ([12fd992](https://github.com/telerik/kendo-theme-default/commit/12fd992))
* **gantt:** update gantt in accordance with design ([9389b48](https://github.com/telerik/kendo-theme-default/commit/9389b48))
* **gantt:** update task tooltip in accordance with design ([b2ff91a](https://github.com/telerik/kendo-theme-default/commit/b2ff91a))
* **gantt:** update task-milestone in accordance with design ([b67f98e](https://github.com/telerik/kendo-theme-default/commit/b67f98e))
* **gantt:** update task-summary in accordance with design ([5fc1fc9](https://github.com/telerik/kendo-theme-default/commit/5fc1fc9))
* **gantt:** use correct background-clip for gantt ([16a10a0](https://github.com/telerik/kendo-theme-default/commit/16a10a0))
* **gantt:** use correct variables for toolbar padding ([d95f93b](https://github.com/telerik/kendo-theme-default/commit/d95f93b))
* **gantt:** use vertical-align middle for gantt treelist content cells ([c57f84e](https://github.com/telerik/kendo-theme-default/commit/c57f84e))
* **gantt:** view switcher is missing selected state ([015b7ec](https://github.com/telerik/kendo-theme-default/commit/015b7ec))
* **gantt:** wrong action button position ([4a76cd6](https://github.com/telerik/kendo-theme-default/commit/4a76cd6))
* **gantt:** wrong task complete position ([873cbf7](https://github.com/telerik/kendo-theme-default/commit/873cbf7))
* **grid:** (Angular) resize contents to fit wrapper ([#859](https://github.com/telerik/kendo-theme-default/issues/859)) ([e57a000](https://github.com/telerik/kendo-theme-default/commit/e57a000))
* **grid:** add autofitting styles for jQuery grid ([116dcfd](https://github.com/telerik/kendo-theme-default/commit/116dcfd))
* **grid:** Add calculation and apply it to form elements margin ([1db82a0](https://github.com/telerik/kendo-theme-default/commit/1db82a0))
* **grid:** Add missing dirty cell styling ([4ec31bf](https://github.com/telerik/kendo-theme-default/commit/4ec31bf))
* **grid:** Add missing loading spinner ([#539](https://github.com/telerik/kendo-theme-default/issues/539)) ([8055d53](https://github.com/telerik/kendo-theme-default/commit/8055d53))
* **grid:** Add negative widget offset margins to column menu icon in header ([29a744d](https://github.com/telerik/kendo-theme-default/commit/29a744d))
* **grid:** Add no-text class styling to checkbox label ([713bbc1](https://github.com/telerik/kendo-theme-default/commit/713bbc1))
* **grid:** add reorder styles for ng grid ([5fc5a30](https://github.com/telerik/kendo-theme-default/commit/5fc5a30))
* **grid:** Add RTL styles for dirty cells ([f683eb1](https://github.com/telerik/kendo-theme-default/commit/f683eb1))
* **grid:** add spacing between buttons ([89de27c](https://github.com/telerik/kendo-theme-default/commit/89de27c))
* **grid:** add styles for virtual content ([05aad12](https://github.com/telerik/kendo-theme-default/commit/05aad12))
* **grid:** Add styles positioning the PDF export progress bar ([ce1c967](https://github.com/telerik/kendo-theme-default/commit/ce1c967))
* **grid:** Adjust checkbox margin in RTL ([22096dd](https://github.com/telerik/kendo-theme-default/commit/22096dd))
* **grid:** Adjust column sorting icon and index positions ([5d3230d](https://github.com/telerik/kendo-theme-default/commit/5d3230d))
* **grid:** Adjust filter row Numerictextbox width ([b61ee19](https://github.com/telerik/kendo-theme-default/commit/b61ee19))
* **grid:** Adjust filterable+sortable header margin for the sake of Edge ([488fe21](https://github.com/telerik/kendo-theme-default/commit/488fe21))
* **grid:** Adjust header styles ([afe0bb8](https://github.com/telerik/kendo-theme-default/commit/afe0bb8))
* **grid:** Adjust input width in edit modes ([2faed78](https://github.com/telerik/kendo-theme-default/commit/2faed78))
* **grid:** adjust row height and grouping token size ([ffb4b65](https://github.com/telerik/kendo-theme-default/commit/ffb4b65))
* **grid:** Adjust sorting index position ([487d077](https://github.com/telerik/kendo-theme-default/commit/487d077))
* **grid:** Adjust sorting indicators positions ([988ff92](https://github.com/telerik/kendo-theme-default/commit/988ff92))
* **grid:** adjust the space between the input and row / cell border ([#296](https://github.com/telerik/kendo-theme-default/issues/296)) ([1e6e487](https://github.com/telerik/kendo-theme-default/commit/1e6e487)), closes [telerik/kendo-theme-default#294](https://github.com/telerik/kendo-theme-default/issues/294)
* **grid:** align bottom multi-column headers ([c3f3bdc](https://github.com/telerik/kendo-theme-default/commit/c3f3bdc))
* **grid:** Align popup checkbox with text ([fd447e7](https://github.com/telerik/kendo-theme-default/commit/fd447e7))
* **grid:** allow filter row components to shrink below min-width ([03ddb42](https://github.com/telerik/kendo-theme-default/commit/03ddb42))
* **grid:** allow filter row to render TD cells ([996a8b6](https://github.com/telerik/kendo-theme-default/commit/996a8b6))
* **grid:** allow for filterable cell input resizing ([6c67e7f](https://github.com/telerik/kendo-theme-default/commit/6c67e7f))
* **grid:** allow integration of resize sensor ([d6dcaaa](https://github.com/telerik/kendo-theme-default/commit/d6dcaaa))
* **grid:** allow use without flexbox in jQuery grid ([#439](https://github.com/telerik/kendo-theme-default/issues/439)) ([4fe6fb4](https://github.com/telerik/kendo-theme-default/commit/4fe6fb4))
* **grid:** Angular grouping header is collapsed in IE ([621cebf](https://github.com/telerik/kendo-theme-default/commit/621cebf))
* **grid:** broken layout when virtualization is used ([11b4775](https://github.com/telerik/kendo-theme-default/commit/11b4775)), closes [telerik/kendo-theme-default#324](https://github.com/telerik/kendo-theme-default/issues/324)
* **grid:** buttons in Grid editor templates misalignments ([b9bf599](https://github.com/telerik/kendo-theme-default/commit/b9bf599))
* **grid:** Change positioning of dirty cell TD in edit mode ([16635bd](https://github.com/telerik/kendo-theme-default/commit/16635bd))
* **grid:** column header text breaks out of narrow columns ([#754](https://github.com/telerik/kendo-theme-default/issues/754)) ([994c116](https://github.com/telerik/kendo-theme-default/commit/994c116))
* **grid:** columns misalignment when Bootstrap is used. ([f6c2828](https://github.com/telerik/kendo-theme-default/commit/f6c2828)), closes [telerik/kendo-theme-default#285](https://github.com/telerik/kendo-theme-default/issues/285)
* **grid:** do not resize columns when all their widths are set ([ca1050c](https://github.com/telerik/kendo-theme-default/commit/ca1050c)), closes [telerik/kendo-angular#689](https://github.com/telerik/kendo-angular/issues/689)
* **grid:** dragclue and grouping clue appearance ([a7d9c44](https://github.com/telerik/kendo-theme-default/commit/a7d9c44))
* **grid:** edit row buttons overlap ([4cb2711](https://github.com/telerik/kendo-theme-default/commit/4cb2711))
* **grid:** enable group ordering ([#795](https://github.com/telerik/kendo-theme-default/issues/795)) ([8156a3a](https://github.com/telerik/kendo-theme-default/commit/8156a3a))
* **grid:** expand/collapse icon is not centered ([599b8ff](https://github.com/telerik/kendo-theme-default/commit/599b8ff))
* **grid:** expand/collapse icon is not centered ([b6df0e2](https://github.com/telerik/kendo-theme-default/commit/b6df0e2))
* **grid:** filter button height ([b5639cd](https://github.com/telerik/kendo-theme-default/commit/b5639cd))
* **grid:** filter menu styles ([ca0d191](https://github.com/telerik/kendo-theme-default/commit/ca0d191))
* **grid:** filter row boolean filter appearance ([76924b9](https://github.com/telerik/kendo-theme-default/commit/76924b9))
* **grid:** filter row boolean operator styling ([da252ed](https://github.com/telerik/kendo-theme-default/commit/da252ed))
* **grid:** filter row components do not shrink ([f75a9a4](https://github.com/telerik/kendo-theme-default/commit/f75a9a4))
* **grid:** filter row height is incorrect in IE when height is set ([c68d26c](https://github.com/telerik/kendo-theme-default/commit/c68d26c))
* **grid:** filter row operators appearance ([ee32c9f](https://github.com/telerik/kendo-theme-default/commit/ee32c9f))
* **grid:** filter row span outside cells ([357d0b7](https://github.com/telerik/kendo-theme-default/commit/357d0b7)), closes [telerik/kendo-angular#830](https://github.com/telerik/kendo-angular/issues/830)
* **grid:** filter row styles ([9e41a82](https://github.com/telerik/kendo-theme-default/commit/9e41a82))
* **grid:** filter row styling ([#262](https://github.com/telerik/kendo-theme-default/issues/262)) ([0edba58](https://github.com/telerik/kendo-theme-default/commit/0edba58))
* **grid:** fix calc usage ([4f7cdd2](https://github.com/telerik/kendo-theme-default/commit/4f7cdd2))
* **grid:** Fix column resizing with virtual scrolling enabled ([16113fb](https://github.com/telerik/kendo-theme-default/commit/16113fb))
* **grid:** fix header layout for locked columns ([022070f](https://github.com/telerik/kendo-theme-default/commit/022070f))
* **grid:** fix header misalignment in Kendo UI for jQuery ([#816](https://github.com/telerik/kendo-theme-default/issues/816)) ([a66bf9c](https://github.com/telerik/kendo-theme-default/commit/a66bf9c))
* **grid:** grouping clue is small in pages that use Bootstrap ([fd0feb9](https://github.com/telerik/kendo-theme-default/commit/fd0feb9))
* **grid:** headers border color ([df33e0f](https://github.com/telerik/kendo-theme-default/commit/df33e0f))
* **grid:** headers misalignment. ([e13234f](https://github.com/telerik/kendo-theme-default/commit/e13234f)), closes [telerik/kendo-theme-default#284](https://github.com/telerik/kendo-theme-default/issues/284)
* **grid:** Improve column selection checkbox position in RTL styling ([a7bb3c8](https://github.com/telerik/kendo-theme-default/commit/a7bb3c8))
* **grid:** Improve dirty cell styling ([78bf826](https://github.com/telerik/kendo-theme-default/commit/78bf826))
* **grid:** improve drag clue layout ([2520770](https://github.com/telerik/kendo-theme-default/commit/2520770))
* **grid:** improve filter menu layout ([900d53e](https://github.com/telerik/kendo-theme-default/commit/900d53e))
* **grid:** Improve filter row styling for jQuery ([b1541a3](https://github.com/telerik/kendo-theme-default/commit/b1541a3))
* **grid:** improve grid group indicator appearance ([e2da9f7](https://github.com/telerik/kendo-theme-default/commit/e2da9f7))
* **grid:** Improve Grid popup editor checkbox alignment ([f8a5bd6](https://github.com/telerik/kendo-theme-default/commit/f8a5bd6))
* **grid:** improve layout calculation performance ([a098fcd](https://github.com/telerik/kendo-theme-default/commit/a098fcd))
* **grid:** Increase specificity of the menu styles ([2f9b010](https://github.com/telerik/kendo-theme-default/commit/2f9b010))
* **grid:** layout is broken in RTL when all column widths are set ([#577](https://github.com/telerik/kendo-theme-default/issues/577)) ([173220f](https://github.com/telerik/kendo-theme-default/commit/173220f)), closes [telerik/kendo-angular#689](https://github.com/telerik/kendo-angular/issues/689)
* **grid:** layout regression when no height is set ([#358](https://github.com/telerik/kendo-theme-default/issues/358)) ([096b5f2](https://github.com/telerik/kendo-theme-default/commit/096b5f2)), closes [telerik/kendo-angular#429](https://github.com/telerik/kendo-angular/issues/429)
* **grid:** multiheaders missing borders ([2c6ef3b](https://github.com/telerik/kendo-theme-default/commit/2c6ef3b)), closes [telerik/kendo-theme-default#298](https://github.com/telerik/kendo-theme-default/issues/298)
* **grid:** multiselect in filter row appearance ([19672ba](https://github.com/telerik/kendo-theme-default/commit/19672ba))
* **grid:** pager items placement. ([29a197a](https://github.com/telerik/kendo-theme-default/commit/29a197a)), closes [telerik/kendo-theme-default#321](https://github.com/telerik/kendo-theme-default/issues/321)
* **grid:** Prevent batch edit mode inputs from overflowing in RTL ([7b9462e](https://github.com/telerik/kendo-theme-default/commit/7b9462e))
* **grid:** prevent grid header from collapsing ([1c8267e](https://github.com/telerik/kendo-theme-default/commit/1c8267e))
* **grid:** prevent wraping and vertically align header column menu in IE ([55c1df1](https://github.com/telerik/kendo-theme-default/commit/55c1df1))
* **grid:** Recalculate edit mode textbox width ([f2354b5](https://github.com/telerik/kendo-theme-default/commit/f2354b5))
* **grid:** remove double border for browsers without scrollbar ([10c9980](https://github.com/telerik/kendo-theme-default/commit/10c9980))
* **grid:** Remove extra margin in header title in Firefox ([6a31326](https://github.com/telerik/kendo-theme-default/commit/6a31326))
* **grid:** remove extra padding in edit mode ([065c713](https://github.com/telerik/kendo-theme-default/commit/065c713))
* **grid:** Remove unnecessary checkbox styles (telerik/kendo[#7680](https://github.com/telerik/kendo-theme-default/issues/7680)) ([1f7abac](https://github.com/telerik/kendo-theme-default/commit/1f7abac))
* **grid:** selected alt rows must have the same shade as non-alt selected rows ([ce6ade1](https://github.com/telerik/kendo-theme-default/commit/ce6ade1))
* **grid:** Switch dirty cell overflow to visible ([f48d44c](https://github.com/telerik/kendo-theme-default/commit/f48d44c))
* **grid:** Tweak in-Grid edit mode widget width ([2474ea5](https://github.com/telerik/kendo-theme-default/commit/2474ea5))
* **grid:** update layout to be reused by other themes ([#230](https://github.com/telerik/kendo-theme-default/issues/230)) ([9a4838a](https://github.com/telerik/kendo-theme-default/commit/9a4838a))
* **grid:** use correct background-clip for grid ([decd830](https://github.com/telerik/kendo-theme-default/commit/decd830))
* **grid:** use flexbox chrome only when scrolling ([f2f5d92](https://github.com/telerik/kendo-theme-default/commit/f2f5d92))
* **grid:** virtual scrolling layout ([dca95a0](https://github.com/telerik/kendo-theme-default/commit/dca95a0)), closes [telerik/kendo-angular#449](https://github.com/telerik/kendo-angular/issues/449)
* **Grid:** Add validation tooltip styling ([1bfa082](https://github.com/telerik/kendo-theme-default/commit/1bfa082))
* **Grid:** Remove Batch edit mode TD padding ([7b77dab](https://github.com/telerik/kendo-theme-default/commit/7b77dab))
* **Grid:** Remove negative margins from input elements in inline edit mode ([e4fe447](https://github.com/telerik/kendo-theme-default/commit/e4fe447))
* **icons:** add aliases for portrait and landscape orientation icons ([cee4852](https://github.com/telerik/kendo-theme-default/commit/cee4852))
* **icons:** Add RTL styles for expand icon (telerik/kendo-ui-core[#3360](https://github.com/telerik/kendo-theme-default/issues/3360)) ([126ebf4](https://github.com/telerik/kendo-theme-default/commit/126ebf4))
* **icons:** update font to include KPI status and trend icons ([b3c0622](https://github.com/telerik/kendo-theme-default/commit/b3c0622))
* **icons:** update incorrect woff file path ([8aab17a](https://github.com/telerik/kendo-theme-default/commit/8aab17a))
* **icons:** use horizontal flipping for specifc rtl icons ([9c48e19](https://github.com/telerik/kendo-theme-default/commit/9c48e19))
* **icons:** use stronger selector for loading-icon ([#118](https://github.com/telerik/kendo-theme-default/issues/118)) ([38a6289](https://github.com/telerik/kendo-theme-default/commit/38a6289))
* **input:** handle special case of .k-input.k-textbox ([#114](https://github.com/telerik/kendo-theme-default/issues/114)) ([1c2285c](https://github.com/telerik/kendo-theme-default/commit/1c2285c))
* **input:** hide -ms-clear element [#105](https://github.com/telerik/kendo-theme-default/issues/105) ([58df7c5](https://github.com/telerik/kendo-theme-default/commit/58df7c5))
* **input:** use correct background-clip for input ([e2d3b5f](https://github.com/telerik/kendo-theme-default/commit/e2d3b5f))
* **inputs:** add missing focused styling to slider and switch ([4f72963](https://github.com/telerik/kendo-theme-default/commit/4f72963))
* **inputs:** apply font-size variable to simple textbox ([#853](https://github.com/telerik/kendo-theme-default/issues/853)) ([5f4dcc4](https://github.com/telerik/kendo-theme-default/commit/5f4dcc4))
* **inputs:** prioritize angular validation over HTML5 validation ([0adecba](https://github.com/telerik/kendo-theme-default/commit/0adecba)), closes [telerik/kendo-angular#511](https://github.com/telerik/kendo-angular/issues/511)
* **listbox:** use correct background-clip for listbox ([3fe2240](https://github.com/telerik/kendo-theme-default/commit/3fe2240))
* **ListBox:** Add vertical alignment addressing telerik/kendo[#7013](https://github.com/telerik/kendo-theme-default/issues/7013) ([7b0194e](https://github.com/telerik/kendo-theme-default/commit/7b0194e))
* **ListBox:** Set correct cursor for ListBox item ([fc9ce15](https://github.com/telerik/kendo-theme-default/commit/fc9ce15))
* **listview:** Add missing focused state, listview component to theme ([df4d3c9](https://github.com/telerik/kendo-theme-default/commit/df4d3c9))
* **loading:** small icon is invisible in Chrome 61 ([642a796](https://github.com/telerik/kendo-theme-default/commit/642a796))
* **loading-icon:** hide text inside loading icon ([d0f47f1](https://github.com/telerik/kendo-theme-default/commit/d0f47f1))
* **map:** Add 100% height to the Map's scroll container ([bc94117](https://github.com/telerik/kendo-theme-default/commit/bc94117))
* **map:** Add marker color ([383206d](https://github.com/telerik/kendo-theme-default/commit/383206d))
* **map:** use svg / font icon instead of image sprite ([491a1f4](https://github.com/telerik/kendo-theme-default/commit/491a1f4))
* **masked/numeric:** Correct position of invalid state icon in RTL ([c999ab2](https://github.com/telerik/kendo-theme-default/commit/c999ab2))
* **maskedtextbox:** allow width to be set on host element ([215890b](https://github.com/telerik/kendo-theme-default/commit/215890b))
* **maskedtextbox:** appearance ([f4a5de3](https://github.com/telerik/kendo-theme-default/commit/f4a5de3))
* **maskedtextbox:** missing border ([ffdfad1](https://github.com/telerik/kendo-theme-default/commit/ffdfad1)), closes [telerik/kendo-theme-default#331](https://github.com/telerik/kendo-theme-default/issues/331)
* **maskedtextbox:** styling refactoring ([8b7c4e5](https://github.com/telerik/kendo-theme-default/commit/8b7c4e5))
* **math:** handle zero values in add-* mixins ([dff792b](https://github.com/telerik/kendo-theme-default/commit/dff792b))
* **mediaplayer:** add opacity to toolbar ([8919a30](https://github.com/telerik/kendo-theme-default/commit/8919a30))
* **mediaplayer:** drag handle in volume slider is not correctly positioned ([80c09fa](https://github.com/telerik/kendo-theme-default/commit/80c09fa))
* **mediaplayer:** make track slider 100% wide ([2f65105](https://github.com/telerik/kendo-theme-default/commit/2f65105))
* **mediaplayer:** use correct padding for mediaplayer toolbar ([c39318b](https://github.com/telerik/kendo-theme-default/commit/c39318b))
* **mediaplyer:** use correct background-clip for mediaplayer ([ffd580a](https://github.com/telerik/kendo-theme-default/commit/ffd580a))
* **menu:** add missing styles for context menu wrapper ([a690733](https://github.com/telerik/kendo-theme-default/commit/a690733))
* **menu:** Add nowrap rule for Menu links ([f832b6b](https://github.com/telerik/kendo-theme-default/commit/f832b6b))
* **menu:** add styles for menu rtl ([e2fd491](https://github.com/telerik/kendo-theme-default/commit/e2fd491))
* **menu:** menu items must nost srink when scrolling is enabled ([3f7dd04](https://github.com/telerik/kendo-theme-default/commit/3f7dd04))
* **menu:** scroll arrows are missaligned ([a8019a7](https://github.com/telerik/kendo-theme-default/commit/a8019a7))
* **menu:** use correct background-clip for menu ([6ede243](https://github.com/telerik/kendo-theme-default/commit/6ede243))
* **multiselect:** add invalid state for Angular ([9af0ad4](https://github.com/telerik/kendo-theme-default/commit/9af0ad4))
* **multiselect:** align search bar after tokens ([582baa8](https://github.com/telerik/kendo-theme-default/commit/582baa8))
* **multiselect:** clear button position ([#576](https://github.com/telerik/kendo-theme-default/issues/576)) ([1ebac36](https://github.com/telerik/kendo-theme-default/commit/1ebac36))
* **multiselect:** do not inherit global .k-button width ([8ffb16c](https://github.com/telerik/kendo-theme-default/commit/8ffb16c))
* **multiselect:** extract border-radius to multiselect layout ([7d19828](https://github.com/telerik/kendo-theme-default/commit/7d19828))
* **multiselect:** hide loading icon ([1cbd639](https://github.com/telerik/kendo-theme-default/commit/1cbd639))
* **multiselect:** improve height of token with empty string telerik/kendo-ui-core[#3723](https://github.com/telerik/kendo-theme-default/issues/3723) ([f8713c4](https://github.com/telerik/kendo-theme-default/commit/f8713c4))
* **multiselect:** layout fixes ([467d8c1](https://github.com/telerik/kendo-theme-default/commit/467d8c1))
* **multiselect:** use correct background-clip for multiselect ([0f9ceaf](https://github.com/telerik/kendo-theme-default/commit/0f9ceaf))
* **multiselect:** use text cursor across focusable area ([8207562](https://github.com/telerik/kendo-theme-default/commit/8207562))
* **multiselect:** virtualized items are not styled ([2c9dfb8](https://github.com/telerik/kendo-theme-default/commit/2c9dfb8))
* **multiselect:** wrap text on long items ([f512790](https://github.com/telerik/kendo-theme-default/commit/f512790)), closes [#263](https://github.com/telerik/kendo-theme-default/issues/263)
* **multiselect:** wrong padding in RTL ([3ef4f71](https://github.com/telerik/kendo-theme-default/commit/3ef4f71))
* **multiselect:** wrong width in IE ([accf6ee](https://github.com/telerik/kendo-theme-default/commit/accf6ee))
* **notification:** add styles for rtl ([9ae4f92](https://github.com/telerik/kendo-theme-default/commit/9ae4f92))
* **notification:** Adjust close icon position ([#78](https://github.com/telerik/kendo-theme-default/issues/78)) ([#162](https://github.com/telerik/kendo-theme-default/issues/162)) ([83bcc85](https://github.com/telerik/kendo-theme-default/commit/83bcc85))
* **notification:** fix padding and close button position ([b5483f6](https://github.com/telerik/kendo-theme-default/commit/b5483f6))
* **notification:** improve close button position ([c5ae062](https://github.com/telerik/kendo-theme-default/commit/c5ae062))
* **notification:** Position close button ([#131](https://github.com/telerik/kendo-theme-default/issues/131)) ([4b2cb7f](https://github.com/telerik/kendo-theme-default/commit/4b2cb7f))
* **notification:** use small font size, introduce variables ([ba6a6b4](https://github.com/telerik/kendo-theme-default/commit/ba6a6b4))
* **numercitextbox:** use correct background-clip for numercitextbox ([1a29f67](https://github.com/telerik/kendo-theme-default/commit/1a29f67))
* **NumericTB:** Fix invalid state spinners color ([1605c01](https://github.com/telerik/kendo-theme-default/commit/1605c01))
* **numerictextbox:** Adjust flex of input fixing Edge weirdness ([d6a758a](https://github.com/telerik/kendo-theme-default/commit/d6a758a))
* **numerictextbox:** icons are not vertically aligned ([7a55a83](https://github.com/telerik/kendo-theme-default/commit/7a55a83))
* **numerictextbox:** k-select links alignment ([9b34417](https://github.com/telerik/kendo-theme-default/commit/9b34417))
* **numerictextbox:** remove invalid input border in Firefox ([08a2770](https://github.com/telerik/kendo-theme-default/commit/08a2770))
* **numerictextbox:** spinner icons alignment; fix select width ([ac4ad5f](https://github.com/telerik/kendo-theme-default/commit/ac4ad5f))
* **numerictextbox:** spinners active appearance ([50d5c8a](https://github.com/telerik/kendo-theme-default/commit/50d5c8a))
* **NumericTextbox:** Improve invalid state feedback icon positioning ([0dce499](https://github.com/telerik/kendo-theme-default/commit/0dce499))
* **pager:** disabled pager links should inherit color ([be5ed18](https://github.com/telerik/kendo-theme-default/commit/be5ed18))
* **pager:** use -padding- for pager ([aa00773](https://github.com/telerik/kendo-theme-default/commit/aa00773))
* **pager:** use flexbox to improve numeric pager align ([540f548](https://github.com/telerik/kendo-theme-default/commit/540f548))
* **panelbar:** style fixes ([#115](https://github.com/telerik/kendo-theme-default/issues/115)) ([67cb403](https://github.com/telerik/kendo-theme-default/commit/67cb403))
* **panelbar:** toggle arrow is in the wrong place for k1 ([2d325c3](https://github.com/telerik/kendo-theme-default/commit/2d325c3))
* **panelbar:** use correct background-clip for panelbar ([3f30da3](https://github.com/telerik/kendo-theme-default/commit/3f30da3))
* **panelbar:** use header variables for item padding ([#265](https://github.com/telerik/kendo-theme-default/issues/265)) ([2ab5c58](https://github.com/telerik/kendo-theme-default/commit/2ab5c58))
* **PanelBar:** update border color of subgroups ([ec933d0](https://github.com/telerik/kendo-theme-default/commit/ec933d0))
* **panels:** styling panels ([0e5c9b8](https://github.com/telerik/kendo-theme-default/commit/0e5c9b8))
* **pickers:** remove focus outline ([16064f3](https://github.com/telerik/kendo-theme-default/commit/16064f3))
* **pivot:** use correct background-clip for pivot ([e745463](https://github.com/telerik/kendo-theme-default/commit/e745463))
* **pivotgrid:** Add missing styles for pseudo elements in PDF export ([28714b1](https://github.com/telerik/kendo-theme-default/commit/28714b1))
* **pivotgrid:** Make grid cells non-wrapable ([defff41](https://github.com/telerik/kendo-theme-default/commit/defff41))
* **pivotgrid:** Remove flex from Grid container, add border-width ([2711bbc](https://github.com/telerik/kendo-theme-default/commit/2711bbc))
* **pivotgrid:** use correct KPI icons ([70b5a56](https://github.com/telerik/kendo-theme-default/commit/70b5a56))
* **popup:** apply popup styles to animation-container ([c6e24ca](https://github.com/telerik/kendo-theme-default/commit/c6e24ca))
* **popup:** no data template alignment in IE ([7263fb7](https://github.com/telerik/kendo-theme-default/commit/7263fb7))
* **popup:** style option label like regular items ([10c9d55](https://github.com/telerik/kendo-theme-default/commit/10c9d55))
* **popup:** use correct background-clip for popup ([1c0046c](https://github.com/telerik/kendo-theme-default/commit/1c0046c))
* **popup:** use specific variable for selected text ([fea14bd](https://github.com/telerik/kendo-theme-default/commit/fea14bd))
* **progressbar:** Add progress status background color ([#129](https://github.com/telerik/kendo-theme-default/issues/129)) ([3923c46](https://github.com/telerik/kendo-theme-default/commit/3923c46))
* **progressbar:** improve fluid progress ([62c6447](https://github.com/telerik/kendo-theme-default/commit/62c6447))
* **progressbar:** improve styling of chunked upload ([d38567a](https://github.com/telerik/kendo-theme-default/commit/d38567a))
* **progressbar:** imrpove selected state position [#764](https://github.com/telerik/kendo-theme-default/issues/764) ([702111f](https://github.com/telerik/kendo-theme-default/commit/702111f))
* **progressbar:** progressbar is missing gradient ([200bfef](https://github.com/telerik/kendo-theme-default/commit/200bfef))
* **progressbar:** use correct background-clip for progressbar ([7a69c77](https://github.com/telerik/kendo-theme-default/commit/7a69c77))
* **progressbar:** use correct border-radius ([ffeaf81](https://github.com/telerik/kendo-theme-default/commit/ffeaf81))
* **ripple:** contain ripple in its container ([5a65049](https://github.com/telerik/kendo-theme-default/commit/5a65049))
* **ripple:** improve effect in flat primary button ([b44fd95](https://github.com/telerik/kendo-theme-default/commit/b44fd95))
* **scheduler:** add spacing between text and icon in show full day ([9af6039](https://github.com/telerik/kendo-theme-default/commit/9af6039))
* **scheduler:** border-color is not properly inherited in FireFox and IE ([35bf322](https://github.com/telerik/kendo-theme-default/commit/35bf322))
* **scheduler:** expand scheduler to its content in IE ([cc190d9](https://github.com/telerik/kendo-theme-default/commit/cc190d9))
* **scheduler:** improve inner dimensions of scheduler ([2d6008f](https://github.com/telerik/kendo-theme-default/commit/2d6008f))
* **scheduler:** RTL appointment resizing issues ([48c33a6](https://github.com/telerik/kendo-theme-default/commit/48c33a6))
* **scheduler:** rtl buttons positioning and border radiuses ([6a5d273](https://github.com/telerik/kendo-theme-default/commit/6a5d273))
* **scheduler:** scope styles for recurrence editors ([bf61394](https://github.com/telerik/kendo-theme-default/commit/bf61394))
* **scheduler:** use correct background-clip for scheduler ([35eb805](https://github.com/telerik/kendo-theme-default/commit/35eb805))
* **scheduler:** wrong close button position in agenda view in rtl ([57aa9bc](https://github.com/telerik/kendo-theme-default/commit/57aa9bc))
* **scheduler:** wrong event actions position ([b75695e](https://github.com/telerik/kendo-theme-default/commit/b75695e))
* **scrollview:** add min flex width for pager ([ecf608d](https://github.com/telerik/kendo-theme-default/commit/ecf608d))
* **scrollview:** add static position for kendo-jquery-scrollview ([7c19eac](https://github.com/telerik/kendo-theme-default/commit/7c19eac))
* **scrollview:** add styles for kendo-jquery-scrollview ([7b464fe](https://github.com/telerik/kendo-theme-default/commit/7b464fe))
* **scrollview:** Add styles for Mobile widget (telerik/kendo[#6508](https://github.com/telerik/kendo-theme-default/issues/6508)) ([#125](https://github.com/telerik/kendo-theme-default/issues/125)) ([a014812](https://github.com/telerik/kendo-theme-default/commit/a014812))
* **scrollview:** add styles for scrollview pager for kendo-jquery ([fce1ebe](https://github.com/telerik/kendo-theme-default/commit/fce1ebe))
* **scrollview:** handle variable button size ([3168f58](https://github.com/telerik/kendo-theme-default/commit/3168f58))
* **scrollview:** tweak flex-grow for pager items ([59f55e5](https://github.com/telerik/kendo-theme-default/commit/59f55e5))
* **scrollview:** use flexbox for scrollview pager ([6bfa1c7](https://github.com/telerik/kendo-theme-default/commit/6bfa1c7))
* **scrollview:** wrong styling on prev/next arrows ([d5a0875](https://github.com/telerik/kendo-theme-default/commit/d5a0875)), closes [telerik/kendo-theme-default#342](https://github.com/telerik/kendo-theme-default/issues/342)
* **slider:** add d.ts file for slider ([#12](https://github.com/telerik/kendo-theme-default/issues/12)) ([83ce469](https://github.com/telerik/kendo-theme-default/commit/83ce469))
* **slider:** draghandle styling improvements ([c451203](https://github.com/telerik/kendo-theme-default/commit/c451203))
* **slider:** extract metrics variables ([#619](https://github.com/telerik/kendo-theme-default/issues/619)) ([fbf5628](https://github.com/telerik/kendo-theme-default/commit/fbf5628))
* **slider:** include component name in path to icons ([038bc1f](https://github.com/telerik/kendo-theme-default/commit/038bc1f))
* **slider:** interaction states. ([238dde0](https://github.com/telerik/kendo-theme-default/commit/238dde0)), closes [telerik/kendo-theme-default#225](https://github.com/telerik/kendo-theme-default/issues/225)
* **slider:** large ticks appearance ([095b645](https://github.com/telerik/kendo-theme-default/commit/095b645))
* **slider:** remove focus outline ([be18669](https://github.com/telerik/kendo-theme-default/commit/be18669))
* **slider:** revert regression in slider animation ([3e96000](https://github.com/telerik/kendo-theme-default/commit/3e96000))
* **slider:** rtl buttons styling ([862d561](https://github.com/telerik/kendo-theme-default/commit/862d561))
* **slider:** vertical ticks are misaligned ([c602975](https://github.com/telerik/kendo-theme-default/commit/c602975))
* **sortable:** apply default display to sortable container ([d1bfa95](https://github.com/telerik/kendo-theme-default/commit/d1bfa95))
* **sparkline:** remove border and padding from tooltip ([1f77425](https://github.com/telerik/kendo-theme-default/commit/1f77425))
* **splitter:** fix flipped collapse arrow in rtl ([9095247](https://github.com/telerik/kendo-theme-default/commit/9095247))
* **splitter:** Fix resize handle, pointer cursor telerik/kendo[#6508](https://github.com/telerik/kendo-theme-default/issues/6508) ([#122](https://github.com/telerik/kendo-theme-default/issues/122)) ([07dfc3a](https://github.com/telerik/kendo-theme-default/commit/07dfc3a))
* **splitter:** nested resize handles have the wrong background ([cfa1aab](https://github.com/telerik/kendo-theme-default/commit/cfa1aab))
* **splitter:** reverse panes in RTL mode ([bd373d3](https://github.com/telerik/kendo-theme-default/commit/bd373d3))
* **splitter:** splitter needs to be inline-flex in gantt ([1016d2a](https://github.com/telerik/kendo-theme-default/commit/1016d2a))
* **splitter:** use col/row-resize cursors ([d1bf7cd](https://github.com/telerik/kendo-theme-default/commit/d1bf7cd))
* **splitter:** use correct background-clip for splitter ([de4a4bb](https://github.com/telerik/kendo-theme-default/commit/de4a4bb))
* **splitter:** use correct colors for splitter normal and hover state ([e5a1f91](https://github.com/telerik/kendo-theme-default/commit/e5a1f91))
* **spreadhsheet:** Add styles for active cell within selection ([574c4ca](https://github.com/telerik/kendo-theme-default/commit/574c4ca))
* **spreadsheet:** add assumed box-sizing for buttons ([00d5fd6](https://github.com/telerik/kendo-theme-default/commit/00d5fd6))
* **spreadsheet:** add styles for formula bar icon ([282156f](https://github.com/telerik/kendo-theme-default/commit/282156f))
* **spreadsheet:** add styles for formula list ([73a2144](https://github.com/telerik/kendo-theme-default/commit/73a2144))
* **spreadsheet:** add styles for spreadsheet autofill range resizing ([f5dc736](https://github.com/telerik/kendo-theme-default/commit/f5dc736))
* **spreadsheet:** borders do not render in 2017.2.x ([7d6b34a](https://github.com/telerik/kendo-theme-default/commit/7d6b34a))
* **spreadsheet:** custom editor button not visible ([f6e3c91](https://github.com/telerik/kendo-theme-default/commit/f6e3c91))
* **spreadsheet:** fix more format layout ([d34f221](https://github.com/telerik/kendo-theme-default/commit/d34f221))
* **spreadsheet:** improve active cell borders by frozen cells telerik/kendo-ui-core[#3254](https://github.com/telerik/kendo-theme-default/issues/3254) ([44bcf30](https://github.com/telerik/kendo-theme-default/commit/44bcf30))
* **spreadsheet:** improve custom formatting dialog ([31f3092](https://github.com/telerik/kendo-theme-default/commit/31f3092))
* **spreadsheet:** improve formula syntax highlight ([dde4575](https://github.com/telerik/kendo-theme-default/commit/dde4575))
* **spreadsheet:** improve formula syntax highlight ([1bdb226](https://github.com/telerik/kendo-theme-default/commit/1bdb226))
* **spreadsheet:** improve spreadsheet dialog layout ([b9fa2ad](https://github.com/telerik/kendo-theme-default/commit/b9fa2ad))
* **spreadsheet:** improve spreadsheet toolbar and tabstrip layout ([615cd91](https://github.com/telerik/kendo-theme-default/commit/615cd91))
* **spreadsheet:** Missing indicator for Spreadsheet range resizing ([6922fd4](https://github.com/telerik/kendo-theme-default/commit/6922fd4))
* **spreadsheet:** page orientation icon in export dialog is not properly positioned ([67c4f2b](https://github.com/telerik/kendo-theme-default/commit/67c4f2b))
* **spreadsheet:** remove border radius of spreadsheet toolbar area ([f3dbdf9](https://github.com/telerik/kendo-theme-default/commit/f3dbdf9))
* **spreadsheet:** remove window customization from spreadsheet ([67fe651](https://github.com/telerik/kendo-theme-default/commit/67fe651))
* **spreadsheet:** replace hardcoded color for merged-cell by variable ([951e2bf](https://github.com/telerik/kendo-theme-default/commit/951e2bf))
* **spreadsheet:** use correct background-clip for spreadsheet ([92e9e27](https://github.com/telerik/kendo-theme-default/commit/92e9e27))
* **spreadsheet:** wrong custom editor button width ([1cb3bdd](https://github.com/telerik/kendo-theme-default/commit/1cb3bdd))
* **stockchart:** navigator handles layout ([64c46b2](https://github.com/telerik/kendo-theme-default/commit/64c46b2))
* **switch:** displaced switch handle ([7296a65](https://github.com/telerik/kendo-theme-default/commit/7296a65)), closes [telerik/kendo-theme-default#226](https://github.com/telerik/kendo-theme-default/issues/226)
* **switch:** improve labels positioning ([#758](https://github.com/telerik/kendo-theme-default/issues/758)) ([dd770bb](https://github.com/telerik/kendo-theme-default/commit/dd770bb))
* **switch:** metrics ([b604715](https://github.com/telerik/kendo-theme-default/commit/b604715))
* **switch:** missing border on macOS / retina displays ([#374](https://github.com/telerik/kendo-theme-default/issues/374)) ([a4728bf](https://github.com/telerik/kendo-theme-default/commit/a4728bf)), closes [telerik/kendo-theme-default#367](https://github.com/telerik/kendo-theme-default/issues/367)
* **switch:** off lable color and contrast ([67c8f35](https://github.com/telerik/kendo-theme-default/commit/67c8f35))
* **switch:** remove focus outline ([57a790a](https://github.com/telerik/kendo-theme-default/commit/57a790a))
* **switch:** use calc for mixed units ([39c52a9](https://github.com/telerik/kendo-theme-default/commit/39c52a9))
* **switch:** use correct background-clip for switch ([a28958a](https://github.com/telerik/kendo-theme-default/commit/a28958a))
* **switch:** use variable units for RTL labels ([#346](https://github.com/telerik/kendo-theme-default/issues/346)) ([4aed3e7](https://github.com/telerik/kendo-theme-default/commit/4aed3e7))
* **tabstrip:** add styles for closable tabstrip ([dbea750](https://github.com/telerik/kendo-theme-default/commit/dbea750))
* **tabstrip:** enable :normal and :hover state customization of individual tabstrip items ([0e0579a](https://github.com/telerik/kendo-theme-default/commit/0e0579a))
* **tabstrip:** improve alignment of close icon ([347e8ad](https://github.com/telerik/kendo-theme-default/commit/347e8ad))
* **tabstrip:** improve layout when wrapper height is set ([bb49170](https://github.com/telerik/kendo-theme-default/commit/bb49170)), closes [#495](https://github.com/telerik/kendo-theme-default/issues/495)
* **tabstrip:** set host display ([3a3f40d](https://github.com/telerik/kendo-theme-default/commit/3a3f40d))
* **tabstrip:** tabstrip scrolling ([#112](https://github.com/telerik/kendo-theme-default/issues/112)) ([f2e6b10](https://github.com/telerik/kendo-theme-default/commit/f2e6b10))
* **tabstrip:** tweak tabstrip styles ([#111](https://github.com/telerik/kendo-theme-default/issues/111)) ([bb5187b](https://github.com/telerik/kendo-theme-default/commit/bb5187b))
* **tabstrip:** use correct background-clip for tabstrip ([2f5292e](https://github.com/telerik/kendo-theme-default/commit/2f5292e))
* **tabstrip:** use scoped tabstrip variables for styling ([4e61adf](https://github.com/telerik/kendo-theme-default/commit/4e61adf))
* **textbox:** add RTL styles for floating label ([#842](https://github.com/telerik/kendo-theme-default/issues/842)) ([5639c7a](https://github.com/telerik/kendo-theme-default/commit/5639c7a))
* **textbox:** apply default width to textbox container ([0b8cd37](https://github.com/telerik/kendo-theme-default/commit/0b8cd37))
* **textbox:** disallow selection of floating label ([54df3e1](https://github.com/telerik/kendo-theme-default/commit/54df3e1))
* **textbox:** inherit kendo-textbox-container size ([e448eac](https://github.com/telerik/kendo-theme-default/commit/e448eac))
* **textbox:** use classes for styling ([4601174](https://github.com/telerik/kendo-theme-default/commit/4601174))
* **textbox:** workaround IE11 limitation ([1cfc1a9](https://github.com/telerik/kendo-theme-default/commit/1cfc1a9))
* **timepicker:** add time list focus state ([#656](https://github.com/telerik/kendo-theme-default/issues/656)) ([e852cda](https://github.com/telerik/kendo-theme-default/commit/e852cda))
* **timepicker:** align time list on MacOS ([f8b9de7](https://github.com/telerik/kendo-theme-default/commit/f8b9de7))
* **timepicker:** update highlight border-color ([7dd890d](https://github.com/telerik/kendo-theme-default/commit/7dd890d))
* **timepicker:** update time list focus state ([#662](https://github.com/telerik/kendo-theme-default/issues/662)) ([aeccee5](https://github.com/telerik/kendo-theme-default/commit/aeccee5))
* **toolbar:** fix overflow button position in RTL telerik/kendo[#8009](https://github.com/telerik/kendo-theme-default/issues/8009) ([2389a89](https://github.com/telerik/kendo-theme-default/commit/2389a89))
* **toolbar:** improve disabled appearance of button telerik/kendo-ui-core[#3684](https://github.com/telerik/kendo-theme-default/issues/3684) ([1d2b3f3](https://github.com/telerik/kendo-theme-default/commit/1d2b3f3))
* **toolbar:** prevent overflowing templates content [#784](https://github.com/telerik/kendo-theme-default/issues/784) ([1e556c5](https://github.com/telerik/kendo-theme-default/commit/1e556c5))
* **toolbar:** use correct background-clip for toolbar ([bb3fa99](https://github.com/telerik/kendo-theme-default/commit/bb3fa99))
* **toolbar:** use correct colors for toggled button ([d53c49f](https://github.com/telerik/kendo-theme-default/commit/d53c49f))
* **toolbar:** wrong split button focus and expand state ([37e45ea](https://github.com/telerik/kendo-theme-default/commit/37e45ea))
* **tooltip:** add callout styles ([9882ec1](https://github.com/telerik/kendo-theme-default/commit/9882ec1))
* **tooltip:** use contrast-wcag for tooltip ([cc86875](https://github.com/telerik/kendo-theme-default/commit/cc86875))
* **tooltip:** use correct padding for collapsible tooltip ([844037f](https://github.com/telerik/kendo-theme-default/commit/844037f))
* **tooltip:** use correct padding for collapsible tooltip ([2ad3894](https://github.com/telerik/kendo-theme-default/commit/2ad3894))
* **Treelist:** Add k-display-block class to handle frozen columns ([98b891d](https://github.com/telerik/kendo-theme-default/commit/98b891d))
* **treeview:** add treeview rtl styles ([40699b5](https://github.com/telerik/kendo-theme-default/commit/40699b5))
* **treeview:** hide scrollbars during a node expansion ([d6541f4](https://github.com/telerik/kendo-theme-default/commit/d6541f4))
* **treeview:** reduce spacing between checkbox and item text ([0556e46](https://github.com/telerik/kendo-theme-default/commit/0556e46))
* **treeview:** remove outline when focus is on items ([b062f16](https://github.com/telerik/kendo-theme-default/commit/b062f16))
* **treeview:** treeview alignment ([#116](https://github.com/telerik/kendo-theme-default/issues/116)) ([4dce864](https://github.com/telerik/kendo-theme-default/commit/4dce864))
* **treeview:** update item layout ([#259](https://github.com/telerik/kendo-theme-default/issues/259)) ([28d3411](https://github.com/telerik/kendo-theme-default/commit/28d3411))
* **treeview:** use correct background-clip for treeview ([90b7960](https://github.com/telerik/kendo-theme-default/commit/90b7960))
* **treeview:** use correct border radius and box shadow for treeview items ([22a75bc](https://github.com/telerik/kendo-theme-default/commit/22a75bc))
* **treeview:** use correct metrics for treeview ([80c8215](https://github.com/telerik/kendo-theme-default/commit/80c8215))
* **upload:** add RTL styling ([#245](https://github.com/telerik/kendo-theme-default/issues/245)) ([fc49b80](https://github.com/telerik/kendo-theme-default/commit/fc49b80))
* **upload:** decrease metric of file list ([441c163](https://github.com/telerik/kendo-theme-default/commit/441c163))
* **upload:** extract metrics variables ([d9db8d3](https://github.com/telerik/kendo-theme-default/commit/d9db8d3))
* **upload:** failed to upload item icon color ([575cd8b](https://github.com/telerik/kendo-theme-default/commit/575cd8b))
* **upload:** improve metrics of toolbar ([a8e8fe7](https://github.com/telerik/kendo-theme-default/commit/a8e8fe7))
* **upload:** incorrect icon size when used with Bootstrap ([47fe0e7](https://github.com/telerik/kendo-theme-default/commit/47fe0e7)), closes [telerik/kendo-angular-upload#39](https://github.com/telerik/kendo-angular-upload/issues/39) [#151](https://github.com/telerik/kendo-theme-default/issues/151)
* **upload:** increase empty space after file name for chunk upload telerik/kendo-ui-core[#3021](https://github.com/telerik/kendo-theme-default/issues/3021) ([b51d5b7](https://github.com/telerik/kendo-theme-default/commit/b51d5b7))
* **upload:** move some metrics to the theme file ([8b3d214](https://github.com/telerik/kendo-theme-default/commit/8b3d214))
* **upload:** trim long file names ([aaa4ff7](https://github.com/telerik/kendo-theme-default/commit/aaa4ff7))
* **upload:** un-nest k-upload button selector ([547ef6a](https://github.com/telerik/kendo-theme-default/commit/547ef6a))
* **upload:** use correct background-clip for upload ([51ccb48](https://github.com/telerik/kendo-theme-default/commit/51ccb48))
* **upload:** visual glitches ([#97](https://github.com/telerik/kendo-theme-default/issues/97)) ([4d00a64](https://github.com/telerik/kendo-theme-default/commit/4d00a64)), closes [telerik/kendo-theme-default#95](https://github.com/telerik/kendo-theme-default/issues/95)
* **validation:** allow nesting of validation tooltip in kendo-popup ([874d572](https://github.com/telerik/kendo-theme-default/commit/874d572))
* **validation:** check ng-dirty and ng-touched before showing errors ([35cef0d](https://github.com/telerik/kendo-theme-default/commit/35cef0d)), closes [#127](https://github.com/telerik/kendo-theme-default/issues/127)
* **validator:** validation message is not aligned ([3f1e21a](https://github.com/telerik/kendo-theme-default/commit/3f1e21a))
* **window:** add styles for content frame ([36bbcfa](https://github.com/telerik/kendo-theme-default/commit/36bbcfa)), closes [#510](https://github.com/telerik/kendo-theme-default/issues/510)
* **window:** add styles for predefined dialog prompt ([454abd7](https://github.com/telerik/kendo-theme-default/commit/454abd7))
* **window:** Adjust header height telerik/kendo[#6508](https://github.com/telerik/kendo-theme-default/issues/6508) ([#100](https://github.com/telerik/kendo-theme-default/issues/100)) ([5fa3cf0](https://github.com/telerik/kendo-theme-default/commit/5fa3cf0))
* **window:** align content with title text ([581f650](https://github.com/telerik/kendo-theme-default/commit/581f650))
* **window:** fix title height for Bootstrap skin [#752](https://github.com/telerik/kendo-theme-default/issues/752) ([9045a54](https://github.com/telerik/kendo-theme-default/commit/9045a54))
* remove inappropriate rule ([a7664f6](https://github.com/telerik/kendo-theme-default/commit/a7664f6))
* remove inherited background from pickers ([212bae6](https://github.com/telerik/kendo-theme-default/commit/212bae6))
* remove native focus outline from popup items ([62cb150](https://github.com/telerik/kendo-theme-default/commit/62cb150))
* remove negative margin of action buttons ([abe8f5f](https://github.com/telerik/kendo-theme-default/commit/abe8f5f))
* remove outdated rule ([956985d](https://github.com/telerik/kendo-theme-default/commit/956985d))
* remove redundant font formats ([5bdc800](https://github.com/telerik/kendo-theme-default/commit/5bdc800))
* remove slider outline ([3075766](https://github.com/telerik/kendo-theme-default/commit/3075766))
* remove switch outline ([09c3a00](https://github.com/telerik/kendo-theme-default/commit/09c3a00))
* remove text-decoration of links ([b402fc5](https://github.com/telerik/kendo-theme-default/commit/b402fc5)), closes [telerik/kendo-angular-scrollview#49](https://github.com/telerik/kendo-angular-scrollview/issues/49)
* remove unnecessary variable ([2643b98](https://github.com/telerik/kendo-theme-default/commit/2643b98))
* remove widgets focus outline ([e19501d](https://github.com/telerik/kendo-theme-default/commit/e19501d))
* rename dialog slide-in effect ([92f90f0](https://github.com/telerik/kendo-theme-default/commit/92f90f0))
* rename input-container to textbox-container, use k-state-empty class ([4c03d85](https://github.com/telerik/kendo-theme-default/commit/4c03d85))
* resolve ruby sass error ([8071100](https://github.com/telerik/kendo-theme-default/commit/8071100))
* reuse common module webpack config for building theme ([92b267c](https://github.com/telerik/kendo-theme-default/commit/92b267c))
* revert 2ff88d3 ([ee1af32](https://github.com/telerik/kendo-theme-default/commit/ee1af32))
* RTL styles for the Slider and Switch ([#344](https://github.com/telerik/kendo-theme-default/issues/344)) ([8f0b432](https://github.com/telerik/kendo-theme-default/commit/8f0b432))
* set block display for dialog host elements ([abc8437](https://github.com/telerik/kendo-theme-default/commit/abc8437))
* set display type of panelbar to work with ng2 host elements ([c460011](https://github.com/telerik/kendo-theme-default/commit/c460011))
* sparkline tooltip marker appearance. ([27d1b72](https://github.com/telerik/kendo-theme-default/commit/27d1b72)), closes [telerik/kendo-theme-default#249](https://github.com/telerik/kendo-theme-default/issues/249)
* split button in normal state misses borders, bg and border-radius ([a953400](https://github.com/telerik/kendo-theme-default/commit/a953400))
* split button in normal state misses borders, bg and border-radius ([b045e71](https://github.com/telerik/kendo-theme-default/commit/b045e71))
* style new overflow wrapper telerik/kendo-ui-core[#3254](https://github.com/telerik/kendo-theme-default/issues/3254) ([1ce1415](https://github.com/telerik/kendo-theme-default/commit/1ce1415))
* tab hover styles ([c76e205](https://github.com/telerik/kendo-theme-default/commit/c76e205))
* tabs alignment in right/left positions ([54e5577](https://github.com/telerik/kendo-theme-default/commit/54e5577))
* tabstrip active tab border ([5961f0d](https://github.com/telerik/kendo-theme-default/commit/5961f0d))
* textbox focused box-shadow ([75f9011](https://github.com/telerik/kendo-theme-default/commit/75f9011))
* title bar overflows dialog ([3347a45](https://github.com/telerik/kendo-theme-default/commit/3347a45))
* tooltip validation appearance ([96fb5de](https://github.com/telerik/kendo-theme-default/commit/96fb5de))
* trim down npm package, provide dist files ([cf6c77a](https://github.com/telerik/kendo-theme-default/commit/cf6c77a))
* Tweak pressed button shadow ([#172](https://github.com/telerik/kendo-theme-default/issues/172)) ([#210](https://github.com/telerik/kendo-theme-default/issues/210)) ([476d504](https://github.com/telerik/kendo-theme-default/commit/476d504))
* unify design of dialog buttons and action buttons ([e54a288](https://github.com/telerik/kendo-theme-default/commit/e54a288))
* update bootstrap dependency ([#765](https://github.com/telerik/kendo-theme-default/issues/765)) ([b53effc](https://github.com/telerik/kendo-theme-default/commit/b53effc))
* update Bootstrap dependency to v4 official ([e96f66b](https://github.com/telerik/kendo-theme-default/commit/e96f66b))
* update dialog action buttons layout; update dialog titlebar sizing ([d87857d](https://github.com/telerik/kendo-theme-default/commit/d87857d))
* update dropdowns transtions ([da3ac97](https://github.com/telerik/kendo-theme-default/commit/da3ac97))
* update license ([8e9fbe6](https://github.com/telerik/kendo-theme-default/commit/8e9fbe6))
* update panelbar states colors ([085bb05](https://github.com/telerik/kendo-theme-default/commit/085bb05))
* update upload styling to match the new design. ([642d3f4](https://github.com/telerik/kendo-theme-default/commit/642d3f4)), closes [telerik/kendo-theme-default#152](https://github.com/telerik/kendo-theme-default/issues/152)
* upload action buttons styling; disabled upload styling ([f58863e](https://github.com/telerik/kendo-theme-default/commit/f58863e))
* upload header background ([e16bf1f](https://github.com/telerik/kendo-theme-default/commit/e16bf1f))
* upload status icon margin ([c0e4cdf](https://github.com/telerik/kendo-theme-default/commit/c0e4cdf))
* use .k-fieldset class to style fieldsets ([#146](https://github.com/telerik/kendo-theme-default/issues/146)) ([e94b839](https://github.com/telerik/kendo-theme-default/commit/e94b839)), closes [telerik/kendo-angular2#193](https://github.com/telerik/kendo-angular2/issues/193)
* use calc to allow mixing of rem/px ([#166](https://github.com/telerik/kendo-theme-default/issues/166)) ([7b07f4b](https://github.com/telerik/kendo-theme-default/commit/7b07f4b))
* use contrast-wcag for variables and grid ([bffe632](https://github.com/telerik/kendo-theme-default/commit/bffe632))
* use correct line-height in autocomplete ([a4bdb22](https://github.com/telerik/kendo-theme-default/commit/a4bdb22))
* use deeper path to hint widget for proper font path ([723bd80](https://github.com/telerik/kendo-theme-default/commit/723bd80))
* use flexbox for dialog centering ([307fad0](https://github.com/telerik/kendo-theme-default/commit/307fad0)), closes [telerik/kendo-angular#227](https://github.com/telerik/kendo-angular/issues/227)
* use icon-size instead of mixed units in checkboxes ([8ef1684](https://github.com/telerik/kendo-theme-default/commit/8ef1684))
* use improved border-radius mixin ([#516](https://github.com/telerik/kendo-theme-default/issues/516)) ([c5fa5a5](https://github.com/telerik/kendo-theme-default/commit/c5fa5a5))
* use setting for border-radius in respective mixins ([57686e7](https://github.com/telerik/kendo-theme-default/commit/57686e7))
* use setting for box-shadow in respective mixins ([a729c5c](https://github.com/telerik/kendo-theme-default/commit/a729c5c))
* use setting for linear-gradient in respective mixins ([6e4b92a](https://github.com/telerik/kendo-theme-default/commit/6e4b92a))
* use transparent border for dialog actions ([a7172b3](https://github.com/telerik/kendo-theme-default/commit/a7172b3))
* variables not inlined into calc blocks ([dd17363](https://github.com/telerik/kendo-theme-default/commit/dd17363))
* vertical align chart shared tooltip marker ([#43](https://github.com/telerik/kendo-theme-default/issues/43)) ([a646c54](https://github.com/telerik/kendo-theme-default/commit/a646c54))
* **window:** reducing title height [#752](https://github.com/telerik/kendo-theme-default/issues/752) ([32244f3](https://github.com/telerik/kendo-theme-default/commit/32244f3))
* visual glitches ([4d4d178](https://github.com/telerik/kendo-theme-default/commit/4d4d178))
* **window:** set layout for resize handles ([f9a29ce](https://github.com/telerik/kendo-theme-default/commit/f9a29ce))
* wrong appearance of the overflow button in editor toolbar ([36c6cc2](https://github.com/telerik/kendo-theme-default/commit/36c6cc2))
* wrong borders in grid ([dd5bcfa](https://github.com/telerik/kendo-theme-default/commit/dd5bcfa))
* wrong colorpcker metrics and states [#174](https://github.com/telerik/kendo-theme-default/issues/174) ([b18b5a5](https://github.com/telerik/kendo-theme-default/commit/b18b5a5))
* wrong styles of toolbar buttons ([1e3965e](https://github.com/telerik/kendo-theme-default/commit/1e3965e))
* wrong styles of toolbar buttons ([389532e](https://github.com/telerik/kendo-theme-default/commit/389532e))
* **window:** streamline window and dialog layout ([a60b9ab](https://github.com/telerik/kendo-theme-default/commit/a60b9ab))
* wrong titleless window selector ([bda4a3b](https://github.com/telerik/kendo-theme-default/commit/bda4a3b))


### Features

* add animated loading indicator ([#77](https://github.com/telerik/kendo-theme-default/issues/77)) ([1e56d09](https://github.com/telerik/kendo-theme-default/commit/1e56d09)), closes [telerik/kendo-theme-default#65](https://github.com/telerik/kendo-theme-default/issues/65)
* add background-color transitions ([12337c6](https://github.com/telerik/kendo-theme-default/commit/12337c6))
* add chart donut center template styles ([edec094](https://github.com/telerik/kendo-theme-default/commit/edec094))
* add classes for styling forms ([#391](https://github.com/telerik/kendo-theme-default/issues/391)) ([f9850b7](https://github.com/telerik/kendo-theme-default/commit/f9850b7))
* add default font-size to components ([6ec271d](https://github.com/telerik/kendo-theme-default/commit/6ec271d)), closes [#33](https://github.com/telerik/kendo-theme-default/issues/33)
* add gantt styles ([e041966](https://github.com/telerik/kendo-theme-default/commit/e041966))
* add grid toolbar styling ([5a57e69](https://github.com/telerik/kendo-theme-default/commit/5a57e69))
* add icon font ([7e4cf6a](https://github.com/telerik/kendo-theme-default/commit/7e4cf6a))
* add layout fixes file for IE9 ([349bbce](https://github.com/telerik/kendo-theme-default/commit/349bbce))
* Add Listbox styles ([08072c6](https://github.com/telerik/kendo-theme-default/commit/08072c6))
* add panelbar styles ([3d0e671](https://github.com/telerik/kendo-theme-default/commit/3d0e671))
* add pivotgrid styles ([#126](https://github.com/telerik/kendo-theme-default/issues/126)) ([eb7177f](https://github.com/telerik/kendo-theme-default/commit/eb7177f))
* add progressbar styles ([99978d1](https://github.com/telerik/kendo-theme-default/commit/99978d1))
* add ripple effect styles ([e1e15f1](https://github.com/telerik/kendo-theme-default/commit/e1e15f1))
* add slider styles ([1b27dce](https://github.com/telerik/kendo-theme-default/commit/1b27dce))
* add styles for gauges ([d67cfa0](https://github.com/telerik/kendo-theme-default/commit/d67cfa0))
* add styles for grid with virtual scrolling enabled ([ad33589](https://github.com/telerik/kendo-theme-default/commit/ad33589))
* add styling for chart selection ([#46](https://github.com/telerik/kendo-theme-default/issues/46)) ([392a480](https://github.com/telerik/kendo-theme-default/commit/392a480))
* add switch styles ([0b4e40d](https://github.com/telerik/kendo-theme-default/commit/0b4e40d))
* add variables for styling checkboxes ([d9316e8](https://github.com/telerik/kendo-theme-default/commit/d9316e8))
* add variables for styling dialog and window ([#574](https://github.com/telerik/kendo-theme-default/issues/574)) ([fb84a4f](https://github.com/telerik/kendo-theme-default/commit/fb84a4f))
* add variables to disabled mixin ([c76535a](https://github.com/telerik/kendo-theme-default/commit/c76535a))
* allow changing of checkbox/radio size ([0f1b4cd](https://github.com/telerik/kendo-theme-default/commit/0f1b4cd))
* bare button class ([#188](https://github.com/telerik/kendo-theme-default/issues/188)) ([eab2862](https://github.com/telerik/kendo-theme-default/commit/eab2862))
* basic window styling ([1a43eb9](https://github.com/telerik/kendo-theme-default/commit/1a43eb9))
* charts package ([a5ff54d](https://github.com/telerik/kendo-theme-default/commit/a5ff54d))
* charts package ([4b6e382](https://github.com/telerik/kendo-theme-default/commit/4b6e382))
* content in panelbar headers should not be selectable ([#29](https://github.com/telerik/kendo-theme-default/issues/29)) ([dd2035b](https://github.com/telerik/kendo-theme-default/commit/dd2035b))
* define active state to allow its use in widgets ([de28454](https://github.com/telerik/kendo-theme-default/commit/de28454))
* define classes for icons different font-size ([#28](https://github.com/telerik/kendo-theme-default/issues/28)) ([671b192](https://github.com/telerik/kendo-theme-default/commit/671b192))
* enable integration with bootstrap forms ([91d5969](https://github.com/telerik/kendo-theme-default/commit/91d5969))
* enable release channels ([2b9f436](https://github.com/telerik/kendo-theme-default/commit/2b9f436))
* Example component CSS ([da1bf90](https://github.com/telerik/kendo-theme-default/commit/da1bf90))
* export variable for icon sizing ([610b08e](https://github.com/telerik/kendo-theme-default/commit/610b08e))
* import basic styles from kendo ([4d9452b](https://github.com/telerik/kendo-theme-default/commit/4d9452b))
* **animation:** change animation container position to fixed ([#45](https://github.com/telerik/kendo-theme-default/issues/45)) ([2c55158](https://github.com/telerik/kendo-theme-default/commit/2c55158))
* **Animation:** Add a toggle effect for a single element animation ([66f01a7](https://github.com/telerik/kendo-theme-default/commit/66f01a7))
* **Animation:** Add Animation effects CSS classes ([2459a09](https://github.com/telerik/kendo-theme-default/commit/2459a09))
* **Animation:** Add appear animation variation of current animation effects ([304549f](https://github.com/telerik/kendo-theme-default/commit/304549f))
* **Animation:** Add slide down/up animation effect ([486edbf](https://github.com/telerik/kendo-theme-default/commit/486edbf))
* **Animation:** Import animation styles into main entry point ([885038e](https://github.com/telerik/kendo-theme-default/commit/885038e))
* **animation-effects:** add horizontal slide effects ([#10](https://github.com/telerik/kendo-theme-default/issues/10)) ([069e272](https://github.com/telerik/kendo-theme-default/commit/069e272))
* **badge:** add styles for badges telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([97cc16d](https://github.com/telerik/kendo-theme-default/commit/97cc16d))
* **badge:** improve styles using variables telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([e83ccc6](https://github.com/telerik/kendo-theme-default/commit/e83ccc6))
* **badge:** prevent expanding badge more than the button width telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([97bf50c](https://github.com/telerik/kendo-theme-default/commit/97bf50c))
* **button:** improve common styles for adding bare button in Bootstrap ([e1b9a0a](https://github.com/telerik/kendo-theme-default/commit/e1b9a0a))
* **buttongroup:** add styles for responsive buttongroup ([#290](https://github.com/telerik/kendo-theme-default/issues/290)) ([f73c892](https://github.com/telerik/kendo-theme-default/commit/f73c892))
* **buttongroup:** add styles for responsive buttongroup ([#290](https://github.com/telerik/kendo-theme-default/issues/290)) ([0941ef6](https://github.com/telerik/kendo-theme-default/commit/0941ef6))
* **buttonGroup:** add styles for button group telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([227e96e](https://github.com/telerik/kendo-theme-default/commit/227e96e))
* **buttonGroup:** improve border radius after improving rendering telerik/kendo[#7846](https://github.com/telerik/kendo-theme-default/issues/7846) ([1f2d915](https://github.com/telerik/kendo-theme-default/commit/1f2d915))
* **buttons:** Add new design styles and improvements ([#91](https://github.com/telerik/kendo-theme-default/issues/91)) ([6ae48ba](https://github.com/telerik/kendo-theme-default/commit/6ae48ba))
* **checkbox:** allow changing of indeterminate state ([9c58b9b](https://github.com/telerik/kendo-theme-default/commit/9c58b9b))
* **checkbox:** introduce variables for checkbox sizing ([543e8d3](https://github.com/telerik/kendo-theme-default/commit/543e8d3))
* **dateinput:** add dateinput ([#128](https://github.com/telerik/kendo-theme-default/issues/128)) ([8922425](https://github.com/telerik/kendo-theme-default/commit/8922425))
* **DateInput:** Add invalid state styles ([5df409f](https://github.com/telerik/kendo-theme-default/commit/5df409f))
* **DatePicker:** Add styles for embedded DateInput - invalid state ([3c4f527](https://github.com/telerik/kendo-theme-default/commit/3c4f527))
* **datetimepicker:** Add invalid state styles ([9aea3f9](https://github.com/telerik/kendo-theme-default/commit/9aea3f9))
* **dropdowns:** add styling for invalid state ([de91d7a](https://github.com/telerik/kendo-theme-default/commit/de91d7a))
* **fade-animation:** rename fade-in to fade. Add fade out effect ([#8](https://github.com/telerik/kendo-theme-default/issues/8)) ([c42632d](https://github.com/telerik/kendo-theme-default/commit/c42632d))
* **forms:** add styling for integration with Bootstrap form-control-sm and form-control-lg classes ([f435f18](https://github.com/telerik/kendo-theme-default/commit/f435f18))
* **grid:** add grid pdf export styling ([#368](https://github.com/telerik/kendo-theme-default/issues/368)) ([e5e659f](https://github.com/telerik/kendo-theme-default/commit/e5e659f))
* **grid:** add rtl styling ([4e9e59a](https://github.com/telerik/kendo-theme-default/commit/4e9e59a))
* **grid:** Add styles for column selection checkboxes ([c4e0f09](https://github.com/telerik/kendo-theme-default/commit/c4e0f09))
* **grid:** Add styles for opaque loading mask ([c8dd437](https://github.com/telerik/kendo-theme-default/commit/c8dd437))
* **grid:** Add styles for sorted column shading ([b72e060](https://github.com/telerik/kendo-theme-default/commit/b72e060))
* **grid:** Improve Grid editor checkbox styling (telerik/kendo[#6747](https://github.com/telerik/kendo-theme-default/issues/6747)) ([5bcd4da](https://github.com/telerik/kendo-theme-default/commit/5bcd4da))
* **grid:** resize when height is set on container ([#400](https://github.com/telerik/kendo-theme-default/issues/400)) ([8b232a8](https://github.com/telerik/kendo-theme-default/commit/8b232a8))
* **grid:** simplification of formula for column menu margin ([78d96f3](https://github.com/telerik/kendo-theme-default/commit/78d96f3))
* **Grid:** Add column sorting order styles ([e746cdc](https://github.com/telerik/kendo-theme-default/commit/e746cdc))
* import button styles ([5c68023](https://github.com/telerik/kendo-theme-default/commit/5c68023))
* import calendar styles ([95e2b86](https://github.com/telerik/kendo-theme-default/commit/95e2b86))
* Improve popup styling for use in DropDownButton ([ff79685](https://github.com/telerik/kendo-theme-default/commit/ff79685))
* introduce dependencies between widgets ([dd6447e](https://github.com/telerik/kendo-theme-default/commit/dd6447e))
* loading indicator improvements ([#366](https://github.com/telerik/kendo-theme-default/issues/366)) ([e4c6b59](https://github.com/telerik/kendo-theme-default/commit/e4c6b59)), closes [telerik/kendo-theme-default#365](https://github.com/telerik/kendo-theme-default/issues/365)
* prefix class names, stop using css modules ([307eaaa](https://github.com/telerik/kendo-theme-default/commit/307eaaa))
* remove box-sizing override ([0fbeeff](https://github.com/telerik/kendo-theme-default/commit/0fbeeff))
* styles for calendar ([433ddfd](https://github.com/telerik/kendo-theme-default/commit/433ddfd))
* **timepicker:** Add invalid state styles ([4d1f5fc](https://github.com/telerik/kendo-theme-default/commit/4d1f5fc))
* styling for grid grouping ([#54](https://github.com/telerik/kendo-theme-default/issues/54)) ([47f3cd4](https://github.com/telerik/kendo-theme-default/commit/47f3cd4))
* **icons:** allow icons to have modifiers ([8a586da](https://github.com/telerik/kendo-theme-default/commit/8a586da)), closes [#806](https://github.com/telerik/kendo-theme-default/issues/806)
* **ListBox:** Add drag and drop styling ([01044fb](https://github.com/telerik/kendo-theme-default/commit/01044fb))
* **MaskedTextbox:** Add separate styles for MTB, invalid state (telerik/kendo[#6825](https://github.com/telerik/kendo-theme-default/issues/6825)) ([0769b10](https://github.com/telerik/kendo-theme-default/commit/0769b10))
* **mediaplayer:** styles for mediaplayer ([a1f1f13](https://github.com/telerik/kendo-theme-default/commit/a1f1f13))
* **menu:** add styling for menu scrolling ([5ae60f0](https://github.com/telerik/kendo-theme-default/commit/5ae60f0))
* **NumericTextbox:** Add invalid state styles(telerik/kendo[#6796](https://github.com/telerik/kendo-theme-default/issues/6796)) ([2ea8f85](https://github.com/telerik/kendo-theme-default/commit/2ea8f85))
* **popup:** introduce a popup styles package ([#18](https://github.com/telerik/kendo-theme-default/issues/18)) ([d89eee4](https://github.com/telerik/kendo-theme-default/commit/d89eee4))
* **radiobutton:** change dot positioning ([fe25c90](https://github.com/telerik/kendo-theme-default/commit/fe25c90))
* **slider:** enable transitions through class ([63db42e](https://github.com/telerik/kendo-theme-default/commit/63db42e))
* **slider:** transition drag handle state ([d8a519a](https://github.com/telerik/kendo-theme-default/commit/d8a519a))
* **splitter:** add styles for flexbox splitter ([f3eb2b0](https://github.com/telerik/kendo-theme-default/commit/f3eb2b0))
* **style:** add lint and commit message validation ([1c648e7](https://github.com/telerik/kendo-theme-default/commit/1c648e7))
* **textbox:** introduce textbox-line-height variable ([536bb3c](https://github.com/telerik/kendo-theme-default/commit/536bb3c))
* **timepicker:** add initial styling ([#640](https://github.com/telerik/kendo-theme-default/issues/640)) ([e8fa4d6](https://github.com/telerik/kendo-theme-default/commit/e8fa4d6))
* **upload:** add correct icon to chunk upload functionality ([72c2c03](https://github.com/telerik/kendo-theme-default/commit/72c2c03))
* **upload:** add styles for focused state ([8f6dc6c](https://github.com/telerik/kendo-theme-default/commit/8f6dc6c)), closes [telerik/kendo-theme-default#312](https://github.com/telerik/kendo-theme-default/issues/312)
* test via node-sass prior to pushing ([5f0011e](https://github.com/telerik/kendo-theme-default/commit/5f0011e))
* update default theme to new design ([2284cc2](https://github.com/telerik/kendo-theme-default/commit/2284cc2))
* use sans-serif by default, add header bg ([432d499](https://github.com/telerik/kendo-theme-default/commit/432d499))


### Reverts

* **common:** revert state-selected ([#130](https://github.com/telerik/kendo-theme-default/issues/130)) ([4248007](https://github.com/telerik/kendo-theme-default/commit/4248007))
