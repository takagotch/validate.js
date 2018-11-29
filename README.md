### validate.js
---
https://github.com/rickharrison/validate.js

```
npm install validate-js
```

```js
var validator = new FormValidator('example_form', [{
  name: 'req',
  display: 'required',
  rules: 'required'
},{
  name: 'alphanumeric',
  rules: 'alpha_numeric'
},{
  name: 'password',
  rules: 'required'
},{
  name: 'password_confirm',
  display: 'password confirmation',
  rules: 'required|matches[password]'
},{
  name: 'email',
  rules: 'valid_email'
},{
  name: 'minlength',
  display: 'min length',
  rules: 'min_length[8]'
},{
  name: ['fname', 'lname'],
  rules: 'required|alpha'
}], function(errors){
  if(errors.length > 0){
  }
});
```

```
```

