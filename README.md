# ninep
Package for implementing clients and servers of the 9P and 9P2000 distributed resource protocols in Go.

## Usage

$ go build ./cmd/ufs/ufs.go

$ ./ufs -h
Usage of ./ufs:
  -addr string
    	Network address (default ":5640")
  -debug int
    	print debug messages
  -ntype string
    	Default network type (default "tcp4")
  -readonly
    	Set the filesystem to readonly
  -root string
    	Set the root for all attaches (default "/")
  -user string
    	Default user name (default "glenda")

$ ./ufs  ./ufs -debug 1 -root <dir> -readonly
