# Bootstrap Datepicker for Rails
Bootstrap is a toolkit from Twitter designed to kickstart development of webapps and sites.
It includes base CSS and HTML for typography, forms, buttons, tables, grids, navigation, and more.

http://twitter.github.com/bootstrap/

Bootstrap Datepicker is a plugin for Bootstrap designed by Stefan Petre. It provides a stylish date picker for Bootstrap.

http://www.eyecon.ro/bootstrap-datepicker/

bootstrap-datepicker-rails project integrates Datepicker with Rails 3 assets pipeline.

http://github.com/Nerian/bootstrap-datepicker-rails

It also integrates the improvements made by Andrew Rowls.

https://github.com/eternicode/bootstrap-datepicker

## Rails > 3.1
Include bootstrap-datepicker-rails in Gemfile;

``` ruby
gem 'bootstrap-datepicker-rails'
```

or you can install from latest build;

``` ruby
gem 'bootstrap-datepicker-rails', :require => 'bootstrap-datepicker-rails',
                              :git => 'git://github.com/Nerian/bootstrap-datepicker-rails.git'
```

and run bundle install.

## Stylesheets

Add necessary stylesheet file to app/assets/stylesheets/application.css

``` css
 *= require bootstrap-datepicker
```

## Javascripts

Add necessary javascript(s) files to app/assets/javascripts/application.js

``` javascript
//= require bootstrap-datepicker
```

## Using bootstrap-datepicker-rails

Just call datepicker() with any selector.

```javascript
$('.datepicker').datepicker()
```

There are a lot of options you can pass to datepicker(). They are documented at [https://github.com/eternicode/bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker)


## License
Copyright (c) 2011 Gonzalo Rodríguez-Baltanás Díaz

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
