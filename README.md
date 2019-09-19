# openrepo

[![license][license-img]][github] [![web][web-img]][web] [![github][github-img]][github]
[![Build Status](https://travis-ci.com/Prismary/openrepo.svg?branch=master)](https://travis-ci.com/Prismary/openrepo)

A h5ai fork for my web repositories.
HTTP web server index for Apache httpd, lighttpd, and nginx.

## Important

* Do **not** install any files from the `src` folder, they need to be
  preprocessed to work correctly!
* Find a preprocessed package and detailed install instructions on the
  [project page][web].
* For bug reports and feature requests please use [issues][github-issues].


## Build

There are installation ready packages for the latest [releases][release] and
[dev builds][develop]. But to build **h5ai** yourself either `git clone` or
download the repository. From within the root folder run the following
commands to find a fresh zipball in folder `build` (tested on linux only,
requires [`node 10.0+`][node] to be installed, might work on other
configurations).

~~~sh
> npm install
> npm run build
~~~

Refer to the [master](https://github.com/lrsjng/h5ai) branch for more info.
