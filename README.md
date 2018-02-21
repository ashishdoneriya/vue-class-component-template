# Vue Class Component Template

> A Vue.js project
Template for https://github.com/vuejs/vue-class-component with linting and formatting enabled

NOTE : You have to install the following extensions in vscode for formatting and linting
1. [Eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
2. [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
3. [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

For more information :
http://csetutorials.com/format-vue-files-visual-studio-code.html
http://csetutorials.com/add-linting-vuejs-project.html

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

Add the below property in vscode
```
"eslint.validate": [
		"javascript",
		{
			"language": "vue",
			"autoFix": true
		}
	],
"vetur.format.defaultFormatter": {
		"html": "prettier",
		"css": "prettier",
		"postcss": "prettier",
		"scss": "prettier",
		"less": "prettier",
		"js": "prettier",
		"ts": "prettier",
		"stylus": "stylus-supremacy"
	}
```


