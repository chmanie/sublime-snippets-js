# JavaScript Snippets for Sublime Text

Vanilla JavaScript snippets for Sublime Text 2 and 3.

## Install

### Package Control

TODO: Include project on Package Control

### Sublime Text 2

TODO: Include instructions for Sublime Text 2

### Sublime Text 3

* Mac OS X

	```
git clone git://github.com/jprichardson/sublime-js-snippets.git ~/Library/Application Support/Sublime Text 3/Packages
	```

* Linux

	```
git clone git://github.com/jprichardson/sublime-js-snippets.git ~/.config/sublime-text-3/Packages
	```

* Windows

	```
git clone git://github.com/jprichardson/sublime-js-snippets.git %userprofile%\AppData\Roaming\Sublime Text 3\Packages
	```

## Console

### [cd] console.dir

```javascript
console.dir(${1:obj});
```

### [ce] console.error

```javascript
console.error(${1:obj});
```

### [cl] console.log

```javascript
console.log(${1:obj});
```

### [cw] console.warn

```javascript
console.warn(${1:obj});
```

## DOM

### [gi] getElementById

```javascript
${1:document}.getElementById('${2:id}');
```

### [gc] getElementsByClassName

```javascript
${1:document}.getElementsByClassName('${2:class}');
```

### [gt] getElementsByTagName

```javascript
${1:document}.getElementsByTagName('${2:tag}');
```

### [qs] querySelector

```javascript
${1:document}.querySelector('${2:selector}');
```

### [qsa] querySelectorAll

```javascript
${1:document}.querySelectorAll('${2:selector}');
```

### [ae] addEventListener

```javascript
${1:document}.addEventListener('${2:event}', function(e) {
	${3}
});
```

### [ac] appendChild

```javascript
${1:document}.appendChild('${2}');
```

### [ce] createElement

```javascript
${1:document}.createElement('${2:elem}');
```

### [ih] innerHTML

```javascript
${1:document}.innerHTML = '${2}';
```

### [tc] textContent

```javascript
${1:document}.textContent = '${2}';
```

## Attribute

### [ga] getAttribute

```javascript
${1:document}.getAttribute('${2:attr}');
```

### [sa] setAttribute

```javascript
${1:document}.setAttribute('${2:attr}', ${3:value});
```

### [ra] removeAttribute

```javascript
${1:document}.removeAttribute('${2:attr}');
```

## Class

### [ca] classList.add

```javascript
${1:document}.classList.add('${2:class}');
```

### [ra] classList.toggle

```javascript
${1:document}.classList.toggle('${2:class}');
```

### [ra] classList.remove

```javascript
${1:document}.classList.remove('${2:class}');
```

## Roadmap

* Add Node.js snippets

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.1.0 May 23, 2013
	* Added DOM manipulation and console snippets

## License

[MIT License](http://zenorocha.mit-license.org/) © Zeno Rocha