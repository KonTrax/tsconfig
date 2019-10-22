# @ktb/tsconfig

Custom TypeScript related config defaults


## Install

### NPM
```
$ npm install --save-dev @ktb/tsconfig
```
or
```
$ npm install --save-dev kontrax/tsconfig
```

### Yarn
```
$ yarn add --dev @ktb/tsconfig
```
or
```
$ yarn add --dev kontrax/tsconfig
```


## Usage

`tsconfig.json`

```json
{
	"extends": "@ktb/tsconfig",
	"compilerOptions": {
		"outDir": "dist",
		"rootDir": "src",
		"target": "esnext",
		"lib": [
			"esnext"
		]
	}
}
```
