# chx
>Hidden challenges: we think most interviewees won't reach here before we get them at the interview booth ;)

Some challenges modified from:

- [HackerRank](http://hackerrank.com)
- [CodeWars](https://www.codewars.com/)
- [Codility](http://codility.com)
- [TopCoder](http://topcoder.com)

### Using JSFiddle for Coding Interviews

Since JSFiddle does not provide a straight forward way of running _console-logging_ JS code, this is a hack [we found here](http://stackoverflow.com/questions/17382200/print-var-in-jsfiddle). 

**HTML**
```html
<pre id="output"></pre>
```

**JavaScript**
```javascript
function print() {
  var args = Array.prototype.slice.call(arguments, 0);
  document.getElementById('output').innerHTML += args.join(" ") + "\n";
}
```
