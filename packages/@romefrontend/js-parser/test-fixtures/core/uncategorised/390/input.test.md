# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 390`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
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
			column: 20
			index: 20
			line: 1
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
			description: Object {
				advice: Array []
				category: "parse/js"
				message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: "Unknown start to an call expression argument"}
			}
			location: Object {
				filename: "input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 10
					index: 10
					line: 1
				}
				start: Object {
					column: 10
					index: 10
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 13
					index: 13
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSObjectExpression {
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 13
						index: 13
						line: 1
					}
					start: Object {
						column: 1
						index: 1
						line: 1
					}
				}
				properties: Array [
					JSObjectProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "set"
								loc: Object {
									filename: "input.js"
									identifierName: "set"
									end: Object {
										column: 6
										index: 6
										line: 1
									}
									start: Object {
										column: 3
										index: 3
										line: 1
									}
								}
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 6
									index: 6
									line: 1
								}
								start: Object {
									column: 3
									index: 3
									line: 1
								}
							}
						}
						value: JSCallExpression {
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 13
									index: 13
									line: 1
								}
								start: Object {
									column: 8
									index: 8
									line: 1
								}
							}
							callee: JSReferenceIdentifier {
								name: "s"
								loc: Object {
									filename: "input.js"
									identifierName: "s"
									end: Object {
										column: 9
										index: 9
										line: 1
									}
									start: Object {
										column: 8
										index: 8
										line: 1
									}
								}
							}
							arguments: Array [
								JSReferenceIdentifier {
									name: "INVALID_PLACEHOLDER"
									loc: Object {
										filename: "input.js"
										end: Object {
											column: 12
											index: 12
											line: 1
										}
										start: Object {
											column: 10
											index: 10
											line: 1
										}
									}
								}
							]
						}
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 13
								index: 13
								line: 1
							}
							start: Object {
								column: 3
								index: 3
								line: 1
							}
						}
					}
				]
			}
		}
		JSBlockStatement {
			body: Array []
			directives: Array []
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 17
					index: 17
					line: 1
				}
				start: Object {
					column: 14
					index: 14
					line: 1
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 19
					index: 19
					line: 1
				}
				start: Object {
					column: 18
					index: 18
					line: 1
				}
			}
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 19
						index: 19
						line: 1
					}
					start: Object {
						column: 18
						index: 18
						line: 1
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 20
					index: 20
					line: 1
				}
				start: Object {
					column: 19
					index: 19
					line: 1
				}
			}
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 20
						index: 20
						line: 1
					}
					start: Object {
						column: 19
						index: 19
						line: 1
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```

 input.js:1:10 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unknown start to an call expression argument

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```