# Arkadiusz Kondas - personal site [![Build Status](https://img.shields.io/travis/akondas/arkadiuszkondas.com.svg)](https://travis-ci.org/akondas/arkadiuszkondas.com)

[![Validate RSS](https://img.shields.io/badge/validate-rss-orange.svg)](https://validator.w3.org/feed/check.cgi?url=http%3A//arkadiuszkondas.com/rss.xml)
[![Validate JSON Feed](https://img.shields.io/badge/validate-json_feed-green.svg)](http://validator.jsonfeed.org/?url=http%3A%2F%2Farkadiuszkondas.com%2Ffeed.json)

My personal web site [https://arkadiuszkondas.com](http://arkadiuszkondas.com).

## What's inside?
- PHP static site generator [Statie](https://github.com/Symplify/Statie) - see documentation at [www.statie.org](https://www.statie.org)
- CSS comes from [Less](http://lesscss.org/) pre-processor.
- Assets and build are handled by task runner [gulp](http://gulpjs.com/) via [Travis](https://travis-ci.org).

## Use it

- `$ composer install && npm install`

Commands:
- `$ gulp` - generates site from source files
- `$ gulp watch` - starts local server and acts upon changes
- `$ gulp build` - generates version ready for production
- `$ gulp clean` - removes output folder
- `$ composer check` - runs code standard and static analysis
- `$ composer fix` - fixes code standard errors

## Thanks

This website is heavy inspired by https://github.com/crazko/romanvesely.com
