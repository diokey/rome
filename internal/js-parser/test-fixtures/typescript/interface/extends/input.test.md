# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > interface > extends`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/interface/extends/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/interface/extends/input.ts"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		TSInterfaceDeclaration {
			id: JSBindingIdentifier {
				name: "I"
				loc: Object {
					filename: "typescript/interface/extends/input.ts"
					identifierName: "I"
					end: Object {
						column: 11
						line: 1
					}
					start: Object {
						column: 10
						line: 1
					}
				}
			}
			typeParameters: undefined
			loc: Object {
				filename: "typescript/interface/extends/input.ts"
				end: Object {
					column: 29
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			body: TSInterfaceBody {
				body: Array []
				loc: Object {
					filename: "typescript/interface/extends/input.ts"
					end: Object {
						column: 29
						line: 1
					}
					start: Object {
						column: 27
						line: 1
					}
				}
			}
			extends: Array [
				TSExpressionWithTypeArguments {
					loc: Object {
						filename: "typescript/interface/extends/input.ts"
						end: Object {
							column: 26
							line: 1
						}
						start: Object {
							column: 20
							line: 1
						}
					}
					expression: TSQualifiedName {
						loc: Object {
							filename: "typescript/interface/extends/input.ts"
							end: Object {
								column: 23
								line: 1
							}
							start: Object {
								column: 20
								line: 1
							}
						}
						left: JSReferenceIdentifier {
							name: "X"
							loc: Object {
								filename: "typescript/interface/extends/input.ts"
								identifierName: "X"
								end: Object {
									column: 21
									line: 1
								}
								start: Object {
									column: 20
									line: 1
								}
							}
						}
						right: JSIdentifier {
							name: "Y"
							loc: Object {
								filename: "typescript/interface/extends/input.ts"
								identifierName: "Y"
								end: Object {
									column: 23
									line: 1
								}
								start: Object {
									column: 22
									line: 1
								}
							}
						}
					}
					typeParameters: TSTypeParameterInstantiation {
						loc: Object {
							filename: "typescript/interface/extends/input.ts"
							end: Object {
								column: 26
								line: 1
							}
							start: Object {
								column: 23
								line: 1
							}
						}
						params: Array [
							TSTypeReference {
								typeParameters: undefined
								loc: Object {
									filename: "typescript/interface/extends/input.ts"
									end: Object {
										column: 25
										line: 1
									}
									start: Object {
										column: 24
										line: 1
									}
								}
								typeName: JSReferenceIdentifier {
									name: "Z"
									loc: Object {
										filename: "typescript/interface/extends/input.ts"
										identifierName: "Z"
										end: Object {
											column: 25
											line: 1
										}
										start: Object {
											column: 24
											line: 1
										}
									}
								}
							}
						]
					}
				}
			]
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
