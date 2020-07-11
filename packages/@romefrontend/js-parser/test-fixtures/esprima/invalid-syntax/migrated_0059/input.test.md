# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0059`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 0
			index: 6
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			location: Object {
				filename: "input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 4
					index: 4
					line: 1
				}
				start: Object {
					column: 4
					index: 4
					line: 1
				}
			}
			description: Object {
				category: "parse/js"
				message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: "Unclosed object"}
				advice: Array [
					log {
						category: "info"
						text: "We expected to find the closing character <emphasis>}</emphasis> here"
					}
					frame {
						location: Object {
							filename: "input.js"
							end: Object {
								column: 0
								index: 6
								line: 2
							}
							start: Object {
								column: 0
								index: 6
								line: 2
							}
						}
					}
				]
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 5
					index: 5
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSBinaryExpression {
				operator: "+"
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 5
						index: 5
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				right: JSObjectExpression {
					properties: Array []
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 5
							index: 5
							line: 1
						}
						start: Object {
							column: 4
							index: 4
							line: 1
						}
					}
				}
				left: JSNumericLiteral {
					value: 1
					format: undefined
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 1
							index: 1
							line: 1
						}
						start: Object {
							column: 0
							index: 0
							line: 1
						}
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```

 input.js:1:4 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unclosed object

  ℹ We expected to find the closing character } here

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```