# code-snippets for Visual Studio Code for Html Css ES6  Vue2  ueRouter Vuex


这个插件基于最新的 Vue 的 API 添加了Code Snippets。
后续将集成 基于vue的各种代码提示，各种解决方案，一键解决

如有需求，或开源解决方案，或并入开发
联系方式: 1194979849@qq.com

## 已集成

### HTML  ES6  Vue VueRouter Vuex CSS大厂初始化 elementUI安装

[![](https://vsmarketplacebadge.apphb.com/version/hollowtree.vue-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=1194979849.code-snippets)
[![](https://vsmarketplacebadge.apphb.com/installs/hollowtree.vue-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=1194979849.code-snippets)

### It looks like:

![](https://raw.githubusercontent.com/hollowtree/vscode-vue-snippets/master/img/show1.png)

![](https://raw.githubusercontent.com/hollowtree/vscode-vue-snippets/master/img/show2.png)

<!-- 模板 -->
<!-- <details>
  <summary style="font-size:30px;font-weight: bold;">iview </summary>

</details> -->

## Snippets

### vue-cli3  vueconfig.js

 键入 vueconfigjs 就会有相关的提示 代码段需自行格式化， 根据需要 可将不需要的部分注释掉，如有不足请联系QQ新增 

## UI安装一键解决

| Trigger  | Content |
| -------: | ------- |
| `ElementUIInstall`   | `Vue-cli: element-ui 全量 引入安装 ` |
| `iviewInstall`   | `Vue-cli: iView 全量 引入安装 ` |

<details>
  <summary style="font-size:30px;font-weight: bold;">CSS 初始化 </summary>

| Trigger  | Content |
| -------: | ------- |
| `CSSInitBySina`   | `CSS:新浪标签样式初始化 ` |
| `CSSInitByTaobao`  | `CSS:淘宝标签样式初始化` |
| `CSSInitBy163`  | `CSS:网易标签样式初始化` |
| `CSSInitByTencent`  | `CSS:腾讯标签样式初始化` |

</details>

<details>
  <summary style="font-size:30px;font-weight: bold;">iview </summary>

|  shortcut   | Content                                  |
| :---------: | :--------------------------------------- |
|  vue-template      | `<template ></template><script></script><style></style>` |
|    func     | `function(){}`                             |
| iview-template | `a iview layout` |
|     iRow     | `<Row></Row>`                              |
|     iCol     | `<Col span=""></Col>`                      |
|     iIcon     | `<Icon type="" />`                      |
|     iCard    | `<Card><p slot="title"></p></Card>`       |
|   iButton    | `<Button type="primary"></Button>`         |
| iButtonGroup | `<ButtonGroup><Button></Button><Button type="primary"></Button></ButtonGroup>` |
|    iInput    | `<Input v-model="" placeholder=""></Input>` |
| iInputnumber | `<Input-number :max="10" :min="1" v-model="model"></Input-number>` |
|    iTable    | `<Table :columns="column" :data="data"></Table>` |
|   iSelect    | `<Select v-model="model"><Option v-for="item in list" :value="value" :key="item"></Option></Select>` |
| iDatepicker  | `<Date-picker type="datetime" format="yyyy/MM/dd HH:mm" placeholder="选择日期和时间"></Date-picker>` |
|   iUpload    | `<Upload action=""><Button type="ghost" icon="ios-cloud-upload-outline">上传文件</Button></Upload>` |
|   iModal     | `<Modal v-model="" title=""><p>Content of dialog</p></Modal>` |
|   iNotice   | `this.$Notice.open('');`                  |
|   iForm   | `from`                  |
|   iRadio   | `<Radio v-model=""></Radio>`                  |
| iRadioGroup  | `<RadioGroup v-model=""><Radio label=""></Radio><Radio label=""></Radio></RadioGroup>`  |
|   iCheckBox   | `<Checkbox v-model=""></Checkbox>`                  |
| iCheckBoxGroup | `<CheckBoxGroup v-model=""><Checkbox label=""></Checkbox></CheckBoxGroup>` |

</details>

<details>
  <summary style="font-size:30px;font-weight: bold;">Element UI </summary>

### Basic Part

|No.|Trigger&nbsp;Key|Element Tag|
|:------:|:--------------:|:--------|
|1. | `elrow` | `<el-row>` |
|2. | `elcol` | `<el-col>` |
|3. | `elcon` | `<el-container>` |
|4. | `elas` | `<el-aside>` |
|5. | `elhe` | `<el-header>` |
|6. | `elma` | `<el-main>` |
|7. | `elfo` | `<el-footer>` |
|8. | `elcb` | `#409EFF` |
|9. | `elcs` | `#67C23A` |
|10. | `elcw` | `#E6A23C` |
|11. | `elcd` | `#F56C6C` |
|12. | `elci` | `#909399` |
|13. | `eltypo` | `font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;` |
|14. | `elb` | `el-button` |

### Form Part

|No. |  Trigger&nbsp;Key | Element Tag|
|:------:|:--------------:|:--------|
|1. | `elr` | `<el-radio>` |
|2. | `elrg` | `<el-radio-group>` |
|3. | `elc` | `<el-checkbox>` |
|4. | `elcg` | `<el-checkbox-group>` |
|5. | `eli` | `<el-input>` |
|6. | `elit` | `<el-input type="textarea">` |
|7. | `elin` | `<el-input-number>` |
|8. | `elsel` | `<el-select>` |
|9. | `elop` | `<el-option>` |
|10. | `elca` | `<el-cascader>` |
|11. | `elsw` | `<el-swtich>` |
|12. | `elsl` | `<el-slider>` |
|13. | `eltp` | `<el-time-picker>` |
|14. | `elts` | `<el-time-select>` |
|15. | `eldp` | `<el-date-picker>` |
|16. | `eldtp` | `<el-date-picker type="datetime">` |
|17. | `elu` | `<el-upload>` |
|18. | `elra` | `<el-rate>` |
|19. | `elcp` | `<el-color-picker>` |
|20. | `eltr` | `<el-transfer>` |
|21. | `elf` | `<el-form>` |
|22. | `elfi` | `<el-form-item>` |

### Data Part

|No. |  Trigger Key | Element Tag|
|:------:|:--------------:|:--------|
|1. | `elta` | `<el-table>` |
|2. | `eltac` | `<el-table-column>` |
|3. | `eltag` | `<el-tag>` |
|4. | `elpr` | `<el-progress>` |
|5. | `elprc` | `<el-progress type="circle">` |
|6. | `eltree` | `<el-tree>` |
|7. | `elpa` | `<el-pagination>` |
|8. | `elba` | `<el-badge>` |

### Notice Part

|No. |  Trigger Key | Element Tag|
|:------:|:--------------:|:--------|
|1. | `elal` | `<el-alert>` |
|2. | `elloads` | 	`element-loading-*` |
|3. | `elme` | 	`this.$message({})` |
|4. | `elmebox` | 	`this.$msgbox({})` |
|5. | `elmeal` | 	`this.$alert({})` |
|6. | `elmecon` | 	`this.$confirm({})` |
|7. | `elmepro` | 	`this.$prompt({})` |
|8. | `elnoti` | 	`this.$notify({})` |

### Navigation Part

|No. |  Trigger Key | Element Tag|
|:------:|:--------------:|:--------|
|1. | `elmen` | `<el-menu>` |
|2. | `elsubmen` | `<el-submenu>` |
|3. | `elmeni` | `<el-menu-item>` |
|4. | `eltabs` | `<el-tabs>` |
|5. | `eltabp` | `<el-tab-pane>` |
|6. | `elbr` | `<el-breadcrumb>` |
|7. | `elbri` | `<el-breadcrumb-item>` |
|8. | `eldr` | `<el-dropdown>` |
|9. | `eldri` | `<el-dropdown-item>` |
|10. | `elsts` | `<el-steps>` |
|11. | `elst` | `<el-step>` |

### Others Part

|No. |  Trigger Key | Element Tag|
|:------:|:--------------:|:--------|
|1. | `eldi` | `<el-dialog>` |
|2. | `elto` | `<el-tooltip>` |
|3. | `elpop` | `<el-popover>` |
|4. | `elcard` | `<el-card>` |
|5. | `elcaro` | `<el-carousel>` |
|6. | `elcaroi` | `<el-carousel-item>` |
|7. | `elcolla` | `<el-collapse>` |
|8. | `elcollai` | `<el-collapse-item>` |

</details>

<details>
  <summary style="font-size:30px;font-weight: bold;">JavaScript Snippets </summary>

### Declarations

| Trigger  | Content |
| -------: | ------- |
| `v⇥`   | `var ` |
| `v=⇥`  | `var name = value;` |
| `l⇥`   | `let ` |
| `l=⇥`  | `let name = value;` |
| `dl=⇥` | `let {name} = value;`|
| `co⇥`  | `const`|
| `co=⇥` | `const name = value;` |
| `dco=⇥`| `const {name} = value;` |

### Flow Control

| Trigger  | Content |
| -------: | ------- |
| `if⇥`  | `if (condition}) {}` |
| `el⇥`  | `else { }` |
| `ife⇥` | `if (condition){ } else { }` |
| `ei⇥`  | `else if (condition) { }` |
| `ter⇥` | `condition ? expressionTrue : expressionFalse;`|
| `fl⇥`  | `for (let i = 0, len = iterable.length; i < len; i ++) {}` |
| `rfl⇥` | `for (let i = iterable.length - 1; i >= 0; i--) {}` |
| `fi⇥` | `for (let key in array) {if (array.hasOwnProperty(key)) {}}` |
| `fo⇥` | `for (let key of array) {}` |
| `wl⇥` | `while (condition) {}` |
| `tc⇥` | `try {} catch (err) {}` |
| `tf⇥` | `try {} finally {}` |
| `tcf⇥` | `try {} catch (err) {} finally {}` |
| `sw⇥` | `switch (expr) { case value: return ; default: return;}` |

### Functions

| Trigger  | Content |
| -------: | ------- |
| `f⇥`  | `function (arguments) {}` |
| `fn⇥`  | `function name (arguments) {}` |
| `iife⇥`  | `((arguments) => {})();` |
| `fa⇥`  | `fn.apply(this, arguments)` |
| `fc⇥`  | `fn.call(this, arguments)` |
| `fb⇥`  | `fn.bind(this, arguments)` |
| `af⇥`  | `(arguments) => statement` |
| `afb⇥`  | `(arguments) => {}` |
| `gf⇥`  | `function* (arguments) {}` |
| `gfn⇥`  | `function* name(arguments) {}` |

### Iterables

| Trigger  | Content |
| -------: | ------- |
| `seq⇥`  | `[...Array(length).keys()]` |
| `fe⇥`  | `${1}.forEach((item) => {});` |
| `map⇥`  | `${1}.map((item) => {});` |
| `reduce⇥`  | `` |
| `filter⇥`  | `${1}.filter(item => {});` |
| `find⇥`  | `${1}.find(item => {});` |

#### `reduce⇥` reduce

```javascript
${1}.reduce((${2:previous}, ${3:current}) => {
}${4:, initial});
```

### Objects and Classes

| Trigger  | Content |
| -------: | ------- |
| `ol⇥`  | `换行对象{<br/>}` |
| `slol⇥`  | `行内对象{ kv${0} };` |
| `kv⇥`  | `key:value,` |
| `c⇥`  | `class name {constructor(arguments) {}}` |
| `cex⇥`  | `class name extends base {constructor(arguments) {super(arguments);}}` |
| `ctor⇥`  | `constructor(arguments) {super(arguments); }` |
| `m⇥`  | `method(arguments) {}` |
| `get⇥`  | `get ${1:property}() {}` |
| `set⇥`  | `set ${1:property}(value) {}` |
| `gs⇥`  | `get property() {} set property(value) {}` |
| `pctor⇥`  | `var Class = function(arguments) {};` |
| `proto⇥`  | `Class.prototype.method = function(arguments) {};` |
| `oa⇥`  | `Object.assign(dest,source)` |
| `oc⇥`  | `Object.assign({}, original, source)` |

### Returning values

| Trigger  | Content |
| -------: | ------- |
| `r⇥`  | `return ${0};` |
| `rp⇥`  | `return new Promise((resolve, reject) => {});` |
| `rc⇥`  | `return ( );` |
| `rc⇥`  | `return ( );` |

### Types

| Trigger  | Content |
| -------: | ------- |
| `tof⇥`  | `typeof source === 'undefined'` |
| `iof⇥`  | `source instanceof Object` |

### Promises

| Trigger  | Content |
| -------: | ------- |
| `pr⇥`  | `new Promise((resolve, reject) => {})` |
| `then⇥`  | `promise.then((value) => {})` |
| `catch⇥`  | `promise.catch((err) => {})` |

### ES6 Modules

| Trigger  | Content |
| -------: | ------- |
| `ex⇥`  | `export member;` |
| `exd⇥`  | `export default member;` |
| `im⇥`  | `import * from 'module';` |
| `ima⇥`  | `import * as name from 'module';` |

### Node.js

| Trigger  | Content |
| -------: | ------- |
| `cb⇥`  | `(err, value) => { }` |
| `re⇥`  | `require('module');` |
| `rel⇥`  | `require('./module');` |
| `req⇥`  | `const module = require('module');` |
| `reql⇥`  | `const module = require('./module');` |
| `dreq⇥`  | `const {module} = require('module');` |
| `dreql⇥`  | `const {module} = require('./module');` |
| `em⇥`  | `exports.member = value;` |
| `me⇥`  | `module.exports = name;` |
| `meo⇥`  | `module.exports = {member };` |
| `on⇥`  | `emitter.on('event', (arguments) => {});` |

### BDD Testing (Mocha, Jasmine, etc.)

| Trigger  | Content |
| -------: | ------- |
| `desc⇥`  | `describe('description', () => {});` |
| `cont⇥`  | `context('description', () => {});` |
| `it⇥`  | `it('description', () => {});` |
| `its⇥`  | `it('description', () => {});` |
| `ita⇥`  | `it('description', (done) => {   done();});` |
| `bf⇥`  | `before(() => {});` |
| `bfe⇥`  | `beforeEach(() => {});` |
| `aft⇥`  | `after(() => {});` |
| `afe⇥`  | `afterEach(() => {});` |

### Console

| Trigger  | Content |
| -------: | ------- |
| `cl⇥`  | `console.log();` |
| `ce⇥`  | `console.error();` |
| `cw⇥`  | `console.warn();` |
| `cll⇥`  | `日至标记 console.log('${0}', ${0});` |
| `cel⇥`  | `日至标记 console.error('${0}', ${0});` |
| `cwl⇥`  | `日至标记 console.warn('${0}', ${0});` |

### Timers

| Trigger  | Content |
| -------: | ------- |
| `st⇥`  | `setTimeout(() => { }, delay);` |
| `si⇥`  | `setInterval(() => { }, delay);` |
| `sim⇥`  | `setImmediate(() => { });` |
| `nt⇥`  | `process.nextTick(() => {});` |

### Miscellaneous

| Trigger  | Content |
| -------: | ------- |
| `us⇥`  | `'use strict';` |

### Miscellaneous

#### `us⇥` insert 'use strict' statement

```javascript
'use strict';
```

</details>

<details>

  <summary style="font-size:30px;font-weight: bold;">JavaScript (ES6) code snippets </summary>

### Import and export

| Trigger  | Content |
| -------: | ------- |
| `imp→`   | imports entire module `import fs from 'fs';`|
| `imn→`   | imports entire module without module name `import 'animate.css'` |
| `imd→`   | imports only a portion of the module using destructing  `import {rename} from 'fs';` |
| `ime→`   | imports everything as alias from the module `import * as localAlias from 'fs';` |
| `ima→`   | imports only a portion of the module as alias `import { rename  as localRename } from 'fs';` |
| `rqr→`   | require package `require('');`|
| `mde→`   | default module.exports `module.exports = {};`|
| `enf→`   | exports name function `export const log = (parameter) => { console.log(parameter);};` |
| `edf→`   | exports default function `export default  (parameter) => { console.log(parameter);};` |
| `ecl→`   | exports default class `export default class Calculator { };` |
| `ece→`   | exports default class by extending a base one `export default class Calculator extends BaseClass { };` |

### Class helpers

| Trigger  | Content |
| -------: | ------- |
| `con→`   | adds default constructor in the class `constructor() {}`|
| `met→`   | creates a method inside a class `add() {}` |
| `pge→`   | creates a getter property `get propertyName() {return value;}` |
| `pse→`   | creates a setter property `set propertyName(value) {}` |

### Various methods

| Trigger  | Content |
| -------: | ------- |
| `fre→`   | forEach loop in ES6 syntax `array.forEach(currentItem => {})`|
| `fof→`   | for ... of loop `for(const item of object) {}` |
| `fin→`   | for ... in loop `for(const item in object) {}` |
| `anfn→`  | creates an anonymous function `(params) => {}` |
| `nfn→`   | creates a named function `const add = (params) => {}` |
| `dob→`   | destructing object syntax `const {rename} = fs` |
| `dar→`   | destructing array syntax `const [first, second] = [1,2]` |
| `sti→`   | set interval helper method `setInterval(() => {});` |
| `sto→`   | set timeout helper method `setTimeout(() => {});` |
| `prom→`  | creates a new Promise `return new Promise((resolve, reject) => {});`|
| `thenc→` | adds then and catch declaration to a promise `.then((res) => {).catch((err) => {});`|

### Console methods

| Trigger  | Content |
| -------: | ------- |
| `cas→`   | console alert method `console.assert(expression, object)`|
| `ccl→`   | console clear `console.clear()` |
| `cco→`   | console count `console.count(label)` |
| `cdi→`   | console dir `console.dir` |
| `cer→`   | console error `console.error(object)` |
| `cgr→`   | console group `console.group(label)` |
| `cge→`   | console groupEnd `console.groupEnd()` |
| `clg→`   | console log `console.log(object)` |
| `clo→`   | console log object with name `console.log('object :', object);` |
| `ctr→`   | console trace `console.trace(object)` |
| `cwa→`   | console warn `console.warn` |
| `cin→`   | console info `console.info` |
| `clt→`   | console table `console.table` |

</details>

<details>
  <summary style="font-size:30px;font-weight: bold;"> Vue 2 Snippets </summary>

Including most of the API of Vue.js 2. You can type `vcom`, choose `VueConfigOptionMergeStrategies`, and press ENTER, then `Vue.config.optionMergeStrategies` appear on the screen.

插件的 Snippets 如下表格所示，比如你可以键入 `vcom` 然后按上下键选中 `VueConfigOptionMergeStrategies` 再按Enter键，就输入了`Vue.config.optionMergeStrategies`了。

As shown in the table below, snippet `vmData` has body like `${this, vm}.$data` will provides choice `this.$data` and `vm.$data` to you.

如下表所示，`vmData` 的内容是 `${this, vm}.$data`，这表明这个 snippet 会提供 `this.$data` and `vm.$data` 两种选项供你选择。

| Prefix | JavaScript Snippet Content |
| ------ | ------------ |
| `import` | `import ... from ...` |
| `newVue` | `new Vue({...})` |
| `VueConfigSilent` | `Vue.config.silent = true` |
| `VueConfigOptionMergeStrategies` | `Vue.config.optionMergeStrategies` |
| `VueConfigDevtools` | `Vue.config.devtools = true` |
| `VueConfigErrorHandler` | `Vue.config.errorHandler = function (err, vm, info) {...}` |
| `VueConfigWarnHandler` | `Vue.config.warnHandler = function (msg, vm, trace) {...}` |
| `VueConfigIgnoredElements` | `Vue.config.ignoredElements = ['']` \
| `VueConfigKeyCodes` | `Vue.config.keyCodes` |
| `VueConfigPerformance` | `Vue.config.performance = true` |
| `VueConfigProductionTip` | `Vue.config.productionTip = false` |
| `vueExtend` | `Vue.extend( options )` |
| `VueNextTick` | `Vue.nextTick( callback, [context] )` |
| `VueNextTickThen` | `Vue.nextTick( callback, [context] ).then(function(){ })` |
| `VueSet` | `Vue.set( target, key, value )` |
| `VueDelete` | `Vue.delete( target, key )` |
| `VueDirective` | `Vue.directive( id, [definition] )` |
| `VueFilter` | `Vue.filter( id, [definition] )` |
| `VueComponent` | `Vue.component( id, [definition] )` |
| `VueUse` | `Vue.use( plugin )` |
| `VueMixin` | `Vue.mixin({ mixin })` |
| `VueCompile` | `Vue.compile( template )` |
| `VueVersion` | `Vue.version` |
| `vmData` | `${this, vm}.$data` |
| `vmProps` | `${this, vm}.$props` |
| `vmEl` | `${this, vm}.$el` |
| `vmOptions` | `${this, vm}.$options` |
| `vmParent` | `${this, vm}.$parent` |
| `vmRoot` | `${this, vm}.$root` |
| `vmChildren` | `${this, vm}.$children` |
| `vmSlots` | `${this, vm}.$slots` |
| `vmScopedSlots` | `${this, vm}.$scopedSlots.default({})` |
| `vmRefs` | `${this, vm}.$refs` |
| `vmIsServer` | `${this, vm}.$isServer` |
| `vmAttrs` | `${this, vm}.$attrs`|
| `vmListeners` | `${this, vm}.listeners`|
| `vmWatch` | `${this, vm}.$watch( expOrFn, callback, [options] )` |
| `vmSet` | `${this, vm}.$set( object, key, value )` |
| `vmDelete` | `${this, vm}.$delete( object, key )` |
| `vmOn` | `${this, vm}.$on( event, callback )` |
| `vmOnce` | `${this, vm}.$once( event, callback )` |
| `vmOff` | `${this, vm}.$off( [event, callback] )` |
| `vmEmit` | `${this, vm}.$emit( event, […args] )` |
| `vmMount` | `${this, vm}.$mount( [elementOrSelector] )` |
| `vmForceUpdate` | `${this, vm}.$forceUpdate()` |
| `vmNextTick` | `${this, vm}.$nextTick( callback )` |
| `vmDestroy` | `${this, vm}.$destroy()` |
| `renderer` | `const renderer = require('vue-server-renderer').createRenderer()` |
| `createRenderer` | `createRenderer({ })` |
| `preventDefault` | `preventDefault();` |
| `stopPropagation` | `stopPropagation();` |

<br />

| Prefix | HTML Snippet Content |
| ------ | ------------ |
| `template` | `<template></template>` |
| `script` | `<script></script>` |
| `style` | `<style></style>` |
| `vText` | `v-text=msg` |
| `vHtml` | `v-html=html` |
| `vShow` | `v-show` |
| `vIf` | `v-if` |
| `vElse` | `v-else` |
| `vElseIf` | `v-else-if` |
| `vForWithoutKey` | `v-for` |
| `vFor` | `v-for="" :key=""` |
| `vOn` | `v-on` |
| `vBind` | `v-bind` |
| `vModel` | `v-model` |
| `vPre` | `v-pre` |
| `vCloak` | `v-cloak` |
| `vOnce` | `v-once` |
| `key` | `:key` |
| `ref` | `ref`|
| `slotA` | `slot=""`|
| `slotE` | `<slot></slot>`|
| `slotScope` | `slot-scope=""`|
| `component` | `<component :is=''></component>`|
| `keepAlive` | `<keep-alive></keep-alive>` |
| `transition` | `<transition></transition>` |
| `transitionGroup` | `<transition-group></transition-group>` |
| `enterClass` | `enter-class=''`|
| `leaveClass` | `leave-class=''`|
| `appearClass` | `appear-class=''`|
| `enterToClass` | `enter-to-class=''`|
| `leaveToClass` | `leave-to-class=''`|
| `appearToClass` | `appear-to-class=''`|
| `enterActiveClass` | `enter-active-class=''`|
| `leaveActiveClass` | `leave-active-class=''`|
| `appearActiveClass` | `appear-active-class=''`|
| `beforeEnterEvent` | `@before-enter=''`|
| `beforeLeaveEvent` | `@before-leave=''`|
| `beforeAppearEvent` | `@before-appear=''`|
| `enterEvent` | `@enter=''`|
| `leaveEvent` | `@leave=''`|
| `appearEvent` | `@appear=''`|
| `afterEnterEvent` | `@after-enter=''`|
| `afterLeaveEvent` | `@after-leave=''`|
| `afterAppearEvent` | `@after-appear=''`|
| `enterCancelledEvent` | `@enter-cancelled=''`|
| `leaveCancelledEvent` | `@leave-cancelled=''`|
| `appearCancelledEvent` | `@appear-cancelled=''`|

<br />

| Prefix | Vue Router Snippet Content |
| ------ | ------------ |
| `routerLink` | `<router-link></router-link>` |
| `routerView` | `<router-view></router-view>` |
| `to` | `to=""` |
| `tag` | `tag=""` |
| `newVueRouter` | `const router = newVueRouter({ })` |
| `routerBeforeEach` | `router.beforeEach((to, from, next) => { }` |
| `routerReplace` | `router.replace()` |
| `routerGo` | `router.go()` |
| `routerPush` | `router.push()` |
| `routes` | `routes: []` |
| `beforeEnter` | `beforeEnter: (to, from, next) => { }` |
| `beforeRouteEnter` | `beforeRouteEnter (to, from, next) { }` |
| `beforeRouteLeave` | `beforeRouteLeave (to, from, next) { }` |
| `scrollBehavior` | `scrollBehavior (to, from, savedPosition) { }` |

<br />

| Prefix | Vuex Snippet Content |
| ------ | ------------ |
| `newVuexStore` | `const store = new Vuex.Store({ })` |

</details>

### Supported languages

* vue(.vue)
* HTML(.html)
* javascript(.js)
* typescript(.ts)
* pug(.pug)

### Base on

[Vue 2 Snippets](https://github.com/hollowtree/vscode-vue-snippets)
[JavaScript (ES6) code snippets](https://github.com/xabikos/vscode-javascript)
[JavaScript Snippets](https://github.com/nathanchapman/vscode-javascript-snippets)

--------------------------------------

### 2019.7.7

  修整 vueConfigjs 的  baseUrl 为 publicPath

### 2019.1.2

  修整 ES6 语法不提示的问题

### 2018.12.28

  新增 vue-cli3 的 vueconfigjs 配置支持

### 2018.11.17

  新增 elementUI 和iview UI提示

### 2018.11.16

  新增 elementUI 和iview 安装一键解决

### 2018.11.12

  集成HTML ES6代码提示，部分提示描述汉化

### 2018.10.26

  部分汉化提示及解决方案
