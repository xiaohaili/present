This is a fork from golang [present](https://godoc.org/golang.org/x/tools/present) tool.

feature
=======

- standalone from golang tools repo.
- cut off heading & footer from tmpl.
- change root path to '/slides'. (It looks complicated to handle 'X-Forwarded-Prefix' in tmpl files.)

todo
====

+ support .md files.