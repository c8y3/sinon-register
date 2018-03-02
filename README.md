# sinon-register

Helper module to register [sinon] in [mocha].

## Usage

First install and add to your devDependencies:

```
npm install sinon-register --save-dev
```

Then, add this option when calling mocha (either directly on the command line or in a configuration file such as `test/mocha.opts`):

```
--require sinon-register
```

That's it, global variable `sinon` is now available in your tests! You are all set to write mocks...


## License

sinon-register is licensed under the AGPL-3.0 license

[sinon]: http://sinonjs.org/
[mocha]: https://mochajs.org/
