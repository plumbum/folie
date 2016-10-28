## Folie v2

![](https://img.shields.io/badge/work-In_Progress-red.svg)
[![GoDoc](https://godoc.org/github.com/jeelabs/folie?status.svg)](http://godoc.org/github.com/jeelabs/folie)
[![license](https://img.shields.io/github/license/jeelabs/folie.svg)]()

The **Forth Live Explorer** is a command-line utility to talk to a
micro-controller via a (local or remote) serial port. Its main mode of operation
is as interactive terminal, but it can also upload code to an STM32 µC and is
tailored in particular for use with [Mecrisp
Forth](http://mecrisp.sourceforge.net/).

This is experimental code, the stable version is at:  
<https://github.com/jeelabs/embello/tree/master/tools/folie>

### Acknowledgments

* [Go](https://golang.org/) - a programming language which gets types,
  concurrency, builds, **and** deployment right (BSD)
* [go-serial](https://github.com/bugst/go-serial) - knows about serial ports
  across all platforms - by [Christian Maglie](https://github.com/cmaglie) (BSD)
* [readline](https://github.com/chzyer/readline) - takes care of local line
  editing and history - by [@chzyer](https://github.com/chzyer) (MIT)
* the JeeLabs chat group - _you know who you are..._
