# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2019 > optional-catch-binding > no-binding`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2019/optional-catch-binding/no-binding/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2019/optional-catch-binding/no-binding/input.js"
		end: Object {
			column: 0
			line: 7
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSTryStatement {
			finalizer: undefined
			loc: Object {
				filename: "es2019/optional-catch-binding/no-binding/input.js"
				end: Object {
					column: 1
					line: 6
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			block: JSBlockStatement {
				body: Array []
				directives: Array []
				loc: Object {
					filename: "es2019/optional-catch-binding/no-binding/input.js"
					end: Object {
						column: 1
						line: 3
					}
					start: Object {
						column: 4
						line: 1
					}
				}
			}
			handler: JSCatchClause {
				param: undefined
				loc: Object {
					filename: "es2019/optional-catch-binding/no-binding/input.js"
					end: Object {
						column: 1
						line: 6
					}
					start: Object {
						column: 0
						line: 4
					}
				}
				body: JSBlockStatement {
					body: Array []
					directives: Array []
					loc: Object {
						filename: "es2019/optional-catch-binding/no-binding/input.js"
						end: Object {
							column: 1
							line: 6
						}
						start: Object {
							column: 6
							line: 4
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
✔ No known problems!

```
