# What is this package?

This repo is simply a sourced tap from an outdated version of homebrew to support the `python@2` formula. This is due to python 2's End of Life (EOL) on Dec 31, 2019. You can create a `tap` from here and install python2 with ease.

## Create a tap

In order to create a local tap, run the following command:

```shell
brew tap bluenove/python2
```

This will git pull the repo down into your local namespace. It will be stored in `/usr/local/Homebrew/Library/Taps` in case you wish to do some tomfoolery.

# How to install python2?

From there, you can install python2 as you would normally.

```shell
brew install bluenove/python2/python@2
```
