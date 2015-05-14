# Middleman (Bootstrap+SCSS)

A [Middleman](http://middlemanapp.com) starter theme with Twitter Bootstrap and SCSS.

## Install this template

* Clone **middleman-bootstrap** into `~/.middleman`. You will need to create this directory if it doesn't exist.

```
git clone https://github.com/imaginarydesign/middleman-bootstrap.git ~/.middleman/middleman-bootstrap
```

## Usage

* Create a new Middleman project based on this template.

```
middleman init project-name --template=middleman-bootstrap
```

* This is your project, so you'll want to remove the included `.git` directory after initializing a new project.
```
rm -rf .git
```

---

*That's it! Initialize your own git repo now, if you like. Delete everything above after initializing a project, and keep the content below as decent starting documentation for your project.*

---

# Middleman Website

Written with [Ruby](https://www.ruby-lang.org/en/)+[Middleman](http://middlemanapp.com)

**Included packages:**

* [Middleman](http://middlemanapp.com/)
* [Sass](http://sass-lang.com/)
* [Bootstrap 3 Sass](https://github.com/twbs/bootstrap-sass)
* [jQuery](http://jquery.com/)

## Setup in development

* Install [rbenv](https://github.com/sstephenson/rbenv) and [ruby-build](https://github.com/sstephenson/ruby-build#installing-as-an-rbenv-plugin-recommended)

* Clone project and cd into project directory

```bash
git clone repo-path.git
cd project-dir
```

* Install Ruby version set in `.ruby-version`

```
rbenv install && rbenv rehash
```

* Setup local ruby (this number should reflect the ruby version that was just installed)

```
rbenv local 2.2.1
```

* Install dependencies

```
gem install bundler && bundle install
```

* Start Middleman server

```
bundle exec middleman
```

## Building

* Run the following to build your website locally into a `build` folder

```bash
bundle exec middleman build
```