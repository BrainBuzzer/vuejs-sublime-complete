# VueJS Code completion for sublime

This package is a complete set of snippets and vue syntax highlighting and is **under development** version number is 0.3.3 . This package is built by [Aditya Giri](https://github.com/BrainBuzzer) and is being used by [LivonAir](http://livonair.com).

## Installation

### Manually

To install this package, clone this repository in your machine and move to your packages folder. You can find packages folder by clicking on Preferences->Browse Packages.

### Package Control

Go ahead and search for __vuejs complete package.__ Just install it.

## Usage

### Syntax Highlighting

We are providing syntax highlighting as it is from a fork of vuejs/vuejs-syntax-highlight. You need not to configure it. It is already configured for you.

### Snippets

We provide following set of snippets. Have  a look at them. They may be increased or decreased as per the version of VueJS. Just put those letters and press <key>tab</key>

**v**:
This is a simple trigger which may be used like this:

	var demo = new Vue({
		data [v]Press tab here to transform in something like this:
		data: {
			Your text here|
		}
	})

**vue**:
This ones is great if you have a brand new js file and you want to trigger the whole thing at ones.

	var vm = new Vue({
		el: "#replace"
	})

**vue-config**:
This snippet is for expanding config of the whole VueJS. It looks like this:

	{
	  debug: true,

	  strict: false,

	  prefix: 'v-',

	  delimiters: ['{{', '}}']},

	  silent: false,

	  interpolate: true,

	  async: true,

	  proto: true
	}

**vue-dir**:
Create a custom directive very easily using this snippet. You custom directive will look like this.

	Vue.directive('my-directive', {
	  bind: function () {

	  },
	  update: function (newValue, oldValue) {

	  },
	  unbind: function () {

	  }
	})

**vue-filter**:
Create a custom filter using this snippet.

	Vue.filter('my-filter', function (value) {
	  //content
	})

**vue-cdn**:
Get a cdn snippet which would expand to something like this:
	
	<script src="http://cdnjs.cloudflare.com/ajax/libs/vue/0.12.14/vue.min.js"></script>

**vue-extend**:
A snippet for extend function.

	var Profile = Vue.extend({
	  template: '<p>{{firstName}} {{lastName}} aka {{alias}}</p>'
	})

**wat**: 
Add a $watch property to any of your object.

	vm.$watch('someObject', callback, {
	  content
	})

**get**: 
Add get easily.

	vm.$get(expression)

**set**:
Setter in easy way:

	vm.$set(key, value)

**add**:
	
	vm.$add(key, value)

**delete**:
	
	vm.$delete(key)

**eval**:

	vm.$eval(msg | uppercase)

**ipo**:

	vm.$interpolate(templateString)

**log**:

	vm.$log([keypath-optional])

And yeah __There are even more that are coming soon__.

## ToDo

* Add more snippets
* Add autocomplete for html

## Maintainer

This library is crafted and maintained by [Aditya Giri](http://github.com/BrainBuzzer). If you would like to contact him for any library, them his email address is [dtrg21@gmail.com](mailto:dtrg21@gmail.com).

This library is a part of a blogging platform [LivonAir](http://livonair.com)
