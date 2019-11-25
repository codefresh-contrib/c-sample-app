Compiling C applications with Codefresh
=============

This project is a C project with `make`.
The project also contains tests 

## Local usage

```
$ make
```

You can also run the tests with `make`.

```
$ make PROFILE=1 COVERAGE=1
$ make test
$ make PROFILE=1 COVERAGE=1 coverage profile
```


## To use this project in Codefresh 

1. Create a [free Codefresh account](https://codefresh.io/docs/docs/getting-started/create-a-codefresh-account/)
1. Fork this project in your Github account
1. Create a new pipeline with [codefresh.yml](codefresh.yml) 

More information at the [documentation page](https://codefresh.io/docs/docs/learn-by-example/cc/c-make/)


Enjoy!

(Original source code at [github](https://github.com/rikusalminen/makefile-for-c))








