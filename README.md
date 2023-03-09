# Simple Error Pages

A handful of error templates to be used as a starting point for serving up 400, 404, 422 and 500 errors in your applications.

## Usage

1. [Download a zip file](https://github.com/phawk/simple-error-pages/archive/refs/heads/master.zip) of these pages and copy them across to your frameworks static folder, for Rails this is `./public`.
2. Add your logo to your `./public` folder, let's assume it's called `logo.svg`.
3. Update each of the html files, changing the img tags src attribute to `/logo.svg`.
4. Enjoy ✌️

### Developing

Simply run a file server in this directory and open the files in your browser.

```
$ gem install adsf
$ adsf
$ open localhost:3000/404.html
```

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Simple error pages</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://rapidruby.com" property="cc:attributionName" rel="cc:attributionURL">http://rapidruby.com</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
