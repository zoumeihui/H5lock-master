# H5lock


## How to use?

```
<script type="text/javascript" src="src/H5lock.publish.js"></script>
var opt = {
  chooseType: 3, // 3 , 4 , 5,
  width: 300, // lock wrap width
  height: 300, // lock wrap height
  container: 'element', // the id attribute of element
  inputEnd: function(psw){} // when draw end param is password string
}
var lock = new H5lock(opt);
lock.init();

## Support Vue

```
原作者：用vue2做的
> Address[vue-lock](https://github.com/guntertien/vue-lock)

```

