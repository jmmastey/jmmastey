# josephmastey

## Actually Using This Thing

0. Run `bundle install` and `npm install`. Also `npm install gulp gulp-cli`.
1. Write a new blog post.
2. Use `bundle exec gulp build --prod` to generate all the files in `/dist`
3. Use `bundle exec gulp deploy` to cause jekyll to push the `/dist` directory to the remote `gh-pages` branch. It'll take a minute to update from cache.
4. I think push the branch `jekyll`, just so we can recreate the whole situation.
5. Verify on `https://github.com/jmmastey/jmmastey/settings` that the custom domain hasn't exploded for some reason.

I don't think the master branch actually does anything...

## To get started

```sh
$ gulp [--prod]
```

## Usage

```sh
$ gulp build [--prod]
```

```sh
$ gulp deploy
```

#### Settings
In your `_config.yml` and `humans.txt` you should add your Github and Twitter
profile if you want to.

## Install
If you have cloned this repo or want to reinstall, make sure there&#39;s no
`node_modules` or `Gemfile.lock` folder/file and then run `npm install` and
`bundle install`.

#### Update
To update: `npm update generator-jekyllized -g`, then run `yo jekyllized:gulp
[--rsync|amazon|pages]` in this directory. Note that this will overwrite any
local changes, so back it up.

## Github
For more information on how to use your new project, please refer to the [README
on Github](https://github.com/sondr3/generator-jekyllized).

## Owner

> [Joseph Mastey](http://jmmastey.github.io/josephmastey)
