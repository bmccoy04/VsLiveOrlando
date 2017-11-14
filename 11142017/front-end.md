# Front-end dev from a .net developer

* use node to run task
* npm to manage packages (nuget for javascript)
** npm is package manager of choice 
* Don't install npm packages globally
* Don't publish Node_Modules folder 
* mixin's are "built" less file
* build less w/ "npm install less --save-dev"
* tell npm to run less/lessc by configuring the scripts t
* Handlebars is a framework that allows for {{}} templating.
* "ts":"tsc ./scripts/app.ts" in npm 
* tsc needs tsconfig.json
* gulp is optional task runner. better options may be webpack or npm scripts
* webpack, start by creating entry points
  module.exports = {
	entry: {
	  scripts:"./scripts/app.ts",
	  styles:"./styles/site.less"
	},
	output: {
	  path: path.resolve("./dist"),
          filename: "[name].[hash].bundle.js"  //[name] is name from top [hash] generates a new hash
	}
	reslove:{
	  extensions: ['.ts','.js']
	}, modules {
	    rules: [
	   {
	     test:/\.ts$/, use: 'ts-loader' } // ts-loader is in npm that loads typescript for webpack
 	   }
	  ]
	},
	plugin {
	  // webpack.ProvidePlugin to include Handlebars into your application
	  // webpack.ProvidePlugin for html plug in to put a dist index.html w/ the bundled hash name 
	}	
  }
  // need includes for webpack and path
* really need to look into webpack loaders
* webpack --watch watches dev files.

@zerokoll
