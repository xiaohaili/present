# present

[![Build Status](https://travis-ci.org/xiaohaili/present.svg?branch=master)](https://travis-ci.org/xiaohaili/present)

This is a fork from golang [present](https://godoc.org/golang.org/x/tools/present) tool.

# feature

- standalone from golang tools repo.
- cut off heading & footer from tmpl.
- change root path to '/slides'. (It looks complicated to handle 'X-Forwarded-Prefix' in tmpl files.)
- support .md files.

# todo

+ display MD as slide/article style