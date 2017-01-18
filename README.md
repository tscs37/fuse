bazil.org/fuse -- Filesystems in Go
===================================

`bazil.org/fuse` is a Go library for writing FUSE userspace
filesystems.

It is a from-scratch implementation of the kernel-userspace
communication protocol, and does not use the C library from the
project called FUSE. `bazil.org/fuse` embraces Go fully for safety and
ease of programming.

Here’s how to get going:

    go get github.com/tscs37/fuse

Website: http://bazil.org/fuse/

Github repository: https://github.com/bazil/fuse

API docs: http://godoc.org/bazil.org/fuse

Our thanks to Russ Cox for his fuse library, which this project is
based on.

## Maintenance Fork

I forked this library to `github.com/tscs37/fuse` to merge some
maintance pull requests and fix bugs if necessary, as the original
library seems to be inactive.

If you are using the `bazil.org/fuse` import you can simply swap it out
for the new import path.