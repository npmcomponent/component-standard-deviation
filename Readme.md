*This repository is a mirror of the [component](http://component.io) module [component/standard-deviation](http://github.com/component/standard-deviation). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-standard-deviation`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# standard-deviation

  standard deviation utility

## Installation

    $ component install component/standard-deviation

## API

### sd(array)

  Return the standard deviation of `array`:

```js
sd([1,5,6,1,2,0])
```

### sd(array, fn)

  standard deviation of `array` with callback `fn(val, i)`:

```js
var age = sd(users, function(u){ return u.age })
```

### sd(array, string)

  standard deviation of `array` with the given property `string`:

```js
var age = sd(users, 'age')
```

# License

  MIT
