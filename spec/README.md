# Build a Simple Database
[Full tutirial](https://cstack.github.io/db_tutorial/)
[Code reference](https://github.com/cstack/db_tutorial)

## Prerequisites
1. *gcc* for compiling, *gdb* for debugging
2. *Ruby* & *rspec* for running tests

## Install rspec
```
gem install rspec
```

##  Initialize rspec
```
rspec init
```

## Install bundles(This may take a while)
```
bundle install --path vendor/bundle
```

## Build
```
gcc -Wall db.c -o db
```

## Run tests
```
bundle exec rspec
```