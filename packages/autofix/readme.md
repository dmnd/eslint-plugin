<p align="center">
  <a href="https://ci.appveyor.com/api/projects/status/v562l6v4h098dvtf?svg=true">
    <img src="https://ci.appveyor.com/api/projects/status/v562l6v4h098dvtf?svg=true"
         alt="build status">
  </a>
  <a href="https://david-dm.org/tplss/node">
    <img src="https://david-dm.org/aladdin-add/eslint-plugin-autofix/status.svg"
         alt="dependency status">
  </a>
</p>

# eslint-plugin-autofix

## Install & usage

```bash
$ npm i eslint-plugin-autofix -D
```

add prefix "autofix" to the rulename in eslintrc:
```js
{
  "plugins": ["autofix"],
  "rules": {
    "autofix/no-debugger": "error"
  }
}
```

## Supported rules

✔️ indicates that a rule is recommended for all users.
🛠 indicates that a rule is fixable.

<!-- __BEGIN AUTOGENERATED TABLE__ -->
Name | ✔️ | 🛠 | Description
----- | ----- | ----- | -----
[array-bracket-newline](https://eslint.org/docs/rules/array-bracket-newline) |  | 🛠 | enforce linebreaks after opening and before closing array brackets
[array-bracket-spacing](https://eslint.org/docs/rules/array-bracket-spacing) |  | 🛠 | enforce consistent spacing inside array brackets
[array-element-newline](https://eslint.org/docs/rules/array-element-newline) |  | 🛠 | enforce line breaks after each array element
[arrow-body-style](https://eslint.org/docs/rules/arrow-body-style) |  | 🛠 | require braces around arrow function bodies
[arrow-parens](https://eslint.org/docs/rules/arrow-parens) |  | 🛠 | require parentheses around arrow function arguments
[arrow-spacing](https://eslint.org/docs/rules/arrow-spacing) |  | 🛠 | enforce consistent spacing before and after the arrow in arrow functions
[block-spacing](https://eslint.org/docs/rules/block-spacing) |  | 🛠 | disallow or enforce spaces inside of blocks after opening block and before closing block
[brace-style](https://eslint.org/docs/rules/brace-style) |  | 🛠 | enforce consistent brace style for blocks
[capitalized-comments](https://eslint.org/docs/rules/capitalized-comments) |  | 🛠 | enforce or disallow capitalization of the first letter of a comment
[comma-dangle](https://eslint.org/docs/rules/comma-dangle) |  | 🛠 | require or disallow trailing commas
[comma-spacing](https://eslint.org/docs/rules/comma-spacing) |  | 🛠 | enforce consistent spacing before and after commas
[comma-style](https://eslint.org/docs/rules/comma-style) |  | 🛠 | enforce consistent comma style
[computed-property-spacing](https://eslint.org/docs/rules/computed-property-spacing) |  | 🛠 | enforce consistent spacing inside computed property brackets
[curly](https://eslint.org/docs/rules/curly) |  | 🛠 | enforce consistent brace style for all control statements
[dot-location](https://eslint.org/docs/rules/dot-location) |  | 🛠 | enforce consistent newlines before and after dots
[dot-notation](https://eslint.org/docs/rules/dot-notation) |  | 🛠 | enforce dot notation whenever possible
[eol-last](https://eslint.org/docs/rules/eol-last) |  | 🛠 | require or disallow newline at the end of files
[eqeqeq](https://eslint.org/docs/rules/eqeqeq) |  | 🛠 | require the use of `===` and `!==`
[func-call-spacing](https://eslint.org/docs/rules/func-call-spacing) |  | 🛠 | require or disallow spacing between function identifiers and their invocations
[function-paren-newline](https://eslint.org/docs/rules/function-paren-newline) |  | 🛠 | enforce consistent line breaks inside function parentheses
[generator-star-spacing](https://eslint.org/docs/rules/generator-star-spacing) |  | 🛠 | enforce consistent spacing around `*` operators in generator functions
[implicit-arrow-linebreak](https://eslint.org/docs/rules/implicit-arrow-linebreak) |  | 🛠 | enforce the location of arrow function bodies
[indent](https://eslint.org/docs/rules/indent) |  | 🛠 | enforce consistent indentation
[indent-legacy](https://eslint.org/docs/rules/indent-legacy) |  | 🛠 | enforce consistent indentation
[jsx-quotes](https://eslint.org/docs/rules/jsx-quotes) |  | 🛠 | enforce the consistent use of either double or single quotes in JSX attributes
[key-spacing](https://eslint.org/docs/rules/key-spacing) |  | 🛠 | enforce consistent spacing between keys and values in object literal properties
[keyword-spacing](https://eslint.org/docs/rules/keyword-spacing) |  | 🛠 | enforce consistent spacing before and after keywords
[linebreak-style](https://eslint.org/docs/rules/linebreak-style) |  | 🛠 | enforce consistent linebreak style
[lines-around-comment](https://eslint.org/docs/rules/lines-around-comment) |  | 🛠 | require empty lines around comments
[lines-around-directive](https://eslint.org/docs/rules/lines-around-directive) |  | 🛠 | require or disallow newlines around directives
[lines-between-class-members](https://eslint.org/docs/rules/lines-between-class-members) |  | 🛠 | require or disallow an empty line between class members
[multiline-comment-style](https://eslint.org/docs/rules/multiline-comment-style) |  | 🛠 | enforce a particular style for multiline comments
[new-parens](https://eslint.org/docs/rules/new-parens) |  | 🛠 | require parentheses when invoking a constructor with no arguments
[newline-after-var](https://eslint.org/docs/rules/newline-after-var) |  | 🛠 | require or disallow an empty line after variable declarations
[newline-before-return](https://eslint.org/docs/rules/newline-before-return) |  | 🛠 | require an empty line before `return` statements
[newline-per-chained-call](https://eslint.org/docs/rules/newline-per-chained-call) |  | 🛠 | require a newline after each call in a method chain
[no-alert](https://eslint.org/docs/rules/no-alert) |  | 🛠 | disallow the use of `alert`, `confirm`, and `prompt`
[no-caller](https://eslint.org/docs/rules/no-caller) |  | 🛠 | disallow the use of `arguments.caller` or `arguments.callee`
[no-confusing-arrow](https://eslint.org/docs/rules/no-confusing-arrow) |  | 🛠 | disallow arrow functions where they could be confused with comparisons
[no-console](https://eslint.org/docs/rules/no-console) | ✔️ | 🛠 | disallow the use of `console`
[no-debugger](https://eslint.org/docs/rules/no-debugger) | ✔️ | 🛠 | disallow the use of `debugger`
[no-else-return](https://eslint.org/docs/rules/no-else-return) |  | 🛠 | disallow `else` blocks after `return` statements in `if` statements
[no-eq-null](https://eslint.org/docs/rules/no-eq-null) |  | 🛠 | disallow `null` comparisons without type-checking operators
[no-extra-bind](https://eslint.org/docs/rules/no-extra-bind) |  | 🛠 | disallow unnecessary calls to `.bind()`
[no-extra-boolean-cast](https://eslint.org/docs/rules/no-extra-boolean-cast) |  | 🛠 | disallow unnecessary boolean casts
[no-extra-label](https://eslint.org/docs/rules/no-extra-label) |  | 🛠 | disallow unnecessary labels
[no-extra-parens](https://eslint.org/docs/rules/no-extra-parens) |  | 🛠 | disallow unnecessary parentheses
[no-extra-semi](https://eslint.org/docs/rules/no-extra-semi) |  | 🛠 | disallow unnecessary semicolons
[no-floating-decimal](https://eslint.org/docs/rules/no-floating-decimal) |  | 🛠 | disallow leading or trailing decimal points in numeric literals
[no-implicit-coercion](https://eslint.org/docs/rules/no-implicit-coercion) |  | 🛠 | disallow shorthand type conversions
[no-lonely-if](https://eslint.org/docs/rules/no-lonely-if) |  | 🛠 | disallow `if` statements as the only statement in `else` blocks
[no-multi-spaces](https://eslint.org/docs/rules/no-multi-spaces) |  | 🛠 | disallow multiple spaces
[no-multiple-empty-lines](https://eslint.org/docs/rules/no-multiple-empty-lines) |  | 🛠 | disallow multiple empty lines
[no-new-symbol](https://eslint.org/docs/rules/no-new-symbol) |  | 🛠 | disallow `new` operators with the `Symbol` object
[no-plusplus](https://eslint.org/docs/rules/no-plusplus) | ✔️ | 🛠 | disallow the unary operators `++` and `--`
[no-proto](https://eslint.org/docs/rules/no-proto) |  | 🛠 | disallow the use of the `__proto__` property
[no-prototype-builtins](https://eslint.org/docs/rules/no-prototype-builtins) |  | 🛠 | disallow calling some `Object.prototype` methods directly on objects
[no-regex-spaces](https://eslint.org/docs/rules/no-regex-spaces) |  | 🛠 | disallow multiple spaces in regular expressions
[no-spaced-func](https://eslint.org/docs/rules/no-spaced-func) |  | 🛠 | disallow spacing between function identifiers and their applications (deprecated)
[no-throw-literal](https://eslint.org/docs/rules/no-throw-literal) |  | 🛠 | disallow throwing literals as exceptions
[no-trailing-spaces](https://eslint.org/docs/rules/no-trailing-spaces) |  | 🛠 | disallow trailing whitespace at the end of lines
[no-undef-init](https://eslint.org/docs/rules/no-undef-init) |  | 🛠 | disallow initializing variables to `undefined`
[no-unneeded-ternary](https://eslint.org/docs/rules/no-unneeded-ternary) |  | 🛠 | disallow ternary operators when simpler alternatives exist
[no-unsafe-negation](https://eslint.org/docs/rules/no-unsafe-negation) |  | 🛠 | disallow negating the left operand of relational operators
[no-unused-labels](https://eslint.org/docs/rules/no-unused-labels) |  | 🛠 | disallow unused labels
[no-unused-vars](https://eslint.org/docs/rules/no-unused-vars) |  | 🛠 | disallow unused variables
[no-useless-catch](https://eslint.org/docs/rules/no-useless-catch) |  | 🛠 | disallow unnecessary `catch` clauses
[no-useless-computed-key](https://eslint.org/docs/rules/no-useless-computed-key) |  | 🛠 | disallow unnecessary computed property keys in object literals
[no-useless-concat](https://eslint.org/docs/rules/no-useless-concat) |  | 🛠 | disallow unnecessary concatenation of literals or template literals
[no-useless-rename](https://eslint.org/docs/rules/no-useless-rename) |  | 🛠 | disallow renaming import, export, and destructured assignments to the same name
[no-useless-return](https://eslint.org/docs/rules/no-useless-return) |  | 🛠 | disallow redundant return statements
[no-var](https://eslint.org/docs/rules/no-var) |  | 🛠 | require `let` or `const` instead of `var`
[no-whitespace-before-property](https://eslint.org/docs/rules/no-whitespace-before-property) |  | 🛠 | disallow whitespace before properties
[nonblock-statement-body-position](https://eslint.org/docs/rules/nonblock-statement-body-position) |  | 🛠 | enforce the location of single-line statements
[object-curly-newline](https://eslint.org/docs/rules/object-curly-newline) |  | 🛠 | enforce consistent line breaks inside braces
[object-curly-spacing](https://eslint.org/docs/rules/object-curly-spacing) |  | 🛠 | enforce consistent spacing inside braces
[object-property-newline](https://eslint.org/docs/rules/object-property-newline) |  | 🛠 | enforce placing object properties on separate lines
[object-shorthand](https://eslint.org/docs/rules/object-shorthand) |  | 🛠 | require or disallow method and property shorthand syntax for object literals
[one-var](https://eslint.org/docs/rules/one-var) |  | 🛠 | enforce variables to be declared either together or separately in functions
[one-var-declaration-per-line](https://eslint.org/docs/rules/one-var-declaration-per-line) |  | 🛠 | require or disallow newlines around variable declarations
[operator-assignment](https://eslint.org/docs/rules/operator-assignment) |  | 🛠 | require or disallow assignment operator shorthand where possible
[operator-linebreak](https://eslint.org/docs/rules/operator-linebreak) |  | 🛠 | enforce consistent linebreak style for operators
[padded-blocks](https://eslint.org/docs/rules/padded-blocks) |  | 🛠 | require or disallow padding within blocks
[padding-line-between-statements](https://eslint.org/docs/rules/padding-line-between-statements) |  | 🛠 | require or disallow padding lines between statements
[prefer-arrow-callback](https://eslint.org/docs/rules/prefer-arrow-callback) |  | 🛠 | require using arrow functions for callbacks
[prefer-const](https://eslint.org/docs/rules/prefer-const) |  | 🛠 | require `const` declarations for variables that are never reassigned after declared
[prefer-destructuring](https://eslint.org/docs/rules/prefer-destructuring) |  | 🛠 | require destructuring from arrays and/or objects
[prefer-numeric-literals](https://eslint.org/docs/rules/prefer-numeric-literals) |  | 🛠 | disallow `parseInt()` and `Number.parseInt()` in favor of binary, octal, and hexadecimal literals
[prefer-object-spread](https://eslint.org/docs/rules/prefer-object-spread) |  | 🛠 | disallow using Object.assign with an object literal as the first argument and prefer the use of object spread instead.
[prefer-spread](https://eslint.org/docs/rules/prefer-spread) |  | 🛠 | require spread operators instead of `.apply()`
[prefer-template](https://eslint.org/docs/rules/prefer-template) |  | 🛠 | require template literals instead of string concatenation
[quote-props](https://eslint.org/docs/rules/quote-props) |  | 🛠 | require quotes around object literal property names
[quotes](https://eslint.org/docs/rules/quotes) |  | 🛠 | enforce the consistent use of either backticks, double, or single quotes
[radix](https://eslint.org/docs/rules/radix) |  | 🛠 | enforce the consistent use of the radix argument when using `parseInt()`
[rest-spread-spacing](https://eslint.org/docs/rules/rest-spread-spacing) |  | 🛠 | enforce spacing between rest and spread operators and their expressions
[semi](https://eslint.org/docs/rules/semi) |  | 🛠 | require or disallow semicolons instead of ASI
[semi-spacing](https://eslint.org/docs/rules/semi-spacing) |  | 🛠 | enforce consistent spacing before and after semicolons
[semi-style](https://eslint.org/docs/rules/semi-style) |  | 🛠 | enforce location of semicolons
[sort-imports](https://eslint.org/docs/rules/sort-imports) |  | 🛠 | enforce sorted import declarations within modules
[sort-vars](https://eslint.org/docs/rules/sort-vars) |  | 🛠 | require variables within the same declaration block to be sorted
[space-before-blocks](https://eslint.org/docs/rules/space-before-blocks) |  | 🛠 | enforce consistent spacing before blocks
[space-before-function-paren](https://eslint.org/docs/rules/space-before-function-paren) |  | 🛠 | enforce consistent spacing before `function` definition opening parenthesis
[space-in-parens](https://eslint.org/docs/rules/space-in-parens) |  | 🛠 | enforce consistent spacing inside parentheses
[space-infix-ops](https://eslint.org/docs/rules/space-infix-ops) |  | 🛠 | require spacing around infix operators
[space-unary-ops](https://eslint.org/docs/rules/space-unary-ops) |  | 🛠 | enforce consistent spacing before or after unary operators
[spaced-comment](https://eslint.org/docs/rules/spaced-comment) |  | 🛠 | enforce consistent spacing after the `//` or `/*` in a comment
[strict](https://eslint.org/docs/rules/strict) |  | 🛠 | require or disallow strict mode directives
[switch-colon-spacing](https://eslint.org/docs/rules/switch-colon-spacing) |  | 🛠 | enforce spacing around colons of switch statements
[template-curly-spacing](https://eslint.org/docs/rules/template-curly-spacing) |  | 🛠 | require or disallow spacing around embedded expressions of template strings
[template-tag-spacing](https://eslint.org/docs/rules/template-tag-spacing) |  | 🛠 | require or disallow spacing between template tags and their literals
[unicode-bom](https://eslint.org/docs/rules/unicode-bom) |  | 🛠 | require or disallow Unicode byte order mark (BOM)
[valid-jsdoc](https://eslint.org/docs/rules/valid-jsdoc) |  | 🛠 | enforce valid JSDoc comments
[valid-typeof](https://eslint.org/docs/rules/valid-typeof) |  | 🛠 | enforce comparing `typeof` expressions against valid strings
[wrap-iife](https://eslint.org/docs/rules/wrap-iife) |  | 🛠 | require parentheses around immediate `function` invocations
[wrap-regex](https://eslint.org/docs/rules/wrap-regex) |  | 🛠 | require parenthesis around regex literals
[yield-star-spacing](https://eslint.org/docs/rules/yield-star-spacing) |  | 🛠 | require or disallow spacing around the `*` in `yield*` expressions
[yoda](https://eslint.org/docs/rules/yoda) |  | 🛠 | require or disallow "Yoda" conditions
<!-- __END AUTOGENERATED TABLE__ -->

## Contributing

+ to add a new rule:
```bash
npm run new ${ruleName}
```

## Acknowledgement
+ [ESLint](https://eslint.org)
+ [eslint-rule-composer](https://github.com/not-an-aardvark/eslint-rule-composer)