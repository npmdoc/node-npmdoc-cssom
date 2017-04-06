# api documentation for  [cssom (v0.3.2)](https://github.com/NV/CSSOM)  [![npm package](https://img.shields.io/npm/v/npmdoc-cssom.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cssom) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cssom.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cssom)
#### CSS Object Model implementation and CSS parser

[![NPM](https://nodei.co/npm/cssom.png?downloads=true)](https://www.npmjs.com/package/cssom)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cssom/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-cssom_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cssom/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cssom/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cssom/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nikita Vasilyev",
        "email": "me@elv1s.ru"
    },
    "bugs": {
        "url": "https://github.com/NV/CSSOM/issues"
    },
    "dependencies": {},
    "description": "CSS Object Model implementation and CSS parser",
    "devDependencies": {
        "jake": "~0.7.3"
    },
    "directories": {},
    "dist": {
        "shasum": "b8036170c79f07a90ff2f16e22284027a243848b",
        "tarball": "https://registry.npmjs.org/cssom/-/cssom-0.3.2.tgz"
    },
    "files": [
        "lib/"
    ],
    "gitHead": "d600816ea9442c5e33f27ff59de536d7b7ccd239",
    "homepage": "https://github.com/NV/CSSOM",
    "keywords": [
        "CSS",
        "CSSOM",
        "parser",
        "styleSheet"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "nv",
            "email": "me@elv1s.ru"
        },
        {
            "name": "domenic",
            "email": "domenic@domenicdenicola.com"
        }
    ],
    "name": "cssom",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/NV/CSSOM.git"
    },
    "scripts": {
        "prepublish": "jake lib/index.js"
    },
    "version": "0.3.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module cssom](#apidoc.module.cssom)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSImportRule ()](#apidoc.element.cssom.CSSImportRule)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSMediaRule ()](#apidoc.element.cssom.CSSMediaRule)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSRule ()](#apidoc.element.cssom.CSSRule)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSStyleDeclaration ()](#apidoc.element.cssom.CSSStyleDeclaration)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSStyleRule ()](#apidoc.element.cssom.CSSStyleRule)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSStyleSheet ()](#apidoc.element.cssom.CSSStyleSheet)
