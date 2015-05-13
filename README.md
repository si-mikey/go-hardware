# Go on hardware

I (Burcu Dogan) originally became a Go user to rewrite my hardware
controllers in a simple, non-fragmented and solid language. This repo
is a directory of tools, packages and tutorials to let you introduce
Go in your hardware projects.

## Why Go?

* Great tooling that comes with a strong cross compilation story.
* Builtin concurrency primitives in Go is making it easier to write
concurrent programs.
* Go runs on ARM boards. ARM boards are getting cheaper, making
it easier for production designs to include them. Higher-level
languages have more opportunities than ever on hardware projects.
* Go is garbage collected but you can still use it to write
non-realtime or networked controllers. There are plenty of
Go users who program their experimental drone flight control
software in Go, it's OK for prototyping.
* Go's network stack is maintained well. Standard library might
be missing higher level implementations for P2P protocols, but
the community works to fill that gap.
* Writing C bindings in Go is a pleasure with
[cgo](https://golang.org/cmd/cgo/).

## Tutorials

## Packages

### Controllers, robotics, etc
### Signal processing and graphics
### Mobile