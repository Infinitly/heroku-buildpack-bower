# Heroku Buildpack Bower

A simple buildpack, which will run install bower and run `bower install`.

## Usage

#### Configure your Heroku App
```
$ heroku config:add BUILDPACK_URL="https://github.com/jplot/heroku-buildpack-bower.git" -a YOUR_APP
```
or
```
$ heroku create --buildpack "https://github.com/jplot/heroku-buildpack-bower.git"
```