1.  [function <span class="apidocSignatureSpan">cssom.</span>MediaList ()](#apidoc.element.cssom.MediaList)
1.  [function <span class="apidocSignatureSpan">cssom.</span>StyleSheet ()](#apidoc.element.cssom.StyleSheet)
1.  [function <span class="apidocSignatureSpan">cssom.</span>clone (stylesheet)](#apidoc.element.cssom.clone)
1.  [function <span class="apidocSignatureSpan">cssom.</span>parse (token)](#apidoc.element.cssom.parse)
1.  object <span class="apidocSignatureSpan">cssom.</span>CSSDocumentRule
1.  object <span class="apidocSignatureSpan">cssom.</span>CSSFontFaceRule
1.  object <span class="apidocSignatureSpan">cssom.</span>CSSHostRule
1.  object <span class="apidocSignatureSpan">cssom.</span>CSSImportRule.prototype
1.  object <span class="apidocSignatureSpan">cssom.</span>CSSKeyframeRule
1.  object <span class="apidocSignatureSpan">cssom.</span>CSSKeyframesRule
1.  object <span class="apidocSignatureSpan">cssom.</span>CSSMediaRule.prototype
1.  object <span class="apidocSignatureSpan">cssom.</span>CSSRule.prototype
1.  object <span class="apidocSignatureSpan">cssom.</span>CSSStyleDeclaration.prototype
1.  object <span class="apidocSignatureSpan">cssom.</span>CSSStyleRule.prototype
1.  object <span class="apidocSignatureSpan">cssom.</span>CSSStyleSheet.prototype
1.  object <span class="apidocSignatureSpan">cssom.</span>CSSValue
1.  object <span class="apidocSignatureSpan">cssom.</span>CSSValueExpression
1.  object <span class="apidocSignatureSpan">cssom.</span>MatcherList
1.  object <span class="apidocSignatureSpan">cssom.</span>MediaList.prototype

#### [module cssom.CSSDocumentRule](#apidoc.module.cssom.CSSDocumentRule)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSDocumentRule ()](#apidoc.element.cssom.CSSDocumentRule.CSSDocumentRule)

#### [module cssom.CSSFontFaceRule](#apidoc.module.cssom.CSSFontFaceRule)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSFontFaceRule ()](#apidoc.element.cssom.CSSFontFaceRule.CSSFontFaceRule)

#### [module cssom.CSSHostRule](#apidoc.module.cssom.CSSHostRule)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSHostRule ()](#apidoc.element.cssom.CSSHostRule.CSSHostRule)

#### [module cssom.CSSImportRule](#apidoc.module.cssom.CSSImportRule)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSImportRule ()](#apidoc.element.cssom.CSSImportRule.CSSImportRule)

#### [module cssom.CSSImportRule.prototype](#apidoc.module.cssom.CSSImportRule.prototype)
1.  [function <span class="apidocSignatureSpan">cssom.CSSImportRule.prototype.</span>constructor ()](#apidoc.element.cssom.CSSImportRule.prototype.constructor)
1.  number <span class="apidocSignatureSpan">cssom.CSSImportRule.prototype.</span>type
1.  object <span class="apidocSignatureSpan">cssom.CSSImportRule.prototype.</span>parentRule
1.  object <span class="apidocSignatureSpan">cssom.CSSImportRule.prototype.</span>parentStyleSheet

#### [module cssom.CSSKeyframeRule](#apidoc.module.cssom.CSSKeyframeRule)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSKeyframeRule ()](#apidoc.element.cssom.CSSKeyframeRule.CSSKeyframeRule)

#### [module cssom.CSSKeyframesRule](#apidoc.module.cssom.CSSKeyframesRule)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSKeyframesRule ()](#apidoc.element.cssom.CSSKeyframesRule.CSSKeyframesRule)

#### [module cssom.CSSMediaRule](#apidoc.module.cssom.CSSMediaRule)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSMediaRule ()](#apidoc.element.cssom.CSSMediaRule.CSSMediaRule)

#### [module cssom.CSSMediaRule.prototype](#apidoc.module.cssom.CSSMediaRule.prototype)
1.  [function <span class="apidocSignatureSpan">cssom.CSSMediaRule.prototype.</span>constructor ()](#apidoc.element.cssom.CSSMediaRule.prototype.constructor)
1.  number <span class="apidocSignatureSpan">cssom.CSSMediaRule.prototype.</span>type
1.  object <span class="apidocSignatureSpan">cssom.CSSMediaRule.prototype.</span>parentRule
1.  object <span class="apidocSignatureSpan">cssom.CSSMediaRule.prototype.</span>parentStyleSheet

#### [module cssom.CSSRule](#apidoc.module.cssom.CSSRule)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSRule ()](#apidoc.element.cssom.CSSRule.CSSRule)
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>CHARSET_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>COUNTER_STYLE_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>DOCUMENT_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>FONT_FACE_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>FONT_FEATURE_VALUES_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>IMPORT_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>KEYFRAMES_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>KEYFRAME_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>MARGIN_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>MEDIA_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>NAMESPACE_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>PAGE_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>REGION_STYLE_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>STYLE_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>SUPPORTS_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>UNKNOWN_RULE
1.  number <span class="apidocSignatureSpan">cssom.CSSRule.</span>VIEWPORT_RULE

#### [module cssom.CSSRule.prototype](#apidoc.module.cssom.CSSRule.prototype)
1.  [function <span class="apidocSignatureSpan">cssom.CSSRule.prototype.</span>constructor ()](#apidoc.element.cssom.CSSRule.prototype.constructor)

#### [module cssom.CSSStyleDeclaration](#apidoc.module.cssom.CSSStyleDeclaration)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSStyleDeclaration ()](#apidoc.element.cssom.CSSStyleDeclaration.CSSStyleDeclaration)

#### [module cssom.CSSStyleDeclaration.prototype](#apidoc.module.cssom.CSSStyleDeclaration.prototype)
1.  [function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>constructor ()](#apidoc.element.cssom.CSSStyleDeclaration.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>getPropertyCSSValue ()](#apidoc.element.cssom.CSSStyleDeclaration.prototype.getPropertyCSSValue)
1.  [function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>getPropertyPriority (name)](#apidoc.element.cssom.CSSStyleDeclaration.prototype.getPropertyPriority)
1.  [function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>getPropertyShorthand ()](#apidoc.element.cssom.CSSStyleDeclaration.prototype.getPropertyShorthand)
1.  [function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>getPropertyValue (name)](#apidoc.element.cssom.CSSStyleDeclaration.prototype.getPropertyValue)
1.  [function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>isPropertyImplicit ()](#apidoc.element.cssom.CSSStyleDeclaration.prototype.isPropertyImplicit)
1.  [function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>removeProperty (name)](#apidoc.element.cssom.CSSStyleDeclaration.prototype.removeProperty)
1.  [function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>setProperty (name, value, priority)](#apidoc.element.cssom.CSSStyleDeclaration.prototype.setProperty)
1.  string <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>cssText

#### [module cssom.CSSStyleRule](#apidoc.module.cssom.CSSStyleRule)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSStyleRule ()](#apidoc.element.cssom.CSSStyleRule.CSSStyleRule)
1.  [function <span class="apidocSignatureSpan">cssom.CSSStyleRule.</span>parse (ruleText)](#apidoc.element.cssom.CSSStyleRule.parse)

#### [module cssom.CSSStyleRule.prototype](#apidoc.module.cssom.CSSStyleRule.prototype)
1.  [function <span class="apidocSignatureSpan">cssom.CSSStyleRule.prototype.</span>constructor ()](#apidoc.element.cssom.CSSStyleRule.prototype.constructor)
1.  number <span class="apidocSignatureSpan">cssom.CSSStyleRule.prototype.</span>type
1.  object <span class="apidocSignatureSpan">cssom.CSSStyleRule.prototype.</span>parentRule
1.  object <span class="apidocSignatureSpan">cssom.CSSStyleRule.prototype.</span>parentStyleSheet

#### [module cssom.CSSStyleSheet](#apidoc.module.cssom.CSSStyleSheet)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSStyleSheet ()](#apidoc.element.cssom.CSSStyleSheet.CSSStyleSheet)

#### [module cssom.CSSStyleSheet.prototype](#apidoc.module.cssom.CSSStyleSheet.prototype)
1.  [function <span class="apidocSignatureSpan">cssom.CSSStyleSheet.prototype.</span>constructor ()](#apidoc.element.cssom.CSSStyleSheet.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">cssom.CSSStyleSheet.prototype.</span>deleteRule (index)](#apidoc.element.cssom.CSSStyleSheet.prototype.deleteRule)
1.  [function <span class="apidocSignatureSpan">cssom.CSSStyleSheet.prototype.</span>insertRule (rule, index)](#apidoc.element.cssom.CSSStyleSheet.prototype.insertRule)
1.  [function <span class="apidocSignatureSpan">cssom.CSSStyleSheet.prototype.</span>toString ()](#apidoc.element.cssom.CSSStyleSheet.prototype.toString)
1.  object <span class="apidocSignatureSpan">cssom.CSSStyleSheet.prototype.</span>parentStyleSheet

#### [module cssom.CSSValue](#apidoc.module.cssom.CSSValue)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSValue ()](#apidoc.element.cssom.CSSValue.CSSValue)

#### [module cssom.CSSValueExpression](#apidoc.module.cssom.CSSValueExpression)
1.  [function <span class="apidocSignatureSpan">cssom.</span>CSSValueExpression (token, idx)](#apidoc.element.cssom.CSSValueExpression.CSSValueExpression)

#### [module cssom.MatcherList](#apidoc.module.cssom.MatcherList)
1.  [function <span class="apidocSignatureSpan">cssom.</span>MatcherList ()](#apidoc.element.cssom.MatcherList.MatcherList)

#### [module cssom.MediaList](#apidoc.module.cssom.MediaList)
1.  [function <span class="apidocSignatureSpan">cssom.</span>MediaList ()](#apidoc.element.cssom.MediaList.MediaList)

#### [module cssom.MediaList.prototype](#apidoc.module.cssom.MediaList.prototype)
1.  [function <span class="apidocSignatureSpan">cssom.MediaList.prototype.</span>appendMedium (medium)](#apidoc.element.cssom.MediaList.prototype.appendMedium)
1.  [function <span class="apidocSignatureSpan">cssom.MediaList.prototype.</span>constructor ()](#apidoc.element.cssom.MediaList.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">cssom.MediaList.prototype.</span>deleteMedium (medium)](#apidoc.element.cssom.MediaList.prototype.deleteMedium)
1.  string <span class="apidocSignatureSpan">cssom.MediaList.prototype.</span>mediaText

#### [module cssom.StyleSheet](#apidoc.module.cssom.StyleSheet)
1.  [function <span class="apidocSignatureSpan">cssom.</span>StyleSheet ()](#apidoc.element.cssom.StyleSheet.StyleSheet)

#### [module cssom.clone](#apidoc.module.cssom.clone)
1.  [function <span class="apidocSignatureSpan">cssom.</span>clone (stylesheet)](#apidoc.element.cssom.clone.clone)

#### [module cssom.parse](#apidoc.module.cssom.parse)
1.  [function <span class="apidocSignatureSpan">cssom.</span>parse (token)](#apidoc.element.cssom.parse.parse)



# <a name="apidoc.module.cssom"></a>[module cssom](#apidoc.module.cssom)

#### <a name="apidoc.element.cssom.CSSImportRule"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSImportRule ()](#apidoc.element.cssom.CSSImportRule)
- description and source-code
```javascript
function CSSImportRule() {
	CSSOM.CSSRule.call(this);
	this.href = "";
	this.media = new CSSOM.MediaList();
	this.styleSheet = new CSSOM.CSSStyleSheet();
}
```
- example usage
```shell
...
					state = "before-name";
					break;
				case "atRule":
					buffer = "";
					state = "before-selector";
					break;
				case "importRule":
					importRule = new CSSOM.CSSImportRule();
					importRule.parentStyleSheet = importRule.styleSheet.parentStyleSheet = styleSheet;
					importRule.cssText = buffer + character;
					styleSheet.cssRules.push(importRule);
					buffer = "";
					state = "before-selector";
					break;
				default:
...
```

#### <a name="apidoc.element.cssom.CSSMediaRule"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSMediaRule ()](#apidoc.element.cssom.CSSMediaRule)
- description and source-code
```javascript
function CSSMediaRule() {
	CSSOM.CSSRule.call(this);
	this.media = new CSSOM.MediaList();
	this.cssRules = [];
}
```
- example usage
```shell
...
				documentRule = new CSSOM.CSSDocumentRule();
				documentRule.__starts = i;
				i += "-moz-document".length;
				buffer = "";
				break;
			} else if (token.indexOf("@media", i) === i) {
				state = "atBlock";
				mediaRule = new CSSOM.CSSMediaRule();
				mediaRule.__starts = i;
				i += "media".length;
				buffer = "";
				break;
			} else if (token.indexOf("@host", i) === i) {
				state = "hostRule-begin";
				i += "host".length;
...
```

#### <a name="apidoc.element.cssom.CSSRule"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSRule ()](#apidoc.element.cssom.CSSRule)
- description and source-code
```javascript
function CSSRule() {
	this.parentRule = null;
	this.parentStyleSheet = null;
}
```
- example usage
```shell
...
 */
CSSOM.CSSDocumentRule = function CSSDocumentRule() {
    CSSOM.CSSRule.call(this);
    this.matcher = new CSSOM.MatcherList();
    this.cssRules = [];
};

CSSOM.CSSDocumentRule.prototype = new CSSOM.CSSRule();
CSSOM.CSSDocumentRule.prototype.constructor = CSSOM.CSSDocumentRule;
CSSOM.CSSDocumentRule.prototype.type = 10;
//FIXME
//CSSOM.CSSDocumentRule.prototype.insertRule = CSSStyleSheet.prototype.insertRule;
//CSSOM.CSSDocumentRule.prototype.deleteRule = CSSStyleSheet.prototype.deleteRule;

Object.defineProperty(CSSOM.CSSDocumentRule.prototype, "cssText", {
...
```

#### <a name="apidoc.element.cssom.CSSStyleDeclaration"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSStyleDeclaration ()](#apidoc.element.cssom.CSSStyleDeclaration)
- description and source-code
```javascript
function CSSStyleDeclaration(){
	this.length = 0;
	this.parentRule = null;

	// NON-STANDARD
	this._importants = {};
}
```
- example usage
```shell
...

/**
 * @constructor
 * @see http://dev.w3.org/csswg/cssom/#css-font-face-rule
 */
CSSOM.CSSFontFaceRule = function CSSFontFaceRule() {
	CSSOM.CSSRule.call(this);
	this.style = new CSSOM.CSSStyleDeclaration();
	this.style.parentRule = this;
};

CSSOM.CSSFontFaceRule.prototype = new CSSOM.CSSRule();
CSSOM.CSSFontFaceRule.prototype.constructor = CSSOM.CSSFontFaceRule;
CSSOM.CSSFontFaceRule.prototype.type = 5;
//FIXME
...
```

#### <a name="apidoc.element.cssom.CSSStyleRule"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSStyleRule ()](#apidoc.element.cssom.CSSStyleRule)
- description and source-code
```javascript
function CSSStyleRule() {
	CSSOM.CSSRule.call(this);
	this.selectorText = "";
	this.style = new CSSOM.CSSStyleDeclaration();
	this.style.parentRule = this;
}
```
- example usage
```shell
...
	var buffer = "";

	var SIGNIFICANT_WHITESPACE = {
		"selector": true,
		"value": true
	};

	var styleRule = new CSSOM.CSSStyleRule();
	var name, priority="";

	for (var character; (character = ruleText.charAt(i)); i++) {

		switch (character) {

		case " ":
...
```

#### <a name="apidoc.element.cssom.CSSStyleSheet"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSStyleSheet ()](#apidoc.element.cssom.CSSStyleSheet)
- description and source-code
```javascript
function CSSStyleSheet() {
	CSSOM.StyleSheet.call(this);
	this.cssRules = [];
}
```
- example usage
```shell
...
 * @see http://dev.w3.org/csswg/cssom/#cssimportrule
 * @see http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSImportRule
 */
CSSOM.CSSImportRule = function CSSImportRule() {
	CSSOM.CSSRule.call(this);
	this.href = "";
	this.media = new CSSOM.MediaList();
	this.styleSheet = new CSSOM.CSSStyleSheet();
};

CSSOM.CSSImportRule.prototype = new CSSOM.CSSRule();
CSSOM.CSSImportRule.prototype.constructor = CSSOM.CSSImportRule;
CSSOM.CSSImportRule.prototype.type = 3;

Object.defineProperty(CSSOM.CSSImportRule.prototype, "cssText", {
...
```

#### <a name="apidoc.element.cssom.MediaList"></a>[function <span class="apidocSignatureSpan">cssom.</span>MediaList ()](#apidoc.element.cssom.MediaList)
- description and source-code
```javascript
function MediaList(){
	this.length = 0;
}
```
- example usage
```shell
...
 * @constructor
 * @see http://dev.w3.org/csswg/cssom/#cssimportrule
 * @see http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSImportRule
 */
CSSOM.CSSImportRule = function CSSImportRule() {
	CSSOM.CSSRule.call(this);
	this.href = "";
	this.media = new CSSOM.MediaList();
	this.styleSheet = new CSSOM.CSSStyleSheet();
};

CSSOM.CSSImportRule.prototype = new CSSOM.CSSRule();
CSSOM.CSSImportRule.prototype.constructor = CSSOM.CSSImportRule;
CSSOM.CSSImportRule.prototype.type = 3;
...
```

#### <a name="apidoc.element.cssom.StyleSheet"></a>[function <span class="apidocSignatureSpan">cssom.</span>StyleSheet ()](#apidoc.element.cssom.StyleSheet)
- description and source-code
```javascript
function StyleSheet() {
	this.parentStyleSheet = null;
}
```
- example usage
```shell
...
*/
CSSOM.CSSStyleSheet = function CSSStyleSheet() {
	CSSOM.StyleSheet.call(this);
	this.cssRules = [];
};


CSSOM.CSSStyleSheet.prototype = new CSSOM.StyleSheet();
CSSOM.CSSStyleSheet.prototype.constructor = CSSOM.CSSStyleSheet;


/**
* Used to insert a new rule into the style sheet. The new rule now becomes part of the cascade.
*
*   sheet = new Sheet("body {margin: 0}")
...
```

#### <a name="apidoc.element.cssom.clone"></a>[function <span class="apidocSignatureSpan">cssom.</span>clone (stylesheet)](#apidoc.element.cssom.clone)
- description and source-code
```javascript
function clone(stylesheet) {

	var cloned = new CSSOM.CSSStyleSheet();

	var rules = stylesheet.cssRules;
	if (!rules) {
		return cloned;
	}

	var RULE_TYPES = {
		1: CSSOM.CSSStyleRule,
		4: CSSOM.CSSMediaRule,
		//3: CSSOM.CSSImportRule,
		//5: CSSOM.CSSFontFaceRule,
		//6: CSSOM.CSSPageRule,
		8: CSSOM.CSSKeyframesRule,
		9: CSSOM.CSSKeyframeRule
	};

	for (var i=0, rulesLength=rules.length; i < rulesLength; i++) {
		var rule = rules[i];
		var ruleClone = cloned.cssRules[i] = new RULE_TYPES[rule.type]();

		var style = rule.style;
		if (style) {
			var styleClone = ruleClone.style = new CSSOM.CSSStyleDeclaration();
			for (var j=0, styleLength=style.length; j < styleLength; j++) {
				var name = styleClone[j] = style[j];
				styleClone[name] = style[name];
				styleClone._importants[name] = style.getPropertyPriority(name);
			}
			styleClone.length = style.length;
		}

		if (rule.hasOwnProperty('keyText')) {
			ruleClone.keyText = rule.keyText;
		}

		if (rule.hasOwnProperty('selectorText')) {
			ruleClone.selectorText = rule.selectorText;
		}

		if (rule.hasOwnProperty('mediaText')) {
			ruleClone.mediaText = rule.mediaText;
		}

		if (rule.hasOwnProperty('cssRules')) {
			ruleClone.cssRules = clone(rule).cssRules;
		}
	}

	return cloned;

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cssom.parse"></a>[function <span class="apidocSignatureSpan">cssom.</span>parse (token)](#apidoc.element.cssom.parse)
- description and source-code
```javascript
function parse(token) {

	var i = 0;

	<span class="apidocCodeCommentSpan">/**
		"before-selector" or
		"selector" or
		"atRule" or
		"atBlock" or
		"before-name" or
		"name" or
		"before-value" or
		"value"
	*/
</span>	var state = "before-selector";

	var index;
	var buffer = "";
	var valueParenthesisDepth = 0;

	var SIGNIFICANT_WHITESPACE = {
		"selector": true,
		"value": true,
		"value-parenthesis": true,
		"atRule": true,
		"importRule-begin": true,
		"importRule": true,
		"atBlock": true,
		'documentRule-begin': true
	};

	var styleSheet = new CSSOM.CSSStyleSheet();

	// @type CSSStyleSheet|CSSMediaRule|CSSFontFaceRule|CSSKeyframesRule|CSSDocumentRule
	var currentScope = styleSheet;

	// @type CSSMediaRule|CSSKeyframesRule|CSSDocumentRule
	var parentRule;

	var name, priority="", styleRule, mediaRule, importRule, fontFaceRule, keyframesRule, documentRule, hostRule;

	var atKeyframesRegExp = /@(-(?:\w+-)+)?keyframes/g;

	var parseError = function(message) {
		var lines = token.substring(0, i).split('\n');
		var lineCount = lines.length;
		var charCount = lines.pop().length + 1;
		var error = new Error(message + ' (line ' + lineCount + ', char ' + charCount + ')');
		error.line = lineCount;
		/* jshint sub : true */
		error['char'] = charCount;
		error.styleSheet = styleSheet;
		throw error;
	};

	for (var character; (character = token.charAt(i)); i++) {

		switch (character) {

		case " ":
		case "\t":
		case "\r":
		case "\n":
		case "\f":
			if (SIGNIFICANT_WHITESPACE[state]) {
				buffer += character;
			}
			break;

		// String
		case '"':
			index = i + 1;
			do {
				index = token.indexOf('"', index) + 1;
				if (!index) {
					parseError('Unmatched "');
				}
			} while (token[index - 2] === '\\');
			buffer += token.slice(i, index);
			i = index - 1;
			switch (state) {
				case 'before-value':
					state = 'value';
					break;
				case 'importRule-begin':
					state = 'importRule';
					break;
			}
			break;

		case "'":
			index = i + 1;
			do {
				index = token.indexOf("'", index) + 1;
				if (!index) {
					parseError("Unmatched '");
				}
			} while (token[index - 2] === '\\');
			buffer += token.slice(i, index);
			i = index - 1;
			switch (state) {
				case 'before-value':
					state = 'value';
					break;
				case 'importRule-begin':
					state = 'importRule';
					break;
			}
			break;

		// Comment
		case "/":
			if (token.charAt(i + 1) === "*") {
				i += 2;
				index = token.indexOf("*/", i);
				if (index === -1) {
					parseError("Missing */");
				} else {
					i = index + 1;
				}
			} else {
				buffer += character;
			}
			if (state === "importRule-begin") {
				buffer += " ";
				state = "importRule";
			}
			break;

		// At-rule
		case "@":
			if (token.indexOf("@-moz-document", i) === i) {
				state = "documentRule-begin";
				documentRule = new CSSOM.CSSDocumentRule();
				documentRule.__starts = i;
				i += "-moz-document".length;
				buffer = "";
				break;
			} else if (token.indexOf("@media", i) === i) {
				state = "atBlock";
				mediaRule = new CSSOM.CSSMediaRule();
				mediaRule.__starts = i;
				i += "media".length;
				buffer = "";
				break;
			} else if (token.indexOf("@host", i) === i) {
				state = "hostRule-begin";
				i += "host".length;
				hostRule = new CSSOM.CSSHostRule();
				hostRule.__starts = i;
				buffer = "";
				break;
			} else if (token.indexOf("@import", i) === i) {
				state = "importRule-begin";
				i += "import".length;
				buffer += "@import";
				break;
			} else if (token.indexOf("@font-face", i) === i) {
				state = "fontFaceRule-begin";
				i += "font-face".length;
				fontFaceRule = new CSSOM.CSSFontFaceRule();
				fontFaceRule.__starts = i;
				buffer = "";
				break;
			} else {
				atKeyframesRegExp.lastIndex = i;
				var matchKeyframes = atKeyframesRegExp.exec(token);
				if (matchKeyframes && matchKeyframes.index === i) {
					state = "keyframesRule-begin";
					keyframesRule = new CSSOM.CSSKeyframesRule();
					keyframesRule.__starts = i;
					keyframesRule._vendorPrefix = matchKeyframes[1]; // Will come out as undefined if no prefix was found
					i += matchKeyframes[0].length - 1; ...
```
- example usage
```shell
...



# CSSOM

CSSOM.js is a CSS parser written in pure JavaScript. It also a partial implementation of [CSS Object Model](http://dev.w3.org/csswg
/cssom/).

CSSOM.parse("body {color: black}")
-> {
  cssRules: [
    {
      selectorText: "body",
      style: {
        0: "color",
        color: "black",
...
```



# <a name="apidoc.module.cssom.CSSDocumentRule"></a>[module cssom.CSSDocumentRule](#apidoc.module.cssom.CSSDocumentRule)

#### <a name="apidoc.element.cssom.CSSDocumentRule.CSSDocumentRule"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSDocumentRule ()](#apidoc.element.cssom.CSSDocumentRule.CSSDocumentRule)
- description and source-code
```javascript
function CSSDocumentRule() {
    CSSOM.CSSRule.call(this);
    this.matcher = new CSSOM.MatcherList();
    this.cssRules = [];
}
```
- example usage
```shell
...
			}
			break;

		// At-rule
		case "@":
			if (token.indexOf("@-moz-document", i) === i) {
				state = "documentRule-begin";
				documentRule = new CSSOM.CSSDocumentRule();
				documentRule.__starts = i;
				i += "-moz-document".length;
				buffer = "";
				break;
			} else if (token.indexOf("@media", i) === i) {
				state = "atBlock";
				mediaRule = new CSSOM.CSSMediaRule();
...
```



# <a name="apidoc.module.cssom.CSSFontFaceRule"></a>[module cssom.CSSFontFaceRule](#apidoc.module.cssom.CSSFontFaceRule)

#### <a name="apidoc.element.cssom.CSSFontFaceRule.CSSFontFaceRule"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSFontFaceRule ()](#apidoc.element.cssom.CSSFontFaceRule.CSSFontFaceRule)
- description and source-code
```javascript
function CSSFontFaceRule() {
	CSSOM.CSSRule.call(this);
	this.style = new CSSOM.CSSStyleDeclaration();
	this.style.parentRule = this;
}
```
- example usage
```shell
...
				state = "importRule-begin";
				i += "import".length;
				buffer += "@import";
				break;
			} else if (token.indexOf("@font-face", i) === i) {
				state = "fontFaceRule-begin";
				i += "font-face".length;
				fontFaceRule = new CSSOM.CSSFontFaceRule();
				fontFaceRule.__starts = i;
				buffer = "";
				break;
			} else {
				atKeyframesRegExp.lastIndex = i;
				var matchKeyframes = atKeyframesRegExp.exec(token);
				if (matchKeyframes && matchKeyframes.index === i) {
...
```



# <a name="apidoc.module.cssom.CSSHostRule"></a>[module cssom.CSSHostRule](#apidoc.module.cssom.CSSHostRule)

#### <a name="apidoc.element.cssom.CSSHostRule.CSSHostRule"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSHostRule ()](#apidoc.element.cssom.CSSHostRule.CSSHostRule)
- description and source-code
```javascript
function CSSHostRule() {
	CSSOM.CSSRule.call(this);
	this.cssRules = [];
}
```
- example usage
```shell
...
				mediaRule.__starts = i;
				i += "media".length;
				buffer = "";
				break;
			} else if (token.indexOf("@host", i) === i) {
				state = "hostRule-begin";
				i += "host".length;
				hostRule = new CSSOM.CSSHostRule();
				hostRule.__starts = i;
				buffer = "";
				break;
			} else if (token.indexOf("@import", i) === i) {
				state = "importRule-begin";
				i += "import".length;
				buffer += "@import";
...
```



# <a name="apidoc.module.cssom.CSSImportRule"></a>[module cssom.CSSImportRule](#apidoc.module.cssom.CSSImportRule)

#### <a name="apidoc.element.cssom.CSSImportRule.CSSImportRule"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSImportRule ()](#apidoc.element.cssom.CSSImportRule.CSSImportRule)
- description and source-code
```javascript
function CSSImportRule() {
	CSSOM.CSSRule.call(this);
	this.href = "";
	this.media = new CSSOM.MediaList();
	this.styleSheet = new CSSOM.CSSStyleSheet();
}
```
- example usage
```shell
...
					state = "before-name";
					break;
				case "atRule":
					buffer = "";
					state = "before-selector";
					break;
				case "importRule":
					importRule = new CSSOM.CSSImportRule();
					importRule.parentStyleSheet = importRule.styleSheet.parentStyleSheet = styleSheet;
					importRule.cssText = buffer + character;
					styleSheet.cssRules.push(importRule);
					buffer = "";
					state = "before-selector";
					break;
				default:
...
```



# <a name="apidoc.module.cssom.CSSImportRule.prototype"></a>[module cssom.CSSImportRule.prototype](#apidoc.module.cssom.CSSImportRule.prototype)

#### <a name="apidoc.element.cssom.CSSImportRule.prototype.constructor"></a>[function <span class="apidocSignatureSpan">cssom.CSSImportRule.prototype.</span>constructor ()](#apidoc.element.cssom.CSSImportRule.prototype.constructor)
- description and source-code
```javascript
function CSSImportRule() {
	CSSOM.CSSRule.call(this);
	this.href = "";
	this.media = new CSSOM.MediaList();
	this.styleSheet = new CSSOM.CSSStyleSheet();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cssom.CSSKeyframeRule"></a>[module cssom.CSSKeyframeRule](#apidoc.module.cssom.CSSKeyframeRule)

#### <a name="apidoc.element.cssom.CSSKeyframeRule.CSSKeyframeRule"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSKeyframeRule ()](#apidoc.element.cssom.CSSKeyframeRule.CSSKeyframeRule)
- description and source-code
```javascript
function CSSKeyframeRule() {
	CSSOM.CSSRule.call(this);
	this.keyText = '';
	this.style = new CSSOM.CSSStyleDeclaration();
	this.style.parentRule = this;
}
```
- example usage
```shell
...
					keyframesRule.parentRule = parentRule;
				}
				keyframesRule.parentStyleSheet = styleSheet;
				currentScope = parentRule = keyframesRule;
				buffer = "";
				state = "keyframeRule-begin";
			} else if (state === "keyframeRule-begin") {
				styleRule = new CSSOM.CSSKeyframeRule();
				styleRule.keyText = buffer.trim();
				styleRule.__starts = i;
				buffer = "";
				state = "before-name";
			} else if (state === "documentRule-begin") {
				// FIXME: what if this '{' is in the url text of the match function?
				documentRule.matcher.matcherText = buffer.trim();
...
```



# <a name="apidoc.module.cssom.CSSKeyframesRule"></a>[module cssom.CSSKeyframesRule](#apidoc.module.cssom.CSSKeyframesRule)

#### <a name="apidoc.element.cssom.CSSKeyframesRule.CSSKeyframesRule"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSKeyframesRule ()](#apidoc.element.cssom.CSSKeyframesRule.CSSKeyframesRule)
- description and source-code
```javascript
function CSSKeyframesRule() {
	CSSOM.CSSRule.call(this);
	this.name = '';
	this.cssRules = [];
}
```
- example usage
```shell
...
				buffer = "";
				break;
			} else {
				atKeyframesRegExp.lastIndex = i;
				var matchKeyframes = atKeyframesRegExp.exec(token);
				if (matchKeyframes && matchKeyframes.index === i) {
					state = "keyframesRule-begin";
					keyframesRule = new CSSOM.CSSKeyframesRule();
					keyframesRule.__starts = i;
					keyframesRule._vendorPrefix = matchKeyframes[1]; // Will come out as undefined if no prefix was found
					i += matchKeyframes[0].length - 1;
					buffer = "";
					break;
				} else if (state === "selector") {
					state = "atRule";
...
```



# <a name="apidoc.module.cssom.CSSMediaRule"></a>[module cssom.CSSMediaRule](#apidoc.module.cssom.CSSMediaRule)

#### <a name="apidoc.element.cssom.CSSMediaRule.CSSMediaRule"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSMediaRule ()](#apidoc.element.cssom.CSSMediaRule.CSSMediaRule)
- description and source-code
```javascript
function CSSMediaRule() {
	CSSOM.CSSRule.call(this);
	this.media = new CSSOM.MediaList();
	this.cssRules = [];
}
```
- example usage
```shell
...
				documentRule = new CSSOM.CSSDocumentRule();
				documentRule.__starts = i;
				i += "-moz-document".length;
				buffer = "";
				break;
			} else if (token.indexOf("@media", i) === i) {
				state = "atBlock";
				mediaRule = new CSSOM.CSSMediaRule();
				mediaRule.__starts = i;
				i += "media".length;
				buffer = "";
				break;
			} else if (token.indexOf("@host", i) === i) {
				state = "hostRule-begin";
				i += "host".length;
...
```



# <a name="apidoc.module.cssom.CSSMediaRule.prototype"></a>[module cssom.CSSMediaRule.prototype](#apidoc.module.cssom.CSSMediaRule.prototype)

#### <a name="apidoc.element.cssom.CSSMediaRule.prototype.constructor"></a>[function <span class="apidocSignatureSpan">cssom.CSSMediaRule.prototype.</span>constructor ()](#apidoc.element.cssom.CSSMediaRule.prototype.constructor)
- description and source-code
```javascript
function CSSMediaRule() {
	CSSOM.CSSRule.call(this);
	this.media = new CSSOM.MediaList();
	this.cssRules = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cssom.CSSRule"></a>[module cssom.CSSRule](#apidoc.module.cssom.CSSRule)

#### <a name="apidoc.element.cssom.CSSRule.CSSRule"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSRule ()](#apidoc.element.cssom.CSSRule.CSSRule)
- description and source-code
```javascript
function CSSRule() {
	this.parentRule = null;
	this.parentStyleSheet = null;
}
```
- example usage
```shell
...
 */
CSSOM.CSSDocumentRule = function CSSDocumentRule() {
    CSSOM.CSSRule.call(this);
    this.matcher = new CSSOM.MatcherList();
    this.cssRules = [];
};

CSSOM.CSSDocumentRule.prototype = new CSSOM.CSSRule();
CSSOM.CSSDocumentRule.prototype.constructor = CSSOM.CSSDocumentRule;
CSSOM.CSSDocumentRule.prototype.type = 10;
//FIXME
//CSSOM.CSSDocumentRule.prototype.insertRule = CSSStyleSheet.prototype.insertRule;
//CSSOM.CSSDocumentRule.prototype.deleteRule = CSSStyleSheet.prototype.deleteRule;

Object.defineProperty(CSSOM.CSSDocumentRule.prototype, "cssText", {
...
```



# <a name="apidoc.module.cssom.CSSRule.prototype"></a>[module cssom.CSSRule.prototype](#apidoc.module.cssom.CSSRule.prototype)

#### <a name="apidoc.element.cssom.CSSRule.prototype.constructor"></a>[function <span class="apidocSignatureSpan">cssom.CSSRule.prototype.</span>constructor ()](#apidoc.element.cssom.CSSRule.prototype.constructor)
- description and source-code
```javascript
function CSSRule() {
	this.parentRule = null;
	this.parentStyleSheet = null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cssom.CSSStyleDeclaration"></a>[module cssom.CSSStyleDeclaration](#apidoc.module.cssom.CSSStyleDeclaration)

#### <a name="apidoc.element.cssom.CSSStyleDeclaration.CSSStyleDeclaration"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSStyleDeclaration ()](#apidoc.element.cssom.CSSStyleDeclaration.CSSStyleDeclaration)
- description and source-code
```javascript
function CSSStyleDeclaration(){
	this.length = 0;
	this.parentRule = null;

	// NON-STANDARD
	this._importants = {};
}
```
- example usage
```shell
...

/**
 * @constructor
 * @see http://dev.w3.org/csswg/cssom/#css-font-face-rule
 */
CSSOM.CSSFontFaceRule = function CSSFontFaceRule() {
	CSSOM.CSSRule.call(this);
	this.style = new CSSOM.CSSStyleDeclaration();
	this.style.parentRule = this;
};

CSSOM.CSSFontFaceRule.prototype = new CSSOM.CSSRule();
CSSOM.CSSFontFaceRule.prototype.constructor = CSSOM.CSSFontFaceRule;
CSSOM.CSSFontFaceRule.prototype.type = 5;
//FIXME
...
```



# <a name="apidoc.module.cssom.CSSStyleDeclaration.prototype"></a>[module cssom.CSSStyleDeclaration.prototype](#apidoc.module.cssom.CSSStyleDeclaration.prototype)

#### <a name="apidoc.element.cssom.CSSStyleDeclaration.prototype.constructor"></a>[function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>constructor ()](#apidoc.element.cssom.CSSStyleDeclaration.prototype.constructor)
- description and source-code
```javascript
function CSSStyleDeclaration(){
	this.length = 0;
	this.parentRule = null;

	// NON-STANDARD
	this._importants = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cssom.CSSStyleDeclaration.prototype.getPropertyCSSValue"></a>[function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>getPropertyCSSValue ()](#apidoc.element.cssom.CSSStyleDeclaration.prototype.getPropertyCSSValue)
- description and source-code
```javascript
getPropertyCSSValue = function () {
		//FIXME
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cssom.CSSStyleDeclaration.prototype.getPropertyPriority"></a>[function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>getPropertyPriority (name)](#apidoc.element.cssom.CSSStyleDeclaration.prototype.getPropertyPriority)
- description and source-code
```javascript
getPropertyPriority = function (name) {
		return this._importants[name] || "";
	}
```
- example usage
```shell
...

	// Doesn't work in IE < 9
	get cssText(){
		var properties = [];
		for (var i=0, length=this.length; i < length; ++i) {
			var name = this[i];
			var value = this.getPropertyValue(name);
			var priority = this.getPropertyPriority(name);
			if (priority) {
				priority = " !" + priority;
			}
			properties[i] = name + ": " + value + priority + ";";
		}
		return properties.join(" ");
	},
...
```

#### <a name="apidoc.element.cssom.CSSStyleDeclaration.prototype.getPropertyShorthand"></a>[function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>getPropertyShorthand ()](#apidoc.element.cssom.CSSStyleDeclaration.prototype.getPropertyShorthand)
- description and source-code
```javascript
getPropertyShorthand = function () {
		//FIXME
	}
```
- example usage
```shell
...
	getPropertyPriority: function(name) {
		return this._importants[name] || "";
	},


	/**
	 *   element.style.overflow = "auto"
	 *   element.style.getPropertyShorthand("overflow-x")
	 *   -> "overflow"
	 */
	getPropertyShorthand: function() {
		//FIXME
	},

	isPropertyImplicit: function() {
...
```

#### <a name="apidoc.element.cssom.CSSStyleDeclaration.prototype.getPropertyValue"></a>[function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>getPropertyValue (name)](#apidoc.element.cssom.CSSStyleDeclaration.prototype.getPropertyValue)
- description and source-code
```javascript
getPropertyValue = function (name) {
		return this[name] || "";
	}
```
- example usage
```shell
...
	},

	// Doesn't work in IE < 9
	get cssText(){
		var properties = [];
		for (var i=0, length=this.length; i < length; ++i) {
			var name = this[i];
			var value = this.getPropertyValue(name);
			var priority = this.getPropertyPriority(name);
			if (priority) {
				priority = " !" + priority;
			}
			properties[i] = name + ": " + value + priority + ";";
		}
		return properties.join(" ");
...
```

#### <a name="apidoc.element.cssom.CSSStyleDeclaration.prototype.isPropertyImplicit"></a>[function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>isPropertyImplicit ()](#apidoc.element.cssom.CSSStyleDeclaration.prototype.isPropertyImplicit)
- description and source-code
```javascript
isPropertyImplicit = function () {
		//FIXME
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cssom.CSSStyleDeclaration.prototype.removeProperty"></a>[function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>removeProperty (name)](#apidoc.element.cssom.CSSStyleDeclaration.prototype.removeProperty)
- description and source-code
```javascript
removeProperty = function (name) {
		if (!(name in this)) {
			return "";
		}
		var index = Array.prototype.indexOf.call(this, name);
		if (index < 0) {
			return "";
		}
		var prevValue = this[name];
		this[name] = "";

		// That's what WebKit and Opera do
		Array.prototype.splice.call(this, index, 1);

		// That's what Firefox does
		//this[index] = ""

		return prevValue;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cssom.CSSStyleDeclaration.prototype.setProperty"></a>[function <span class="apidocSignatureSpan">cssom.CSSStyleDeclaration.prototype.</span>setProperty (name, value, priority)](#apidoc.element.cssom.CSSStyleDeclaration.prototype.setProperty)
- description and source-code
```javascript
setProperty = function (name, value, priority) {
		if (this[name]) {
			// Property already exist. Overwrite it.
			var index = Array.prototype.indexOf.call(this, name);
			if (index < 0) {
				this[this.length] = name;
				this.length++;
			}
		} else {
			// New property.
			this[this.length] = name;
			this.length++;
		}
		this[name] = value + "";
		this._importants[name] = priority;
	}
```
- example usage
```shell
...
		Array.prototype.splice.call(this, 0, this.length);
		this._importants = {};

		var dummyRule = CSSOM.parse('#bogus{' + text + '}').cssRules[0].style;
		var length = dummyRule.length;
		for (i = 0; i < length; ++i) {
			name = dummyRule[i];
			this.setProperty(dummyRule[i], dummyRule.getPropertyValue(name), dummyRule.getPropertyPriority(name));
		}
	}
};


//.CommonJS
exports.CSSStyleDeclaration = CSSOM.CSSStyleDeclaration;
...
```



# <a name="apidoc.module.cssom.CSSStyleRule"></a>[module cssom.CSSStyleRule](#apidoc.module.cssom.CSSStyleRule)

#### <a name="apidoc.element.cssom.CSSStyleRule.CSSStyleRule"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSStyleRule ()](#apidoc.element.cssom.CSSStyleRule.CSSStyleRule)
- description and source-code
```javascript
function CSSStyleRule() {
	CSSOM.CSSRule.call(this);
	this.selectorText = "";
	this.style = new CSSOM.CSSStyleDeclaration();
	this.style.parentRule = this;
}
```
- example usage
```shell
...
	var buffer = "";

	var SIGNIFICANT_WHITESPACE = {
		"selector": true,
		"value": true
	};

	var styleRule = new CSSOM.CSSStyleRule();
	var name, priority="";

	for (var character; (character = ruleText.charAt(i)); i++) {

		switch (character) {

		case " ":
...
```

#### <a name="apidoc.element.cssom.CSSStyleRule.parse"></a>[function <span class="apidocSignatureSpan">cssom.CSSStyleRule.</span>parse (ruleText)](#apidoc.element.cssom.CSSStyleRule.parse)
- description and source-code
```javascript
parse = function (ruleText) {
	var i = 0;
	var state = "selector";
	var index;
	var j = i;
	var buffer = "";

	var SIGNIFICANT_WHITESPACE = {
		"selector": true,
		"value": true
	};

	var styleRule = new CSSOM.CSSStyleRule();
	var name, priority="";

	for (var character; (character = ruleText.charAt(i)); i++) {

		switch (character) {

		case " ":
		case "\t":
		case "\r":
		case "\n":
		case "\f":
			if (SIGNIFICANT_WHITESPACE[state]) {
				// Squash 2 or more white-spaces in the row into 1
				switch (ruleText.charAt(i - 1)) {
					case " ":
					case "\t":
					case "\r":
					case "\n":
					case "\f":
						break;
					default:
						buffer += " ";
						break;
				}
			}
			break;

		// String
		case '"':
			j = i + 1;
			index = ruleText.indexOf('"', j) + 1;
			if (!index) {
				throw '" is missing';
			}
			buffer += ruleText.slice(i, index);
			i = index - 1;
			break;

		case "'":
			j = i + 1;
			index = ruleText.indexOf("'", j) + 1;
			if (!index) {
				throw "' is missing";
			}
			buffer += ruleText.slice(i, index);
			i = index - 1;
			break;

		// Comment
		case "/":
			if (ruleText.charAt(i + 1) === "*") {
				i += 2;
				index = ruleText.indexOf("*/", i);
				if (index === -1) {
					throw new SyntaxError("Missing */");
				} else {
					i = index + 1;
				}
			} else {
				buffer += character;
			}
			break;

		case "{":
			if (state === "selector") {
				styleRule.selectorText = buffer.trim();
				buffer = "";
				state = "name";
			}
			break;

		case ":":
			if (state === "name") {
				name = buffer.trim();
				buffer = "";
				state = "value";
			} else {
				buffer += character;
			}
			break;

		case "!":
			if (state === "value" && ruleText.indexOf("!important", i) === i) {
				priority = "important";
				i += "important".length;
			} else {
				buffer += character;
			}
			break;

		case ";":
			if (state === "value") {
				styleRule.style.setProperty(name, buffer.trim(), priority);
				priority = "";
				buffer = "";
				state = "name";
			} else {
				buffer += character;
			}
			break;

		case "}":
			if (state === "value") {
				styleRule.style.setProperty(name, buffer.trim(), priority);
				priority = "";
				buffer = "";
			} else if (state === "name") {
				break;
			} else {
				buffer += character;
			}
			state = "selector";
			break;

		default:
			buffer += character;
			break;

		}
	}

	return styleRule;

}
```
- example usage
```shell
...



# CSSOM

CSSOM.js is a CSS parser written in pure JavaScript. It also a partial implementation of [CSS Object Model](http://dev.w3.org/csswg
/cssom/).

CSSOM.parse("body {color: black}")
-> {
  cssRules: [
    {
      selectorText: "body",
      style: {
        0: "color",
        color: "black",
...
```



# <a name="apidoc.module.cssom.CSSStyleRule.prototype"></a>[module cssom.CSSStyleRule.prototype](#apidoc.module.cssom.CSSStyleRule.prototype)

#### <a name="apidoc.element.cssom.CSSStyleRule.prototype.constructor"></a>[function <span class="apidocSignatureSpan">cssom.CSSStyleRule.prototype.</span>constructor ()](#apidoc.element.cssom.CSSStyleRule.prototype.constructor)
- description and source-code
```javascript
function CSSStyleRule() {
	CSSOM.CSSRule.call(this);
	this.selectorText = "";
	this.style = new CSSOM.CSSStyleDeclaration();
	this.style.parentRule = this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cssom.CSSStyleSheet"></a>[module cssom.CSSStyleSheet](#apidoc.module.cssom.CSSStyleSheet)

#### <a name="apidoc.element.cssom.CSSStyleSheet.CSSStyleSheet"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSStyleSheet ()](#apidoc.element.cssom.CSSStyleSheet.CSSStyleSheet)
- description and source-code
```javascript
function CSSStyleSheet() {
	CSSOM.StyleSheet.call(this);
	this.cssRules = [];
}
```
- example usage
```shell
...
 * @see http://dev.w3.org/csswg/cssom/#cssimportrule
 * @see http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSImportRule
 */
CSSOM.CSSImportRule = function CSSImportRule() {
	CSSOM.CSSRule.call(this);
	this.href = "";
	this.media = new CSSOM.MediaList();
	this.styleSheet = new CSSOM.CSSStyleSheet();
};

CSSOM.CSSImportRule.prototype = new CSSOM.CSSRule();
CSSOM.CSSImportRule.prototype.constructor = CSSOM.CSSImportRule;
CSSOM.CSSImportRule.prototype.type = 3;

Object.defineProperty(CSSOM.CSSImportRule.prototype, "cssText", {
...
```



# <a name="apidoc.module.cssom.CSSStyleSheet.prototype"></a>[module cssom.CSSStyleSheet.prototype](#apidoc.module.cssom.CSSStyleSheet.prototype)

#### <a name="apidoc.element.cssom.CSSStyleSheet.prototype.constructor"></a>[function <span class="apidocSignatureSpan">cssom.CSSStyleSheet.prototype.</span>constructor ()](#apidoc.element.cssom.CSSStyleSheet.prototype.constructor)
- description and source-code
```javascript
function CSSStyleSheet() {
	CSSOM.StyleSheet.call(this);
	this.cssRules = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cssom.CSSStyleSheet.prototype.deleteRule"></a>[function <span class="apidocSignatureSpan">cssom.CSSStyleSheet.prototype.</span>deleteRule (index)](#apidoc.element.cssom.CSSStyleSheet.prototype.deleteRule)
- description and source-code
```javascript
deleteRule = function (index) {
	if (index < 0 || index >= this.cssRules.length) {
		throw new RangeError("INDEX_SIZE_ERR");
	}
	this.cssRules.splice(index, 1);
}
```
- example usage
```shell
...

/**
 * Used to delete a rule from the style sheet.
 *
 *   sheet = new Sheet("img{border:none} body{margin:0}")
 *   sheet.toString()
 *   -> "img{border:none;}body{margin:0;}"
 *   sheet.deleteRule(0)
 *   sheet.toString()
 *   -> "body{margin:0;}"
 *
 * @param {number} index within the style sheet's rule list of the rule to remove.
 * @see http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSStyleSheet-deleteRule
 */
CSSOM.CSSStyleSheet.prototype.deleteRule = function(index) {
...
```

#### <a name="apidoc.element.cssom.CSSStyleSheet.prototype.insertRule"></a>[function <span class="apidocSignatureSpan">cssom.CSSStyleSheet.prototype.</span>insertRule (rule, index)](#apidoc.element.cssom.CSSStyleSheet.prototype.insertRule)
- description and source-code
```javascript
insertRule = function (rule, index) {
	if (index < 0 || index > this.cssRules.length) {
		throw new RangeError("INDEX_SIZE_ERR");
	}
	var cssRule = CSSOM.parse(rule).cssRules[0];
	cssRule.parentStyleSheet = this;
	this.cssRules.splice(index, 0, cssRule);
	return index;
}
```
- example usage
```shell
...

/**
* Used to insert a new rule into the style sheet. The new rule now becomes part of the cascade.
*
*   sheet = new Sheet("body {margin: 0}")
*   sheet.toString()
*   -> "body{margin:0;}"
*   sheet.insertRule("img {border: none}", 0)
*   -> 0
*   sheet.toString()
*   -> "img{border:none;}body{margin:0;}"
*
* @param {string} rule
* @param {number} index
* @see http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSStyleSheet-insertRule
...
```

#### <a name="apidoc.element.cssom.CSSStyleSheet.prototype.toString"></a>[function <span class="apidocSignatureSpan">cssom.CSSStyleSheet.prototype.</span>toString ()](#apidoc.element.cssom.CSSStyleSheet.prototype.toString)
- description and source-code
```javascript
toString = function () {
	var result = "";
	var rules = this.cssRules;
	for (var i=0; i<rules.length; i++) {
		result += rules[i].cssText + "\n";
	}
	return result;
}
```
- example usage
```shell
...
CSSOM.CSSStyleSheet.prototype.constructor = CSSOM.CSSStyleSheet;


/**
* Used to insert a new rule into the style sheet. The new rule now becomes part of the cascade.
*
*   sheet = new Sheet("body {margin: 0}")
*   sheet.toString()
*   -> "body{margin:0;}"
*   sheet.insertRule("img {border: none}", 0)
*   -> 0
*   sheet.toString()
*   -> "img{border:none;}body{margin:0;}"
*
* @param {string} rule
...
```



# <a name="apidoc.module.cssom.CSSValue"></a>[module cssom.CSSValue](#apidoc.module.cssom.CSSValue)

#### <a name="apidoc.element.cssom.CSSValue.CSSValue"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSValue ()](#apidoc.element.cssom.CSSValue.CSSValue)
- description and source-code
```javascript
function CSSValue() {
}
```
- example usage
```shell
...
*
*/
CSSOM.CSSValueExpression = function CSSValueExpression(token, idx) {
	this._token = token;
	this._idx = idx;
};

CSSOM.CSSValueExpression.prototype = new CSSOM.CSSValue();
CSSOM.CSSValueExpression.prototype.constructor = CSSOM.CSSValueExpression;

/**
* parse css expression() value
*
* @return {Object}
*         - error:
...
```



# <a name="apidoc.module.cssom.CSSValueExpression"></a>[module cssom.CSSValueExpression](#apidoc.module.cssom.CSSValueExpression)

#### <a name="apidoc.element.cssom.CSSValueExpression.CSSValueExpression"></a>[function <span class="apidocSignatureSpan">cssom.</span>CSSValueExpression (token, idx)](#apidoc.element.cssom.CSSValueExpression.CSSValueExpression)
- description and source-code
```javascript
function CSSValueExpression(token, idx) {
	this._token = token;
	this._idx = idx;
}
```
- example usage
```shell
...
			}
			break;

		case "(":
			if (state === 'value') {
				// ie css expression mode
				if (buffer.trim() === 'expression') {
					var info = (new CSSOM.CSSValueExpression(token, i)).parse();

					if (info.error) {
						parseError(info.error);
					} else {
						buffer += info.expression;
						i = info.idx;
					}
...
```



# <a name="apidoc.module.cssom.MatcherList"></a>[module cssom.MatcherList](#apidoc.module.cssom.MatcherList)

#### <a name="apidoc.element.cssom.MatcherList.MatcherList"></a>[function <span class="apidocSignatureSpan">cssom.</span>MatcherList ()](#apidoc.element.cssom.MatcherList.MatcherList)
- description and source-code
```javascript
function MatcherList(){
    this.length = 0;
}
```
- example usage
```shell
...

/**
 * @constructor
 * @see https://developer.mozilla.org/en/CSS/@-moz-document
 */
CSSOM.CSSDocumentRule = function CSSDocumentRule() {
    CSSOM.CSSRule.call(this);
    this.matcher = new CSSOM.MatcherList();
    this.cssRules = [];
};

CSSOM.CSSDocumentRule.prototype = new CSSOM.CSSRule();
CSSOM.CSSDocumentRule.prototype.constructor = CSSOM.CSSDocumentRule;
CSSOM.CSSDocumentRule.prototype.type = 10;
//FIXME
...
```



# <a name="apidoc.module.cssom.MediaList"></a>[module cssom.MediaList](#apidoc.module.cssom.MediaList)

#### <a name="apidoc.element.cssom.MediaList.MediaList"></a>[function <span class="apidocSignatureSpan">cssom.</span>MediaList ()](#apidoc.element.cssom.MediaList.MediaList)
- description and source-code
```javascript
function MediaList(){
	this.length = 0;
}
```
- example usage
```shell
...
 * @constructor
 * @see http://dev.w3.org/csswg/cssom/#cssimportrule
 * @see http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSImportRule
 */
CSSOM.CSSImportRule = function CSSImportRule() {
	CSSOM.CSSRule.call(this);
	this.href = "";
	this.media = new CSSOM.MediaList();
	this.styleSheet = new CSSOM.CSSStyleSheet();
};

CSSOM.CSSImportRule.prototype = new CSSOM.CSSRule();
CSSOM.CSSImportRule.prototype.constructor = CSSOM.CSSImportRule;
CSSOM.CSSImportRule.prototype.type = 3;
...
```



# <a name="apidoc.module.cssom.MediaList.prototype"></a>[module cssom.MediaList.prototype](#apidoc.module.cssom.MediaList.prototype)

#### <a name="apidoc.element.cssom.MediaList.prototype.appendMedium"></a>[function <span class="apidocSignatureSpan">cssom.MediaList.prototype.</span>appendMedium (medium)](#apidoc.element.cssom.MediaList.prototype.appendMedium)
- description and source-code
```javascript
appendMedium = function (medium) {
		if (Array.prototype.indexOf.call(this, medium) === -1) {
			this[this.length] = medium;
			this.length++;
		}
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cssom.MediaList.prototype.constructor"></a>[function <span class="apidocSignatureSpan">cssom.MediaList.prototype.</span>constructor ()](#apidoc.element.cssom.MediaList.prototype.constructor)
- description and source-code
```javascript
function MediaList(){
	this.length = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cssom.MediaList.prototype.deleteMedium"></a>[function <span class="apidocSignatureSpan">cssom.MediaList.prototype.</span>deleteMedium (medium)](#apidoc.element.cssom.MediaList.prototype.deleteMedium)
- description and source-code
```javascript
deleteMedium = function (medium) {
		var index = Array.prototype.indexOf.call(this, medium);
		if (index !== -1) {
			Array.prototype.splice.call(this, index, 1);
		}
	}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cssom.StyleSheet"></a>[module cssom.StyleSheet](#apidoc.module.cssom.StyleSheet)

#### <a name="apidoc.element.cssom.StyleSheet.StyleSheet"></a>[function <span class="apidocSignatureSpan">cssom.</span>StyleSheet ()](#apidoc.element.cssom.StyleSheet.StyleSheet)
- description and source-code
```javascript
function StyleSheet() {
	this.parentStyleSheet = null;
}
```
- example usage
```shell
...
*/
CSSOM.CSSStyleSheet = function CSSStyleSheet() {
	CSSOM.StyleSheet.call(this);
	this.cssRules = [];
};


CSSOM.CSSStyleSheet.prototype = new CSSOM.StyleSheet();
CSSOM.CSSStyleSheet.prototype.constructor = CSSOM.CSSStyleSheet;


/**
* Used to insert a new rule into the style sheet. The new rule now becomes part of the cascade.
*
*   sheet = new Sheet("body {margin: 0}")
...
```



# <a name="apidoc.module.cssom.clone"></a>[module cssom.clone](#apidoc.module.cssom.clone)

#### <a name="apidoc.element.cssom.clone.clone"></a>[function <span class="apidocSignatureSpan">cssom.</span>clone (stylesheet)](#apidoc.element.cssom.clone.clone)
- description and source-code
```javascript
function clone(stylesheet) {

	var cloned = new CSSOM.CSSStyleSheet();

	var rules = stylesheet.cssRules;
	if (!rules) {
		return cloned;
	}

	var RULE_TYPES = {
		1: CSSOM.CSSStyleRule,
		4: CSSOM.CSSMediaRule,
		//3: CSSOM.CSSImportRule,
		//5: CSSOM.CSSFontFaceRule,
		//6: CSSOM.CSSPageRule,
		8: CSSOM.CSSKeyframesRule,
		9: CSSOM.CSSKeyframeRule
	};

	for (var i=0, rulesLength=rules.length; i < rulesLength; i++) {
		var rule = rules[i];
		var ruleClone = cloned.cssRules[i] = new RULE_TYPES[rule.type]();

		var style = rule.style;
		if (style) {
			var styleClone = ruleClone.style = new CSSOM.CSSStyleDeclaration();
			for (var j=0, styleLength=style.length; j < styleLength; j++) {
				var name = styleClone[j] = style[j];
				styleClone[name] = style[name];
				styleClone._importants[name] = style.getPropertyPriority(name);
			}
			styleClone.length = style.length;
		}

		if (rule.hasOwnProperty('keyText')) {
			ruleClone.keyText = rule.keyText;
		}

		if (rule.hasOwnProperty('selectorText')) {
			ruleClone.selectorText = rule.selectorText;
		}

		if (rule.hasOwnProperty('mediaText')) {
			ruleClone.mediaText = rule.mediaText;
		}

		if (rule.hasOwnProperty('cssRules')) {
			ruleClone.cssRules = clone(rule).cssRules;
		}
	}

	return cloned;

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cssom.parse"></a>[module cssom.parse](#apidoc.module.cssom.parse)

#### <a name="apidoc.element.cssom.parse.parse"></a>[function <span class="apidocSignatureSpan">cssom.</span>parse (token)](#apidoc.element.cssom.parse.parse)
- description and source-code
```javascript
function parse(token) {

	var i = 0;

	<span class="apidocCodeCommentSpan">/**
		"before-selector" or
		"selector" or
		"atRule" or
		"atBlock" or
		"before-name" or
		"name" or
		"before-value" or
		"value"
	*/
</span>	var state = "before-selector";

	var index;
	var buffer = "";
	var valueParenthesisDepth = 0;

	var SIGNIFICANT_WHITESPACE = {
		"selector": true,
		"value": true,
		"value-parenthesis": true,
		"atRule": true,
		"importRule-begin": true,
		"importRule": true,
		"atBlock": true,
		'documentRule-begin': true
	};

	var styleSheet = new CSSOM.CSSStyleSheet();

	// @type CSSStyleSheet|CSSMediaRule|CSSFontFaceRule|CSSKeyframesRule|CSSDocumentRule
	var currentScope = styleSheet;

	// @type CSSMediaRule|CSSKeyframesRule|CSSDocumentRule
	var parentRule;

	var name, priority="", styleRule, mediaRule, importRule, fontFaceRule, keyframesRule, documentRule, hostRule;

	var atKeyframesRegExp = /@(-(?:\w+-)+)?keyframes/g;

	var parseError = function(message) {
		var lines = token.substring(0, i).split('\n');
		var lineCount = lines.length;
		var charCount = lines.pop().length + 1;
		var error = new Error(message + ' (line ' + lineCount + ', char ' + charCount + ')');
		error.line = lineCount;
		/* jshint sub : true */
		error['char'] = charCount;
		error.styleSheet = styleSheet;
		throw error;
	};

	for (var character; (character = token.charAt(i)); i++) {

		switch (character) {

		case " ":
		case "\t":
		case "\r":
		case "\n":
		case "\f":
			if (SIGNIFICANT_WHITESPACE[state]) {
				buffer += character;
			}
			break;

		// String
		case '"':
			index = i + 1;
			do {
				index = token.indexOf('"', index) + 1;
				if (!index) {
					parseError('Unmatched "');
				}
			} while (token[index - 2] === '\\');
			buffer += token.slice(i, index);
			i = index - 1;
			switch (state) {
				case 'before-value':
					state = 'value';
					break;
				case 'importRule-begin':
					state = 'importRule';
					break;
			}
			break;

		case "'":
			index = i + 1;
			do {
				index = token.indexOf("'", index) + 1;
				if (!index) {
					parseError("Unmatched '");
				}
			} while (token[index - 2] === '\\');
			buffer += token.slice(i, index);
			i = index - 1;
			switch (state) {
				case 'before-value':
					state = 'value';
					break;
				case 'importRule-begin':
					state = 'importRule';
					break;
			}
			break;

		// Comment
		case "/":
			if (token.charAt(i + 1) === "*") {
				i += 2;
				index = token.indexOf("*/", i);
				if (index === -1) {
					parseError("Missing */");
				} else {
					i = index + 1;
				}
			} else {
				buffer += character;
			}
			if (state === "importRule-begin") {
				buffer += " ";
				state = "importRule";
			}
			break;

		// At-rule
		case "@":
			if (token.indexOf("@-moz-document", i) === i) {
				state = "documentRule-begin";
				documentRule = new CSSOM.CSSDocumentRule();
				documentRule.__starts = i;
				i += "-moz-document".length;
				buffer = "";
				break;
			} else if (token.indexOf("@media", i) === i) {
				state = "atBlock";
				mediaRule = new CSSOM.CSSMediaRule();
				mediaRule.__starts = i;
				i += "media".length;
				buffer = "";
				break;
			} else if (token.indexOf("@host", i) === i) {
				state = "hostRule-begin";
				i += "host".length;
				hostRule = new CSSOM.CSSHostRule();
				hostRule.__starts = i;
				buffer = "";
				break;
			} else if (token.indexOf("@import", i) === i) {
				state = "importRule-begin";
				i += "import".length;
				buffer += "@import";
				break;
			} else if (token.indexOf("@font-face", i) === i) {
				state = "fontFaceRule-begin";
				i += "font-face".length;
				fontFaceRule = new CSSOM.CSSFontFaceRule();
				fontFaceRule.__starts = i;
				buffer = "";
				break;
			} else {
				atKeyframesRegExp.lastIndex = i;
				var matchKeyframes = atKeyframesRegExp.exec(token);
				if (matchKeyframes && matchKeyframes.index === i) {
					state = "keyframesRule-begin";
					keyframesRule = new CSSOM.CSSKeyframesRule();
					keyframesRule.__starts = i;
					keyframesRule._vendorPrefix = matchKeyframes[1]; // Will come out as undefined if no prefix was found
					i += matchKeyframes[0].length - 1; ...
```
- example usage
```shell
...



# CSSOM

CSSOM.js is a CSS parser written in pure JavaScript. It also a partial implementation of [CSS Object Model](http://dev.w3.org/csswg
/cssom/).

CSSOM.parse("body {color: black}")
-> {
  cssRules: [
    {
      selectorText: "body",
      style: {
        0: "color",
        color: "black",
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
