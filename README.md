Contains a fork of the go toolchain needed to work with MTE enabled. This repo will be retired once the following upstream issues are resolved:

* https://github.com/golang/go/issues/27610
* https://github.com/golang/go/issues/59090

Included upstream fixes:

* `>=go1.26.0-mte.2`
  * https://go-review.googlesource.com/c/go/+/749062
  * https://go-review.googlesource.com/c/go/+/751020
* `>=go1.26.1-mte.1`, `<go1.26.3-mte.0`
  * https://go-review.googlesource.com/c/go/+/750040
  * https://go-review.googlesource.com/c/go/+/758902
