
# MSP Integration Tests

These tests are designed to test the MSP binary by comparing
output. They are highly accurate tests which look for exact output from
the compiler. It provides actionable feedback when an error occurs.
The selection of test cases is meant to be comprehensive, and as such
multiple different sources are used to create them, including Piazza, the
lab handouts, and other users' public test cases.

# See An Error?

File an issue on the right, open a pull request, or contact me otherwise.

### Setup

As with any go program, ensure you have $GOPATH set properly.
See [this link](https://golang.org/doc/code.html) for more information.

### Installing

`go get github.com/mhoc/cs352-integration-test`

### Running

`go run github.com/mhoc/cs352-integration-test location/to/binary`

Obviously insert the path to your binary. You can add this line to your make
file if you like. If $GOPATH is set properly then you can run it from anywhere
on your system and it will work. Go is pretty cool, huh?
