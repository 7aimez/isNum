# isNum() function

A simple funtion to decide if the argument is a number.

## How does it work?

The function uses a simple `if` function to check if it is a numerical value. It uses the variable boolean, `(value - value == 0)` which will return true if value is numerical but false if not. The whole function is:

```javascript
function isNum(value) {
  if (value - value == 0) {
    return true;
  } else {
    return false;
  };
};
```

## Output

The function is used to output a boolean based upon if `value` is numerical. If you write the script,

```javascript
boolean = isNum(25);
```

`boolean` will equal `true`. But if you write the script,

```javascript
boolean = isNum("25");
```

`boolean` will equal `false`.
